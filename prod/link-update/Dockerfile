FROM alpine:latest

MAINTAINER Pedro Angelo <pangelo@void.io>

#COPY documenta-update-links.sh /usr/bin

COPY update-links /etc/periodic/15min

RUN apk update && apk add apk-cron

CMD crond -f -d 8

