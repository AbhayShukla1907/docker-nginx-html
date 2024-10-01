<<<<<<< HEAD
# docker-nginx-html
=======
# Dockerized Nginx with a Simple HTML Page

## Overview
This project demonstrates how to Dockerize a simple HTML page using Nginx as the web server.

## Files
- `index.html`: A simple HTML file that is served by Nginx.
- `nginx.conf`: A custom Nginx configuration file that serves the `index.html`.
- `Dockerfile`: Defines the Docker image using the official Nginx base image, and copies the HTML and configuration files.

## Steps to Build and Run the Docker Container
1. Build the Docker image:
   ```bash
   docker build -t my-nginx-image .
>>>>>>> 1874e29 (Initial commit)
