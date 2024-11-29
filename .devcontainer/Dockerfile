# Use the specified base image
FROM registry.gitlab.com/islandoftex/images/texlive:latest

# Install additional packages if needed
RUN apt-get update && apt-get install -y \
    openssh-client \
    git \
    && rm -rf /var/lib/apt/lists/*