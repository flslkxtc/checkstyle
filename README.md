## Checkstyle Plugin ruleset
### How to use  
#### Maven

In your pom.xml include link to file checkstyle.xml from this repository

```xml
<plugin>
    <groupId>org.apache.maven.plugins</groupId>
    <artifactId>maven-checkstyle-plugin</artifactId>
    <version>3.0.0</version>
    <configuration>
        <configLocation>https://raw.githubusercontent.com/flslkxtc/checkstyle/master/checkstyle.xml</configLocation>
    </configuration>
</plugin>
```
