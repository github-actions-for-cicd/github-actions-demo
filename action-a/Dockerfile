FROM debian:9.13-slim

ADD entrypoint.sh /entrypoint.sh
RUN python --version
RUN chmod +x /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
