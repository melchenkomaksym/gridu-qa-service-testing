FROM adoptopenjdk/openjdk14
EXPOSE 8282
COPY target/classes/application.properties application.properties
COPY target/payment-management-api-1.0-SNAPSHOT-repacked.jar pm.jar
CMD ["java","-jar","pm.jar", "--spring.config.location=file:application.properties"]