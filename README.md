# docker-compose-labs

Please follow the instructions to install docker-compose from the official documentation:

https://docs.docker.com/compose/install/

to check the exercise files out, go inside to the folder and execute:
docker-compose up -d

You can verify executing other commands:
docker-compose up -d
docker-compose ps
docker-compose stop
docker-compose restart
docker-compose logs
docker-compose rm
docker-compose down
docker-compose exec
docker-compose scale <servicename>=<number>
docker-compose build
docker-compose port

To check network interfaces:
docker network ls
docker network inspect <code>
docker inspect <code>

To create a specific network interface:
docker network create --driver bridge superbridge

Any docker-compose parameters:
depends_on: dependency between services
links: link to containers in another service and also express dependency between services

Type of network interfaces:
network bridge: create a private network
network overlay: to work with a swarm
network macvlan: connect container interfaces directly to host interfaces



