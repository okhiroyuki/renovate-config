FROM mcr.microsoft.com/devcontainers/javascript-node:1-22@sha256:896bfba10582c9239d1c36bab53b80af06253019f62b846fa440ee643ca63eb1

RUN apt-get update && apt-get install -y --no-install-recommends \
        pre-commit \
    && apt-get clean && rm -rf /var/lib/apt/lists/*
