# Docker compose package: docker-composer-php-mysql-apache2

This builds apache2.2, mysql5.7 and php5.5 from images on hub.docker.com
Images are hosted here: https://hub.docker.com/u/dr4g0nsr/

Folders for user data and config are created relative to cloned folder where you run build.sh

Mounted volumes and files:
apache/config/000-default.conf - config file for apache virtual host
php/config/php.ini - ini that is used by php-fpm
php/config/php-fpm.conf - fpm config
php/config/pool/www.conf - web user config
mysql/config/docker.cnf - user mysqld config (usually mysqld.cnf)