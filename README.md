# Node.js Hello World Docker App

A simple Node.js application built with Docker and deployed using a CI/CD pipeline (GitHub Actions).

## How to Run with Docker

The application is packaged as a Docker image available on Docker Hub.

To run the container:

```bash
docker run -d -p 3000:3000 --name my-node-app mostafa7helmy/node-hello-world:latest