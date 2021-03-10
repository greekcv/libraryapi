
## LibraryAPI Demo project

PHP 7.4, Laravel 8, Mysql, Docker

#### Install

    git clone https://github.com/greekcv/libraryapi.git
    cd libraryapi

    docker build -t libraryapi .
    docker-compose up -d mysql

    cp .env.example .env

    composer install
    php artisan migrate

#### Start Web API

    docker-compose up -d

Docker port: http://127.0.0.1:8002/api/

or

    php artisan serve
