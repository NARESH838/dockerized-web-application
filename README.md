# Dockerized Web Application

A simple Python Flask web application containerized using Docker.

## Technologies

- Python
- Flask
- Docker
- Git
- GitHub

## Project Structure


dockerized-web-application/
├── app.py
├── requirements.txt
├── Dockerfile
├── .dockerignore
└── README.md

## Docker Workflow

 Python Flask Application
          ↓
       Dockerfile
          ↓
    Docker Image
          ↓
   Docker Container
          ↓
     Port 5000
          ↓
   Web Application



  ## Docker Commands Used

  
Build image : docker build -t dockerized-web-app .
all images : docker images
Run container : docker run -d -p 5000:5000 --name docker-new-web-app dockerized-web-app
running containers : docker ps
stopped or exited containers : docker ps -a
view container logs : docker logs docker-new-web-app
stop containers : docker stop docker-new-web-app
start containers : docker start docker-new-web-app
inspect containers : docker inspect docker-new-web-app
checking ports : docker port docker-new-web-app



 
## Application Endpoints

/ — Home page
/health — Health check
/info — Application information
