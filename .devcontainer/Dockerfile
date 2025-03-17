FROM mcr.microsoft.com/devcontainers/javascript-node:1-22@sha256:78fda8c284dd3247d7385d55974e278314233f1acc130ba89757703137dbda45

RUN apt-get update && apt-get install -y --no-install-recommends \
        pre-commit \
    && apt-get clean && rm -rf /var/lib/apt/lists/*
