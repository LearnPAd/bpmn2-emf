# Introduction

This project is used to package a standalone JAR with all the needed classes for processing BPMN2. These classes are taken from the [Eclipse BPMN2 Modeler project](http://eclipse.org/bpmn2-modeler), and [Tycho](http://www.eclipse.org/tycho) is used for correctly get all the needed dependencies.

The resulting JAR can then be used in plain Java applications that don't use OSGi.

The solution for implementing this has been taken from [this post on Stack Overflow](http://stackoverflow.com/questions/6682028/use-dependencies-from-eclipse-p2-repository-in-a-regular-maven-build)