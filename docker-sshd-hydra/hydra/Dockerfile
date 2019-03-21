FROM ubuntu:18.04
MAINTAINER Sonny Yu <sonnyyuirm@gmail.com>
RUN  apt-get update -y && \
apt-get install -y hydra
ADD 500-worst-passwords.txt /root/500-worst-passwords.txt
ENTRYPOINT ["/usr/bin/hydra"]
