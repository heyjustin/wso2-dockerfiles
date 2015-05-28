FROM justinwalsh/centos-jre7

# Maintainer
MAINTAINER Byron Munday

RUN wget -P /opt http://dist.wso2.org/maven2/org/wso2/dss/wso2dss/3.2.2/wso2dss-3.2.2.zip && \
    unzip /opt/wso2dss-3.2.2.zip -d /opt && \
    rm /opt/wso2dss-3.2.2.zip

EXPOSE 9443
CMD ["/opt/wso2dss-3.2.2/bin/wso2server.sh"]


