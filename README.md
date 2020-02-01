Vanilla Java Blank
---
Maven archetype to create a maven project for a Vanilla Java application.

## Install
```bash
./mvnw install
```

## How to use
```bash
mvn archetype:generate \
  -DarchetypeGroupId=com.miya10kei.archetype \
  -DarchetypeArtifactId=vanilla-java-blank-archetype \
  -DarchetypeVersion=0.0.4
```

Example
```bash
mvn archetype:generate \
  -DarchetypeGroupId=com.miya10kei.archetype \
  -DarchetypeArtifactId=vanilla-java-blank-archetype \
  -DarchetypeVersion=0.0.4 \
  -DgroupId=com.example \
  -DartifactId=hello \
  -Dversion=1.0.0-SNAPSHOT \
  -B
```
```bash
cd hello
chmod +x mvnw*
./mvnw clean package
java -jar target/hello-1.0.0-SNAPSHOT.jar

Hello World!
```


