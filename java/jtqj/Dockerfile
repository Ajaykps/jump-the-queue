FROM openjdk:11
ADD server/target/jtqj-server-bootified.war jtqj-server-bootified.war
ENTRYPOINT ["java", "-war","jtqj-server-bootified.war"]
EXPOSE 8080