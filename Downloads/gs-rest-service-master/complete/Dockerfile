FROM openjdk:10
 
# copy the packaged jar file into our docker image
COPY ./target/rest-service-0.0.1-SNAPSHOT.jar /demo.jar

RUN chmod +x /demo.jar

# set the startup command to execute the jar
CMD ["java", "-jar","-Dserver.port=8888","/demo.jar"]