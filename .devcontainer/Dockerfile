FROM mcr.microsoft.com/devcontainers/javascript-node:4-22@sha256:d2cfecfcd1cf79b0a0b03796c5fd777601b76f8948cd423c1cd06a6e5a3c718a

RUN apt-get update && apt-get install -y --no-install-recommends \
        pre-commit \
    && apt-get clean && rm -rf /var/lib/apt/lists/*
