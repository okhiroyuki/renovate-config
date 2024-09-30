FROM mcr.microsoft.com/devcontainers/javascript-node:1-22@sha256:61c3428ca51d3e899b4d2850e0395fd72d67c7e7de5139c9a9d7d6e2843e3284

RUN apt-get update && apt-get install -y --no-install-recommends \
        pre-commit \
    && apt-get clean && rm -rf /var/lib/apt/lists/*
