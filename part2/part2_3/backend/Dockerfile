FROM golang:1.16

WORKDIR /usr/src/app

COPY example-backend/ .

ENV PORT=8000

ENV REQUEST_ORIGIN=*

RUN go build

CMD ./server

EXPOSE 8000