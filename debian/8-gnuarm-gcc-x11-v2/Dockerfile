FROM ilegeul/debian:8-gnuarm-gcc-x11
MAINTAINER Liviu Ionescu <ilg@livius.net>
WORKDIR /root

RUN \
apt-get -y update && \
apt-get -y upgrade && \
apt-get -y install chrpath

CMD ["/bin/bash"]

