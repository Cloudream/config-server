FROM java:8
MAINTAINER George <ubuntu_vip@sina.cn>
VOLUME /tmp
ADD config-server.jar config-server.jar
#RUN bash -c 'touch /config-server.jar'
EXPOSE 8768
ENTRYPOINT ["java","-Xmx128m","-Djava.security.egd=file:/dev/./urandom","-jar","/config-server.jar"]