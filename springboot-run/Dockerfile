FROM debianmaster/centos-java
MAINTAINER 9chakri@gmail.com

COPY ./s2i/bin/ $STI_SCRIPTS_PATH

RUN chown -R 1001:0 /opt/app-root
USER 1001

CMD $STI_SCRIPTS_PATH/usage
EXPOSE 8080