# Getting Started with Create React App and Docker

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app) and set up with docker.

## Available Scripts

### `git clone`

Clone application to your repository.\

### `cd hello-world`

Change directory.\

### Development

### `docker-compose build`

Create an image for development.\

### `docker-compose up`

Create and start container for development.
The application is available on localhost:3001.\

### Deployment

### `docker build -f Dockerfile.prod -t hello-word:prod .`

Create an image for production.\

### `docker run -it --rm -p 8787:80 hello-world:prod`

Create and start container for production.
The application is available on localhost:8787.\
