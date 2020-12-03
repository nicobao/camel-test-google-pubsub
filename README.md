# Camel :: Test Infra Google Pub/Sub

The original source code is available on Apache Camel original repository: [test-infra](https://github.com/apache/camel/tree/master/test-infra/camel-test-infra-google-pubsub) and [google-pubsub-component](https://github.com/apache/camel/blob/master/components/camel-google-pubsub/src/test/java/org/apache/camel/component/google/pubsub/PubsubTestSupport.java).

## Requirements

- Java 11

## Build

### Linux/macOS

```bash
./mvnw install
```

### Windows

```bash
mvnw.cmd install
```

## Usage

### Maven

Add in your pom.xml:

```xml
    <project>
      ...
      <dependencies>
        <dependency>
          <groupId>com.github.nicobao</groupId>
          <artifactId>camel-test-google-pubsub</artifactId>
          <classifier>tests</classifier>
          <type>test-jar</type>
          <version>1.0.0</version>
          <scope>test</scope>
        </dependency>
      </dependencies>
      ...
    </project>
```

### In your Java project

Refer to [how the Apache Camel developers use it to test their Google PubSub Camel component](https://github.com/apache/camel/tree/master/test-infra/camel-test-infra-google-pubsub/src/test/java/org/apache/camel/test/infra/google/pubsub).

## License

The original work is made by the Apache Foundation and released under the Apache Licence v2.
My modified work - if any - is also released under the Apache License v2.
