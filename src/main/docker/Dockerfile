FROM openjdk:8u171-jdk-alpine3.8

MAINTAINER Stefan van Risswyck "risswyck@gmx.de"

EXPOSE 8080

WORKDIR /usr/local/bin

COPY maven/fleetman-0.0.1-SNAPSHOT.jar webapp.jar

CMD ["java", "-Dspring.profiles.active=docker-demo", "-jar", "webapp.jar"]
