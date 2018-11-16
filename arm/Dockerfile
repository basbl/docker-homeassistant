FROM homeassistant/raspberrypi3-homeassistant:0.82.1
MAINTAINER Bas Bloembergen <basbloembergen@gmail.com>

RUN apk -U update && \
    apk -U upgrade \
    && rm -rf /var/cache/apk/*

# RUN pip install --upgrade pip
RUN pip3 install https://storage.googleapis.com/tensorflow/linux/cpu/tensorflow-1.12.0-cp36-cp36m-linux_x86_64.whl