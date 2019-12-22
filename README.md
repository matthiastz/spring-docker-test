https://spring.io/guides/gs/spring-boot-docker/#scratch

https://spring.io/guides/gs/gradle/

https://sdkman.io/

https://gradle.org/install/

# change default port 
https://www.baeldung.com/spring-boot-change-port

gradle build
sudo docker build -t springio/gs-spring-boot-docker .

# map host port 8081 to docker shell port 8080
sudo docker run -p 8081:8080 -t springio/gs-spring-boot-docker

