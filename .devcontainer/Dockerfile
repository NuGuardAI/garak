FROM mcr.microsoft.com/devcontainers/python:3.12-slim

# Install system dependencies
RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && apt-get -y install --no-install-recommends libmagic1 libsndfile1
