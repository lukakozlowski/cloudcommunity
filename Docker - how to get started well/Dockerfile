FROM nginx:latest

ARG TEST=CloudCommunity

RUN apt-get update && apt-get install -y \
    vim \
    curl \
    && rm -rf /var/lib/apt/lists/*

RUN ["/bin/bash", "-c", "touch /var/cloudcommunity && echo $TEST > /var/cloudcommunity"]