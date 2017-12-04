FROM centos:7
RUN yum -y --nogpgcheck install ruby-devel gcc make rpm-build rubygems epel-release && gem install fpm -V && \
yum clean all && rm -rf /var/cache/yum/*
CMD [ "tailf", "/dev/null" ]
