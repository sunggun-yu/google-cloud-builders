FROM gcr.io/gcp-runtimes/ubuntu_20_0_4

RUN apt-get -y update && \
    apt-get -y install \
      apt-transport-https \
      ca-certificates \
      curl \
      dnsutils \
      inetutils-traceroute \
      inetutils-ping \
      net-tools \
      netcat && \
    rm -rf /var/lib/apt/lists/*
