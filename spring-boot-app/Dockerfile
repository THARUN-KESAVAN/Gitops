FROM adoptopenjdk/openjdk11:alpine-jre
LABEL maintainer=THARUN K 
ARG artifact=target/spring-boot-web.jar
WORKDIR /opt/app
COPY ${artifact} app.jar
ENTRYPOINT ["java","-jar","app.jar"]

