# mysql8withschooldb

Docker File Generator
===

MySQL DB v8.0.16, created school DB for SQL study.


## Git address for Dockerfile

```
git clone https://github.com/abc0012544/mysql8withschooldb.git
```

## Get docker image
```
docker pull abc0012544/mysql8withschooldb
```

## Run image
```
docker run -it -d --name container_name -p 30036:3306 -p 30022:22 abc0012544/mysql8withschooldb
```

## attache container
```
docker exec -it container_name /bin/bash
```

## Login MySQL in container
```
mysql -u root -p
```

## MySQL login password
Test1234

### Author
* v1.0: Johnny Tsao
Test
Test01