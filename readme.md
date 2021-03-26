# Run
```$ docker-compose build && docker-compose up -d```

# Run migration
## Mysql connection in .env file
```
DB_CONNECTION=mysql
DB_HOST=mysql #host name of service
DB_PORT=3036
DB_DATABASE=homestead
DB_USERNAME=homestead
DB_PASSWORD=secret
```

```docker-compose exec php php /var/www/html/artisan migrate```