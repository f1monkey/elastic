# ELK

ELK docker images

## Usage

#### Starting containers
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

#### Elasticsearch
Kibana will be available on port 9200 by default (http://localhost:9200)
#### Kibana
Kibana will be available on port 5601 by default (http://localhost:5601)
#### Logstash
Logstash uses http connector on port 8080:
```
$ curl -XPOST http://f1monkey-elk-logstash:8080 ...
```