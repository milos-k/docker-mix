# lamp-stack

## compleate stack for web/php testing
containers included:
- php-httpd
- mariadb
- phpmyadmin

**Directories explanation:**
- ./DocumentRoot - is a link to the dirrectory that is presented with apache
- ./maria-dbstorage - is a directory where db data is stored localy 
- ./php-httpd - place for a Dockerfile with additional configuration (directory is the same name as service in docker-compose.yml)

**instructions to run:**
run with:
```bash
sudo docker-compose up -d
```

stop with:
```bash
sudo docker-compose stop
```