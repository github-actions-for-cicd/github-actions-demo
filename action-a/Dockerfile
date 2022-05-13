FROM debian:stretch-20220509-slim

ADD entrypoint.sh /entrypoint.sh
RUN python --version
RUN chmod +x /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
