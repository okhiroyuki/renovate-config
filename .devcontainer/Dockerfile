FROM mcr.microsoft.com/devcontainers/javascript-node:1-22@sha256:be11ae66559ef546d02d407b9f4303391c291182b91d1013f16dc665a53fae82

RUN apt-get update && apt-get install -y --no-install-recommends \
        pre-commit \
    && apt-get clean && rm -rf /var/lib/apt/lists/*
