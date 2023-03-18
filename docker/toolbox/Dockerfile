FROM alpine
RUN df -h
RUN apk add --no-cache mysql-client && \
    df -h
RUN hostname
ENTRYPOINT ["mysql"]
