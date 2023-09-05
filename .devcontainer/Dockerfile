FROM mcr.microsoft.com/devcontainers/php:1-8.2-bullseye

# Install Chrome for Desktop Testing through VNC
RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
  && curl -sSL https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb -o /tmp/chrome.deb \
  && apt-get -y install /tmp/chrome.deb