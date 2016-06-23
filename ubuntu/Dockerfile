FROM ubuntu:latest

RUN apt-get update
RUN apt-get install -y apache2 mysql-client php php-mysql libapache2-mod-php
RUN echo 'service apache2 start' >> /root/.bashrc
