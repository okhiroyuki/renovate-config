FROM mcr.microsoft.com/devcontainers/javascript-node:1-22@sha256:f1e8fdca29c437891d8d793bf59d368e4c1850884c22161f7401086da63332d4

RUN apt-get update && apt-get install -y --no-install-recommends \
        pre-commit \
    && apt-get clean && rm -rf /var/lib/apt/lists/*
