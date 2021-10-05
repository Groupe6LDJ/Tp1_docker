# Tp1_docker

Setting up a PhpMyAdmin and MySQL server for a WordPress blog via Docker

## TO START

git clone https://github.com/Groupe6LDJ/Tp1_docker.git

### TO INSTALL AND RUN THE BLOG

cd Tp1_docker
docker-compose up

### TO ACCESS THE BLOG
📄 http://localhost:8080/

### TO ACCESS THE SITE CONTROL PANEL
📄http://localhost:8080/wp-admin/

### TO ACCESS DATABASE
📄 http://localhost:8081/

## DOCKER IMAGES USED

:heavy_check_mark: [phpmyadmin](https://hub.docker.com/_/phpmyadmin) - PhpMyAdmin (A web interface for MySQL and MariaDB)  
:heavy_check_mark: [mysql](https://hub.docker.com/_/) - MySQL MySQL (A widely used, open-source relational database management system)  
:heavy_check_mark: [wordpress](https://hub.docker.com/_/wordpress) - WordPress  

## VERSIONS
🔴 phpmyadmin:latest  
🔴 mysql:latest  
🔴 wordpress:latest

## AUTHORS

🧔 **Bastien BOURGON** _alias_ [@Bastien-Bourgon](https://github.com/Bastien-Bourgon)  
🧔 **Guyllian BELAYEL** _alias_ [@GuyllianB](https://github.com/GuyllianB)  

## LICENSE

MIT License
