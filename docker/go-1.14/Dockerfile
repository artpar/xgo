# Go cross compiler (xgo): Go 1.11.1
# Copyright (c) 2018 Péter Szilágyi. All rights reserved.
#
# Released under the MIT license.

FROM karalabe/xgo-base

MAINTAINER Péter Szilágyi <peterke@gmail.com>

# Configure the root Go distribution and bootstrap based on it
ENV GO_VERSION 114
RUN \
  export ROOT_DIST=https://dl.google.com/go/go1.14.linux-amd64.tar.gz    && \
  export ROOT_DIST_SHA=b449f1b0daf8435cd25387901b296eeacd115d38 && \
  \
  $BOOTSTRAP_PURE

