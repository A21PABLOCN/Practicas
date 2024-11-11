FROM debian:12

RUN apt update && apt install -y net-tools procps most iproute2  iputils-ping dnsutils bind9 bind9utils

RUN apt clean && rm -rf /var/lib/apt/lists/*

ENTRYPOINT ["tail", "-f", "/dev/null"]