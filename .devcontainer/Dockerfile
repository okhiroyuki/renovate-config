FROM mcr.microsoft.com/devcontainers/javascript-node:5-22@sha256:3bdc47194215f83b47b49fe5403ac6d8b105e704a19e2b2b3fcc88e8657fb33e

RUN apt-get update && apt-get install -y --no-install-recommends \
        pre-commit \
    && apt-get clean && rm -rf /var/lib/apt/lists/*
