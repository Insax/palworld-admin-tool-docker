# Palworld Admin Tool

A docker-compose setup for https://github.com/Insax/palworld-admin-tool

## Prerequisites

1. Docker Compose - The project uses Docker Compose to manage project services.

### Installation

1. Either clone or download the project as zip and extract at your desired location.
2. Adjust the `connections` section in rcon.php to match your servers rcon settings. Don't edit the default entry, it will be ignored in the project.
3. `docker compose up -d`
4. Visit http://localhost 