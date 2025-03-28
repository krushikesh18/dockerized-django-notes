# Dockerized Django Notes

This project is a **Django-based Notes application** containerized using Docker. It allows users to create, edit, and manage notes efficiently while providing an easy-to-deploy, portable development environment.

## Features
- Django-based notes management system.
- Dockerized setup for easy deployment.
- Uses `docker-compose` for service orchestration.
- Supports environment variable configuration.

## Prerequisites
Before running the project, ensure you have the following installed:

- [Docker](https://www.docker.com/get-started)
- [Docker Compose](https://docs.docker.com/compose/install/)

## Getting Started
Follow these steps to set up and run the project locally using Docker.

### 1. Clone the Repository
```sh
 git clone https://github.com/krushikesh18/dockerized-django-notes.git
 cd dockerized-django-notes
```

### 2. Build and Start the Containers
Run the following command to build and start the project:
```sh
docker-compose up --build
```
This will start the Django application in a container.

### 3. Access the Application
- Open the browser and visit: `http://localhost:8000`
- To access the Django admin panel: `http://localhost:8000/admin`

## Stopping the Application
To stop the running container, use:
```sh
docker-compose down
```
