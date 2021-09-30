# Instalación de symfony con Docker

## Clonar repositorio

> git clone git:repo

#
## Docker

> docker build -t symfony

> docker run -p -it 80:80 symfony

> docker exec symfony /bin/bash

#
## Docker Compose

> docker-compose build

> docker-compose up -d

> docker-compose exec symfony /bin/bash