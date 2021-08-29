FROM golang:1.16-alpine3.13

COPY ./example-backend /app
WORKDIR /app
RUN go build
ENV REQUEST_ORIGIN=http://localhost:3000

EXPOSE 8080
CMD ["./server"]
