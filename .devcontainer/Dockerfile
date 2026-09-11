FROM mcr.microsoft.com/devcontainers/javascript-node:5-22@sha256:7168390386e56b74bf966aaf076f13b67e5b7290133489d18e0d0a818633dab7

RUN apt-get update && apt-get install -y --no-install-recommends \
        pre-commit \
    && apt-get clean && rm -rf /var/lib/apt/lists/*
