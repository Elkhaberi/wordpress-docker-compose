# WordPress based on Docker

WordPress Platform deployed on docker.

## Table of Contents

* [General info](#general-info)
* [Technologies](#technologies)
* [How To Build](#how-to-build)
* [More Details](#more-details)

## General info

WordPress Platform deployed on docker.

## Technologies

* [Mysql]
* [Wordpress]
* [Docker]

## How To Build

### prerequisite

1. [Install Docker](https://docs.docker.com/engine/install/)
2. [Install Docker Compose](https://docs.docker.com/compose/install/)

### Build Steps

#### 1. Build Docker image

```sh
gh repo clone Elkhaberi/wordpress-docker-compose
```

```sh
cd wordpress-docker-compose/
```

```sh
docker-compose up -d
```

```sh
docker-compose ps
```

Open in Browser:
```
http://127.0.0.1/
```
## More Details

[reference](https://www.digitalocean.com/community/tutorials/how-to-install-wordpress-with-docker-compose)

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO -)

   [Mysql]: <https://www.mysql.com/>
   [Wordpress]: <https://wordpress.com/>
   [Docker]: <https://www.docker.com/>
