FROM mcr.microsoft.com/devcontainers/javascript-node:1-22@sha256:d493ef047b5ee96655fb543919e6e036dc87582509e6c622c9fe999b6eeb5148

RUN apt-get update && apt-get install -y --no-install-recommends \
        pre-commit \
    && apt-get clean && rm -rf /var/lib/apt/lists/*
