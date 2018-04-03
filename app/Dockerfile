#Alpine Linux
FROM httpd:alpine
COPY . /usr/local/apache2/htdocs/
CMD ["/bin/sh"]

#PHP 7
FROM php:7.0-apache
COPY . /var/www/html/
RUN docker-php-ext-install pdo_mysql
RUN ["apt-get", "update"]
RUN ["apt-get", "install", "-y", "vim"]



##VIM FOR THE BABY CUZ BABY NEEDS HIS VIM
#FROM  confluent/postgres-bw:0.1
#RUN ["apt-get", "update"]
#RUN ["apt-get", "install", "-y", "vim"]

