FROM openjdk:8
VOLUME /tmp
ARG JAR_FILE=build/libs/gateway-service.jar
EXPOSE 8088
COPY ${JAR_FILE} gateway-service.jar
ENTRYPOINT ["java","-jar","/gateway-service.jar"]