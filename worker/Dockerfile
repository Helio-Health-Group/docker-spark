FROM jordanburke/spark-base:2.4.6

LABEL maintainer="Gezim Sejdiu <g.sejdiu@gmail.com>, Giannis Mouchakis <gmouchakis@gmail.com>"

COPY worker.sh /

ENV SPARK_WORKER_WEBUI_PORT 8081
ENV SPARK_WORKER_LOG /spark/logs
ENV SPARK_MASTER "spark://spark-master:7077"

EXPOSE 8081

ENV JAVA_HOME /usr/lib/jvm/default-jvm

CMD ["/bin/bash", "/worker.sh"]
