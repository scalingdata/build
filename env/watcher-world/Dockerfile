# Copyright 2015 The Go Authors. All rights reserved.
# Use of this source code is governed by a BSD-style
# license that can be found in the LICENSE file.

# Commit watcher's environment for Go repos, but without the commit
# watcher itself. That is now folded into the coordinator binary
# itself. This Dockerfile is just the environment in which that binary
# then runs.

FROM debian:sid
MAINTAINER golang-dev <golang-dev@googlegroups.com>

ENV DEBIAN_FRONTEND noninteractive

ADD /scripts/install-apt-deps.sh /scripts/
RUN /scripts/install-apt-deps.sh
