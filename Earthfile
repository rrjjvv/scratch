VERSION 0.7

cache:
    FROM maven:3.8-eclipse-temurin-11-alpine
    CACHE /root/.m2/repository
    WORKDIR work
    RUN mvn -V -B archetype:generate -DgroupId=fake -DartifactId=fake -Dpackage=fake
    SAVE ARTIFACT fake/*
