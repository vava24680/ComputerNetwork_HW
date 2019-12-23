FROM openjdk:8-alpine

WORKDIR /computer_network

RUN set -x && \
    apk update && \
    apk add --no-cache bash tar && \
    mkdir -p /computer_network/gns && \
    wget https://github.com/MobilityFirst/GNS/releases/download/v1.19.16/GNS-1.19.16.tgz && \
    tar -zxf GNS-1.19.16.tgz -C gns --strip=1
