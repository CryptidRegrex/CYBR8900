# Run dnsmasq on container start
FROM debian:bullseye

RUN apt-get update && \
    apt-get install -y dnsmasq && \
    apt-get clean

# Run dnsmasq on container start
COPY dnsmasq.conf /etc/dnsmasq.conf

# Run dnsmasq on container start
CMD ["dnsmasq", "-d"]