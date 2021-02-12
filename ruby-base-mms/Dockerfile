FROM ubuntu:16.04

RUN apt-get update && apt-get install -y software-properties-common && \
    apt-add-repository ppa:brightbox/ruby-ng && \
    apt-get update && apt-get install -y default-jdk nodejs build-essential ruby2.5 ruby2.5-dev \
    make libxslt-dev libxml2-dev zlib1g-dev \
    libmysqlclient-dev libmysqlclient20 && apt-get remove -y --auto-remove software-properties-common && apt-get -y autoclean