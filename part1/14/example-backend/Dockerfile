FROM golang

EXPOSE 8080

WORKDIR /usr/src/app

COPY . .

ENV PORT=8080
ENV REQUEST_ORIGIN=http://localhost:5000

RUN go build

CMD ./server
