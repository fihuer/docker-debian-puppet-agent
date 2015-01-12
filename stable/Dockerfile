FROM debian:wheezy

MAINTAINER Romain Fihue <romain.fihue@gmail.com>

RUN apt-get update   
RUN apt-get install -y wget

RUN wget -O /tmp/puppetlabs-release-wheezy.deb https://apt.puppetlabs.com/puppetlabs-release-wheezy.deb

RUN dpkg -i /tmp/puppetlabs-release-wheezy.deb

RUN apt-get update

RUN apt-get install puppet
