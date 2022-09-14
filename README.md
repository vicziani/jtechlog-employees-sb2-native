# Spring Boot 3 p�lda

Ez a program a JTechLog (<http://jtechlog.hu>) blog "Mi v�rhat� a Spring Boot 3-ban?" posztj�hoz k�sz�lt p�ldaprogram.
Spring Boot alkalmaz�s.

Futtat�s�hoz adatb�zis sz�ks�ges, mely Dockerrel a k�vetkez�k�pp ind�that�:

```shell
docker run -d -e MARIADB_DATABASE=employees -e MARIADB_USER=employees -e MARIADB_PASSWORD=employees -e MARIADB_ALLOW_EMPTY_ROOT_PASSWORD=yes -p 3306:3306 --name employees-mariadb mariadb
```