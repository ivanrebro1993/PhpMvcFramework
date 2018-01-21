FROM php:7.2.1-apache
COPY ./php.ini /usr/local/etc/php
RUN apt-get update \
	&& docker-php-ext-install mbstring