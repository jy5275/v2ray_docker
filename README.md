# Docker Fly

docker build repo for v2fly

https://hub.docker.com/r/v2fly/v2fly-core
https://hub.docker.com/repository/docker/frozenlight/v2ray

## Server

1. Clone this repos
2. `docker build -t v2ray .`
3. `docker run -p 1080:1080 --name v2rayd v2ray:latest`


## Client

Config the local client as follow:
```
port: 1080
IP: Your Server IP
id: b831381d-6324-4d53-ad4f-8cda48b30811
alterId: 0
```
