FROM justinwalsh/centos-jre7

# Maintainer
MAINTAINER Byron Munday

RUN wget -P /opt http://dist.wso2.org/maven2/org/wso2/identity/wso2is/4.5.0/wso2is-4.5.0.zip && \
    unzip /opt/wso2is-4.5.0.zip -d /opt && \
    rm /opt/wso2is-4.5.0.zip

EXPOSE 9443
CMD ["/opt/wso2is-4.5.0/bin/wso2server.sh"]


