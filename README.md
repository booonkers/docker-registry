# docker-registry


create an .env file & setup the required env. variables:

~~
REGISTRY_HOST_DIR=/PATH/TO/VOLUME
REGISTRY_CONTAINER_NAME=NAME_OF_CONTAINER
REGISTRY_VIRTUAL_HOST=DOMAIN_NAME
~~

run the container using docker compose:

~~
docker-compose up -d
~~

If you encounter issues with files permissions in the mounted volumes, run the following:

~~
sudo chown -R 1000 PATH_TO_VOLUMES
~~
