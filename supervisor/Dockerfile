FROM alpine:edge
MAINTAINER ckeyer <me@ckeyer.com>

RUN apk add --no-cache tzdata supervisor && \
	mkdir /etc/supervisor.d/ && \
    cp /usr/share/zoneinfo/Asia/Shanghai /etc/localtime && \
    echo "Asia/Shanghai" > /etc/timezone
