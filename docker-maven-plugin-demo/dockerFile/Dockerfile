FROM openjdk:8-jdk-alpine
MAINTAINER wangmin <641718840@qq.com>
RUN mkdir -p /app/www/logs/docker-plugin-test/log/
RUN mkdir -p /home/app/
ADD docker-maven-plugin-demo.jar /home/app/app.jar
CMD java -jar /home/app/app.jar