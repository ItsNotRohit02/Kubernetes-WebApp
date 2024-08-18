FROM openjdk:8 AS build_image
RUN apt update && apt install git -y && apt install maven -y
RUN git clone https://github.com/ItsNotRohit02/Docker-WebApp.git
RUN cd Docker-WebApp && mvn install

FROM tomcat:8-jre11

RUN rm -rf /usr/local/tomcat/webapps/*

COPY --from=build_image Docker-WebApp/target/Sample-v10.war /usr/local/tomcat/webapps/ROOT.war

EXPOSE 8080
CMD ["catalina.sh", "run"]