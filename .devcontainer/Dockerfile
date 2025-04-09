FROM mcr.microsoft.com/devcontainers/javascript-node:1-22@sha256:ee45bc4188a3804b597f707ceeaea98c59f118722d40094eaba3d71ca00fd3c8

RUN apt-get update && apt-get install -y --no-install-recommends \
        pre-commit \
    && apt-get clean && rm -rf /var/lib/apt/lists/*
