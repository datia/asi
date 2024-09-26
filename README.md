# Support material for ASI master course @ [ISEL](http://www.isel.pt)

The course give students competences on designing modern information system (IS).
For more details about the course check this [page](https://www.isel.pt/en/meic/information-systems-architecture).

## Dependencies

This base development kit uses [Docker](https://www.docker.com) to setup a [PostgreSQL](https://www.postgresql.org/docs/15/index.html) relational database.

It is necessary to install Docker in you computer to use this kit.

## Usage

To start the container, run the command ` docker compose up` in the directory where `docker-compose.yml` is. Do note that for some instalations you may need to uso `sudo.`
The `setup-master` directory stores initialization scripts to bootstrap the database.
The `data` directory will have the database files after the database initialization.
**To create a fresh installation of the database just delete the data directory**

Tested using Docker Desktop 4.34.2 in Mac Sonoma (Intel)


## License

[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://choosealicense.com/licenses/mit/)

![maintained](https://img.shields.io/badge/Maintained%3F-yes-green.svg)