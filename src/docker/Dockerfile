###
#
#	Yves Vindevogel (vindevoy)
#	2019-10-25
#
#	Basic Debian 10 (slim version) image with possibility to change the timezone
#
###
 
FROM debian:10-slim

LABEL maintainer="Yves Vindevogel (vindevoy) - yves.vindevogel@asynchrone.com"

ARG TZ_REGION=Europe
ARG TZ_CITY=Brussels

RUN rm -f /etc/localtime
RUN ln -s /usr/share/zoneinfo/$TZ_REGION/$TZ_CITY /etc/localtime

CMD ["/bin/sh"]
