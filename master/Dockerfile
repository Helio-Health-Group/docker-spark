FROM jordanburke/spark-base:2.4.6

LABEL maintainer="Gezim Sejdiu <g.sejdiu@gmail.com>, Giannis Mouchakis <gmouchakis@gmail.com>"

COPY master.sh /

ENV SPARK_MASTER_PORT 7077
ENV SPARK_MASTER_WEBUI_PORT 8080
ENV SPARK_MASTER_LOG /spark/logs

EXPOSE 8080 7077 6066

ENV JAVA_HOME /usr/lib/jvm/default-jvm

CMD ["/bin/bash", "/master.sh"]
