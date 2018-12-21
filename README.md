# Restfull API Platform

Api Platform is a powerfull full stack framework dedicated to API-driven projects

# Introduction

For this project we will use the Docker based setup to generate the project.

- https://docs.docker.com/docker-for-mac/release-notes/#stable-releases-of-2018 #Install Docker and Docker-Compose
- \$ docker-compose up -d #Running in detached mode
- \$ composer create-project symfony/skeleton rest-api #Create the api project
- \$ composer req api \$composer req friendsofsymfony/rest-bundle #Install Api server component && fos
- \$ composer require symfony/orm-pack \$ composer require symfony/maker-bundle --dev #Install Doctrine
- \$ bin/console doctrine:database:create #Create Database
- \$ bin/console doctrine:schema:create #Create Database Schema
- \$ bin/console make:entity #Generate Entity
- \$ bin/console doctrine:schema:update --force
- \$ composer req server --dev #Install Symfony WebServer Bundle
- \$ bin/console server:run #Run Symfony server

# Architecture

### Api Structure

![alt text](https://github.com/Bibi10/restPiMob/blob/essoDev/apistruct.png 'Api Structure')

### Api Swagger

![alt text](https://github.com/Bibi10/restPiMob/blob/essoDev/apibooks.png 'Api Swagger')

# Getting Started

cd rest-api
bin/console server:run

<!-- ### Contributors -->
