FROM codefresh/workspace-manager as workspace


FROM codefresh/cfbase

COPY --from=workspace /workspace-manager /usr/local/bin/

RUN apk update && \
    apk add rsync