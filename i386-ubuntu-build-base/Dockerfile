FROM ioft/i386-ubuntu:16.04

RUN apt-get install -y software-properties-common && \
    add-apt-repository ppa:ubuntu-toolchain-r/test && apt-get update && \
    apt-get install -y wget cmake gcc-7 g++-7 build-essential && \
    update-alternatives --install /usr/bin/gcc gcc /usr/bin/gcc-7 10 --slave /usr/bin/g++ g++ /usr/bin/g++-7

