# Software Testing : Unit 1

# Index
  - [What is software testing?](#What-is-software-testing?)
  - [Project Quality Management](#Project-Quality-Management)
  - [Verification & Validation](#Verification-and-Validation)
  - [Software Testing Life Cycle (STLC)](#Software-Testing-Life-Cycle)
  - [Software Testing Types](#Software-Testing-Types)

# What is software testing?
[Index](#Index)

- Software testing is a fundamental part of software development
- A process consisting of all life cycle activities both static and dynamic concerned with planning, preparation and evaluation of the software product and related work to determine if they have satisfied specific requirements, to demonstrate that they are fit for purpose.
- Also detects defects.

- Software Testing
  - Has to be planned
  - has to be performed in a reasonable way
  - should be independent of the objective
  - has to be managed

# Project Quality Management
[Index](#Index)

## What is software quality?

 1. Conformance to requirements.
 2. Lack of defects.
 3. Low defect rate (# of defects / size unit)
 4. High reliability (# of failures per hour)
 5. Probability of failure of operation in specified time (MTTF)

 - IEEE:
    - meets software requirements
    - meets user expectations


  - Pressman:
    - Same as IEEE + implicit characteristics that are expected of professionally developed software

## Generic reasons for software failure

1. Uniqueness of software product
2. High complexity
3. Limited opportunity to detect bugs
4. Environment in which the software is developed
5. Lack of teamwork

## Quality factors
- Correctness
- Reliability
- Efficiency
- Integrity
- Usability
- Maintainability
- Flexibility
- Testability
- Portability
- Interoperability
- Reusability

## Quality Concepts

PMBOK : Quality of conformance to standards or requirements.

ISO 9000 : Quality is the totality of features and
characteristics of a product or service that bear on its ability to
satisfy stated and implied needs.

- Quality is viewed as a process rather than a product.
  - continuous refinement of the process

## Quality Management

- Major processes
  - Quality Planning
  - Quality Assurance : Prevention rather than correction
  - Quality Control : test for behavior, correct and rebuild of required
  - Quality Improvement

  - Cost of Quality : Total price of all efforts to achieve product or service quality
    - Prevention
    - Appraisal
    - Internal Failure
    - External Failure

## Different Between Quality Assurance and Quality Control

| QA | QC |
| --- | --- |
| Concentrates on the process of producing products | Concentrates on specific Product |
| Defect prevention | Defect detection & correction |
| Done throughout life cycle | Done after product is built |
| Staff function | Line function |

# Verification and Validation
[Index](#Index)

## Verification

Process of evaluating a system or component at the end of a phase to determine if it satisfies all the conditions imposed at the starting of that phase.

## Validation

Process of evaluating a system or component at the end of development to determine if it satisfies all the stated requirements.

## ETVX model

1. **E**ntry
2. **T**ask
3. **V**erification
4. e**X**it

# Software Testing Life Cycle
[Index](#Index)

Stages :

1. Requirements Analysis
  - Entry
  ```
  Requirements document, Acceptance criteria defined.
  ```
  - Activity
  ```
  Id types of test to be performed.
  Details about testing priorities and focus.
  Prepare RTM.
  Id test env details.
  Automation feasibility analysis.
  ```
  - Exit
  ```
  Signed off RTM.
  Automation feasibility report.
  ```
  - Deliverable
  ```
  Signed off RTM.
  Automation feasibility report.
  ```

2. Test Planning
  - Entry
  ```
  Requirements document.
  RTM.
  Automation feasibility report.
  ```
  - Activity
  ```
  Prepare test plan/strategy document.
  Test tool selection.
  Test effort estimation.
  Resource planning.
  Training requirements.
  ```
  - Exit
  ```
  Approved test plan/strategy.
  Effort estimation document.
  ```
  - Deliverable
  ```
  Approved test plan/strategy.
  Effort estimation document.
  ```

3. Test Case Development  
  - Entry
  ```
  Requirements document.
  RTM.
  Automation feasibility report.
  ```
  - Activity
  ```
  Create test cases, scripts.
  Review cases & scripts.
  Create test data.
  ```
  - Exit
  ```
  Reviewed test cases, scripts and data.
  ```
  - Deliverable
  ```
  Test cases, scripts and data.
  ```

4. Test Environment Setup  
  - Entry
  ```
  System architecture and design document.
  Env setup plan.
  ```
  - Activity
  ```
  Understand requirements.
  Prepare hardware & software requirements list.
  Setup env and test data.
  Perform smoke test on build.
  ```
  - Exit
  ```
  Successful smoke test
  ```
  - Deliverable
  ```
  Environment ready.
  ```

5. Test Execution   
  - Entry
  ```
  Test plan.
  Test env.
  RTM.
  ```
  - Activity
  ```
  Execute tests.
  Map tests to RTM.
  Retest fixes.
  Regression testing.
  ```
  - Exit
  ```
  All tests executed.
  Defects logged & tracked to closure.
  ```
  - Deliverable
  ```
  Completed RTM.
  Test cases updated with results.
  Defect report.
  ```

6. Test Cycle Closure   
  - Entry
  ```
  Test results.
  Defect logs.
  ```
  - Activity
  ```
  Evaluation.
  Test metrics.
  Document learning.
  Prepare closure report.
  ```
  - Exit
  ```
  Signed off report.
  ```
  - Deliverable
  ```
  Report and metrics.
  ```

# Software Testing Types
[Index](#Index)

## Based on method

- white box : focus on code
- black box : focus on functionality

## Based on requirement type

- Functional
- Non-Functional

## Based on life cycle phase

- Unit testing
- Component testing
- Integration testing
- System testing
- User acceptance testing

## Based on needs

- Regression testing : ensure changes have not affected existing behaviour
- Acceptance testing : customer - before accepting into production.
- Alpha testing  
- Beta testing
