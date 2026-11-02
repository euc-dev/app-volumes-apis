FROM mcr.microsoft.com/devcontainers/base:bookworm@sha256:73d85a96694a2cadca1ba3fcb5721f2312a64f1d571dd86f6c77e10a708931dc
RUN apt-get update && \
    export DEBIAN_FRONTEND=noninteractive && \
    apt-get -y install \
        python3 \
        python3-pip && \
    apt clean && \
    rm -rf /usr/lib/python3.11/EXTERNALLY-MANAGED
