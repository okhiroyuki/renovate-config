FROM mcr.microsoft.com/devcontainers/javascript-node:1-22@sha256:1ab856e1911cc980d1439b0758f8772236b539da67b79a82f8248ce014c37c8c

RUN apt-get update && apt-get install -y --no-install-recommends \
        pre-commit \
    && apt-get clean && rm -rf /var/lib/apt/lists/*
