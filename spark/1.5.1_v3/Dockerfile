FROM registry.cn-hangzhou.aliyuncs.com/google_containers/spark:1.5.1_v3
MAINTAINER 285414629@qq.com
ADD spark-cassandra-connector_2.10-1.5.1.jar /
ADD spark-defaults.conf /
RUN cp -f spark-defaults.conf /opt/spark/conf
