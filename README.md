# PAYMENT APP

### Clone repository

`git clone https://github.com/mayrajp/payment-app.git`

### Enter directory

*OBS.: If you are using container make this steps and the following ones inside the container*

`cd payment-app`

### Configure .env with your environment configuration

`cp .env.example .env`

### Make this config on .env

```dosini
DB_CONNECTION=mysql
DB_HOST=db
DB_PORT=3306
DB_DATABASE=payment_db
DB_USERNAME=root
DB_PASSWORD=root

CACHE_DRIVER=redis
QUEUE_CONNECTION=redis
SESSION_DRIVER=redis

REDIS_HOST=redis
REDIS_PASSWORD=null
REDIS_PORT=6379

```

### To run docker

`sudo docker compose up -d`

### Enter the container

`sudo docker exec -it laravel-docker bash`

### Install dependencies

`composer install`

### Migrate the Databse

`php artisan migrate`

### Open on browser

`http://localhost:8989/`





