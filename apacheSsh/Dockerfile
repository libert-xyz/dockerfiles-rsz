FROM centos:latest

MAINTAINER Libert Schmidt <rschmidt@libert.xyz>

RUN yum -y update && yum -y install httpd && echo "/sbin/service httpd start" >> /root/.bashrc && yum -y install openssh-server && echo "/sbin/service sshd start" >> /root/.bashrc && echo "The system configuration is ended" > /root/README

EXPOSE 80 22
