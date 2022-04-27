FROM zerotier/zerotier:latest

COPY entrypoint-custom.sh /entrypoint-custom.sh
RUN chmod 755 /entrypoint-custom.sh

HEALTHCHECK --interval=1s CMD bash /healthcheck.sh

CMD []
ENTRYPOINT ["/entrypoint-custom.sh"]