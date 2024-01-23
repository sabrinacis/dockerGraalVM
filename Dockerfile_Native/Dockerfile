FROM findepi/graalvm
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} springNativeJFR-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java","-jar","/springNativeJFR-0.0.1-SNAPSHOT.jar"]