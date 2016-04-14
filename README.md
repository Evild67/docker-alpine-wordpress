[![Docker Stars](https://img.shields.io/docker/stars/evild/alpine-wordpress.svg?style=flat-square)](https://hub.docker.com/r/evild/alpine-wordpress/)
[![Docker Pulls](https://img.shields.io/docker/pulls/evild/alpine-wordpress.svg?style=flat-square)](https://hub.docker.com/r/evild/alpine-wordpress/)
[![ImageLayers Size](https://img.shields.io/imagelayers/image-size/evild/alpine-wordpress/latest.svg?style=flat-square)](https://hub.docker.com/r/evild/alpine-wordpress/)

# Alpine Wordpress

This image is based on [evild/alpine-php](https://hub.docker.com/r/evild/alpine-php/)

## Version

- `latest` [(Dockerfile)](https://github.com/Evild67/docker-alpine-wordpress/blob/master/Dockerfile)
- `4.5` [(Dockerfile)](https://github.com/Evild67/docker-alpine-wordpress/blob/master/Dockerfile)
- `4.4.2` [(Dockerfile)](https://github.com/Evild67/docker-alpine-wordpress/blob/master/Dockerfile)


## What is WordPress?
WordPress is a free and open source blogging tool and a content management system (CMS) based on PHP and MySQL, which runs on a web hosting service. Features include a plugin architecture and a template system. WordPress is used by more than 22.0% of the top 10 million websites as of August 2013. WordPress is the most popular blogging system in use on the Web, at more than 60 million websites. The most popular languages used are English, Spanish and Bahasa Indonesia.

## Available Configuration Parameters

Please refer the docker run command options for the --env-file flag where you can specify all required environment variables in a single file. This will save you from writing a potentially long docker run command. Alternatively you can use docker-compose.

Below is the complete list of available options that can be used to customize your WordPress installation.
* **WP_DEBUG**: Set this to true to enable debugging.
* **WORDPRESS_DB_HOST**: The hostname of the database server.
* **WORDPRESS_DB_USER**: The database database user. Defaults to `root`
* **WORDPRESS_DB_PASSWORD**: The database database password.
* **WORDPRESS_DB_NAME**: The database database name. Defaults to to `wordpress`
* **WORDPRESS_AUTH_KEY**: Defaults to unique random SHA1s
* **WORDPRESS_SECURE_AUTH_KEY**: Defaults to unique random SHA1s
* **WORDPRESS_LOGGED_IN_KEY**: Defaults to unique random SHA1s
* **WORDPRESS_NONCE_KEY**: Defaults to unique random SHA1s
* **WORDPRESS_AUTH_SALT**: Defaults to unique random SHA1s
* **WORDPRESS_SECURE_AUTH_SALT**: Defaults to unique random SHA1s
* **WORDPRESS_WORDPRESS_LOGGED_IN_SALT**: Defaults to unique random SHA1s
* **WORDPRESS_NONCE_SALT**: Defaults to unique random SHA1s
