FROM mcr.microsoft.com/devcontainers/javascript-node:5-22@sha256:2dffe9cdd928c3ebf074fb47b6a37df7934d090df160fae46aa4eb36780942ea

RUN apt-get update && apt-get install -y --no-install-recommends \
        pre-commit \
    && apt-get clean && rm -rf /var/lib/apt/lists/*
