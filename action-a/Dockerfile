FROM debian:stretch-20211220-slim

ADD entrypoint.sh /entrypoint.sh
RUN python --version
RUN chmod +x /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
