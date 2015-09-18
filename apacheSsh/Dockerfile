FROM centos:latest

MAINTAINER Libert Schmidt <rschmidt@libert.xyz>

RUN yum -y update
RUN yum -y install httpd
RUN echo "/sbin/service httpd start" >> /root/.bashrc

RUN yum -y install openssh-server
RUN echo "/sbin/service sshd start" >> /root/.bashrc

RUN echo "The system configuration is ended" > root

