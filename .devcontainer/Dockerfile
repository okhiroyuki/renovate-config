FROM mcr.microsoft.com/devcontainers/javascript-node:1-22@sha256:b3030464fe18c02840992f9b0b46422e0ea3589a424c9617efda22b71308f023

RUN apt-get update && apt-get install -y --no-install-recommends \
        pre-commit \
    && apt-get clean && rm -rf /var/lib/apt/lists/*
