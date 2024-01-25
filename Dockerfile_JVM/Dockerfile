FROM openjdk:21
VOLUME /tmp
EXPOSE 7082
ARG JAR_FILE=/*.jar
ADD ${JAR_FILE} appjvm21.jar
ENTRYPOINT ["java","-jar","/appjvm21.jar"]
