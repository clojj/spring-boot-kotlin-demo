# Spring Boot Kotlin sample project

This is the source code for the a sample Spring Boot application developed with Kotlin and Spring Data JPA. 

You can launch the application with by running:

    $ ./gradlew bootRun

    $ ./gradlew test

    $ ./gradlew --stop

This project uses `kotlin-spring` plugin to avoid requiring `open` modifier on proxified
classes and methods, see [this blog post](https://blog.jetbrains.com/kotlin/2016/12/kotlin-1-0-6-is-here/) for more details.

This project uses a [Kotlin based Gradle](https://github.com/gradle/kotlin-dsl) configuration.

TODO
----
* IntelliJ editor errors, if classes not "open" (apply kotlin-jpa plugin ?)
* run tests with Intellij has error "... no default constructor" (apply kotlin-jpa plugin ?)
