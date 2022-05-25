FROM openjdk:11.0-jdk-oracle
COPY apache-activemq-5.17.1 /opt/apache-activemq-5.17.1
COPY jmx_prometheus_javaagent-0.17.0.jar /opt/jmx_prometheus_javaagent-0.17.0.jar
WORKDIR /opt/apache-activemq-5.17.1/bin
ENTRYPOINT ["./activemq","console"]