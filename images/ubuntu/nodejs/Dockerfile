ARG ubuntu_base=fczuardi/bionic

FROM ${ubuntu_base} AS ubuntu
MAINTAINER Fabricio Zuardi <fabricio@fabricio.org>
ARG ubuntu_base
ARG DOCKER_TAG
ARG NODE_VERSION
RUN echo Ubuntu base is: $ubuntu_base
RUN echo Docker tag is: $DOCKER_TAG
RUN echo Node version is: $NODE_VERSION
ENV download_url https://nodejs.org/dist/v10.16.3/node-v10.16.3-linux-x64.tar.xz
RUN echo Download URL is: $download_url
ENV download_url https://nodejs.org/dist/v$NODE_VERSION/node-v$NODE_VERSION-linux-x64.tar.xz
RUN echo Download URL is: $download_url
ENV download_url https://nodejs.org/dist/v$DOCKER_TAG/node-v$DOCKER_TAG-linux-x64.tar.xz


