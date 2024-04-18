FROM openjdk:21-slim

# copy file
COPY ["./target/accessing-data-mysql-complete-0.0.1-SNAPSHOT.jar", "/app/app.jar"]
COPY ["./env-config/prod/", "/app/config/"]

# mysql port
EXPOSE 3307

# cd 
WORKDIR /app

# command
CMD ["java", "-jar", "app.jar"]
