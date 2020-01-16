# 1월 16일 프로젝트입니다
## lab1
## lab2
## lab3
```
$ cd ./2.docker
$ docker-compose up
(manager)       $ docker swarm init
(workor1,2,3)   $ docker swarm join ...
(manager)       $ docker network create --driver=overlay --attachable frontend
(manager)       $ docker network create --driver=overlay --attachable backend
(manager)       $ docker stack deploy -c /stack/vote_app.yml vote_app
```