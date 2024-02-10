# Palworld Admin Tool

A docker-compose setup for https://github.com/Insax/palworld-admin-tool

## Prerequisites

1. Docker Compose - The project uses Docker Compose to manage project services.

### Installation

1. Either clone or download the project as zip and extract at your desired location.
2. `docker compose up -d`
3. Visit http://localhost 

If your palworld server also is inside a docker container and you want to use dockers internal networking you have to connect it to the tools isolated network

`docker network connect your-palworld-container-name palworld-admin_sail`
