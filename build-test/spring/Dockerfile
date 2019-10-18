FROM openjdk:8-jre-alpine

ADD target/tekton-build-test.jar /opt/tekton-build-test/
EXPOSE 8080
WORKDIR /opt/tekton-build-test/
CMD ["java", "-Xms512m", "-Xmx1g", "-jar", "tekton-build-test.jar"]