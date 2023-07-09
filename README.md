# Maven Compile Will Stuck

Reproduce Steps:

1. Install dependency

```bash
mvn install:install-file \
    -Dtaobao-sdk-java-auto.jar \
    -DgroupId=com.dingtalk.open \
    -DartifactId=taobao-sdk-java-auto \
    -Dversion=0.0.1 \
    -Dpackaging=jar
```

2. Install OpenJDK 11

Download at https://jdk.java.net/java-se-ri/11-MR2

3. Donwload Maven

- Maven version: 3.6.3

Finally, use OpenJDK 11 to compile, it will stuck at complie.

