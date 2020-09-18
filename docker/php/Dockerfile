FROM php:7.2-php

RUN apt-get update && apt-get install -y

# Install composer
RUN curl -sS https://getcomposer.org/installer | php -- \
	--install-dir=/usr/local/bin \
	--filename=composer

