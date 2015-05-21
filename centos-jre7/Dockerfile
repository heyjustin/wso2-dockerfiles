FROM centos:6

# Maintainer
MAINTAINER Justin Walsh

# Update system
RUN yum update -y
RUN yum install -y wget
RUN yum install -y unzip
RUN yum install -y tar

## Download and install Oracle JAVA JRE 1.7
RUN cd /tmp && wget -q --no-check-certificate -O /tmp/jre-7.tar.gz --no-cookies --header "Cookie: oraclelicense=accept-securebackup-cookie" http://download.oracle.com/otn-pub/java/jdk/7u79-b15/jre-7u79-linux-x64.tar.gz
RUN tar -zxf /tmp/jre-7.tar.gz -C /opt
RUN rm /tmp/jre-7.tar.gz
RUN ln -s /opt/jre1.7.0_79 /opt/java

# Set up Java environment variables
ENV JAVA_HOME /opt/java
ENV PATH ${PATH}:${JAVA_HOME}/bin
