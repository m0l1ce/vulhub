FROM tomcat:8.5.95

MAINTAINER phithon <root@leavesongs.com>

RUN sed -i 's/securerandom\.source=file:\/dev\/random/securerandom.source=file:\/dev\/.\/urandom/g' $JAVA_HOME/lib/security/java.security