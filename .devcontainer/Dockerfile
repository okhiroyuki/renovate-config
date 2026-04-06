FROM mcr.microsoft.com/devcontainers/javascript-node:4-22@sha256:a01a914a47f9693114101e24e1cdede1fa76a286f03ee98d11a373a64dbd0e5e

RUN apt-get update && apt-get install -y --no-install-recommends \
        pre-commit \
    && apt-get clean && rm -rf /var/lib/apt/lists/*
