# Documentation page for Graphite ![Build Status](https://img.shields.io/github/actions/workflow/status/GraphiteMC/Graphite/build.yml)  ![CodeFactor Grade](https://img.shields.io/codefactor/grade/github/GraphiteMC/Graphite/ver%2F1.20.1)

This site contains all the documentation for [Graphite](https://github.com/GraphiteMC/Graphite)
___
## How To (Plugin Developers)

#### Repository (For Graphite-API)
  * ##### Maven
```html
    <repository>
        <id>graphitemc</id>
        <url>https://repo.graphitemc.org/releases</url>
    </repository>
```
```html
    <dependency>
        <groupId>org.graphitemc.graphite</groupId>
        <artifactId>graphite-api</artifactId>
        <version>1.20.1-R0.1-SNAPSHOT</version>
        <scope>provided</scope>
    </dependency>
```

* ##### Gradle
```kotlin
repositories {
    maven("https://repo.graphitemc.org/releases")
}
```
```kotlin
dependencies {
    compilyOnly("org.graphitemc.graphite:graphite-api:1.20.1-R0.1-SNAPSHOT")
}
```


#### Repository (For dev-bundle)
* ##### Gradle
```kotlin
repositories {
    maven("https://repo.graphitemc.org/releases")
}
```
```kotlin
dependencies {
    paperweight.devBundle("org.graphitemc.graphite", "1.20.1-R0.1-SNAPSHOT")
}
```