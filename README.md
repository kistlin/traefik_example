[Install Docker (Ubuntu)](https://docs.docker.com/engine/install/ubuntu/)
[Install docker-compose (Ubuntu)](https://docs.docker.com/compose/install/)

# Create required network
sudo docker network create web

# Run
sudo docker-compose -f docker-compose.yml up

# Access sites
https://localhost/traefik/dashboard/
https://localhost/jenkins

# Features
- Traefik used as reverse proxy
- Traefik by default doesn't expose anything
- Traefik redirects all http requests to https
- Traefik uses certificates for https (self signed in this case)
