FROM techknowlogick/xgo:base

# Configure the root Go distribution and bootstrap based on it
ENV GO_VERSION 1117

RUN \
  export ROOT_DIST=https://storage.googleapis.com/golang/go1.11.7.linux-amd64.tar.gz    && \
  export ROOT_DIST_SHA=db687814288b3b541c1754dfd4ecc2b8fd0d5e7995624945e3054a350ca573d8 && \
  \
$BOOTSTRAP_PURE
