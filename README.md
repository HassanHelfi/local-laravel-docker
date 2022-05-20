## Setup Laravel with docker ;-)
nginx - php - mysql - phpmyadmin and composer

move your laravel code base in src folder or clone laravel woth 
```properties           
    git clone https://github.com/laravel/laravel.git
```
## run docker
```properties
    docker-compose build
    docker-compose up -d
```

### run artisan commands
```properties
    docker-compose exec php php /var/www/html/artisan config:clear
    docker-compose exec php php /var/www/html/artisan migrate
    docker-compose exec php php /var/www/html/artisan make:model Hassan
```
---
### run composer commands
```properties
    docker-compose exec php composer require fabpot/goutte
```


### Reference

 - [youtube](https://www.youtube.com/watch?v=5N6gTVCG_rw)
 - [github](https://github.com/do-community/travellist-laravel-demo)