# docker-wordpress-mariadb
Boilerplate for WordPress + MariaDB container on Docker

## Clone the repository into an empty folder example-site/
git clone git@github.com:pango-studio/docker-wordpress-mariadb.git .

## Create the required folders
mkdir mysql/ wordpress/

## Copy .env.sample and change variables
cp .env.sample .env

## Run docker-compose
$ docker-compose up -d

Ref: https://github.com/evertramos/docker-wordpress-letsencrypt
