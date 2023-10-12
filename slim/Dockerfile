FROM alpine:3.18
LABEL maintainer "f97 <huynhduckhoan@gmail.com>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --no-cache \
    git \
    bash \
    nodejs

RUN apk --purge del apk-tools