FROM registry.cn-hangzhou.aliyuncs.com/google_containers/spark:1.5.1_v3
MAINTAINER 285414629@qq.com
RUN mkdir -p /opt/spark/managed-lib
ADD cassandra-clientutil-3.0.2.jar /opt/spark/managed-lib/
ADD cassandra-driver-core-3.1.4.jar /opt/spark/managed-lib/
ADD guava-16.0.1.jar /opt/spark/managed-lib/
ADD cassandra-thrift-3.0.2.jar /opt/spark/managed-lib/
ADD joda-convert-1.2.jar /opt/spark/managed-lib/
ADD joda-time-2.9.9.jar /opt/spark/managed-lib/
ADD libthrift-0.9.1.jar /opt/spark/managed-lib/
ADD spark-cassandra-connector_2.10-1.5.1.jar /opt/spark/managed-lib/
ADD spark-env.sh /opt/spark/conf/

