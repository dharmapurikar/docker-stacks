FROM ruby:2.5.3-alpine

LABEL maintainer="sachin@kodelounge.com"

RUN apk add --no-cache --virtual build-dependencies \
  build-base \
  gcc \
  wget \
  git \
  mariadb-dev \
  nodejs \
  tzdata

RUN apk add --no-cache imagemagick6 imagemagick6-dev imagemagick6-c++