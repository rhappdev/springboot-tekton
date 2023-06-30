
FROM registry.access.redhat.com/ubi8/openjdk-17:1.15

COPY target/*.jar  /deployments

EXPOSE 8081
ENTRYPOINT ["/opt/jboss/container/java/run/run-java.sh", "--server.port=8081"]

