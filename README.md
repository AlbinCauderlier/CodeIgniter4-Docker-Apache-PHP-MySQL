# CodeIgniter4-Docker-Apache-PHP-MySQL

Step 1 - https://avenir.ro/codeigniter-4-using-docker-apache-mysql/

Step 2 - https://avenir.ro/codeigniter-4/xinstall-codeigniter-in-docker-containers/

1. Cloner ce repository Git

2. Dans la racine du repository, lancer les commandes :

# Build des containers et lancement des serveurs
$ docker-compose up -d 

# Lister les containers up poour avoir leurs noms
$ docker ps 

# Entrer dans le container web 
$ docker exec -it codeigniter4-docker-apache-php-mysql-web-1 bash

