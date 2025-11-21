# Gradle Hello World with Log4j

This is a minimal Java project using Gradle that logs "Hello, world!" with Log4j.

Prerequisites
- Java 17+ installed
- Gradle installed (or generate the wrapper with `gradle wrapper`)

Build and run
- To run with your system Gradle:

```bash
gradle run
```

- If you want to add the Gradle wrapper (recommended for reproducible builds):

```bash
gradle wrapper
./gradlew run
```

Files of interest
- `build.gradle`: Gradle build file (adds Log4j dependencies)
- `src/main/java/com/example/Hello.java`: main class that logs and prints Hello
- `src/main/resources/log4j2.xml`: Log4j2 configuration
