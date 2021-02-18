FROM golang:1.10.5-alpine3.8

LABEL maintainer="aryoputrap@gmail.com"
WORKDIR /go/src/app
COPY jwb3.go .
RUN go build -o jwb3 .
EXPOSE 3000 
CMD ["./jwb3"]