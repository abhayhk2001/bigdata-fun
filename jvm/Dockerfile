FROM ubuntu:16.04
MAINTAINER Karl Stoney <me@karlstoney.com> 

VOLUME /data

ENV JAVA_HOME /usr/lib/jvm/openjdk-8-jdk
ENV JAVA_OPTS "-Xms512m -Xmx2g"
ENV TERM xterm-256color

# Get dependencies
RUN apt update
RUN apt -y -q install curl wget openjdk-8-jdk openjdk-8-jdk-headless

CMD ["/bin/true"]
