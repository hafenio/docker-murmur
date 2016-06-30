# Alpine Linux Murmur Server

![Docker Stats](http://dockeri.co/image/hafenio/murmur)

**Alpine Linux:** edge

**Mumur Server:** 1.2.16

**Size:** 53.05 MB

[Docker Hub](https://hub.docker.com/r/hafenio/murmur/)

### Start Murmur Server
```
docker run -d --name murmur -p 64738:64738/tcp -p 64738:64738/udp hafenio/murmur
```

### Murmur Snapshot

**Version:** 1.3.0~1383~g4f4e5ac~snapshot

If you want to use the Murmur snapshot you can pull the Docker image with the **develop** tag:

```
docker run -d --name murmur -p 64738:64738/tcp -p 64738:64738/udp hafenio/murmur:develop
```
