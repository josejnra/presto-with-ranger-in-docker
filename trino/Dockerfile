FROM trinodb/trino:360

COPY ranger-2.1.0-presto-plugin.tar.gz /usr/lib/trino

RUN cd /usr/lib/trino && \
    tar zxvf /usr/lib/trino/ranger-2.1.0-presto-plugin.tar.gz && \
    mv /usr/lib/trino/ranger-2.1.0-presto-plugin ranger-trino-plugin && \
    rm /usr/lib/trino/ranger-2.1.0-presto-plugin.tar.gz

COPY install.properties /usr/lib/trino/ranger-trino-plugin

# USER root

# RUN /usr/lib/trino/plugin/ranger-trino-plugin/enable-presto-plugin.sh

# USER trino
