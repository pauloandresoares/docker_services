# Services - docker-compose

## Setup
This setup assumes you already have docker-compose and docker (using docker toolbox) installed.

```
git clone git@github.com:pauloandresoares/docker_services.git
cd docker_services
docker-compose up
```

# Postgres
## Play
Open [http://localhost:5432/](http://localhost:5432/) (or what ever IP you get when you run `docker-machine ip`)

and use the login

```
username: postgres
password: abcd1234
```

# RabbitMQ
## Play
Open [http://localhost:15672/](http://localhost:15672/) (or what ever IP you get when you run `docker-machine ip`)

```
open http://$(docker-machine ip default):15672/
```
and use the login

```
username: rabbitmq
password: rabbitmq
```
