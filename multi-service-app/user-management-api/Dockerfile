FROM adoptopenjdk/openjdk14
EXPOSE 8080
COPY target/classes/application.properties application.properties
COPY target/user-management-api-1.0-SNAPSHOT-repacked.jar um.jar
CMD ["java","-jar","um.jar", "--spring.config.location=file:application.properties"]