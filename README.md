# CodeIgniter4-Docker-Apache-PHP-MySQL

First sources of informations, from 2020

Step 1 - https://avenir.ro/codeigniter-4-using-docker-apache-mysql/

Step 2 - https://avenir.ro/codeigniter-4/xinstall-codeigniter-in-docker-containers/


## Install

1. Clone this git repository


2. Open a terminal at the path of the repository + send the command :

'docker-compose up -d'

It's up and running localy


3. Controls 

a. Controls that you access the main page in your browser at localhost

b. Controls that you access the database at the TCP-3306 port (MySQL Workbench or HeidiSQL)



# Useful commands

### Lister les containers up poour avoir leurs noms
$ docker ps 

### Entrer dans le container web 
$ docker exec -it codeigniter4-docker-apache-php-mysql-web-1 bash

