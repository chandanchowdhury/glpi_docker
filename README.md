# glpi_docker

docker-compose file and collection of configuration files
to run [GLPI](https://github.com/glpi-project/glpi) in docker.

*WARNING: Do not use for production.* 

## Docker Images
* [bitnami/mysql](https://github.com/bitnami/bitnami-docker-mysql)
* [bitnami/php-fpm](https://github.com/bitnami/bitnami-docker-php-fpm)
* [bitnami/apache](https://github.com/bitnami/bitnami-docker-apache)

## Steps
* Clone the repo
* Download and extract GLPI in a directory named `glpi`
* Update `docker-compose.yaml` to change MySQL credentials
* `docker-compose up`

## TODO
* Configure TLS
* Use MariaDB instead of MySQL