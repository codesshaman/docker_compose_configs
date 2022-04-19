# docker_compose_configs
My training simple configs with docker compose

Your need docker and docker-compose in your operation system.

Every commands executed into the folder with docker-compose.yml file.

RUN:
docker-compose up -d

STOP:
docker-compose down

CONNECT:
docker exec -it nginx_simple sh (for 00 configuration)
docker exec -it nginx_alphine sh (for 01 configuration)
