MySQL 5.6 pre-configured for utf8mb4

On Docker Hub: [https://hub.docker.com/r/cursork/mysql-utf8mb4/](https://hub.docker.com/r/cursork/mysql-utf8mb4/)

```
docker run -e MYSQL_ROOT_PASSWORD=$ROOT_PASSWORD_HERE -itP cursork/mysql-utf8mb4
```

See [upstream image](https://hub.docker.com/_/mysql/) for all environment variables that can be passed.
