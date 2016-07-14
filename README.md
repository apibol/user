## MariaDB Docker instructions

### Pull Docker Image:

docker pull mariadb

### Run Docker Container:

docker run --name user-mariadb -e MYSQL_ROOT_PASSWORD=admin -e MYSQL_DATABASE=user -d -p 3306:3306 mariadb
