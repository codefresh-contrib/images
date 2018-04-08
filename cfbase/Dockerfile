FROM alpine

RUN apk add --update ca-certificates \
    && apk add coreutils bash curl jq\
    && rm /var/cache/apk/* \
    && rm -rf /tmp/*

CMD ["bash"]