# Docker-Everything

A collection of docker-compose files for easily self-hosting essential development tools.

## Supported Services

- Excalidraw
- PostgreSQL
- MySQL
- MongoDB
- Minio (mock S3)
- Redis

## Prerequisites

- Docker: [Installation Instructions](https://docs.docker.com/get-docker/)
- docker-compose

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/harsh07may/Docker-Everything.git
   ```
2. Change directory to the service you want to self-host:

   ```bash
   cd Docker-Everything/self-host-<service-name>
   ```

3. Start the container
   ```bash
   docker-compose up -d
   ```
