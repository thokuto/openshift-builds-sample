FROM registry.access.redhat.com/rhscl/nodejs-4-rhel7:latest

USER root

RUN yum install -y npm && yum clean all -y && npm install -g bower && npm install -g gulp