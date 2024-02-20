FROM mcr.microsoft.com/devcontainers/typescript-node:1-20-bullseye

ADD xpra.asc /usr/share/keyrings/
ADD xpra.sources /etc/apt/sources.list.d/
RUN apt update && DEBIAN_FRONTEND=noninteractive apt install -y xpra dbus-x11 x11-apps 