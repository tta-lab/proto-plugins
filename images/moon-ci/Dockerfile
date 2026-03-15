FROM node:22.14.0

RUN curl -fsSL https://moonrepo.dev/install/moon.sh | bash -s -- --yes 2>/dev/null || \
    curl -fsSL https://moonrepo.dev/install/moon.sh | bash

ENV PATH="/root/.moon/bin:$PATH"
