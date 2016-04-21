FROM alpine:edge
MAINTAINER ckeyer <me@ckeyer.com>

RUN apk add --update git subversion vim make go gcc g++ curl bash bash-completion

ENV GOPATH=/go
ENV PATH=$PATH:$GOPATH/bin
