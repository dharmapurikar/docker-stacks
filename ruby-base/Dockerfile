FROM ruby:3.1-alpine3.19

LABEL maintainer="sachin@dharmapurikar.in"

RUN apk add --no-cache --virtual build-dependencies \
  build-base \
  gcc \
  wget \
  git \
  mariadb-dev \
  nodejs \
  tzdata \
  curl \
  curl-dev \
  ruby-dev