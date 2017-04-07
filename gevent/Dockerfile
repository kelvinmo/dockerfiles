FROM alpine:3.5
MAINTAINER Kelvin Mo

RUN apk add --no-cache \
    libev \
    python py-pip \
    python-dev build-base \
&& pip install --upgrade setuptools \
&& pip install gevent \
&& apk del python-dev build-base

