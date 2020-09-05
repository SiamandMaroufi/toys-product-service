# Toy Service

This service can be used for serving a list of products via a rest call.

# How To

### Quick start

for having a quick start, you can easily use the `startup.sh` script, it uses the docker; 
therefore, you should have docker installed.

```
$ ./startup.sh
```

#### Manual run (Developing)
if you  want to run it manually without taking advantage of docker, you can 
run a redis-server locally then build and run via maven as the following:
```
$ redis-server &
$ mvn clean install
$ java -jar target/toys-0.0.1.jar
``` 

 ### Run tests
 
 for running tests you can use mvn:
 
 ```
$ mvn clean verify
```