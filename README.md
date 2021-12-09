# java-cli-gradle-pmd-junit-test-html-xml-hello-world

## Description
Analyze source code for potential bugs.
Analyze source code for potential bugs.
A POC for gradle app using JUnit.
Uses test task to dump html and xml
to shared folder.

## Tech stack
- java
- gradle
	- pmd
	- spotbugs
  - junit

## Docker stack
- gradle:jdk11

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
[Code concept](https://github.com/eugenp/tutorials/tree/master/maven-modules/maven-integration-test)
[Path to reports](https://courses.cs.washington.edu/courses/cse331/19wi/docs/tools/test-reports.html)
[Code for test task](https://stackoverflow.com/questions/25963554/how-to-make-gradle-build-produce-html-test-report-instead-of-xml-default)
