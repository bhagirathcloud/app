FROM bitnami/minideb-extras:jessie

MAINTAINER Bitnami <containers@bitnami.com>

COPY app-code/http-sample /app/http-sample

USER bitnami

WORKDIR /app

EXPOSE 3000

ENTRYPOINT ["/app/http-sample"]

