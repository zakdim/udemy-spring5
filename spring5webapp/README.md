### Run from command line ###

```
./mvnw spring-boot:run
```

### Access in memory H2 DB ###
```
http://localhost:8080/h2-console
# Use JDBC URL
jdbc:h2:mem:testdb
```

### Create branch from master ###
```
# create new branch jpa-entities and switch to it
git checkout -b jpa-entities

# push new branch to github
git push -u origin jpa-entities
```

