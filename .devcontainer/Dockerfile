FROM mcr.microsoft.com/devcontainers/javascript-node:4-22@sha256:e3e9ad58dd68386c000354e8f65fa1e66adb452bbb138b7c871c760155eac06d

RUN apt-get update && apt-get install -y --no-install-recommends \
        pre-commit \
    && apt-get clean && rm -rf /var/lib/apt/lists/*
