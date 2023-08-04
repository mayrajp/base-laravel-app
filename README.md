# PAYMENT APP


## Installation

Befora instalation, make sure you have created your db. Set  the db config in .env file.

### Clone repository

`git clone https://github.com/CityConnectBr/api-gsu-angra.git`

### Enter directory

*OBS.: If you are using container make this steps and the following ones inside the container*

`cd api-gsu-angra`

### Configure .env with your environment configuration

`cp .env.example .env`

### Install dependencies

`composer install`

### Migrate the Databse

`php artisan migrate`



