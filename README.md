# docker-nginx-website

A simple project to deploy a static website using Nginx inside a Docker container.

## Project Overview
This project demonstrates how to serve a custom static HTML page with Nginx running inside a Docker container.  
It mounts the local directory containing the HTML files to the Nginx default directory, exposing the website on port 8080.

## Tech Stack
- Nginx
- Docker
- HTML

## How to Run

1. Clone the repo:
   '''bash
   git clone https://github.com/Omarmohamed-74/docker-nginx-website.git

2. Run the Docker container:
docker run -it -d --name web -p 8080:80 -v $(pwd):/usr/share/nginx/html nginx


3. Open your browser and go to http://localhost:8080 to see the website.

