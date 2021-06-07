FROM aapanel/aapanel:lib

USER root

RUN su
# RUN yum -y update && yum upgrade -y

# Update AAPanel
RUN bt 16

# Reload AAPanel
RUN bt 1
RUN bt 9

WORKDIR /www/