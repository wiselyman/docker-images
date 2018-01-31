FROM registry.cn-hangzhou.aliyuncs.com/google_containers/spark:1.5.1_v3
MAINTAINER 285414629@qq.com
#ADD spark-defaults.conf /opt/spark/conf/spark-defaults.conf
ADD spark-cassandra-connector-assembly-1.5.1.jar /opt/spark/
RUN spark-shell --jars /opt/spark/spark-cassandra-connector-assembly-1.5.1.jar

#ENV SPARK_CASSANDRA_CONNECTOR_VERSION=1.5.1
#RUN git clone https://github.com/datastax/spark-cassandra-connector.git && \
#        cd spark-cassandra-connector && \
#        git checkout v${SPARK_CASSANDRA_CONNECTOR_VERSION} && \
#        sbt/sbt assembly && \
#        mv /spark-cassandra-connector/spark-cassandra-connector/target/scala-2.10/spark-cassandra-connector-assembly-${SPARK_CASSANDRA_CONNECTOR_VERSION}.jar /opt/spark/ && \
#        rm -rf /spark-cassandra-connector && \
#        /opt/spark/bin/spark-shell --jars /opt/spark/spark-cassandra-connector-assembly-${SPARK_CASSANDRA_CONNECTOR_VERSION}.jar
