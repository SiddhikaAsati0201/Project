FROM openjdk:8u131-jdk-alpine
EXPOSE 80
COPY ./target/authorization-microservice.jar authorization-microservice.jar 
ENTRYPOINT ["java","-jar","/authorization-microservice.jar"]