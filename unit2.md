# Software Testing : Unit 2

Index:
  - [Test Driven Development](#Test-Driven-Development)
  - [Refactoring](#Refactoring)
  - [White Box Testing](#White-Box-Testing)
  - [Static Methods](#Static-Methods)
  - [Structural Testing](#Structural-Testing)
  - [Unit Testing](#Unit-Testing)
  - [Code Coverage Testing](#Code-Coverage-Testing)
  - [Code complexity testing](#Code-complexity-testing)
  - [Integration Testing](#Integration-Testing)
  - [Scenario Testing](#Scenario-Testing)
  - [System Testing](#System-Testing)

# Test Driven Development
[Index](#Software-Testing-:-Unit-2)

Two simple rules:

1. Write a failing automated test before writing any code.
2. Remove duplicates.

> Forces developer to consider the use of a unit before implementing  it.

- Promotes affirmative testing
- Reduces the documentation process at the developer's end.

# Refactoring
[Index](#Software-Testing-:-Unit-2)

The process of changing a software system in such a way that it does not affect the external behavior of the system but improves it's internal structure.

# White Box Testing
[Index](#Software-Testing-:-Unit-2)

- Testing based on the knowledge of the internal structure of the system.
- Performs testing by mapping program code to functionality.

## Limitations of white box testing

1. Can miss big picture
2. Implementation & technology skill required.
3. Greater effort

# Static Methods
[Index](#Software-Testing-:-Unit-2)

- Involves only source code and not the executable.
- Humans going through the source code or using tools.
- No execution involved.
- Checking if good development principles and guidelines are being followed.
- Checking for obvious arithmetic or logical errors.

Methods:

1. Desk checking : Informal check by author
2. Code walkthrough : Group oriented checking with senior member involved
3. Code inspection :  Group oriented checking, formal, documentation involved

## Roles of formal inspection

- Author
- Moderator
- Inspectors
- Scribe

# Structural Testing
[Index](#Software-Testing-:-Unit-2)

- Done by executing code on machine

Types:

1. Unit testing
2. Code coverage testing
3. Code complexity testing

# Unit Testing
[Index](#Software-Testing-:-Unit-2)

- White box testing technique
- Usually performed by the developer
- Individual units or components of software are tested.
- Done during development phase.
- First level of testing.

## Why unit testing?

1. Reduced defect cost - detects bugs early.
2. More reliable code.
3. Increases development speed.
4. Easy debugging.
5. Good unit tests serve as project documentation.

## Types

Unit Testing
  - Manual
  - Automated

Commonly automated.

> Using a separate testing environment helps isolate code and reveal any unnecessary dependencies.

> Cannot be used to catch broad system level errors or defects.

# Code Coverage Testing
[Index](#Software-Testing-:-Unit-2)

- Focus is to cover all/required parts of code
- Map parts of code to required functionality
- Can help identify critical sections of code

## Types of code coverage

1. Statement coverage
2. Path coverage
3. Condition coverage
4. Function coverage

# Code complexity testing
[Index](#Software-Testing-:-Unit-2)

Cyclomatic complexity:

- Provides indication of how many independent paths are there in a program

# Integration Testing
[Index](#Software-Testing-:-Unit-2)

Testing of a partially built system with more than one components integrated together.

## Need for integration testing

- uncovers inter-component interface and functional problems
- potential problems with external interfaces can be identified at an early stage
- potential problems at the system level can be identified at an early stage

## Approaches

1. Top down : Highest levels are integrated first
2. Bottom up : Lower levels are integrated first
3. Bi-directional
4. System integration : Big bang approach

> All are incremental except system integration

## Bi-directional integration

- Combination of Top down & Bottom up
- Uses drivers and stubs

# Scenario Testing
[Index](#Software-Testing-:-Unit-2)

- Uses a speculative story to help the tester work through a complicated problem.
- Scenarios cover a number of tests; different from end users.
- Scenarios describe the usage of a software by an end user.

Five key characteristics:

1. Story driven
2. Motivating
3. Credible
4. Complex
5. Easy to evaluate  

# System Testing
[Index](#Software-Testing-:-Unit-2)

- Testing of the entire integrated system
- Only phase where both functional and non-functional requirements are checked for compliance.
- Focus is on functionality and performance and not exceptions or negative cases.

## Types of Non-functional testing

1. Performance & Load testing
2. Scalability testing
3. Reliability testing
4. Stress testing
5. Interoperability testing
6. Localization testing   
