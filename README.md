# Nifi Docker Cluster

Nifi Docker image support cluster with remote Zookeeper.
This image based on [docker-compose-nifi-cluster](https://github.com/thuongdinh/docker-compose-nifi-cluster) and [mkobit/docker-nifi](https://github.com/mkobit/docker-nifi).

## What it Gives You
 - Apache Nifi 1.0.0
 - Openjdk-8

## Example Docker Compose

```
$ docker-compose up -d
```

Wait until Apache Nifi start success and open http://localhost:8080/nifi to see the Nifi UI.
