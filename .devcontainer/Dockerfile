FROM mcr.microsoft.com/devcontainers/javascript-node:5-22@sha256:47d7cc5f0521da0dae71cc327756da1932f27e35314f4c138e64fd1c3031497c

RUN apt-get update && apt-get install -y --no-install-recommends \
        pre-commit \
    && apt-get clean && rm -rf /var/lib/apt/lists/*
