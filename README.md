# Hello-world project for Scala with maven

Example project showing how to build and run Scala code with maven instead of SBT

It utilizes the maven plugins [scala-maven-plugin](http://davidb.github.io/scala-maven-plugin/) (for compiling and running)
and [scalatest-maven-plugin](http://www.scalatest.org/user_guide/using_the_scalatest_maven_plugin) (for running unit-tests)

Compiling
---------

The project can be compiled with the standard command, `mvn compile`

Running
-------
To run the application, type `mvn scala:run`

To run unit-tests, type `mvn test`



