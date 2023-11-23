# RepasoContenedores
Contenedores con Apache y mysql


docker-php-ext-install mysqli

docker run -d --name web1 -p 8081:80 -v "C:\Users\Usuario\Desktop\stop\web1":/var/www/html php:apache-bullseye

docker run -d --name web2 -p 8082:80 -v "C:\Users\Usuario\Desktop\stop\web2":/var/www/html php:apache-bullseye

docker run -d --name sql -e MYSQL_ROOT_PASSWORD=12345 -v C:\Users\Usuario\Desktop\stop\sql:/docker-entrypoint-initdb.d mysql:debian
