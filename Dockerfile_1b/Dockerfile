FROM ubuntu:latest

LABEL com.example.version="0.0.1-beta" \
      vendor1="ACME Incorporated" \
      vendor2=ZENITH\ Incorporated \
      com.example.release-date="2015-02-12" \
      com.example.version.is-production=""

RUN apt-get update && apt-get install -y \
    vim \
    sudo \
    curl \
    nmap \
    && rm -rf /var/lib/apt/lists/*