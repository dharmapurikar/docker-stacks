FROM ubuntu:16.04

LABEL maintainer="sachin@kodelounge.com"

RUN apt-get update \
  && apt-get install -y \
  build-essential \
  git \
  make \
  curl \
  wget \
  libxslt-dev \
  libxml2-dev \
  zlib1g-dev \
  libmysqlclient-dev \
  libmysqlclient20 \
  g++ \
  htop \
  unzip \
  sysstat \
  libssl-dev \
  libreadline-dev \
  tzdata \
  &&  apt-get clean \
  &&  rm -rf /var/cache/apt/archives/* /var/lib/apt/lists/*

RUN curl -sL https://deb.nodesource.com/setup_10.x | bash -

RUN apt-get install -y nodejs

RUN echo "America/New_York" > /etc/timezone \
  &&  dpkg-reconfigure -f noninteractive tzdata

EXPOSE 3000

ENTRYPOINT [ "/bin/bash" ]