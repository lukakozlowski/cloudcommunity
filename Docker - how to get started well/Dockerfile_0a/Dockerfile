FROM ubuntu:latest
LABEL com.example.version="0.0.1-alfa"
ENV MY_NAME="John Doe"
WORKDIR /tmp
RUN apt-get update && apt-get install -y \
    cron \
    sudo \
    vim \
    nginx \
    && rm -rf /var/lib/apt/lists/*
COPY index.html /var/www/html
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]