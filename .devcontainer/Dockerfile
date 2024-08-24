FROM mcr.microsoft.com/devcontainers/javascript-node:1-22@sha256:aedf26ccde02f734a8d8879778f5daac6c71609bb1df1b5a3e9d708f3c2827a2

RUN apt-get update && apt-get install -y --no-install-recommends \
        pre-commit \
    && apt-get clean && rm -rf /var/lib/apt/lists/*
