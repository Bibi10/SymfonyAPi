# Restfull API Platform

Api Platform is a powerfull full stack framework dedicated to API-driven projects

# Introduction

For this project we will use the Docker based setup to generate the project.

- https://docs.docker.com/docker-for-mac/release-notes/#stable-releases-of-2018 #Install Docker and Docker-Compose
- \$ docker-compose up -d #Running in detached mode
- \$ composer create-project symfony/skeleton rest-api #Create the api project
- \$ composer req api #Install Api server component

# Architecture

##### Routing :

##### Database :

##### Authentication :

# Api Structure

```
—-- api

-- controllers
-

-- models
-

-- routes
-

```

# RESTful Endpoint & Status Code

### REST URI

| HTTP Verb | URL               | Action                       |
| --------- | ----------------- | ---------------------------- |
| POST      | `/users`          | Create user account          |
| GET       | `/users/`         | Read users account           |
| GET       | `/users/:user_id` | Read a specific user account |
| PUT       | `/users/`         | Update user account          |
| DELETE    | `/users`          | Delete user account          |
| POST      | `/users/login`    | User connexion               |

### Status Codes

| Status | Descricption            |
| ------ | ----------------------- |
| 200    | `OK`                    |
| 201    | `CREATED`               |
| 400    | `BAD REQUEST`           |
| 404    | `NOT FOUND`             |
| 500    | `INTERNAL SERVER ERROR` |

# Getting Started

### Prerequisites

- Dependencies

| dependencies | Version |
| ------------ | ------- |
|              |         |
|              |         |

### Getting Set Up

<!-- ### Contributors -->
