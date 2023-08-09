FROM golang:1.18-alpine

RUN mkdir /app

RUN addgroup -S dzgroup
RUN adduser -S -D -h /app dzkdzk dzgroup
RUN chown -R dzkdzk:dzgroup /app

USER dzkdzk

COPY main.go /app

EXPOSE 8080
CMD go run /app/main.go