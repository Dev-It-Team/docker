clone the repo and, inside the project's folder, issues these commands depending on the situation:

0. You want help:
- `docker --help` or `docker image|container --help` or `docker-compose --help`

1. You've pulled a new commit, or this is the first time you run the docker-compose, then:
- `docker-compose up` will execute the docker-compose file, i.e. create the images, networks etc. and start the containers

2. You want to start, stop or restart all the existing containers, then:
- `docker-compose stop` will stop all the running containers
- `docker-compose start` will start all the containers
- `docker-compose restart` will restart all the containers

3. You want to get rid of everything in one go:
- `docker-compose down` (USE WITH CAUTION) will remove what the file created completely
