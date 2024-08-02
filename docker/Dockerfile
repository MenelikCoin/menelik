FROM debian:stretch
LABEL maintainer="Menelik Developers <dev@menelik.fun>"
LABEL description="Dockerised MenelikCore, built from Travis"

RUN apt-get update && apt-get -y upgrade && apt-get clean && rm -fr /var/cache/apt/*

COPY bin/* /usr/bin/
