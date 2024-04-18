# Docker-with-MySQL 
- SpringBoot
- Backend

# Local 

```
mvn spring-boot:run
```

# Production with docker

```
./run.sh
```

# Test mysql database

```
curl http://localhost:8080/demo/add -d name=First -d email=someemail@someemailprovider.com
curl http://localhost:8080/demo/all
```