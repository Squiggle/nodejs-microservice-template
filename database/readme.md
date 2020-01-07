# Database docker template

```
docker-compose up -d
```

This will:
1. Spin up the docker container with a MySQL database
1. Make the init sql script available
1. Execute the init sql script to create the database tables

To test:

```
docker exec -it <id> bash

> mysql
> use rw;
> show tables;
```

Should run a shell on the docker image, execute the MySQL CLI and show the tables in the `rw` database