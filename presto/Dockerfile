FROM ahanaio/prestodb-sandbox:0.259

COPY ranger-2.1.0-presto-plugin /opt/presto-server/plugin/ranger-presto-plugin

RUN export JAVA_HOME="/usr/lib/jvm/java-1.8.0-openjdk-1.8.0.282.b08-1.amzn2.0.1.x86_64/jre" && \
    /opt/presto-server/plugin/ranger-presto-plugin/enable-presto-plugin.sh

# COPY /opt/presto-server/etc/
