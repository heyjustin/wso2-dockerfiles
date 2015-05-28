FROM justinwalsh/centos-jre7

# Maintainer
MAINTAINER Byron Munday

RUN wget -P /opt http://dist.wso2.org/maven2/org/wso2/store/wso2store/1.1.0/wso2store-1.1.0.zip && \
    unzip /opt/wso2store-1.1.0.zip -d /opt && \
    rm /opt/wso2store-1.1.0.zip

EXPOSE 9443
CMD ["/opt/wso2store-1.1.0/bin/wso2server.sh"]


