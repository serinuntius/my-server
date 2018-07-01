FROM alpine:latest

RUN apk --update add \
    curl \
    zip

RUN mkdir /myapp

RUN curl -L https://github.com/acidlemon/mirage/releases/download/v0.3.1/mirage-v0.3.1-linux-amd64.zip > mirage.zip && \
    unzip mirage.zip && \
    mv mirage/* /myapp

WORKDIR /myapp
