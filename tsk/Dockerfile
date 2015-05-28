FROM justinwalsh/centos-jre7

# Maintainer
MAINTAINER Byron Munday

RUN wget -P /opt http://dist.wso2.org/maven2/org/wso2/ts/wso2ts/1.0.1/wso2ts-1.0.1.zip && \
    unzip /opt/wso2ts-1.0.1.zip -d /opt && \
    rm /opt/wso2ts-1.0.1.zip

EXPOSE 9443
CMD ["/opt/wso2ts-1.0.1/bin/wso2server.sh"]


