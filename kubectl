FROM codefresh/cfbase

ARG KUBECTL_VERSION

RUN curl -L "https://storage.googleapis.com/kubernetes-release/release/v${KUBECTL_VERSION}/bin/linux/amd64/kubectl" -o /usr/local/bin/kubectl \
    && chmod +x /usr/local/bin/kubectl

CMD bash
