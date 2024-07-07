FROM openjdk:8-alpine

COPY ./target/ical-svc-1.0.0.jar /usr/app/

WORKDIR /usr/app

RUN sh -c 'touch ical-svc-1.0.0.jar'

ENTRYPOINT ["java", "-jar", "ical-svc-1.0.0.jar"]