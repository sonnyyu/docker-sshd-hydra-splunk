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

docker run -it docker-hydra

docker run -it docker-hydra -l root -P /root/500-worst-passwords.txt -s 2222 10.145.89.1 ssh