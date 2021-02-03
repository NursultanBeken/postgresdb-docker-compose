# postgresdb-docker-compose
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

Use Docker Compose to launch sandbox PostgreSQL DB


## Prerequisites
* git
* docker-compose
> pip install docker-compose

## Quick Start

1. Clone repo
```
git clone https://github.com/NursultanBeken/postgresdb-docker-compose.git
```
2. Start the Database
```
cd postgresdb-docker-compose
docker-compose up
```
3. Opne PG-Admin console \
open http://localhost/ in browser and use login/pass from .env.pg_admin file

## Clean up
> docker-compose down --volumes

## Appendix
### Lint docker-compose file
> docker-compose -f docker-compose.yml config
