FROM node:22.14.0

SHELL ["/bin/bash", "-o", "pipefail", "-c"]

RUN curl -fsSL https://moonrepo.dev/install/moon.sh | bash && \
    /root/.moon/bin/moon --version

ENV PATH="/root/.moon/bin:$PATH"
