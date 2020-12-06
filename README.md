# SQL-index-example

An example of index usage in database

---

### Use mysql image for local database via docker

```
$ docker run --name clothing-db -p 3306:3306 -e MYSQL_ROOT_PASSWORD=12345 -e MYSQL_DATABASE=clothing-db -e MYSQL_ROOT_HOST=% -d mysql:latest

$ docker start clothing-db
```
