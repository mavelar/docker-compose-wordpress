FROM wordpress:latest
MAINTAINER Manuel Avelar <me@mavelar.com>

RUN apt-get update && apt-get install -y \
	zlib1g-dev \
	&& docker-php-ext-install zip

WORKDIR /var/www/html