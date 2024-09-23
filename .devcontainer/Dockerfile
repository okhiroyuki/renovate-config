FROM mcr.microsoft.com/devcontainers/javascript-node:1-22@sha256:426f06d22e8a81d047d7cae9c08509907d2663bc137ccc6ba597ddd8a6808aa1

RUN apt-get update && apt-get install -y --no-install-recommends \
        pre-commit \
    && apt-get clean && rm -rf /var/lib/apt/lists/*
