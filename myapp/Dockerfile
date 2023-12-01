FROM openjdk:11-jre-slim

RUN useradd -m -u 1001 my-user

WORKDIR /app

COPY ./target/myapp-1.0.1.jar /app/app.jar

EXPOSE 8080

USER my-user

CMD ["java", "-jar", "app.jar"]