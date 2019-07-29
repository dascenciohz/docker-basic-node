## Basic Web Node

## Use with docker run

1.- Download image

    docker pull dascencio/basic-node

2.- Startup

    docker run -it --name some-name -p 3000:3000 dascencio/basic-node:latest

3.- Test

    curl http://localhost:3000

## Use with docker-compose

1.- Build and startup your APP.

    docker-compose -f "docker-compose.yml" up -d --build

2.- Tear down your APP.

    docker-compose down
