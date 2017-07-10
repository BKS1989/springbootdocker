FROM frolvlad/alpine-oraclejdk8:slim
ENV version 0.0.1-SNAPSHOT
RUN apk update && apk upgrade && apk add git
ADD *.jar springboot-$version.jar
ENTRYPOINT ["java","-jar","/springboot-$version.jar"]
