# [Choice] Node.js version: 14, 16, 17
FROM node:latest

# Install Python
ARG PYTHON_VERSION="3.10"
RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && apt-get -y install --no-install-recommends python${PYTHON_VERSION} python3-pip python3-venv \
    && apt-get clean -y && rm -rf /var/lib/apt/lists/*
