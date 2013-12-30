 [Jade](http://jade-lang.com)
====
[![Build Status](https://api.travis-ci.org/bednar/jade.png?branch=master)](https://travis-ci.org/bednar/jade)

### Supported Versions

|   Jade    |   Maven   |
|:---------:|:---------:|
|   1.0.1   |   1.0.1   |
|   0.35.0  |   0.35.0  |


### Dependency

    <dependency>
        <groupId>com.github.bednar</groupId>
        <artifactId>jade</artifactId>
        <version>1.0.1</version>
    </dependency>

### Reference in HTML

    <script src="lib/jade/runtime.js" type="text/javascript"></script>
    <script src="lib/jade/runtime.min.js" type="text/javascript"></script>

    <script src="lib/jade/jade.js" type="text/javascript"></script>
    <script src="lib/jade/jade.min.js" type="text/javascript"></script>

### Use in Java

    this.getClass().getResourceAsStream("/lib/jade/runtime.js")
    this.getClass().getResourceAsStream("/lib/jade/runtime.min.js")

    this.getClass().getResourceAsStream("/lib/jade/jade.js")
    this.getClass().getResourceAsStream("/lib/jade/jade.min.js")

### Repository

    <repository>
        <id>bednar-public</id>
        <name>Bednar Public Repository</name>
        <url>http://nexus-bednar.rhcloud.com/nexus/content/groups/public/</url>
    </repository>
