# Deploy de uma aplicação React usando Docker

## Requisitos:
- Docker
- Docker Compose
- Git

-----------

## Instruções:

Execute os seguintes comandos (Linux):
```console
$ git clone https://github.com/danielmaraujo/react-app-deploy.git
$ cd react-app-deploy
$ docker-compose up -d --build
```

Devido a utilização do NGINX, a aplicação estará disponível na porta 80.

