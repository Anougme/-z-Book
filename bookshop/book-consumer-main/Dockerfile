FROM java:8

MAINTAINER zhulin

ARG JAR_FILE

COPY target/${JAR_FILE} /app.jar
EXPOSE 9002
ENTRYPOINT ["java","-jar","/app.jar"]