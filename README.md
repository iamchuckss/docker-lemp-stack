# :whale: Docker LEMP stack

### Docker Multicontainer: 

- Nginx 
- PHP7.1.30-fpm
- MySQL
- PHPMyAdmin
- Maildev

### Requirements
- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/install/)


### Installation 

Clone this repository 
```sh
$ git clone git@github.com:iamchuckss/docker-lemp-stack.git
```

Configure port number and database credentials
```sh
Override the default .env configurations with your own .env
$ cp .env.dist .env
```

### Usage

Start containers with docker-compose 
```sh
$ docker-compose up -d
```

Stop containers with docker-compose 
```sh
$ docker-compose stop
```

Connect to Docker container
```sh
$ docker exec -i -t <CONTAINER_ID> /bin/bash
```

Remove containers with docker-compose
```sh
$ docker-compose rm -f
```
