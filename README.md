
```shell
docker run -d -e MARIADB_DATABASE=employees -e MARIADB_USER=employees -e MARIADB_PASSWORD=employees -e MARIADB_ALLOW_EMPTY_ROOT_PASSWORD=yes -p 3306:3306 --name employees-mariadb mariadb
```