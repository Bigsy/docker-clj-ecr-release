FROM java:8

ADD target/docker-release.jar /srv/myproj-app.jar

EXPOSE 8080

CMD ["java", "-jar", "/srv/myproj-app.jar"]