# traefik-docker-sample

This repository shows how to create a simple hosting setup with [Docker](https://docker.com/) and [Traefik](https://traefik.io/).

### Features

- Uses [docker-compose](https://docs.docker.com/compose/overview/) for container definition and management
- Preconfigured for HTTPS and automatic [Let's Encrypt certificate acquisition and renewal](https://github.com/apkd/traefik-docker-sample/blob/master/traefik/traefik.toml#L14-L19)
- Set up for automatic [HTTP -> HTTPS redirection](https://github.com/apkd/traefik-docker-sample/blob/master/traefik/traefik.toml#L7)
- Simple template for [configuration of additional containers](https://github.com/apkd/traefik-docker-sample/blob/master/example-container/docker-compose.yml#L14-L18)
- The `acme.json` file is conveniently [stored outside the container](https://github.com/apkd/traefik-docker-sample/blob/master/traefik/docker-compose.yml#L15)
