# Nifi Docker Cluster

Nifi Docker image support cluster with remote Zookeeper.
This image based on [docker-compose-nifi-cluster](https://github.com/thuongdinh/docker-compose-nifi-cluster) and [mkobit/docker-nifi](https://github.com/mkobit/docker-nifi).

//ifdef::badges[]
image:{uri-shields-mit}[title="MIT license", alt="MIT License"]
image:{uri-shields-docker-stars}[title="Docker repository stars", alt="Stars on Docker Hub", link="https://hub.docker.com/r/thuongdinh/nifi-cluster/"]
image:{uri-shields-docker-pulls}[title="Docker image pulls", alt="Docker image pulls", link="https://hub.docker.com/r/thuongdinh/nifi-cluster/"]
image:{uri-shields-github-issues}[title="Github issues", alt="Github issues", link="https://github.com/thuongdinh/nifi-cluster/issues"]
//endif::[]

## What it Gives You
 - Apache Nifi 1.0.0
 - Openjdk-8

## Example Docker Compose

```
$ docker-compose up -d
```

Wait until Apache Nifi start success and open http://localhost:8080/nifi to see the Nifi UI.
