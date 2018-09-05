# maven-jar-plugin-demo-java8 [![Build Status][travis-img]][travis]

Maven JAR Plugin demo in Java 8. See also [maven-jar-plugin-demo-java11](https://github.com/mincong-h/maven-jar-plugin-demo-java11).

## Usage

macOS/Linux (use `:` as separator):

```
$ mvn clean package
$ java -classpath shop-api/target/shop-api-1.0-SNAPSHOT.jar:shop-core/target/shop-core-1.0-SNAPSHOT.jar \
       shop.core.Main
Welcome to Java 8
```

Windows (use `;` as separator):

```
$ mvn clean package
$ java -classpath shop-api/target/shop-api-1.0-SNAPSHOT.jar;shop-core/target/shop-core-1.0-SNAPSHOT.jar \
       shop.core.Main
Welcome to Java 8
```

[travis]: https://travis-ci.org/mincong-h/maven-jar-plugin-demo-java8
[travis-img]: https://travis-ci.org/mincong-h/maven-jar-plugin-demo-java8.svg?branch=master
