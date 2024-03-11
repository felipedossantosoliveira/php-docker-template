# PHP Docker Template

This is a template for setting up a PHP development environment using Docker.

## Prerequisites

Make sure you have the following installed on your machine:

- Docker: [Install Docker](https://docs.docker.com/get-docker/)
- Docker Compose: [Install Docker Compose](https://docs.docker.com/compose/install/)

## Getting Started

1. Clone this repository:

   ```bash
   git clone https://github.com/felipedossantosoliveira/php-docker-template.git
   ```

2. Set up the environment file:

   ```bash
   cp .env.example .env
   ```

3. Build and start the container in the background:

   ```bash
   docker-compose up -d
   ```

Now you're ready to start developing your PHP application within the configured Docker environment!