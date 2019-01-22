# Overview
This repository contains a template for running selenium based test cases using a headless Web Driver for testing particularly in a Linux based environments which don't have Virtualization support(Particularly for AWS)
The Pom.xml has all the required dependencies.
# Use
In order to use this repository you can just clone https://github.com/arjunkapur95/HTMLHeadlessDriverForCI.git
Open with An IDE and edit AppTest.java (**Location : src/test/java.basic_Web_appJenkins/Jenkins**) to update the test cases to run the test cases that you design.  

# Pre-Requisites
Have a valid installation of JAVA and Maven 
Have a valid Jenkins Instance
Configure JAVA And Maven on Jenkins
# JenkinsWebDriver
Start a new Maven Job On Jenkins
Configure the JOB Like so

* General Configuration ![General Configuration](https://i.imgur.com/v48AVkB.png)
* Source Code Management Configuration ![myimage-alt-tag](https://i.imgur.com/gJcb2U7.png)
* Maven Build Management ![myimage-alt-tag](https://i.imgur.com/37WdYrX.png)
