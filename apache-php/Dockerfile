FROM centos:7
RUN yum -y update && \
  yum -y install https://rpms.remirepo.net/enterprise/remi-release-7.rpm httpd && \
  yum -y install --enablerepo=remi-php80 php
EXPOSE 80
CMD ["/usr/sbin/httpd", "-D", "FOREGROUND"]