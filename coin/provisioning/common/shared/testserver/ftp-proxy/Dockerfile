FROM qt_ubuntu_16.04
ARG packages="avahi-daemon ftp-proxy"
RUN apt-get update && apt-get install -y $packages && dpkg -l $packages
EXPOSE 2121
