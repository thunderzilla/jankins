FROM alpine
RUN df -h
RUN apk add --no-cache mysql-client
RUN df -h
RUN hostname
ENTRYPOINT ["mysql"]