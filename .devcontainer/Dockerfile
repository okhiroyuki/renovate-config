FROM mcr.microsoft.com/devcontainers/javascript-node:1-22

RUN apt-get update && apt-get install -y --no-install-recommends \
        pre-commit \
    && apt-get clean && rm -rf /var/lib/apt/lists/*
