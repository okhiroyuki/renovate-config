FROM mcr.microsoft.com/devcontainers/javascript-node:5-22@sha256:cd275c65a4b27a7790de915909be221d585fe645cf976cb1113b1ea9f62610d3

RUN apt-get update && apt-get install -y --no-install-recommends \
        pre-commit \
    && apt-get clean && rm -rf /var/lib/apt/lists/*
