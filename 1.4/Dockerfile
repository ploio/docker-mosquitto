# VERSION 1.4.8.r2
# AUTHOR:         Nicolas Lamirault <nicolas.lamirault@gmail.com>
# DESCRIPTION:    portefaix/grafana

FROM portefaix/base:3.4
MAINTAINER Nicolas Lamirault <nicolas.lamirault@gmail.com>

RUN apk add --update mosquitto=1.4.8-r2 && \
    rm -rf /var/cache/apk/*

VOLUME /etc/mosquitto/

EXPOSE 1883 9001

ENTRYPOINT ["mosquitto"]
