FROM mcr.microsoft.com/devcontainers/base:alpine

USER vscode

RUN apt-get update && apt-get install -y \
    build-essential \
    udev \
    git \
    && rm -rf /var/lib/apt/lists/* \
    && pip3 install --no-cache-dir platformio