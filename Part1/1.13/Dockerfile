FROM openjdk:8
RUN ./mvnw package
EXPOSE 4567
COPY . .
CMD [ "java" ,"-jar","./target/docker-example-1.1.3.jar" ]