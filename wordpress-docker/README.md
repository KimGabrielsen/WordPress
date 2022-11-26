A docker setup of
- Wordpress
- Mysql
- phpmyadmin

All running in docker containers.

Datafiles as well as WP files are all stored outside their respective docker containers, to ensure data is persisted between docker builds and open for the opportunity to change the WP configuration.

## Geting started

Make sure you have docker running and docker-compose installed.

### To start the system

Go to the directory where the docker compose file is located and write

```
docker-compose up -d

```

this will run the containers as demons. If it's the first time, docker-compose will build the different parts of the setup.

When all containers are running they can be accessed on the ports assigned in the docker compose file.



### Stop the system

```
docker-compose down

```

