FROM rhel7:7.5

MAINTAINER username <username@example.com>

LABEL version="1.0" \
      description="This is a simple container image" \
      creationDate="31 March 2018"

ENV VAR1="hello" \
    VAR2="world"

ADD training.repo /etc/yum.repos.d/training.repo

RUN yum install -y bind-utils && \
yum clean all

