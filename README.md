# Red-Team-Infrastructure
A testing Red Team Infrastructure created with Docker.

# Structure
![enter image description here](RedTeam_Infra.png)
The Infrastructure Comprehends the following services:
- NGINX: It's the only service exposed and it's used as proxy for the different internal services
- Empire: 
- Metasploit
- pwndrop: It's used to serve our files and payloads.
- Postgress
- CodiMD: Note taking service.

# Deployment
    docker-compose up -d

