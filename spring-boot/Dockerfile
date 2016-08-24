FROM java:8
COPY ./spring-boot-api*.jar /usr/src/ra/spring-boot-api.jar
WORKDIR /usr/src/ra/
EXPOSE 8080

ENTRYPOINT ["java", "-jar", "spring-boot-api.jar"]
CMD [""]
