# FROM registry.access.redhat.com/rhscl/nodejs-4-rhel7:latest
FROM registry.access.redhat.com/openshift3/nodejs-010-rhel7:latest

USER root

# RUN yum-config-manager --enable rhel-server-rhscl-7-rpms && yum-config-manager --enable rhel-7-server-optional-rpms && yum install -y npm && yum clean all -y && npm install -g bower && npm install -g gulp

RUN npm install -g bower && npm install -g gulp