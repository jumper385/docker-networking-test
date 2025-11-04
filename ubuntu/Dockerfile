# Dockerfile
FROM ubuntu:24.04

# Avoid interactive prompts
ENV DEBIAN_FRONTEND=noninteractive

# OS packages
RUN apt-get update && \
    apt-get install -y --no-install-recommends \
        curl \
        git \
        vim \
        build-essential \
        python3 \
        python3-pip \
	iproute2 \
	sudo \
	net-tools \
	iputils-ping \
    && rm -rf /var/lib/apt/lists/*
