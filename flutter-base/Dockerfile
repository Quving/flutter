FROM debian:stable-slim

# Description
# This Dockerfile is inspired by the official docs to install flutter on linux.
# Source: https://flutter.dev/docs/get-started/install/linux

MAINTAINER vinh-ngu@hotmail.com


RUN apt update && apt install -y wget xz-utils git curl unzip

# Select flutter version.
ENV FLUTTER_VERSION "flutter_linux_v1.9.1+hotfix.6-stable.tar.xz"

# Install flutter
RUN wget "https://storage.googleapis.com/flutter_infra/releases/stable/linux/"${FLUTTER_VERSION}
ENV PATH="$PATH:/flutter/bin"
RUN tar xf ${FLUTTER_VERSION}
RUN rm ${FLUTTER_VERSION}

RUN flutter --help
RUN flutter precache
RUN flutter doctor

