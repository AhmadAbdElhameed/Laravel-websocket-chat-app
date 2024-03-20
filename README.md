## Laravel WebSockets Chat Application 

Realtime chat application built with Laravel WebSockets. 


## Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Configuration](#configuration)

## Introduction

This Chat App using websocket to show messages in realtime and dockernized all services using docker compose
## Prerequisites

For installation Docker

- Docker Engine: [Installation Guide](https://docs.docker.com/engine/install/)
- Docker Compose: [Installation Guide](https://docs.docker.com/compose/install/)

## Installation

to use this app ,clone this repo and run the following script in the same directory
```bash
git clone https://github.com/AhmadAbdElhameed/Laravel-websocket-chat-app.git
cd Laravel-websocket-chat-app
docker-compose up --build
```


## Configuration

Explain how users can configure the application. Include instructions for setting environment variables, modifying configuration files, or any other customization options.

### Environment Variables

Description of the environment variables used in application and their purpose.

- `APP_ENV`: The environment mode for the application (e.g., development, production).
- `DB_HOST`: The hostname of the MySQL database server.
- `DB_PORT`: The port number for the database connection.
- `DB_DATABASE`: The name of the MySQL database.
- `DB_USERNAME`: The username for accessing the database.
- `DB_PASSWORD`: The password for accessing the database.
- `CACHE_DRIVER`: The cache driver used by the application.
##### Pusher Configuration

- `PUSHER_APP_ID`: The Pusher application ID. This ID uniquely identifies your Pusher application.
- `PUSHER_APP_KEY`: The Pusher application key used for authentication.
- `PUSHER_APP_SECRET`: The Pusher application secret used for secure authentication.
- `PUSHER_APP_CLUSTER`: The Pusher cluster your application is using for efficient request routing.

##### Laravel WebSockets Configuration

- `LARAVEL_WEBSOCKETS_INTERNAL_HOST`: The internal host address for Laravel WebSockets within Docker containers.
- `LARAVEL_WEBSOCKETS_INTERNAL_PORT`: The internal port number for Laravel WebSockets within Docker containers.
- `LARAVEL_WEBSOCKETS_EXTERNAL_HOST`: The external host address for accessing Laravel WebSockets outside Docker containers.
- `LARAVEL_WEBSOCKETS_EXTERNAL_PORT`: The external port number for accessing Laravel WebSockets outside Docker containers.

These environment variables are crucial for configuring real-time communication via Pusher and Laravel WebSockets in your Laravel application. Ensure they are set correctly according to your application's requirements and environment.

### Accessing the Application

Once the containers are running, you can access the application using the following URL:

```
http://localhost:8000
```
