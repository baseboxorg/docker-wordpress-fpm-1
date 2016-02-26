docker-wordpress-fpm
===============

This is an example setup of using the Wordpress official "wordpress:fpm" image to create a Wordpress site. There are many ways to use that image, here is one of them.

## Getting Started
Firstly, decide your site's code name, I will use "myblog" for now (doesn't affect functionality, just for clarity)
```sh
$ git clone https://github.com/madcoda/docker-wordpress-fpm.git myblog
$ cd myblog
$ docker-compose up -d
```

You're good to go, go to the browser with the following URL:
- Linux: http://localhost:8000
- OSX: http://192.168.99.100:8000
- Windows: http://192.168.99.100:8000

## Customize the docker-compose
(more doc soon)