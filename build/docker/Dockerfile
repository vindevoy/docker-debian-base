FROM debian:11.2-slim

LABEL maintainer="Yves Vindevogel (vindevoy) - yves.vindevogel@asynchrone.com"

ARG TZ_REGION=Europe
ARG TZ_CITY=Brussels

ENV DEBIAN_FRONTEND noninteractive

RUN set -x && \ 
    apt-get update -y && \ 
    apt-get dist-upgrade -y && \ 
    apt-get install apt-utils --no-install-recommends -y && \ 
    apt-get autoremove && \ 
    apt-get clean all && \ 
    rm -f /etc/localtime && \ 
    ln -s /usr/share/zoneinfo/$TZ_REGION/$TZ_CITY /etc/localtime

CMD ["/bin/sh"]
