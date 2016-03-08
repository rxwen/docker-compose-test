usage:

- install necessary docker images: docker pull mysql
- build local openfire image with: [docker openfire](https://github.com/rxwen/docker-openfire)
- run docker-compose run -d
- browse to http://ip:9090, and configure openfire to use database: jdbc:mysql://mysql:3306/openfire_database?rewriteBatchedStatements=true

