FROM mcr.microsoft.com/devcontainers/javascript-node:0-18

# Install Chrome for Desktop Testing through VNC
RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
  && curl -sSL https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb -o /tmp/chrome.deb \
  && apt-get -y install /tmp/chrome.deb