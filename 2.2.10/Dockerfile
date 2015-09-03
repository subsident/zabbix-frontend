FROM php:apache

MAINTAINER ODY <ody@gmail.com>

RUN apt-get -y update && apt-get -y upgrade

COPY ../src/zabbix-2.2.10.tar.gz /tmp/

RUN cd	/tmp \
	&& tar