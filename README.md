Alpine Linux docker image with Maria DB (MySQL).

```bash
$ docker run -d -v /data/mariadb:/data -p 3306:3306 --name mariadb jimlei/alpine-mariadb
```
