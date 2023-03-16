FROM mcr.microsoft.com/devcontainers/base:focal

RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && curl -sSL https://dl.google.com/linux/direct/google-chrome-stable_current_$(dpkg --print-architecture).deb -o /tmp/chrome.deb \
    && apt-get -y install /tmp/chrome.deb

RUN apt-get update && export DEBIAN_FRONTEND=noninteractive && apt-get install -y firefox libreoffice
