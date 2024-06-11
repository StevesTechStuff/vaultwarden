# Vaultwarden

This repository contains the configuration and setup for running Vaultwarden in a Docker container with Traefik as a reverse proxy.

## Prerequisites

- Docker
- Docker Compose
- A domain name configured to point to your server's IP address

## Setup

1. Clone this repository to your local machine:

    
    git clone https://github.com/StevesTechStuff/vaultwarden.git
    cd vaultwarden
    ```

2. Edit the `.env` file with your domain and email details:

    
    DOMAIN=vaultwarden.url.net
    EMAIL=youremail@example.com
    ```

3. Start the Docker containers:

    
    docker-compose up -d
    ```

## Access

- Vaultwarden should be accessible at `https://${DOMAIN}`.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
