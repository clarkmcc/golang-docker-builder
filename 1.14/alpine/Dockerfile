FROM golang:1.14-alpine

MAINTAINER clarkmccauley@gmail.com

# Install Docker and dependencies
RUN apk --update add \
  bash \
  iptables \
  ca-certificates \
  e2fsprogs \
  docker \
  && rm -rf /var/cache/apk/*
