# Alpine Linux Murmur Server

![Docker Stats](http://dockeri.co/image/hafenio/murmur)

**Alpine Linux:** edge

**Mumur Server:** 1.2.16

[Docker Hub](https://hub.docker.com/r/hafenio/murmur/)

### Start Murmur Server
```
docker run -d --name murmur -p 64738:64738/tcp -p 64738:64738/udp hafenio/murmur
```