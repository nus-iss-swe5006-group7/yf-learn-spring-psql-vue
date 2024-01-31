# Stage 1
FROM eclipse-temurin:17.0.9_9-jdk as BUILDER
RUN apt-get update -y && apt-get install -y maven



WORKDIR /workspace/src/backend

# RUN 1 TIME to generate pom.xml, template and mvnw
# CMD ["bash", "-c", "mvn archetype:generate -DgroupId=yf.spring -DartifactId=yf_app -DarchetypeArtifactId=maven-archetype-quickstart -DarchetypeVersion=1.4 -DinteractiveMode=false"]
# then docker compose run backend bash:
    # cd /workspace/src/backend/yf_app# mvn wrapper:wrapper
    # ./mvnw spring-boot:run


