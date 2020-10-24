FROM debian:10-slim

LABEL maintainer="Yves Vindevogel (vindevoy) - yves.vindevogel@asynchrone.com"

ARG TZ_REGION=Europe
ARG TZ_CITY=Brussels

RUN set -x && \ 
    rm -f /etc/localtime && \ 
    ln -s /usr/share/zoneinfo/$TZ_REGION/$TZ_CITY /etc/localtime

CMD ["/bin/sh"]
