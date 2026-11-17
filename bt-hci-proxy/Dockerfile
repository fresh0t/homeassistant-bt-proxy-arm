ARG BUILD_FROM
FROM $BUILD_FROM

RUN apk add --no-cache bluez bluez-btmgmt dbus

COPY run.sh /run.sh
RUN chmod a+x /run.sh

CMD ["/run.sh"]
