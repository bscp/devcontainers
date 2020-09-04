FROM ubuntu:20.04

RUN apt-get update \
   && apt-get -y install --no-install-recommends git nano \
   #
   # Clean up
   && apt-get autoremove -y \
   && apt-get clean -y \
   && rm -rf /var/lib/apt/lists/*

RUN mkdir /workspace