# JavaCV Template

This project is a simple template for applications using [Gradle](http://gradle.org) as the build system and including [JavaCV](https://code.google.com/p/javacv/) for computer vision. 

It also includes Google's [Guava](https://code.google.com/p/guava-libraries/) utility libraries and [SLF4J](http://www.slf4j.org) for logging, and [JUnit](http://junit.org) for testing. 

This project is ready to use with Gradle supporting IDEs. 

Note that JavaCV depends on [OpenCV](http://opencv.org), Gradle, and Java 7 on your system. 

## Current versions

* JavaCV 0.7 (OpenCV 2.4.8)
* Guava (16.0.1)


## Customization

You can add your main class name to the bottom line in `build.gradle`, enabling the build task `gradle run`
	
	mainClassName = ""

Of course, you can customize the dependencies in `build.gradle`