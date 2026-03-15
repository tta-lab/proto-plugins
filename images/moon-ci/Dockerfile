FROM node:22.14.0

RUN curl -fsSL https://moonrepo.dev/install/proto.sh | bash -s -- --yes

ENV PROTO_HOME=/root/.proto
ENV PATH="$PROTO_HOME/shims:$PROTO_HOME/bin:$PATH"
