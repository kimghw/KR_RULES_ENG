# Guidance for Computer-based System Conformity Assessment

> OTHER RULES AND GUIDANCE / GC-30-E / 2025 / EN / Guidance

## CHAPTER 2 COMPUTER BASED SYSTEM

### Section 1 General

#### 101. General

- **1.** All functions mentioned in the user documentation(product description/requirement definition) shall be executable with the corresponding facilities, properties, and data, and within the given limitations, according to all the statements in the user documentation.
- **2.** The function of the software shall be able to execute according to the description defined in the product description/requirement definition.
- **3.** The software shall be free from contradictions within itself and with the product description/requirement definition.
- **4.** The control of the software operation by the end user following product description/requirement definition and the software behaviour shall be consistent.
- **5.** The software shall perform in accordance with the reliability features defined in the product description/requirement definition.
- **6.** The function related to error handling shall be consistent with corresponding statements in the product description/requirement definition
- **7.** The software shall not lose data when used within the limitations stated in the product description/requirement definition.
- **8.** The software shall recognize violations of syntactic conditions for input and it shall not process this as permissible input.
- **9.** The software shall perform in accordance with the effectiveness features stated in the product description/requirement definition.
- **10.** The product description/requirement definition shall state whether maintenance is offered or not. If offered, the product description/requirement definition. shall describe the maintenance services in accordance with the release plan of the software.
- **11.** If the user can carry out installation, the product description/requirement definition shall contain, as applicable, statements on Portability, taking into account adaptability, installability and replaceability, written such that verifiable evidence of compliance can be demonstrated, based on ISO/IEC 25010.
- **12.** If the user can carry out the installation, the software shall be installed successfully by following the information in the the product description/requirement definition.
- **13.** If the user can carry out installation, successful installation and correct operation of the software application shall be verified for all supported platforms and systems listed in the product description/requirement definition.
- **14.** If the user can carry out installation, the software shall provide a mean for the user to uninstall all its installed components.

#### 102. Test Plan

- **1.** Information contained in the test plan shall be verifiable and correct.
- **2.** All document shall be written based on **Ch 1, 201. 5** (1).
- **3.** The test plan in accordance with the requirements of **Ch 1, 201. 5** (1) shall include:
  - **(1)** All the functions described in the product description/requirement definition, as well as the combinations of functions representative of the task to be achieved, shall be subject to test cases.
  - **(2)** Each function described in the product description/requirement definition shall be subject to at least one test case.
  - **(3)** All the installation procedures shall be subject to test cases.
  - **(4)** All the operational limits indicated in the product description and user documentation shall be subject to test cases.
  - **(5)** The test plan shall indicate the criteria used to decide if the test results demonstrate the conformity of the software to the product description

#### 103. Test report

- **1.** The faults shall not be detected in software static testing. however, fault that are not correctable can be handled as an anomaly due to false alarms and software characteristics.
- **2.** The detected false alarm shall be analyzed and made an anomaly report due to limitations of the static testing tool.
- **3.** The alarms that are not correctable shall be made an anomaly report due to software characteristics, even if false alarms detected by software static testing tool.
- **4.** For software dynamic testing, all function and non-function requirement described by product description shall be tested. if dynamic testing is not possible, anomaly report shall be made.
- **5.** For software dynamic testing, the 100% coverage of product shall be achieved. however, where anomaly report shall be made in case of grey code or unable to measure.
- **6.** The test report is to include the requirement specified in **Ch 1, 201. 5** (2), (3).
- **7.** For the static testing result: at least following information is to be included;
  - **(1)** The computer systems used for testing (hardware, software, and their configuration)
  - **(2)** The test tool used for testing
  - **(3)** The software development environment, e.g., complier, development tool, OS, etc.
  - **(4)** The static testing process included test tool
  - **(5)** The criteria applied to the static testing
  - **(6)** Pass/fail criteria
  - **(7)** The overall summary of the potential product defects detected by static testing
  - **(8)** A number of potential defects classified by criteria type
  - **(9)** Where there is anomaly, the summary of the defects is written with identifier
  - **(10)** The weakness list applied to the testing
  - **(11)** The source code metric check list applied to the testing
- **8.** For the dynamic testing result: at least following information is to be included;
  - **(1)** The testing completion date and product identifier shall be included.
  - **(2)** The overall summary of the result of all test case and coverage shall be included.
  - **(3)** The test report shall be proved that all of test cases in test plan were carried out.
  - **(4)** The configuration of hardware and software for testing shall be specified.
  - **(5)** All test case shall be included, as test case identifier, test case name, test case purpose and description, preconditions, test procedure, expected results, and actual results. however, where it is necessary to change product configuration because of product characteristic, the product configuration may be partly changed subject to the approval by the Society.
  - **(6)** The test tools used in the test shall be specified.
  - **(7)** The procedure for performing the tool for coverage measurement shall be specified.
  - **(8)** The results of coverage test shall contain, as overall coverage, file or module coverage, function coverage, etc.
  - **(9)** The errors found in the test shall be corrected prior to the application, and anomaly item shall be reported in the anomaly report.

#### 104. Anomaly report

- **1.** The anomaly report shall include an overall summary of the anomalies found.
- **2.** The anomaly report separated by static and dynamic test shall be submitted to the Society.
- **3.** The anomaly report shall include for each anomaly:
  - **(1)** the identifier and name of the anomaly
  - **(2)** the point in the test case the anomaly occurred
  - **(3)** the anomaly description


### Section 2 Embedded software

#### 201. Application

The requirements of this Section apply to tests and inspection for the conformity assessment of the software installed in embedded OS, real time OS or without OS software for use in the marine environment.

#### 202. Data to be submitted

The following reference data are to be submitted to the Society in addition to those specified in **Ch 1, 201. 5.**

#### 203. Conformity test

- **1.** The static testing in accordance with the requirements of **Ch 1, 201. 5** (1) are to be as given in **Table 2.1.** however, where the language is not C, the rules/standards suitable for the language can be applied and the reference of the rules/standards should be specified.

  | Name | Description |
  | --- | --- |
  | Defensive Programming | Prohibit to use the object which is not verified as a specific factor of specific function. |
  | Defensive Programming | Inspect the scope of constant value coming as a specific factor of specific function. |
  | Defensive Programming | When calling a function, check if the numbers of parameter are same. |
  | Defensive Programming | When calling a function, check if the numbers of parameter are same. |
  | Defensive Programming | Prohibit to assign constant which is out of the type size of variable. |
  | Defensive Programming | In Boolean type variables, prohibit to use values other than boolean type variables and the values of 0 and 1. |
  | Defensive Programming | Inspect a value assignment before using variables. |
  | Defensive Programming | Check if it verifies a divisor for avoiding division by zero. |
  | Defensive Programming | Prohibit explicit conversion for removing const or volatile. |
  | Defensive Programming | Check if a shift operator with value out of scope is used. |
  | Defensive Programming | Prohibit to use plain char type for the purpose other than using or saving character value. |
  | Defensive Programming | Prohibit to used signed and unsigned char types for the purpose other than using or saving numeric value. |
  | Defensive Programming | Prohibit to use a statement which the result is different depending on the assessment order(sequence point detection). |
  | Defensive Programming | Check if the parameter of function macro is enclosed with parenthesis(except that it is connected with # or ##) |
  | Defensive Programming | All macro identifiers in preprocessor directives shall be defined before use, except in #indef and #ifndef preprocessor directives and the defined() operator |
  | Defensive Programming | Prohibit to use the address of local variable to return statement |
  | Defensive Programming | Prohibit to assign an address of local variable to the variable having address which is beyond own scope. |

  | Name | Description |
  | --- | --- |
  | Defensive Programming | If a pointer type parameter of function prototype is not used to modify the object which the pointer directs to, the pointer shall be declared as const. |
  | Defensive Programming | Check all switch clauses having statement is ended by break statement. |
  | Defensive Programming | Check a switch statement has more than one case statement. |
  | Defensive Programming | The last clause of switch statement shall be default clause. |
  | Defensive Programming | Prohibit to use an expression which the operation of conditional expression has always the same result. |
  | Defensive Programming | Prohibit to use bitwise operators(&,\|) in the conditional statement. |
  | Defensive Programming | If there is else if, check if there is else. |
  | Defensive Programming | Check if the bodies of switch, while, do-while, for and if statements are compound statement. |
  | Defensive Programming | Check if explicit return is existed in non-void return type function |
  | Use of coding standard | Prohibit recursive call directly/indirectly. |
  | Use of coding standard | Prohibit to use exit function. |
  | No dynamic variables or dynamic objects | Prohibit to assign dynamic memory. |
  | Online checking during creation of dynamic variables or dynamic objects | Online inspection for installing dynamic variable or dynamic object. |
  | Limited use of pointers | Prohibit to use a pointer which is not inspected by conditional expression. |
  | Limited use of recursion | Prohibit recursive call directly/indirectly. |
  | Structured programming | Prohibit to use goto statement. |
  | Structured programming | Check if initializer/loop-test/counting expressions of for statement are related to loop control. |
  | Information hiding/encapsulation | Prohibit define a global variable to header file. |
  | Information hiding/encapsulation | Prohibit define a function to header file. |
  | Modular approach | Check if a function has one exit point. |
  | Modular approach | Check if the parameters only related to function are declared. |
  | Modular approach | Prohibit to use longjmp function and setjmp macro. |
- **2.** The static testing in accordance with the requirements of **Ch 1, 201. 5** (1) are to be carried out the weakness check. the weakness check are to be done in accordance with the requirements in CWE(CWE-658 for C, CWE-659 for C++, CWE-660 for JAVA). however, where the language is not C or JAVA, the rules/standards suitable for the language can be applied and the reference of the rules/standards should be specified. and also, if there are no rules/standard for the weakness check, the weakness check is not performed.
- **3.** The static testing in accordance with the requirements of **Ch 1, 201. 5** (1) are to be carried out the source code metric check as given in **Table 2.2.**

  | Kind of metric | Acceptance criteria | Note |
  | --- | --- | --- |
  | Cyclomatic Complexity | Max. 20 |   |
  | Number of Call Levels | Max. 6 | Maximum nesting depth |
  | Number of Function Parameters | Max. 8 |   |
  | Number of Calling Functions | Max. 8 | How many other functions are called for this function |
  | Number of Called Functions | Max. 10 | How many other functions does this function call? |
  | Number of Executable Code Lines | Max. 200 |   |
- **4.** The dynamic testing in accordance with the requirements of **Ch 1, 201. 5** (1) are to be as given in **Table 2.3** and function requirement shall be carried out based on equivalence partitioning method, boundary value analysis method(refer to IEC 61508-3 Table b.3).

  | Criteria | Description | Acceptance criteria |
  | --- | --- | --- |
  | Function requirement | How well does the system function meet the specified target as intended? | 100% |
  | Non-Function requirement | How well does the system response time meet the specified target? | 100% |
  | Non-Function requirement | How well does the turnaround time meet the specified targets? | 100% |
  | Non-Function requirement | How may users can access the system simultaneously at a certain time against the specified target? | 100% |
- **5.** The dynamic testing in accordance with the requirements of **Ch 1, 201. 5** (1) are to be carried out the coverage check as given in **Table 2.4.**

  | Criteria | Description | Acceptance criteria |
  | --- | --- | --- |
  | Code coverage | How much of the required test cases has been executed based on requirement definition during testing? | 100% |

#### 204. Other requirements

- **1.** **Requirement definition**
  - **(1)** The requirement shall be defined in a way that is clear, concise, clear, verifiable, testable, maintainable, and feasible.
  - **(2)** The requirement shall be free of terms and descriptions that are not understood by those who use the relevant documents
  - **(3)** In cases where a term used in a particular context could have multiple meanings, terms shall be included in a requirement definition as a glossary where its meaning is made more specific.
  - **(4)** The requirement shall include all requirements, whether relating to functionality, performance, design constraints, attributes, or external interfaces. In particular any external requirements imposed by a system specification should be acknowledged and treated.
  - **(5)** The requirement shall define responses of the software to all realizable input data in all realizable situations with the responses to both valid and invalid input values.
  - **(6)** In case of TBD(To be determined); following information shall be included.
    - **(A)** A description of the conditions causing the TBD (e.g., why an answer is not known) so that the situation can be resolved;
    - **(B)** A description of the customization timing and action to be taken.
  - **(7)** The requirement definition shall specify the logical characteristics of each interface between the software product and the hardware components of the system. this includes configuration characteristics (number of ports, instruction sets, etc.). it also covers such matters as what devices are to be supported, how they are to be supported, and protocols.
  - **(8)** For the external interfaces; at least following information is to be included;
    - **(A)** Name of item
    - **(B)** Description of purpose
    - **(C)** Source of input or destination of output
    - **(D)** Valid range, accuracy and/or tolerance
    - **(E)** Units of measure
    - **(F)** Timing
    - **(G)** Relationships to other inputs/outputs
    - **(H)** Screen formats/window formats
    - **(I)** Data formats
    - **(J)** Command formats
    - **(K)** End messages
  - **(9)** For the external interfaces; at least following information is to be included;
    - **(A)** Exact sequence of operations
    - **(B)** Responses to abnormal situations(overflow, communication facilities, error handling and recovery)
  - **(10)** Effect of parameters
  - **(11)** Relationship of outputs to inputs
    - **(A)** Input/output sequences
    - **(B)** Formulas for input to output conversion
  - **(12)** For the performance requirements; at least following information is to be included;
    - **(A)** The number of terminals to be supported
    - **(B)** The number of simultaneous users to be supported
    - **(C)** Amount and type of information to be handled
  - **(13)** For the database; at least following information is to be included;
    - **(A)** Type of information used by various functions
    - **(B)** Frequency of use
    - **(C)** Accessing capabilities
    - **(D)** Data entities and their relationships
    - **(E)** Integrity constraints
    - **(F)** Data retention requirements


### Section 3 Application software

#### 301. Application

The requirements of this Section apply to tests and inspection for the conformity assessment of standalone software installed on commercial OS for use in the marine environment.

#### 302. Data to be submitted

The following reference data are to be submitted to the Society in addition to those specified in **Ch 1, 201.**

#### 303. Conformity test

- **1.** The static testing in accordance with the requirements of **Ch 1, 201. 5** (1) are to be as given in **Table 3.1.** however, where the language is not C, the rules/standards suitable for the language can be applied and the reference of the rules/standards should be specified.

  | Name | Description |
  | --- | --- |
  | Defensive Programming | Prohibit to use the object which is not verified as a specific factor of specific function. |
  | Defensive Programming | Inspect the scope of constant value coming as a specific factor of specific function. |
  | Defensive Programming | When calling a function, check if the numbers of parameter are same. |
  | Defensive Programming | When calling a function, check if the numbers of parameter are same. |
  | Defensive Programming | Prohibit to assign constant which is out of the type size of variable. |
  | Defensive Programming | In Boolean type variables, prohibit to use values other than boolean type variables and the values of 0 and 1. |
  | Defensive Programming | Inspect a value assignment before using variables. |
  | Defensive Programming | Check if it verifies a divisor for avoiding division by zero. |
  | Defensive Programming | Prohibit explicit conversion for removing const or volatile. |
  | Defensive Programming | Check if a shift operator with value out of scope is used. |
  | Defensive Programming | Prohibit to use plain char type for the purpose other than using or saving character value. |

  | Name | Description |
  | --- | --- |
  | Defensive Programming | Prohibit to used signed and unsigned char types for the purpose other than using or saving numeric value. |
  | Defensive Programming | Prohibit to use a statement which the result is different depending on the assessment order(sequence point detection). |
  | Defensive Programming | Check if the parameter of function macro is enclosed with parenthesis(except that it is connected with # or ##) |
  | Defensive Programming | All macro identifiers in preprocessor directives shall be defined before use, except in #indef and #if ndef preprocessor directives and the defined operator |
  | Defensive Programming | Prohibit to use the address of local variable to return statement |
  | Defensive Programming | Prohibit to assign an address of local variable to the variable having address which is beyond own scope. |
  | Defensive Programming | If a pointer type parameter of function prototype is not used to modify the object which the pointer directs to, the pointer shall be declared as const. |
  | Defensive Programming | Check all switch clauses having statement is ended by break statement. |
  | Defensive Programming | Check a switch statement has more than one case statement. |
  | Defensive Programming | The last clause of switch statement shall be default clause. |
  | Defensive Programming | Prohibit to use an expression which the operation of conditional expression has always the same result. |
  | Defensive Programming | Prohibit to use bitwise operators(&,\|) in the conditional statement. |
  | Defensive Programming | If there is else if, check if there is else. |
  | Defensive Programming | Check if the bodies of switch, while, do-while, for and if statements are compound statement. |
  | Defensive Programming | Check if explicit return is existed in non-void return type function |
  | Use of coding standard | Prohibit recursive call directly/indirectly. |
  | Use of coding standard | Prohibit to use exit function. |
  | No dynamic variables or dynamic objects | Prohibit to assign dynamic memory. |
  | Online checking during creation of dynamic variables or dynamic objects | Online inspection for installing dynamic variable or dynamic object. |
  | Limited use of pointers | Prohibit to use a pointer which is not inspected by conditional expression. |
  | Limited use of recursion | Prohibit recursive call directly/indirectly. |
  | Structured programming | Restrict function complexity(cyclomatic complexity number) |
  | Structured programming | Prohibit to use goto statement. |
  | Structured programming | Check if initializer/loop-test/counting expressions of for statement are related to loop control. |
  | Structured programming | Restrict the maximum nesting depth of function |
  | Information hiding/encapsulation | Prohibit define a global variable to header file. |
  | Information hiding/encapsulation | Prohibit define a function to header file. |
  | Modular approach | Restrict the line of code(LOC) for function. |
  | Modular approach | Check if a function has one exit point. |
  | Modular approach | Check if the parameters only related to function are declared. |
  | Modular approach | Prohibit to use longjmp function and setjmp macro. |
- **4.** The dynamic testing in accordance with the requirements of **Ch 1, 201. 5** (1) are to be as given in **Table 3.2.**

  | Criteria | Description | Acceptance criteria |
  | --- | --- | --- |
  | Function requirement | How well does the software function meet the specified target as intended? | 100% |
  | Non-Function requirement | How well does the software response time, turnaround time, User access capacity, etc. meet the specified target? | 100% |

#### 304. Other requirements

- **1.** **Product description**
  - **(1)** The product description shall display a unique identification.
  - **(2)** The software shall be designated by its product identification(name, version, release date)
  - **(3)** The product description shall contain the name and address(postal or web) of the supplier and, if applicable, of the sellers, e-commerce sellers or distributors.
  - **(4)** The product description shall identify the intended work tasks and services that can be performed with the software.
  - **(5)** The product description shall identify the requirements documents when the supplier wants to claim conformity to documents defined by a law or by a regulatory body that affects the software
  - **(6)** The product description shall contain the license type
  - **(7)** If the product description documentation makes reference to known user callable interfaces to other software, these interfaces or software shall be identified.
  - **(8)** The product description documentation shall indicate where the software relies on specific software and/or hardware with appropriate references(name of software/hardware, version, specific operating system).
  - **(9)** The product description shall state whether maintenance is offered or not. if offered, the product description shall describe the maintenance services offered.
  - **(10)** The functionality in the product description shall include clear terms and criteria in order to avoid ambiguity. especially, the clear value shall be stated if there are performance efficiency, etc. non-function requirement. ![](images/image3.png)
