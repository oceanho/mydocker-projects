FROM centos:7
RUN yum -y install ruby rubygems ruby-devel && gem install fpm && \
yum clean all && rm -rf /var/cache/yum/*
CMD [ "tailf", "/dev/null" ]
