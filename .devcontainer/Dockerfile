FROM mcr.microsoft.com/devcontainers/javascript-node:5-22@sha256:d09635f31d8a29c1040fc99e1edc0ce5da16334aefdfd31cbbebf4ac90bf5b83

RUN apt-get update && apt-get install -y --no-install-recommends \
        pre-commit \
    && apt-get clean && rm -rf /var/lib/apt/lists/*
