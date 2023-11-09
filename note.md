See https://spring.io/guides/tutorials/spring-security-and-angular-js/

See https://github.com/spring-guides/tut-spring-security-and-angular-js/tree/master

See https://www.baeldung.com/spring-boot-angular-web

See https://github.com/alexlondon07/spring-boot-microservices-angular/tree/main


See https://github.com/spring-guides/tut-spring-security-and-angular-js
See https://github.com/cyela/Angular-Springboot/tree/master
See https://dzone.com/articles/angular-docker-spring-boot-a-match-made-in-heaven

See https://github.com/dsyer/spring-boot-angular

```sh
mkdir ui && cd ui
curl https://start.spring.io/starter.tgz -d type=maven-project -d language=java -d platformVersion=2.7.17 -d packaging=jar -d jvmVersion=1.8 -d groupId=com.farhad.example -d artifactId=spring_security_angular -d packageName=com.farhad.example.spring_security_angular -d dependencies=web,security,lombok -d name=ui | tar -xzvf -
```

or 

```sh
$ spring init --dependencies web,security ui/ && cd ui
```


