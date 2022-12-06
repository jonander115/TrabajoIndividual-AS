FROM httpd:alpine

RUN apk -qq update
ADD app/ /usr/local/apache2/htdocs

CMD ["httpd-foreground"]
