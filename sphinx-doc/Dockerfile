FROM python:3
MAINTAINER Dênis Volpato Martins <denisvm@gmail.com>

RUN apt-get update && apt-get install -y \
    make git \
    && pip --no-cache-dir install sphinx \
    && rm -rf /var/lib/apt/lists/*
