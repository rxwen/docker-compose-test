usage:

- install necessary docker images: docker pull mysql
- build local openfire image with: [docker openfire](https://github.com/rxwen/docker-openfire)
- run docker-compose run -d
- browse to http://ip:9090, and configure openfire to use database: jdbc:mysql://mysql:3306/openfire_database?rewriteBatchedStatements=true
- it's assumed that the dababase has been initialized in named volume mysql_data. if need to run openfire setup wizward again, remove the openfire_cfg/openfire.xml file.

