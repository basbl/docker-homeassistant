FROM homeassistant/raspberrypi3-homeassistant:0.82.1
MAINTAINER Bas Bloembergen <basbloembergen@gmail.com>

RUN apk -U update && \
    apk -U upgrade \
    && rm -rf /var/cache/apk/*

RUN pip3 install --upgrade pip3 && pip3 install tensorflow==1.11.0