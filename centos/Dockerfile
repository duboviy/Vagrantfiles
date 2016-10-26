FROM centos
MAINTAINER Eugene Duboviy <eugene.dubovoy@gmail.com> | github.com/duboviy

RUN yum -y install httpd
RUN yum -y install php

CMD ["/usr/sbin/apachectl", "-DFOREGROUND"]
