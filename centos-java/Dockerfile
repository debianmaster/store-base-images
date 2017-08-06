FROM openshift/base-centos7
MAINTAINER 9chakri@gmail.com

#Install java
ENV JAVA_VERSON 1.8.0
RUN yum update -y && \
  yum install -y curl && \
  yum install -y java-$JAVA_VERSON-openjdk java-$JAVA_VERSON-openjdk-devel && \
  yum clean all
  
ENV JAVA_HOME /usr/lib/jvm/java
