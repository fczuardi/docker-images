# Ubuntu LTS and Node LTS as defaults
ARG ubuntu_base=fczuardi/bionic
ARG node_version=10.16.3

FROM ${ubuntu_base} AS ubuntu
MAINTAINER Fabricio Zuardi <fabricio@fabricio.org>
ARG ubuntu_base
ARG node_version
ENV download_url https://nodejs.org/dist/v${node_version}/node-v${node_version}-linux-x64.tar.xz

RUN echo Ubuntu base is: $ubuntu_base

RUN echo Nodejs version is: $node_version

RUN echo Download URL is: $download_url

