FROM mcr.microsoft.com/devcontainers/javascript-node:5-22@sha256:d13ec0be0bd5bcf0a9c55b104e5ce0ee34d3b2140dd34aab838d0e29ac134557

RUN apt-get update && apt-get install -y --no-install-recommends \
        pre-commit \
    && apt-get clean && rm -rf /var/lib/apt/lists/*
