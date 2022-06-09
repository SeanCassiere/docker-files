# Docker files

This repository contains the docker-compose files used on my machine.

## Setup the machine

The following will need to be installed and configured on the machine.

1. Docker
2. Docker compose

Afterwards, create the shared `webnet` bridge network in Docker using the following command.

```bash
docker network create -d bridge webnet
```

## Using docker-compose files

To run any of the `docker-compose.yml` files, simply clone the repository, then `cd` into the respective directory.

Once in, spin-up the docker-compose file in detached mode using the following command.

```bash
## Example

cd portainer-ce
docker-compose up -d
```
