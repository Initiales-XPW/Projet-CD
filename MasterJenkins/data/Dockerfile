FROM openjdk
RUN mkdir /app;\
    mkdir /app/data
WORKDIR /app
EXPOSE 8080
VOLUME /app/data
COPY target/devops-1.0.war /app
CMD ["/usr/bin/java", "-jar", "devops-1.0.war"]