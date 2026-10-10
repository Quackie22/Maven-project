FROM eclipse-temurin:17-jre

WORKDIR /app

COPY target/artjenkinsuat-jenkins1.jar app.jar

# El jar no tiene Main-Class en el manifest, por eso se indica la clase
CMD ["java", "-cp", "app.jar", "jenkins_1.App"]
