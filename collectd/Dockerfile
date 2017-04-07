FROM centos:7
MAINTAINER Matthias Runge <mrunge@redhat.com>

RUN yum install -y centos-release-opstools
RUN yum install -y collectd

ADD collectd.conf /etc/collectd.conf
CMD ["/usr/sbin/collectd", "-f"]
