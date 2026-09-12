FROM eclipse-temurin:25-jdk

WORKDIR /app

COPY . .

RUN chmod +x gradlew
RUN ./gradlew clean build -x test

EXPOSE 8080

CMD ["java", "-jar", "build/libs/NBE12-14-1-TEAM07-0.0.1-SNAPSHOT.jar"]
