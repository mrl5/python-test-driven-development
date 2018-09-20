# Test-driven development
* [ ] Examples from [Unit Testing and Test Driven Development in Python] by [Richard Wells]

## Table of contents
* [Levels of testing](#levels-of-testing)
* [Unit Testing](#unit-testing)

## Levels of testing
(safety nets)
- Unit Testing - testing at the function level
- Component Testing - testing at the library and compiled binary level
- System Testing - tests the external interfaces of a system which is a collection of sub-systems
- Performance Testing - testing done at sub-system and system levels to verify timing and resource usages are acceptable

## Unit Testing
### Why do we unit test?
- software bugs can hurt the business
- software testing catches bugs before they get to the field
- need several levels of safety nets

### Unit Testing specifics
- tests individual functions
- a test should be written for each test case for a function (all positive and negative test cases)
- groups of test can be combined into test suites for better organization
- executes in the development environment rather than the production environment
- execution of the test should be automated

### Summary
- unit tests are the first safety net for catching bugs before the get to the field
- unit test validate test cases for individual functions
- they should build and run in the developer's IDE
- unit tests should run fast


[Unit Testing and Test Driven Development in Python]: https://www.linkedin.com/learning/unit-testing-and-test-driven-development-in-python
[Richard Wells]: https://www.linkedin.com/learning/instructors/richard-wells
