# pocketbase

This is an automated build for [reverie89/pocketbase](https://hub.docker.com/r/reverie89/pocketbase/).

Checks daily for updates from [Pocketbase](https://github.com/pocketbase/pocketbase/releases/).

## Usage example
docker-compose.yaml
```sh
services:
  pocketbase:
    image: reverie89/pocketbase
    ports:
      - 8080:8080
    volumes:
      - /path/to/pocketbase:/pb/pb_data
```

- Dockerfile example copied from [Pocketbase docs](https://pocketbase.io/docs/going-to-production/#using-docker)