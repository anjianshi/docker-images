FROM alpine:3.12

RUN echo "http://mirrors.aliyun.com/alpine/v3.12/main" > /etc/apk/repositories && echo "http://mirrors.aliyun.com/alpine/v3.12/community" >> /etc/apk/repositories
RUN apk add --no-cache rsync sshpass openssh && rm -rf /var/cache/apk/*
