FROM golang:1.16-alpine3.13

COPY ./example-backend .

RUN go build

EXPOSE 8080

CMD ["./server"]