FROM alpine:3.11.2
RUN apk update && apk add --no-cache  openjdk11
COPY build/libs/evoSpringOne-0.0.1-SNAPSHOT.jar /app/
CMD ["java", "-jar" , "/app/evoSpringOne-0.0.1-SNAPSHOT.jar"]
