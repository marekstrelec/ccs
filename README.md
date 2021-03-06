Cruise Control System
===
Informatics 2 - Software Engineering Homework 3 (2014)
University of Edinburgh

## Description

The Cruise Control System is responsible for automatically controlling the speed of the car. The system takes over the throttle of the car to maintain a steady speed as set by the driver and to accelerate the car upon the request of the driver.

### Authors
* Marek Strelec s1354741
* Dovile Vitonyte s1237357

### Version
1.0.0

### Required files
    - requirements_test_matrix.pdf      -- tracebility matrix
    - Tests_coverage.html               -- Eclemma coverage report
    - JUnit_BasicTests.xml              -- JUnit tests report

### Additional Files
In regard of the previous feedback, we have attached
modified class diagram as well as updated requirements.
We hope they will be much better than previously.

    - updated_class_diagram.pdf
    - Requirements.pdf

### Instructions

```sh
$ cd to CruiseControl/src/ directory
$ javac -cp /usr/share/java/junit4.jar *.java
$ java -cp .:/usr/share/java/junit4.jar org.junit.runner.JUnitCore BasicTests
```