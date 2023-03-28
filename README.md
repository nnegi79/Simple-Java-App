# simple-java-maven-app

This repository is for the
[Build a Java app with Maven] using the AWS code build

The repository contains a simple Java application which outputs the string
"Hello world!" and is accompanied by a couple of unit tests to check that the
main application works as expected. The results of these tests are saved to a
JUnit XML report.
The build-spec file which is collection of build command and related setting in YAML format, that is used to run a build using AWS codebuild services.
In this build spec declaration:
•	version represents the version of the build spec standard being used. This build spec declaration uses the latest version,0.2.
•	phases represents the build phases during which you can instruct AWS CodeBuild to run commands. These build phases are listed here as install, pre_build, build, and post_build
•	artifacts represents the set of build output artifacts that AWS CodeBuild will upload to the output bucket


# Adding line for mirror sync testing to gitlab
