# antidote-docker-alpine 
[![](https://images.microbadger.com/badges/image/itoumlilt/antidote-alpine:0.1.svg)](https://microbadger.com/images/itoumlilt/antidote-alpine:0.1 )
[![](https://images.microbadger.com/badges/version/itoumlilt/antidote-alpine:0.1.svg)](https://microbadger.com/images/itoumlilt/antidote-alpine:0.1 )

This repository contains a [Docker](http://docker.io) file for a tiny container 
image of [AntidoteDB][antidote] based on Alpine Linux.

Image on Docker Hub: https://hub.docker.com/r/itoumlilt/antidote-alpine/

The image on the `iptables` branch includes iptables, which can be useful to 
create network partitions for testing AntidoteDB.

## Running

```bash
docker pull itoumlilt/antidote-alpine:latest
docker run --rm -it -p "8087:8087" itoumlilt/antidote-alpine
```

## License

WTFPL.  

[antidote]: https://www.antidotedb.eu/