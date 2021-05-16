FROM ubuntu:18.04

WORKDIR /usr/src/app

COPY curler.sh .

RUN apt update
RUN apt install curl -y

CMD ./curler.sh