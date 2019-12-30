FROM codefresh/workspace-manager:0.3.1 as workspace

FROM alpine:3.11

COPY --from=workspace /workspace-manager /usr/local/bin/

LABEL io.codefresh.engine="true"

RUN apk add --no-cache \
    bash \
    rsync