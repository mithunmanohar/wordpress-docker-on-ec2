# wordpress-setup-on-ec2

### Setup wordpress website on ec2 machine in single step using Docker and docker-compose

- Clone the repo
- Run `./setup.sh`
- The script installs docker, docker-compose and runs the docker-compose file in the repo.
- The installation also sets up a self signed certificate for https connections.
- Your wordpress installation will be accesible at https://<your_server_host>

This is not a production ready setup. Its useful if you want to hack around with a simple standalone wordpress installation.
