FROM mcr.microsoft.com/devcontainers/go:1-1.23-bookworm

# Install tools
#RUN apt-get update && apt-get install -y \
#    curl \
#    git \
#    unzip \
#    && rm -rf /var/lib/apt/lists/*

# Install the Modus CLI
RUN npm install -g @hypermode/modus-cli

RUN modus sdk install go --force
