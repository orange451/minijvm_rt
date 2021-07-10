Cloned from https://github.com/digitalgust/miniJVM

This repository serves as a means to easily include minijvm_rt as a dependency.

Maven:
```xml
	<repositories>
		<repository>
		    <id>jitpack.io</id>
		    <url>https://jitpack.io</url>
		</repository>
	</repositories>

	<dependency>
	    <groupId>com.github.orange451</groupId>
	    <artifactId>minijvm_rt</artifactId>
	    <version>master-SNAPSHOT</version>
	</dependency>
```

Gradle:
```gradle
	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
	
	dependencies {
	        implementation 'com.github.orange451:minijvm_rt:master-SNAPSHOT'
	}
```
