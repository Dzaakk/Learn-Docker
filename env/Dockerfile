FROM golang:1.18-alpine

ENV APP_PORT=8080

RUN mkdir app
COPY main.go app

EXPOSE ${APP_PORT}

CMD go run app/main.go

# docker container create --name env --env APP_PORT=9090 -p 9090:9090 dzaakk/env