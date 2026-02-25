# Java_app Sample Maven Project

This is a simple Maven-based Java project to demonstrate building and testing a HelloWorld application.

## Structure
```
Java_app/
├── pom.xml
├── src/
│   ├── main/
│   │   └── java/
│   │       └── com/example/Main.java
│   └── test/
│       └── java/
│           └── com/example/MainTest.java
```

## Prerequisites
- Java 11 or above
- [Maven](https://maven.apache.org/)

## Build
```sh
mvn compile
```

## Run
```sh
mvn exec:java -Dexec.mainClass="com.example.Main"
```

## Test
```sh
mvn test
```

---

Feel free to modify and expand this template for your needs.