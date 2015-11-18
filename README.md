# An Example of Spring Project with Gradle

* This is the "hello world" example from the [official doc](https://spring.io/guides/gs/rest-service/).

* To run it from IntelliJ, enable your spring framework plugin and set the main class to hello.Application. 

* To run it from command line: ```./gradlew build && java -jar build/libs/gs-spring-boot-0.1.0.jar```

* The application is at [http://localhost:9000/greeting](http://localhost:9000/greeting) and [http://localhost:8080/greeting?name=User](http://localhost:8080/greeting?name=User)after running.

* Strongly suggest to read the [Gradle getting start page](https://spring.io/guides/gs/gradle/)