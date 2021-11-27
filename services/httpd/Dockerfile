FROM httpd:alpine

RUN adduser -D -h /home/container container

USER container

CMD [ "httpd-foreground" ]
