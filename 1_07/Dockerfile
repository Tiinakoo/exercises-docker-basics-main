FROM ubuntu:24.04

RUN apt-get update && \
    apt-get install -y curl

COPY script.sh /script.sh

CMD ["/script.sh"]