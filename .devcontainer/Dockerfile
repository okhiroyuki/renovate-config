FROM mcr.microsoft.com/devcontainers/javascript-node:4-22@sha256:aac847b276570cac53f0fef23733793a38190e655cecd7b74c5cac7816b6ff53

RUN apt-get update && apt-get install -y --no-install-recommends \
        pre-commit \
    && apt-get clean && rm -rf /var/lib/apt/lists/*
