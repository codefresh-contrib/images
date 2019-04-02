FROM codefresh/workspace-manager:0.2.1 as workspace


FROM codefresh/cfbase

COPY --from=workspace /workspace-manager /usr/local/bin/

RUN apk update && \
    apk add rsync
