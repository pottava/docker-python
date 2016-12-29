# Python v3.5.2
# docker run --rm pottava/python:3.5 python --version

FROM alpine:3.5

RUN apk --no-cache add python3 \
    && ln -sf /usr/bin/python3.5 /usr/bin/python

CMD ["/usr/bin/python", "--version"]
