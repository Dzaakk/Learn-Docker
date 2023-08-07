FROM alpine:3

RUN mkdir hello
RUN echo "Hello Command" > "hello/command.txt"

CMD cat "hello/command.txt"

# docker build -t dzaakk/command command
# docker image inspect dzaakk/command
# docker container create --name command dzaakk/command
# docker container start command
# docker container logs command