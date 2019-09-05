# Ubuntu 18.04 and Node 10.16.3 as defaults
ARG ubuntu_base=fczuardi/bionic
ARG node_version=10.16.3

# image containing downloaded binaries
FROM fczuardi/node_download:${node_version} as download

FROM ${ubuntu_base}
WORKDIR "/opt/node"
COPY --from=download /opt/node/bin bin
ENV PATH=$PATH:/opt/node/bin
