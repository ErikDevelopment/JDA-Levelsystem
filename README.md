# JDA-Economy
A test project for Economy System.

## Requirements
The following things are required to use JDACommands:
* Java 8+
* [JDA](https://github.com/DV8FromTheWorld/JDA) v5.0.0-alpha.20

### Maven
Add the following to your `pom.xml`:
```xml
<repositories>
  <repository>
    <id>jitpack.io</id>
    <url>https://jitpack.io</url>
  </repository>
</repositories>

<dependencies>
	<dependency>
	    <groupId>com.github.ErikDevelopment</groupId>
	    <artifactId>JDA-Economy</artifactId>
	    <version>x.y.z</version>
	</dependency>
</dependencies>
```

### Gradle
Add the following to your `build.gradle`:
```kt
allprojects {
  repositories {
    maven { url 'https://jitpack.io' }
  }
}
  
dependencies {
	        implementation 'com.github.ErikDevelopment:JDA-Economy:x.y.z'
}
```
