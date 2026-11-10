FROM mcr.microsoft.com/devcontainers/base:1.0.0-alpine-3.19

USER vscode

RUN apt-get update && apt-get install -y \
    build-essential \
    udev \
    git \
    && rm -rf /var/lib/apt/lists/* \
    && pip3 install --no-cache-dir platformio