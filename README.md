# Building Microservices with JHipster
Developing a microservice architecture with Java and Spring Boot using Jhipster

WARNING! Docker Compose configuration generated, but no Jib cache found

If you forgot to generate the Docker image for this application, please run:

To generate the missing Docker image(s), please run:

```zsh
./mvnw -ntp -Pprod verify jib:dockerBuild in /jhipster-microservices-example/getaway
./mvnw -ntp -Pprod verify jib:dockerBuild in /jhipster-microservices-example/invoice
./gradlew bootJar -Pprod jibDockerBuild in /jhipster-microservices-example/notification
```

You can launch all your infrastructure by running : docker-compose up -d