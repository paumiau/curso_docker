FROM alpine:latest
RUN apk update && \
    apk add --no-cache squid

COPY squid.conf /etc/squid/squid.conf
EXPOSE 3128

CMD ["squid", "-NYCd", "1"]
