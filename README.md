# Strapi CMS POC

It's a simple POC using [Strapi](https://strapi.io/) running in Docker.

## Prerequisites

- [Docker](https://www.docker.com/)

## How to Run

- Download Docker images with `docker-compose pull`
- Turn on the container with `docker-compose up -d`
- To see logs from the container you need to execute the following `docker-compose logs --tail=all -f | grep strapi`

## Troubleshooting

- Issues with images or containers you can cleanup with `docker-compose down -rmi all`
- Issues with the port already used check with `sudo lsof -i -P -n | grep <PORT>`

## References

- [Strapi: Installing using Docker](https://strapi.io/documentation/developer-docs/latest/setup-deployment-guides/installation/docker.html)
- [Strapi Cheat Sheet](https://strapi-showcase.s3-us-west-2.amazonaws.com/CheatSheet.pdf)
- [How to run a Strapi dev stack with Docker compose](https://strapi.io/blog/how-to-run-a-strapi-dev-stack-with-docker-compose)
