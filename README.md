# docker-wordpress-mariadb
Boilerplate for WordPress + MariaDB container on Docker

## Prerequisites
This requires a network container set up. For an Nginx proxy setup see: https://github.com/pango-studio/docker-nginx-proxy

## Wordpress + MariaDB instance

### 1. Clone the repository into an empty folder example-site/
git clone git@github.com:pango-studio/docker-wordpress-mariadb.git .

### 2. Create the required folders
mkdir mysql/ wordpress/

### 3. Copy .env.sample and change variables
cp .env.sample .env

### 4. Run docker-compose
$ docker-compose up -d

Ref: https://github.com/evertramos/docker-wordpress-letsencrypt
