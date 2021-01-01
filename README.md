# Project Title

Automated requirements as mentioned in the Assignment

## Getting Started

Tools used: Intellij as IDE
Browser: Chrome Version : 87
Language: JAVA
framework : TestNG
Build tool: Maven
OS: MAC

### Prerequisites

Java 1.8+ version installed
Maven installed

## Running the tests

1. Import the pom.XML
2. Use commands: mvn clean followed by mvn install to install the dependencies
3. Invoke the test by running testNG.xml from IDE or
   via terminal using command: mvn test

testng.xml includes:
source class: QlearlyFeatures.java
Methods: 10 methods that would run based on priority mentioned one after another.

### Scenarios and exceptions handled

1.Have automated happy path scenarios with various combinations around folders, boards, columns and bookmarks.

2.Have automated bookmark managing and navigated to specific bookmarks to validate the routing is as per expectation.

3.Better try-catch mechanisms to handle, in case of exceptions.

4.Proper asserts and reporting used to provide a detailed context, can be witnessed in testNG Report or surefire reports - have checked in the same.

5.Detailed description of the tests for better understanding.

6.Have used explicit wait to handle time-out issues.

7.Easy integration with jenkins, clone the project and have a build task to execute: mvn test supplied via shell command. Test gets invoked.

## Authors

Vinayak kaladhar

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc
