FROM alpine

RUN apk add --update ca-certificates \
    && apk add bash curl jq\
    && rm /var/cache/apk/* \
    && rm -rf /tmp/*

ENTRYPOINT bash
