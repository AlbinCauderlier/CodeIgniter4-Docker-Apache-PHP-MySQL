# CodeIgniter4-Docker-Apache-PHP-MySQL

First sources of informations, from 2020

Step 1 - https://avenir.ro/codeigniter-4-using-docker-apache-mysql/

Step 2 - https://avenir.ro/codeigniter-4/xinstall-codeigniter-in-docker-containers/


## Install

1. Clone this git repository


2. On a terminal at the path of the repository:

a. Building the containers

```
docker-compose up -d
```

b. List of the running containers, in order to catch the <name_of_the_web_container>

```
docker ps 
```

c. Let's go in the web container

```
docker exec -it <name_of_the_web_container> bash
```

In the container terminal:
```
composer create-project codeigniter4/appstarter
exit
```




3. Controls 

a. Controls that you access the main page in your browser at http://localhost

b. Controls that you access the database at the TCP-3306 port (MySQL Workbench or HeidiSQL)


## Upgrade

### PHP upgrades 

The PHP version is declared in the /docker/apache/Dockerfile line 1

Currently: 'FROM php:8.2-apache'


### MySQL and Apache

The versions are not declared in the docker-compose.yml 

=> The latest versions are used for these containers


