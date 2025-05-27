FROM fedora:latest

RUN dnf -y update && \
    dnf -y install gcc && \
    dnf -y install fish && \
    dnf clean all

RUN mkdir -p /app
WORKDIR /app

CMD ["fish"]