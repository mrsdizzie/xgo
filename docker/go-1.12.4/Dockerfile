FROM techknowlogick/xgo:base

# Configure the root Go distribution and bootstrap based on it
ENV GO_VERSION 1124

RUN \
  export ROOT_DIST=https://storage.googleapis.com/golang/go1.12.4.linux-amd64.tar.gz    && \
  export ROOT_DIST_SHA=d7d1f1f88ddfe55840712dc1747f37a790cbcaa448f6c9cf51bbe10aa65442f5 && \
  \
$BOOTSTRAP_PURE
