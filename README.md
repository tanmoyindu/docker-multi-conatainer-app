## Overview
This project demonstrates how to build and manage a multi-container application using Docker. It showcases how different services interact using Docker Compose, making it easier to manage dependencies and configurations.

## Features
Containerized backend, frontend, and database services

Network communication between services

Persistent data storage using volumes

Environment variable management for configurations

## Technologies Used
Docker: Containerization of applications

Node.js / Express: Backend service

React.js: Frontend application

PostgreSQL / MongoDB: Database storage

## Prerequisites
Docker

## Getting Started
Clone this repository:
git clone https://github.com/yourusername/multi-container-app.git
cd multi-container-app

## Access the application:
Frontend: http://localhost:3000

## Useful Docker Commands
docker ps → List running containers
docker ps -a → List all containers (including stopped)
docker stop <container_id> → Stop a running container
docker start <container_id> → Start a stopped container
docker restart <container_id> → Restart a container
docker rm <container_id> → Remove a container
docker logs -f <container_id> → View logs of a container
docker images → List all images
docker rmi <image_id> → Remove an image
docker build -t my_image . → Build an image from a Dockerfile
