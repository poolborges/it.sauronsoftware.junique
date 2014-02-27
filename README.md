# JUnique

Helps in preventing multiple instances of the same application

This project is a fork of [here](http://www.sauronsoftware.it/projects/junique/) 


## Instructions

* Download jar [here](https://github.com/poolborges/it.sauronsoftware.junique/downloads/)
* Add the JUnique JAR to your application CLASSPATH and enjoy it.
* Supported platforms: Java 2 version 1.2 or later


## Documentation

Developer API documentation [here](http://poolborges.github.com/it.sauronsoftware.junique/)
Working code examples in examples

## How to add to Maven POM

Add a repository configuration to my Maven Repo
```
<repository>
    <id>poolborges-github-thirdparty</id>
    <name>poolborges-github</name>
    <url>https://github.com/poolborges/maven/raw/master/thirdparty/</url>
</repository>
```

Add dependency
```
<dependency>
    <groupId>it.sauronsoftware</groupId>
    <artifactId>junique</artifactId>
    <version>1.0.4</version>
    <type>jar</type>
</dependency>
```



## How to build

Project POM file use: 
* [Official GitHub Maven Plugins](https://github.com/github/maven-plugins)
  * [Example](https://github.com/kevinsawicki/github-maven-example)


## Maven goals

upload jar to github see [here](https://github.com/poolborges/it.sauronsoftware.junique/downloads/)
* mvn clean install ghDownloads:upload

upload project/site to github see [here](http://poolborges.github.com/it.sauronsoftware.junique/)
* mvn site

See BUILD.txt


## License

See LICENSE.txt


## Changelog

See CHANGELOG.txt
