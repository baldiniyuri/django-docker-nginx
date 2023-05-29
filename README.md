# Django-Nginx-Docker


## Description

Basic django app with nginx, and docker configuration.

App básico de Django com o nginx e docker configurados.

## Configuration

Create a .env file with the following variables.

Criar um arquivo .env com as seguintes variáveis.

```
DB_HOST=db
DB_NAME=db-sample
DB_USER=sample
DB_PASS=password
SECRET_KEY=devsecretkey
```

## Installation and Running Local
```
docker-compose build
docker-compose up
```

## Installation and Running Prod
```
docker-compose -f docker-compose-deploy.yml build
docker-compose -f docker-compose-deploy.yml up
```
