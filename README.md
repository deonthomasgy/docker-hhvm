# HHVM 

HHVM is an open-source virtual machine designed for executing programs written in Hack and PHP.

# Installation
The following command will pull the latest php-fpm build.
```sh
$ docker pull princeamd/hhvm:latest
```
# Create Container
The following command creates a container with HHVM that's available on port: 9000.
```sh
docker run --name thomas-hhvm -h php -v /etc/localtime:/etc/localtime:ro -d princeamd/hhvm:latest
```
License
---
MIT