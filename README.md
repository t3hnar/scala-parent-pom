# Parent pom for Scala projects

<table border="0">
  <tr>
    <td>[Scala](http://www.scala-lang.org) </td>
    <td>2.10.3</td>
  </tr>
  <tr>
    <td>[Specs2](http://etorreborre.github.io/specs2) </td>
    <td>2.3.3</td>
  </tr>
  <tr>
    <td>[ScalaCheck](http://www.scalacheck.org) </td>
    <td>1.11.0</td>
  </tr>
</table>

## Setup

1. Add this repository to your pom.xml:
```xml
    <repository>
        <id>thenewmotion</id>
        <name>The New Motion Repository</name>
        <url>http://nexus.thenewmotion.com/content/repositories/releases-public</url>
    </repository>
```

2. Add dependency to your pom.xml:
```xml
    <dependency>
        <groupId>ua.t3hnar</groupId>
        <artifactId>scala-parent-pom_2.10</artifactId>
        <version>2.4</version>
    </dependency>
```