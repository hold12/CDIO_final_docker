# Docker script for CDIO_final

## Usage:

Firstly, create a new environment file:

`# cp .env-example .env`

Change the usernames and passwords.

Next, start the docker containers using docker-compose:

`# docker-compose up -d`

To stop the instances:

`# docker-compose stop`

To remove the instances:

`# docker-compose rm -f`

To stop and remove the instances:

`# docker-compose down --volumes`

## Access:

To access the database:

```
# mysql -u <username> -h 127.0.0.1 -P 3306 -p
# <enter password>
```

To access phpmyadmin, open `http://localhost:8080/` in the browser.