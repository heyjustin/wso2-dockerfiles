FROM justinwalsh/centos-jre7

# Maintainer
MAINTAINER Byron Munday

RUN wget -P /opt http://dist.wso2.org/maven2/org/wso2/am/wso2am/1.8.0/wso2am-1.8.0.zip && \
    unzip /opt/wso2am-1.8.0.zip -d /opt && \
    rm /opt/wso2am-1.8.0.zip

EXPOSE 9443
CMD ["/opt/wso2am-1.8.0/bin/wso2server.sh"]


