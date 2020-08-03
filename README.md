<p align="center"><img src="https://res.cloudinary.com/dtfbvvkyp/image/upload/v1566331377/laravel-logolockup-cmyk-red.svg" width="400"></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>

## About Laravel

This is Dockerized Laravel Project which we can deploy within few simple steps

step:-1

clone the project and cd to the project

$ git clone https://github.com/GopiPacha1996/Laravel.git && cd Laravel

step-2:-

$ docker-compose up -d

step -3:-
install the composer and do artisan and migrations

$ docker-compose exec app composer install

$ docker-compose exec app php artisan 

$ docker-compose exec app php artisan migrate

step-4:-
give permissions to the folder

$ docker-compose exec app chmod -R 777 /var/www


Now check on the port your application ruuning on 8000 port
