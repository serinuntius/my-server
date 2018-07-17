FROM alpine:latest

RUN mkdir /myapp

WORKDIR /myapp

ADD config.yml .
ADD mirage .

CMD ["./mirage"]