# Software Testing : Unit 4

# Index

  - [Acceptance Testing](#Acceptance-Testing)
  - [Non-Functional Testing](#Non-Functional-Testing)

## Acceptance Testing

Testing done in accordance with customer specified criteria.
Typically the criteria is pre-defined and mutually agreed on.

Performed by :

  - Clients
  - End users

### Types  

1. User AT
2. Business AT
3. Contract AT
4. Regulations AT
5. Operational AT
6. Alpha Testing
7. Beta Testing

### Approaches

1. Design / Architecture Based Approach
2. Business vertical / customized instance
3. Deployment focused

### Acceptance Testing Criteria

- Specifying business functionality of some complexity.
- Legal and Statutory requirements.
- May cover some non-functional requirements.
- Process / Procedure requirements (eg : Test coverage)
- Service level agreement

### Challenges

- Needs good effort from customer
- Multiple iterations & customer representatives
- Results need to be carefully analyzed

## Non-Functional Testing

Testing for :
- Reliability
  - Ability to perform functions for specified time / iterations
- Scalability
  - Max scalability of product parameters
- Performance
  - Efficiency evaluation
- Stress
  - Product behavior when pushed beyond specified limits  
- Interoperability
- Compatibility
- Security
  - identification of security vulnerabilities

### Functional vs Non-Functional Testing

| Functional | Non Functional |
| --- | --- |
| Product features and functionality | Quality Factors |
| Product Behavior | Behavior and experience |
| Simple steps; checked against expected results | Huge amounts of data collected and analyzed |
| Defect Detection | Qualification of Product |
| Unit, component, integration and system | System |
| Repeated multiple times | Repeated in case of failures and for different configs |

## Regression Testing

Blackbox testing technique

Used to make sure code change does not impact existing functionality od product.

### Types

1. Corrective

Used when there are no changes made to product specification.

2. Retest-all

Testing all existing aspects of the particular product.
Tedious - not recommended for minor changes

3. Selective

After analyzing impact of new code on existing code, uses subset of existing test cases to reduce cost and effort.

4. Progressive

Used when there are changes in the product specification.

5. Complete

Best technique to be used in case of major changes

6. Partial

Tests when minor changes to existing code

7. Unit

Focuses on units of code while blocking all associated dependencies and interactions during testing. 
