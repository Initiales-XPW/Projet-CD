FROM openjdk
RUN mkdir /app;\
    mkdir /app/data
WORKDIR /app
EXPOSE 8001
VOLUME /app/data
COPY target/devops-1.0.war /app
