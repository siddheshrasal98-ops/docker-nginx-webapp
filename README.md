# dockerized-nginx-webapp
## Project Overview

This project demonstrates containerizing a simple static website using Docker and Nginx.

## Technologies

- Docker
- Docker Compose
- Nginx
- HTML

## Features

- Custom Docker image
- Nginx web server
- Static website deployment
- Docker Compose support

## Author

Siddhesh Rasal

Project Structure

docker-nginx-webapp/
├── .github/
│   └── workflows/
│       └── docker.yml
├── html/
│   └── index.html
├── kubernetes/
│   ├── deployment.yaml
│   └── service.yaml
├── .dockerignore
├── Dockerfile
├── docker-compose.yml
└── README.md

## How to Run

Build the Docker image

docker build -t nginx-webapp .

Run the container

docker run -d -p 80:80 nginx-webapp

Using Docker Compose

docker-compose up -d



Future Improvements

- Multi-stage Docker builds
- Container registry integration
- Kubernetes Ingress
- Helm Charts
- Monitoring with Prometheus & Grafana
