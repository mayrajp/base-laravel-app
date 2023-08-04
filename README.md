# PAYMENT APP


## Installation

Befora instalation, make sure you have created your db. Set  the db config in .env file.

### Clone repository

`git clone https://github.com/mayrajp/payment-app.git`

### Enter directory

*OBS.: If you are using container make this steps and the following ones inside the container*

`cd payment-app`

### Configure .env with your environment configuration

`cp .env.example .env`

### Configure database on .env

```dosini
DB_CONNECTION=mysql
DB_HOST=mysql_db
DB_PORT=3306
DB_DATABASE=payment_db
DB_USERNAME=root
DB_PASSWORD=root

```

### To run docker

`sudo docker compose up -d`

### Enter the container

`sudo docker exec -it laravel-docker bash`

### Install dependencies

`composer install`

### Migrate the Databse

`php artisan migrate`



