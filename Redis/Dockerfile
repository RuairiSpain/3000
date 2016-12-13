FROM ubuntu:latest
ARG BUILT=2018-01-01​
RUN echo ${BUILT} " by root" >> /build.log
RUN useradd -ms /bin/bash me
USER me
WORKDIR /home/me