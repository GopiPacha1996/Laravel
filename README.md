<p align="center"><img src="https://miro.medium.com/max/888/1*M-HoF7qx8AlSu9lzO4JmUA.png" width="400"></p>

<p align="center">
</p>

## About Laravel-Docker

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
