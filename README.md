# Wiki installation

This wiki installation is a bookstack application running in a docker
environment using a mysql database.

The application is exposed using the port 6875.

References:
- [Bookstackapp](https://www.bookstackapp.com/)
- [App Container Used](https://github.com/linuxserver/docker-bookstack)

## Installation

- Add an `.env` file (there is an example provided).
- Start with `docker-compose up -d`.

## Docker Compose Commands

Start application: `docker-compose up -d`

Stop application: `docker-compose kill`

Delete volume: `docker-compose down --volumes`
