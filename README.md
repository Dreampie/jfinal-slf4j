jfinal-slf4j
============

jfinal  slf4j  log api，查看其他插件-> [Maven](http://search.maven.org/#search%7Cga%7C1%7Ccn.dreampie)

maven 引用  ${jfinal-slf4j.version}替换为相应的版本如:0.1

```xml
<dependency>
 <groupId>cn.dreampie</groupId>
 <artifactId>jfinal-slf4j</artifactId>
 <version>${jfinal-slf4j.version}</version>
</dependency>
```

```java
public void configConstant(Constants constants) {
    //set log to slf4j
    Logger.setLoggerFactory(new Slf4jLogFactory());
  }

```
