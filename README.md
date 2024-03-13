# Task 20. Unit Testing. TestNG.

## Introduction
TestNG is one more unit-testing framework, which was developed using experience of JUnit.

For getting more info about differences between TestNg and JUnit5 - please read: <https://testsigma.com/blog/junit-vs-testng/>](https://testsigma.com/blog/junit-vs-testng/)

Complete task 20 with the help of [TestNG documentation](http://testng.org/doc/documentation-main.html).

## Task conditions
Do not change the code of the application.

Project contains a piece of internet-shop. Each user has a cart, which contains items(products).

Each cart can be stored in JSON format and then you can load the cart from JSON file. Simple example of usage is placed in src/main/java/Main.

All test classes, which you are going to create, should be placed in src/test/java.

## Tasks:
1. Develop unit tests for JsonParser class (one of them should be Exception test with >= 5 datasets). Determine by yourself, how many tests should be developed
2. Develop 1 test for RealItem class
3. Develop 1 test for VirtualItem class
4. Develop 2 tests for Cart class
5. Disable one of tests from point 1
6. Add 3-4 testng.xml files. They should be different: with including groups/excluding groups/including classes/excluding classes/with parameters/etc. 
7. Add grouped assertion for one of tests *

Tests should be grouped into different categories. Usage of Before/After annotations is required. Use the latest version of TestNG.