# Docker LEMP stack

### Docker multicontainer: Nginx, PHP7.1.30-fpm, MySQL, PHPMyAdmin, Maildev

### Installation 

Clone this repository 
```
$ git clone git@github.com:iamchuckss/docker-lemp-stack.git
```

Configure port number and database credentials
```
Override the default .env configurations with your own .env
$ cp .env.dist .env
```

Start docker-compose
```
$ docker-compose up -d
```
