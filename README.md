# Docker 101 Tutorial Lab

This repository contains the Dockerfile used for the Docker 101 tutorial.

## Build the image

docker build -t getting-started .

## Run the container

docker run -dp 3000:3000 getting-started

## Open the application

Open a browser and go to:
http://localhost:3000
