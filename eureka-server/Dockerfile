FROM openjdk:11-jre-slim
WORKDIR eureka/src
ADD ./target/eureka-server-0.0.1-SNAPSHOT.jar /eureka/src/eureka-server-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java","-jar","eureka-server-0.0.1-SNAPSHOT.jar"]