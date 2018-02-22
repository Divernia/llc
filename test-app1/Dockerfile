FROM frolvlad/alpine-oraclejdk8:slim
VOLUME /tmp
ADD target/test-app1-0.0.1-SNAPSHOT.jar app.jar
ENTRYPOINT [ "sh", "-c", "java -jar app.jar" ]