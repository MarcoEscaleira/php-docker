# Project structure

```
|-- projects
|   |-- php-docker
|   |   |-- README.md
|   |   |-- docker-compose.yml
|   |   |-- apache...
|   |   |-- mariadb...
|   |-- sites
|   |   |-- index.php
|   |   |-- something.php
```

This is important, make sure that you create a `sites` folder on the same level as this repository.

# Start

``` docker compose up``` - To create the container and run it for the first time.


# Variables

Make sure to update environment variables to your needs on `./docker-compose.yml`

# Debugging

1. If you get a <b>docker compose error</b> on install of your container, make sure to update the hash key insinide `/php-apache/Dockerfile` with the latest hash key from https://getcomposer.org/download/