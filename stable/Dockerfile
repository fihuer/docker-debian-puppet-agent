FROM debian:wheezy

MAINTAINER Romain Fihue <romain.fihue@gmail.com>

RUN wget -O /tmp/puppetlabs-release-wheezy.deb https://apt.puppetlabs.com/puppetlabs-release-wheezy.deb

RUN dpkg -i /tmp/puppetlabs-release-wheezy.deb

RUN apt-get update

RUN apt-get install puppet
