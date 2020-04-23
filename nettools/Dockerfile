FROM ubuntu:latest

ADD netperf_scripts /root/netperf_scripts
RUN apt update -y
RUN apt install -y jq \
    netperf \
    net-tools \
    tuned \
    psmisc \
    curl \
    qperf \
    iproute2
