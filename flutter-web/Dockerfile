FROM pingu/flutter:latest

# Description:
# This Dockerfile uses the base-image built by the 'Dockerfile' in this repository
# and add the additionel dependency for flutter web.
# The instructions are inspired by the official doc to install flutter web: 
# https://flutter.dev/docs/get-started/web

MAINTAINER vinh-ngu@hotmail.com

# Enable flutter web
RUN flutter channel dev
RUN flutter upgrade
RUN flutter config --enable-web
