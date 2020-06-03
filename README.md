# Elastic

Elasticsearch docker image

## Usage

* Copy `docker-compose.override.yml.dist` to `docker-compose.override.yml`
```
$ cp docker-compose.override.yml.dist docker-compose.override.yml
```
* Create docker network (if not exists)
```
$ docker network create f1monkey
```
* Start container
```
$ docker-compose up -d
```