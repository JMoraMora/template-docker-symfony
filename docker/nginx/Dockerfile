FROM nginx:1.19

ARG UID
EXPOSE $UID

RUN adduser -u ${UID} --disable-password --gecos "" appuser

COPY default.conf /etc/nginx/conf.d/