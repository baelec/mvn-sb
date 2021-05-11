FROM adoptopenjdk/openjdk11
WORKDIR /
ADD ./maven/${project.build.finalName}-${classifier}.jar main.jar
CMD ["java", "-jar", "main.jar"]
