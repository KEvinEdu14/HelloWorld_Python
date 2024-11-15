# Python Project

This is a simple Python project that prints "Hola Mundo" to the console.

## Technologies Used
- Language: Python
- Container: Docker

## Prerequisites
- Docker installed
- Python 3.9 installed locally (optional for direct execution without Docker)

## Project Files
- *main.py*: Main file of the project that prints "Hola Mundo" to the console.
- *Dockerfile*: Docker file for building the Docker image.
- *Procfile*: Specifies the command to run the application (used for deployment on platforms like Railway).

## Create Docker Image

Run the following command in the project directory:

~~~
docker build -t kevineduardo14/helloworldpython .
~~~
## Run the Docker Container
~~~
docker run kevineduardo14/helloworldpython
~~~

## Login the Docker Hub
~~~
docker login
~~~
## Docker Desktop pull in Docker Hub
~~~
docker pull kevineduardo14/helloworldpython
~~~

## Imagen in Docker Hub

https://hub.docker.com/r/kevineduardo14/helloworldpython

# RailWay
We log in and link to GitHub to deploy the repositories.
