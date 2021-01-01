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
3. Invoke the testNG.xml from IDE or
  via terminal: mvn test

xml includes:
class: QlearlyFeatures.java
Methods: 10 methods that would run based on priority one after another.

### Scenarios and exceptions handled

1.Have automated happy path scenarios such as folder, board and column creation

2.Have automated bookmark managing and have navigated to specific bookmarks to validate the same.

3.Better try-catch mechanism to handle, in case of exceptions.

4.Proper asserts and reporting used to provide a detailed context, can be witnessed in testNG Report - have checked in the same.

5.Detailed description of the method name for better understanding.

6.Have used explicit wait to handle time-out issues.

7.Easy integration with jenkins, clone the project and have command: mvn test supplied via shell command. Test gets invoked.

## Authors

Vinayak kaladhar

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc
