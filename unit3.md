# Software Testing : Unit 3

# Index
  - [Black Box Testing](#Black-Box-Testing)
  - [Requirements Traceability Matrix](#Requirements-Traceability-Matrix)
  - [Positive and Negative Testing](#Positive-and-Negative-Testing)
  - [Boundary Value Analysis](#Boundary-Value-Analysis)
  - [Decision Based Testing](#Decision-Based-Testing)
  - [Equivalence Partitioning](#Equivalence-Partitioning)
  - [State Or Graph Based Testing](#State-Or-Graph-Based-Testing)

## Black Box Testing
[Index](#Index)

Testing done :

  - With only functional knowledge of the system.
  - Without any knowledge about the internals of the system.

Characteristics :

1. Done based on requirements.
2. Addresses stated as well as implied requirements.
3. Encompasses the end user perspective.
4. Checks for valid and invalid conditions/inputs.

Advantages :

1. The whole system functionality is under test.
2. Broader picture.
3. This approach sees an application from user's perspective.

### Difference between black box and white box testing methods.

| Black Box Testing | White Box Testing |
| --- | --- |
| No access to code | Access to code |
| Requires external perspective | Requires knowledge of program code |
| Set of techniques applicable to all other phases of testing | Typically applies only to unit testing |

## Requirements Traceability Matrix
[Index](#Index)

Is a document that maps user requirements to test cases.
The purpose is to make sure that all requirements are covered while testing.

### Contents Of RTM

1. Requirement ID
2. Description
3. Priority
4. Test conditions
5. Test case ID
6. Phase of testing

## Positive and Negative Testing
[Index](#Index)

Positive : To check if the product does what it is supposed to.
Negative : To show that the product does not fail when given unexpected inputs.

## Boundary Value Analysis
[Index](#Index)

Most defects tend to occur near range boundaries.
Therefore test near boundary values instead of the entire range of values.

> Any discontinuity in a range that affects the system is considered a boundary value.
> Also include documented limits on hardware resources (Eg : RAM - 4GB)

## Decision Based Testing
[Index](#Index)

Decision variables : influence a program's behavior

  - Distinct combination of these decision variables lead to different scenarios.

## Equivalence Partitioning
[Index](#Index)

Divides input data into partitions of equivalent data from which test cases can be derived.

> Is a generalization of BVA and Decision based testing

## State Or Graph Based Testing
[Index](#Index)

Useful for :

1. Language processing.
2. Workflow modeling.
3. Dataflow modeling.

General characteristics of graph based testing :

  - The application can be characterized by a set of states.
  - The data values that cause transitions are well understood.
  - The methods of processing the data values are also well understood.
