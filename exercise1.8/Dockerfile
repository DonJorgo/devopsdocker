FROM ubuntu:20.04

RUN apt-get update; apt-get install -y curl;

WORKDIR /usr/src/app

COPY readsite.sh .

RUN chmod +x readsite.sh

CMD ./readsite.sh

