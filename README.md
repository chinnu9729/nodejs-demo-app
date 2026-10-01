# Node.js CI/CD Pipeline

## Objective

Automate the build, testing, and Docker image deployment of a Node.js application using GitHub Actions.

## Technologies

- AWS EC2
- Ubuntu
- Node.js
- Express.js
- Git
- GitHub
- GitHub Actions
- Docker
- Docker Hub

## Pipeline

The pipeline is triggered whenever code is pushed to the `main` branch.

### Pipeline Stages

1. Checkout source code
2. Setup Node.js
3. Install dependencies
4. Run automated tests
5. Build Docker image
6. Push Docker image to Docker Hub

## Application

The Node.js application runs on port `3000`.

## Endpoints

- `/`
- `/health`

## Docker

Docker image:

`chinnu9729/nodejs-demo-app:latest`
