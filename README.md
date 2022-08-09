How to run with docker

1. docker run -d -e POSTGRES_USER=odoo -e POSTGRES_PASSWORD=odoo -e POSTGRES_DB=postgres --name db postgres:14

2. docker run -v odoo15-docker/addons:/mnt/extra-addons -p 8069:8069 --name odoo --link db:db odoo15

Docker

1. docker ps -a

2. docker start/stop/restart CONTAINER_ID

Note

1. https://hub.docker.com/_/odoo/