FROM alpine:3.6
ARG tshark_version

RUN \
    apk update && \
    apk add tshark=${tshark_version}

CMD ["sh"]