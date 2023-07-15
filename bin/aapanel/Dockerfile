FROM aapanel/aapanel:lnmp

USER root

RUN yum -y update
RUN mv /www/server/panel/pyenv/lib/python3.7/site-packages/OpenSSL /tmp/OpenSSL_bak
RUN btpip install pyOpenSSL

# Update AAPanel
RUN bt 16

WORKDIR /www/
