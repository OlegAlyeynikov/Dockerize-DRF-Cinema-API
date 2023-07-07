# Cinema-API

API service for cinema management written on DRF. 
Django project for ordering movie tickets. You don't have to go anywhere else to buy tickets. 
Just place an order online and tickets will be sent to your email.

## Features

* JWT authenticated
* Admin panel/admin/
* Documentation is located at api/doc/swagger
* Managing orders and tickets
* Creating movies with genres, actors
* Creating cinema halls
* Adding movie sessions
* Filtering movies and movie sessions

## Installing using GitHub

Install PostgresSQL and create db

* git clone https://github.com/AlenOl/Dockerize-DRF-Cinema-API.git
* cd Dockerize-DRF-Cinema-API
* python -m venv venv
* source venv/bin/activate
* pip install -r requirements.txt
* set DB_HOST=<your db hostname>
* set DB_NAME=<your db name>
* set DB_USER=<your db username>
* set DB_PASSWORD=<your db user password>
* set SECRETKEY=<your secret key>
* python manage.py migrate
* python manage.py runserver

## Run with docker

Docker should be installed

* docker-compose build
* docker-compose up

## Getting access

* create user via/api/user/register/
* get access token via/api/user/token/
