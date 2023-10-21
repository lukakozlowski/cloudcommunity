FROM ubuntu:latest

LABEL com.example.version="0.0.1-beta"
LABEL vendor1="ACME Incorporated"
LABEL vendor2=ZENITH\ Incorporated
LABEL com.example.release-date="2015-02-12"
LABEL com.example.version.is-production=""

RUN apt-get update
RUN apt-get install vim -y
RUN apt-get install sudo -y
RUN apt-get install curl -y
RUN apt-get install nmap -y
#RUN rm -rf /var/lib/apt/lists/*