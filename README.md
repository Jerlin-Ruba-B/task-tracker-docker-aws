# Task Tracker — Docker & AWS EC2 Deployment

A full-stack MEAN application containerized with Docker and deployed on an AWS EC2 instance. This project demonstrates containerization, Docker networking, image publishing, cloud deployment, and application data persistence.

## Project Overview

Task Tracker is a web application for managing tasks. The Angular frontend communicates with a Node.js/Express backend, which uses MongoDB to store task data.

### Architecture

```text
User Browser
     |
     v
Angular Frontend (Docker)
     |
     v
Node.js / Express API (Docker)
     |
     v
MongoDB (Docker + Persistent Volume)

Docker Images → Docker Hub
Application Deployment → AWS EC2
```

## Technologies Used

- **Frontend:** Angular, HTML, CSS, Bootstrap
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Containerization:** Docker, Docker Compose
- **Container Registry:** Docker Hub
- **Cloud Platform:** AWS EC2 (Ubuntu Linux)
- **Version Control:** Git and GitHub

## Key Features

- Create and manage tasks through a web interface.
- Communicate with the backend through REST APIs.
- Run frontend, backend, and database services in Docker containers.
- Connect application services using Docker networking.
- Build and publish Docker images to Docker Hub.
- Deploy the application on an AWS EC2 instance.
- Use persistent MongoDB storage to retain task data.

## Screenshots

### 1. Live Application

![Task Tracker live application](screenshots/01-live-application.png)

### 2. Docker Containers

![Docker containers](screenshots/02-docker-containers.png)

### 3. Docker Network

![Docker network](screenshots/03-docker-network.png)

### 4. Frontend Image on Docker Hub

![Frontend Docker Hub image](screenshots/04-frontend-dockerhub.png)

### 5. Backend Image on Docker Hub

![Backend Docker Hub image](screenshots/05-backend-dockerhub.png)

### 6. AWS EC2 Instance

![AWS EC2 instance](screenshots/06-aws-ec2.png)

### 7. Task Persistence Test

![Task persistence verification](screenshots/07-task-persistence.png)

## What I Learned

- Writing Dockerfiles for frontend and backend applications.
- Configuring multi-container applications with Docker Compose.
- Connecting application services through Docker networking.
- Building, tagging, and pushing images to Docker Hub.
- Deploying a containerized application on AWS EC2.
- Configuring cloud server access and troubleshooting deployment issues.
- Verifying application behavior after a backend container restart.

## Future Improvements

- Automate builds and deployments using Jenkins.
- Provision AWS infrastructure using Terraform.
- Configure HTTPS with a domain name.
- Add monitoring, logging, and deployment automation.

## Author

**Jerlin Ruba B.**

GitHub: [Jerlin-Ruba-B](https://github.com/Jerlin-Ruba-B)
