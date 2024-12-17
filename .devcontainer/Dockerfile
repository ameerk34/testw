FROM mcr.microsoft.com/devcontainers/universal:2-linux

# Install Python3 and pip
RUN apt-get update && \
    apt-get install -y python3 python3-pip && \
    pip3 install --no-cache-dir django
