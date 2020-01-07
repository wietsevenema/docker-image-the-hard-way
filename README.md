# Build a Docker Image the Hard Way

Who needs a Dockerfile anyway? In this DIY workshop I will teach you how to build a docker image using nothing but your bare hands (and a text editor). Join me and build your first hand-crafted image.

## Requirements

- Make sure you have Docker installed

## Tasks

1. Load the contents of the directory **the-hard-way** as an image (send a tar archive to _docker load_)
2. Run the container image and run `busybox --help`
3. Add a _layer_ which adds "uptime" as a command using busybox (either add symlink or copy the binary)

## Some useful commands:

- `tar -c . | docker load`
- `shasum -a 256 layer.tar`
- `docker run -it the-hard-way`
- `docker save nginx > nginx.tar`
