docker-compose config

docker-compose up --build

docker-compose stop

docker-compose up -d

docker logs splunk

docker-compose down

docker container prune -f

docker image prune -a -f

docker volume prune -f

docker network prune -f

docker system prune -f

sudo rm -rf /var/lib/docker/volumes/*

docker exec -it docker-splunk /bin/bash

curl -k  https://10.145.89.1:8088/services/collector/event -H "Authorization: Splunk 3f066d2a-c871-4800-87fc-e6be5fa69f1b" -d '{"event": "hello world"}'

{"text": "Success", "code": 0}

docker-compose  --file  docker-sshd-hydra/docker-compose.yml config

docker-compose  --file  docker-splunk-hec/docker-compose.yml config

docker-compose  --file  docker-sshd-hydra/docker-compose.yml down

docker-compose  --file  docker-splunk-hec/docker-compose.yml down 

docker-compose  --file  docker-splunk-hec/docker-compose.yml up --build

docker-compose  --file  docker-sshd-hydra/docker-compose.yml up --build

docker run -it docker-hydra -l root -P /root/500-worst-passwords.txt -s 2222 10.145.89.1 ssh


