# Database integration with QuickFIXJ server

### Basic setup

The repository contains the example code for the server applications uses QuickFIXJ library

Both server stores the data in the dedicated database

### To start the example stack execute the next command:

```sh
docker-compose -f docker-compose.yml up -d
```

### To stop the stack

```sh
docker-compose -f docker-compose.yml down --volumes
```

### Logs

```sh
docker logs -f quickfixj-server-client-with-database-quickfixj-spring-boot-server-1
```
