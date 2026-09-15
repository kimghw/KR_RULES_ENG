# Guidance for Integrated Software Process Management

> OTHER RULES AND GUIDANCE / GC-34-E / 2025 / EN / Guidance

## CHAPTER 1 GENERAL

### Section 1 General

#### 101. Application

- **1.** This Guidance presents procedures and criteria applied by the Society through the review and survey of computer-based control systems related to software development. The purpose of this guidance is to reduce software-related incidents that can negatively affect system performance.
- **2.** This Guidance specifies methods for the engineering management of software development processes for the design, development and maintenance of integrated computer-based control systems.
- **3.** Ships or offshore structures that meet the procedures and criteria set out in this Guidance can be assigned a notation ISPM.
- **4.** This Guidance highlights the software aspects of the control system. Security standards for hardware, failure mode and effect analysis (FMEA), and computer-based control systems are provided in other rules, guidelines issued by the Society and other standards. In addition to the ones provided in this Guidance, other criteria must be met.
- **5.** The procedures and criteria provided in this guidance are structured processes based on best practices for the engineering management of the software development process in the design, implementation and maintenance of computer-based systems. Compliance with the process and standards of this Guidance is intended to increase the safety, accessibility, reliability and maintainability of computer-based control systems.
- **6.** Software for purpose other than control(e.g. monitoring, management), when it affects on the performance of the control system, is to be developed accordance with the procedures and criteria in this guidance. *(2021)*

#### 102. Definitions

The definitions of terms are to follow the Rules for Steel ships, unless otherwise specified in this Guidance.

- **1.** **"Software Product"** means set of computer programs, procedures, and possibly associated documentation and data.
- **2.** **"Adaptive Maintenance"** means the defect of concept error detected during the Verification process
- **3.** **"Anomaly"** means Modification of a software product performed after delivery to keep a computer program usable in a changed or changing environment.
- **4.** **"Artifact"** means a tangible product or by-product produced during the development of software. Some artifacts help describe the function, architecture, and design of software. Other artifacts are concerned with the process of development itself – such as project plans, business cases, and risk assessments. Much of what are considered artifacts is software documentation.
- **5.** **"Change Control"** means Management of change as one part of the SCM process.
- **6.** **"Closed Loop Verification"** means that the inputs and outputs of the computer-based integrated system are to be simulated with minimal interaction of the other integrated components. The V&V may require changing register values of the program to evaluate the integrated control system software response. A comprehensive understanding of the software code and functions limits this option to simple systems.
- **7.** **"Completeness"** means that the state of software in which full implementation of the required functions is provided.
- **8.** **"Component"** means one of the parts that make up a system. A component may be hardware of software and may be subdivided into other components. The terms “Module“, “component“, and “unit“ are often used interchangeably or defined to be sub-elements of one another in different ways depending upon the context. The relationship of these terms is not yet standardized.
- **9.** **"Comprehensibility"** means that The quality of being able to be understood; intelligibility, conceivability.
- **10.** **"Concept Error"** means that the interpretation of the ConOps is in error when compared to the SRS and SDS or where the intended purpose of the function was not described correctly leading to software modules not performing the intended function properly.
- **11.** **"Concept of Operations(ConOps)"** means a group that is responsible for accepting or rejecting changes in configuration items.
- **12.** **"Configuration Item"** means that an aggregation of hardware, software, or both, that is designated for configuration management and treated as a single entity in the configuration management process.
- **13.** **"Consistency"** means uniformity of design and implementation techniques and notation.
- **14.** **"Corrective Maintenance"** means reactive modification of a software product performed after delivery to correct discovered faults.
- **15.** **"Correctness"** means the state of software in which traceability, consistency, and completeness are provided.
- **16.** **"Cosmetic Defects"** means that these types of defects are the ones, which are primarily related to the presentation or the layout of the data. However there is no danger of corruption of data and incorrect values.
- **17.** **"Critical Defects"** means that These are extremely severe defects, which have already halted or are capable of halting the operation of the computer-based control system.
- **18.** **"Defect"** means a software coding error.
- **19.** **"Deficiency"** means that software appears not to be performing the functions as listed in the ConOps, SRS and SDS.
- **20.** **"Degraded"** means that a component or part of the control system or connected equipment is not functioning per the specification.
- **21.** **"Emergency Maintenance"** means unscheduled corrective maintenance performed to keep a system operational.
- **22.** **"Emulator"** means that an emulator duplicates the functions of one system using a different system. The second system “behaves” like the first system.
- **23.** **"Essential Services"** means those services essential for propulsion and steering, and safety of the ship, which are made up of "primary essential services" and "secondary essential services" and definitions and examples are to be in accordance with Pt. Ch1 101. 4 of the Rules for the Classification of Steel Ships.
- **24.** **"Failed"** means that The ISPM control system or significant portions of the connected equipment is not functioning normally.
- **25.** **"FMECA(Failure Modes, Effects and Criticality Analysis)"** means that the criticality analysis is used to chart the probability of failure modes against the severity of their consequences. The analysis highlights failure modes with relatively high probability and severity of consequences.
- **26.** **"Firmware"** means the combination of a hardware device and computer instructions and data that reside as read-only software on that device.
- **27.** **"Flexibility Matrix"** means a method that facilitates tradeoff analysis concerning scope, schedule and resources during project definition and work planning.
- **28.** **"Function"** means The purpose of the equipment under control (i.e., the hydraulic power unit, winch, power management system).
- **29.** **"Hardware"** means physical equipment used to process, store, or transmit computer software or data.
- **30.** **"Hardware-In-the-Loop"** means that the integrated system’s program is being executed on its native hardware (CPU or controller hardware) and the simulation is being executed on a separate machine. Interfaces between the two are developed for the testing. The simulation is to be of sufficient fidelity to include physical real world dynamic systems to verify the central control system’s programming and documenting the results of the stimulus. The real world represented by mathematical models in the simulation program.
- **31.** **"Human Machine Interface"** means a display and operator input device.
- **32.** **"Instrumentation"** means the attributes of software that provide for the measurement of usage or identification of errors.
- **33.** **"Integrity Level"** means A number assigned by Owner and/or User to a computer-based function based upon the severity of the consequence of a failure of the function. Where 0 has little consequence to 3 where the consequence of a function failure is of significant concern with corresponding consequences.
- **34.** **"Interoperability Testing"** means Testing conducted to determine that a modified system retains the capability of exchanging information with systems of different types, and of using that information.
- **35.** **"Major Defects"** means that these are severe defects, which have not halted the system, but have seriously degraded the performance, caused unintended action or incorrect data transmitted.
- **36.** **"Minor Defects"** means Defects which can or have caused a low-level disruption of function(s). Such defects can result in data latency but not in essential or IL2 or IL3 functions. The integrated system and the function continue to operate, although with a failure. Such a disruption or non-availability of some functionality can be acceptable for a limited period of time for IL1 functions. Minor defects could cause corruption of some none critical data values in a way that is tolerable for a short period.
- **37.** **"Moderate Defects"** means that software function performs differently than specified in the SRS and SDS or FDD leading to a change in the Operating Manual, may be called a Moderate Defect. The Owner is to review the impact and risk of such a change.
- **38.** **"Modification Request"** means A generic term that includes the forms associated with the various trouble/problem-reporting documents (e.g., incident report, trouble report) and the configuration change control documents.
- **39.** **"Modularity"** means Being provided with a structure of highly independent modules.
- **40.** **"Native Computer"** means that the program is being executed on the hardware that it will execute upon when installed.
- **41.** **"Non-native Computer"** means that the program is being executed on an emulation of the target hardware using an emulator.
- **42.** **"Nonoperational"** means that not in working order or ready to use.
- **43.** **"Normal"** means that the control system, connected components and associated input and output modules are in working order.
- **44.** **"Operational"** means (1) Pertaining to a system or component that is ready for use in its intended environment. (2) Pertaining to a system or component that is installed in its intended environment. (3) Pertaining to the environment in which a system or component is intended to be used. (IEEE Std. 610, 1990, IEEE Standard Computer Dictionary, A Compilation of IEEE Standard Computer Glossaries)
- **45.** **"Owner"** means that the Owner is the organization which decides to develop the system, and provides funding.
- **46.** **"Package"** means a test used to determine whether changing part of an issue has created a new issue for a different part of the application.
- **47.** **"Peer Review"** means a process where a document or author’s work is scrutinized by others who are competent or are considered experts in the same field.
- **48.** **"Perfective Maintenance"** means Modification of a software product after delivery to improve performance or maintainability.
- **49.** **"Unit Testing"** means a method wherein the smallest testable portions of a module are verified. Individual units are first tested then these are tested in combination with other units within the module to assess proper interactions and outcomes. Once the module has been proven then inter-module interactions can be tested.
- **50.** **"V&V"** means Verification and Validation of the integrated software program.
- **51.** **"V&V Organization"** means that The V&V organization is to verify the functions defined in the Software Requirement Specification (SRS) and Software Design Requirement (SDS) or Functional Description Documents (FDD) using Closed Loop (specially considered), Software-In-the-Loop or Hardware-In-the-Loop methodology. The V&V organization may be part of the System Integrator’s organization or may be independent, as directed by the Owner, with limitation.
- **52.** **"Validation"** means that Determines if the software satisfy the intended use as documented in the ConOps.
- **53.** **"Verifiability"** means the capability of software to be verified, proved, or confirmed by examination or investigation.
- **54.** **"Verification"** means that Demonstrate the software performs as delineated in the SRS and SDS or FDD. Also determines whether development products of a given activity conform to the requirements of that activity.
- **55.** **"Version Control"** means management of the asset versions generated as part of the SCM process.
- **56.** **"Virus Definition"** means Database of computer virus signature used by anti-virus programs.

#### 103. Equivalence

The Society may consider the acceptance of alternatives to this Guidance, provided that they are deemed to be equivalent or above to those complying with the requirements of the Guidance.

#### 104. Exclusion from the Guidance

The Society cannot assume responsibility for use of unauthorized commercial products and other technical characteristics not specified in the Guidance. ![](images/image4.png)
