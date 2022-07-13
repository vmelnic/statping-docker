# Statping

Status Page & Monitoring Server - https://github.com/statping/statping

## Installation

Copy file `.env` file.

```
cp .env.example .env
```

Copy self-signed SSL certificates or put yours.

```
cp docker/ssl/server.crt.example docker/ssl/server.crt
cp docker/ssl/server.key.example docker/ssl/server.key
```

In order to install MySQL server via docker-compose run the following command:

```
docker-compose up -d --build
```

## Configurations

Exposed ports: 8088, 8089
