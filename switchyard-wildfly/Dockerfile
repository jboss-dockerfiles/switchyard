FROM jboss/wildfly:8.1.0.Final
MAINTAINER Jorge Morales <jmorales@redhat.com>

ENV JBOSS_SY_VERSION 2.0.0.Final
ENV JBOSS_SY_VERSION_MAIN v2.0.Final

#
# Install switchyard
RUN cd $JBOSS_HOME && curl http://downloads.jboss.org/switchyard/releases/$JBOSS_SY_VERSION_MAIN/switchyard-$JBOSS_SY_VERSION-WildFly.zip | bsdtar -xvf-
