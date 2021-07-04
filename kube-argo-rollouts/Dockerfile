ARG KUBECTL_VERSION=latest

FROM codefresh/kubectl:${KUBECTL_VERSION}

WORKDIR /tmp

RUN curl -LO "https://github.com/argoproj/argo-rollouts/releases/latest/download/kubectl-argo-rollouts-linux-amd64" \
    && chmod +x ./kubectl-argo-rollouts-linux-amd64 \
    && mv ./kubectl-argo-rollouts-linux-amd64 /usr/local/bin/kubectl-argo-rollouts

WORKDIR ~

ENTRYPOINT ["bash"]
