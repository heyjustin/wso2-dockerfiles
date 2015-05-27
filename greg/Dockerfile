FROM justinwalsh/centos-jre7

# Maintainer
MAINTAINER Byron Munday

RUN wget -P /opt http://dist.wso2.org/maven2/org/wso2/governance/wso2greg/4.6.0/wso2greg-4.6.0.zip && \
    unzip /opt/wso2greg-4.6.0.zip -d /opt && \
    rm /opt/wso2greg-4.6.0.zip

EXPOSE 9443
CMD ["/opt/wso2greg-4.6.0/bin/wso2server.sh"]


