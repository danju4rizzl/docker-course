# This Dockerfile is used to build a Docker image for a Node.js application
# The image is based on the node:20-alpine image, which is a lightweight version of Node.js running on Alpine Linux

FROM node:20-alpine

# Set the working directory inside the container
WORKDIR /app

# Copy the application files from the host machine to the container
COPY . .

# Define the command to run when the container starts
CMD node hello.js
