# NGINX + Docker Configuration

This repository provides a structured and minimal setup for serving static media files using **NGINX** and **Docker** technologies.

## Contents

The repository includes the following components:

- `Dockerfile` – configuration for building a custom Docker image.
- `docker-compose.yml` – configuration file for orchestrating services.
- `.dockerignore` – defines files and directories to exclude from the Docker build context.
- `.gitignore` – lists files and directories to be excluded from version control.
- `media/` – directory containing static media content to be served.
- `nginx/` – directory containing NGINX configuration files.
- `nginx.conf` – primary configuration file for NGINX.

## Features

- Optimized NGINX configuration for serving static files efficiently.
- Simple and clear Docker setup for development and testing.
- Organized project structure for ease of maintenance and scalability.

## Getting Started

To build and launch the project, execute the following command in the root directory:

```bash
docker-compose up --build -d
