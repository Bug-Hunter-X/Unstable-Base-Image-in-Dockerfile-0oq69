# Unstable Base Image in Dockerfile

This repository demonstrates a common error in Dockerfiles: using an unstable base image (`ubuntu:latest`).  The provided Dockerfile uses `ubuntu:latest`, which can lead to unexpected behavior and build failures as the base image changes.

A fixed version is provided in `Dockerfile-fixed`, using a more specific version of Ubuntu.