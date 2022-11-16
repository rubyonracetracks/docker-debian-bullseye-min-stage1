[![CI](https://github.com/rubyonracetracks/docker-debian-bullseye-min-stage1/actions/workflows/build.yml/badge.svg)](https://github.com/rubyonracetracks/docker-debian-bullseye-min-stage1/actions/workflows/build.yml)

# Docker Debian Bullseye - Minimal - Stage 1

This repository is used for building the Stage 1 Minimal Debian Bullseye Docker image for [Ruby on Racetracks](https://www.rubyonracetracks.com/).

## Name of This Docker Image
[ghcr.io/rubyonracetracks/docker-debian-bullseye-min-stage1](https://github.com/rubyonracetracks/docker-debian-bullseye-min-stage1/pkgs/container/docker-debian-bullseye-min-stage1)

## Upstream Docker Image
[Official Debian Bullseye Docker image](https://hub.docker.com/_/debian)

## What's Added
* Sudo
* A regular user with the username "winner" and sudo access
* Nano editor
* Time stamp file, automatically displayed during every login

## What's the Point?
* This Docker image is a basic building block for all other Docker images for [Ruby on Racetracks](https://www.rubyonracetracks.com/).
* This Docker image is deliberately kept small in to minimize the time needed for building, uploading, and downloading this image.  This is useful for getting quick feedback when experimenting.

## More Information
General information common to all Docker Debian build repositories is in the [FAQ](https://gitlab.com/rubyonracetracks/docker-common/blob/master/FAQ.md).
