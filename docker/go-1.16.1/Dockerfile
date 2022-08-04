# Go cross compiler (xgo): Go 1.13.4
# Copyright (c) 2019 Péter Szilágyi. All rights reserved.
#
# Released under the MIT license.

FROM karalabe/xgo-base

MAINTAINER Péter Szilágyi <peterke@gmail.com>

# Configure the root Go distribution and bootstrap based on it
ENV GO_VERSION 11601

RUN \
  export ROOT_DIST=https://storage.googleapis.com/golang/go1.16.1.linux-amd64.tar.gz    && \
  export ROOT_DIST_SHA=3edc22f8332231c3ba8be246f184b736b8d28f06ce24f08168d8ecf052549769 && \
  \
  $BOOTSTRAP_PURE
