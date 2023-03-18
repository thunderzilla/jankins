FROM alpine
RUN df -h
RUN apk add --no-cache mysql-client && \
    df -h
RUN apk add --no-cache postgresql-client
ENTRYPOINT ["mysql"]
RUN hostname