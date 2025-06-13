FROM fedora:latest

# Instala dependências
RUN dnf -y update && \
    dnf -y install fish gcc glibc-devel make git vim && \
    dnf clean all

WORKDIR /app

CMD ["fish"]