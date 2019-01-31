FROM ruby:2.5.3-alpine

LABEL maintainer="sachin@kodelounge.com"

RUN apk update \
&& apk add --virtual build-dependencies \
build-base \
gcc \
wget \
git \
mariadb-dev

RUN rm -rf /var/cache/apk
