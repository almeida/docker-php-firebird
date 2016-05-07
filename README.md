# PHP with Firebird module Dockerfile

[![Docker Pulls](https://img.shields.io/docker/pulls/almeida/php-firebird.svg)](https://hub.docker.com/r/almeida/php-firebird/)
[![Docker Stars](https://img.shields.io/docker/stars/almeida/php-firebird.svg)](https://hub.docker.com/r/almeida/php-firebird/)

## Description

 Minimal PHP with Firebird module + nginx

### Volumes

 * /usr/share/nginx/html

### Exposed Ports

 * 80

## Run

	$ docker run -d \
		--name php-firebird \	
		-p 80:80 \
		-v /somehostdir/php/:/usr/share/nginx/html/ \
		almeida/php-firebird
