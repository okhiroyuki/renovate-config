FROM mcr.microsoft.com/devcontainers/javascript-node:5-22@sha256:99376c11fd6f94b8c30ee2ee7799c0592dbb8789694b488c1a9be2b7996d1e37

RUN apt-get update && apt-get install -y --no-install-recommends \
        pre-commit \
    && apt-get clean && rm -rf /var/lib/apt/lists/*
