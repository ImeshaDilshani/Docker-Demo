# Docker-Demo

This repository contains a simple Docker demonstration project. It walks through the basic steps of installing Docker, building a Docker image, and running a container from that image.

## Getting Started
To get started with Docker, follow these steps:

1. Install Docker
You can install Docker Desktop on Windows, Mac, or Linux. Visit the official Docker website for installation instructions: [Docker Desktop](https://docs.docker.com/desktop/install/windows-install/)

2. Build Docker Image
Navigate to the root directory of this project in your terminal or command prompt, and run the following command to build the Docker image:
```
docker build -t demo .
```
3. Run Docker Container
Once the Docker image is built, you can run a Docker container using the following command:
```
docker run -p 8080:80 demo
```
This command maps port 8080 of your host machine to port 80 of the Docker container, assuming the container is running a web server on port 80.

4. Access the Application
Open your web browser and navigate to ```http://localhost:8080``` to access the application running inside the Docker container.



