FROM openjdk:8-jdk-alpine
ENV FILE=monopoly-0.0.1-SNAPSHOT.jar
WORKDIR apps
ADD target/${FILE} ${FILE}
CMD java -jar ${FILE}