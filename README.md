# Build a Docker Image the Hard Way

## Requirements

- Make sure you have Docker installed

## Tasks

- Load the contents of this directory as an image (using _docker load_)
- Add a _layer_ which adds "echo" as a command

## Some useful commands:

- `docker save nginx > nginx.tar`
- `tar -c . | docker load`
- `shasum -a 256 layer.tar`
- `docker run -it the-hard-way`
