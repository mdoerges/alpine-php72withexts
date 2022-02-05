# Alpine with PHP 7.2 and additional PHP modules
[Dockerfile](https://github.com/mdoerges/alpine-php72withexts/blob/master/Dockerfile) Alpine with PHP 7.2 and additional PHP modules

Based on Docker image [php:7.2-fpm-alpine](https://hub.docker.com/_/php) with additional PHP modules

Please use the Docker image [nginx:mainline-alpine](https://hub.docker.com/_/nginx) or [nginx:stable-alpine](https://hub.docker.com/_/nginx) for the web server part

## Please take care that PHP7.2 is out of support. So no security updates anymore.

## Can be used with

[Grav](https://getgrav.org/)

[Wallabag](https://www.wallabag.org/) (with SQLite)

## Usage

please see [docker-compose.yml](https://github.com/mdoerges/alpine-php72withexts/blob/master/docker-compose.yml) for basic usage as an example based on a [Grav](https://getgrav.org) installation
