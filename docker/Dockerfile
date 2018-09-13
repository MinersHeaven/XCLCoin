FROM debian:stretch
LABEL maintainer="XCL Developers <dev@xcl.org>"
LABEL description="Dockerised XCLCore, built from Travis"

RUN apt-get update && apt-get -y upgrade && apt-get clean && rm -fr /var/cache/apt/*

COPY bin/* /usr/bin/
