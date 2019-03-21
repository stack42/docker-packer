# docker-packer
[![](https://images.microbadger.com/badges/image/stack42/packer.svg)](http://microbadger.com/images/stack42/packer "Get your own image badge on microbadger.com")
[![](https://images.microbadger.com/badges/version/stack42/packer.svg)](https://hub.docker.com/r/stack42/packer/)
[![Docker Hub](http://img.shields.io/docker/pulls/stack42/packer.svg)](https://hub.docker.com/r/stack42/packer/)

## About packer

Packer is an open source tool for creating identical machine images for multiple platforms from a single source configuration. Packer is lightweight, runs on every major operating system, and is highly performant, creating machine images for multiple platforms in parallel. Packer does not replace configuration management like Chef or Puppet. In fact, when building images, Packer is able to use tools like Chef or Puppet to install software onto the image.

http://www.packer.io/

## Dockerfile

This Docker image is based on the official [Debian:stable-slim](https://hub.docker.com/_/debian) image.

## Dockerhub

https://hub.docker.com/r/stack42/packer

## How to run this image

Latest stable version
```
docker run -it --rm  stack42/packer <command> [<args>]
```
