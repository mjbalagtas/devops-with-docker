#!/usr/bin/env sh

FROM golang:1.16
WORKDIR /usr/src/app
EXPOSE 8080
COPY ./material-applications/example-backend .
RUN go build
CMD ["./server"]
