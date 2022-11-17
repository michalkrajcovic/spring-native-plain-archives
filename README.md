# spring-native-plain-archives

This is a simple project to demonstrate that `nativeCompile` gradle task fails with `Error: Main entry point class '<application class>' neither found on the classpath nor on the modulepath.` error when `jar` task is disabled.

## Environment
- Spring Boot: 3.0.0-RC2
- Native Buildtools: 0.9.17
- GraalVM version : graalvm-ce-java17-22.3.0
- JDK version: openjdk 17.0.5
- Architecture: AMD64

## Compile
```
./gradlew nativeCompile
```

## Fails with
```
Error: Main entry point class 'com.example.springnativeplainarchives.Application' neither found on the classpath nor on the modulepath.
....
```
