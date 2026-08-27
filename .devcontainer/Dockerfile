FROM mcr.microsoft.com/devcontainers/javascript-node:5-22@sha256:fcbc5024294e6d60cbd4661d2f908fe10d3411d1427c3101321d85f7b553ad2c

RUN apt-get update && apt-get install -y --no-install-recommends \
        pre-commit \
    && apt-get clean && rm -rf /var/lib/apt/lists/*
