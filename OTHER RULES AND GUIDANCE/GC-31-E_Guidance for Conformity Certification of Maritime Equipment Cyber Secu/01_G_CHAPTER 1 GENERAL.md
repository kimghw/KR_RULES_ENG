# Guidance for Conformity Certification of Maritime Equipment Cyber Security

> OTHER RULES AND GUIDANCE / GC-31-E / 2025 / EN / Guidance

## CHAPTER 1 GENERAL

### Section 1 General

#### 101. Application

- **1.** This Guidance is to apply to all computer-based systems or their components mounted on ships and offshore facilities. *(2023)*
- **2.** This Guidance defines the security level of computer-based systems and its requirement according to the level, and the application scope is determined by request of the ship owner. *(2023)*
- **3.** Conformity certification in accordance with this Guidance is voluntary unless otherwise stated in the Rules for the Classification of Steel Ships(hereafter referred to as "the **Rules for Steel Ships**") and **Guidance for Approval of Manufacturing Process and Type Approval, Etc.** *(2023)*
- **4.** This Guidance do not address the environmental performance of the hardware and software functions of computer-based systems. *(2023)*
- **5.** Items not included in this Guidance may comply with ISO, IEC or equivalent recognized standards by the appropriate consideration of the Society.
- **6.** Where the specific requirements in international regulation such as IMO are or as Information technology & operating technology develops, when it deems necessary, additional requirements to this Guidance may be required.

#### 102. Definitions (2023)

The definitions of terms are to follow the **Rules for Steel ships**, unless otherwise specified in this Guidance.

- **1.** **Authentication** refers to the verification of the claimed identity of an entity.
- **2.** **Authenticator** refers to means used to confirm the identity of an entity.
- **3.** **Authenticity** refers to the quality of records that can be deduced from internal and external evidence, including physical characteristics, structure, content and context of records, in which some records are intact and undamaged.
- **4.** **Authorization** refers to privileges or permissions granted to system objects to access system resources.
- **5.** **Availability** refers to property of ensuring timely and reliable access to and use of system information and functionality.
- **6.** **Component** refers to entity belonging to a system that exhibits the characteristics of one or more of a host device, network device, software application, or embedded device.
- **7.** **Confidentiality** refers to assurance that information is not disclosed to unauthorized individuals, processes, or device.
- **8.** **Computer Based System**(CBS) refers to a programmable electronic device, or interoperable set of programmable electronic devices, organized to achieve one or more specified purposes such as collection, processing, maintenance, use, sharing, dissemination, or disposition of information. CBS on-board include IT and OT systems. A CBS may be a combination of subsystems connected via network. On-board CBS may be connected directly or via public means of communications (e.g. Internet) to ashore CBSs, other vessels’ CBS and/or other facilities.
- **9.** Conduit refers to a logical grouping of communication channels connecting two or more zones that share common security requirements.
- **10.** Device refers to an individual physical asset that provides a set of functions.
- **11.** Embedded device refers to a special purpose device designed to directly monitor or control a system is called a special purpose device.
- **12.** **Event** refers to occurrence of or change to a particular set of circumstances.
- **13.** Firewall refers to a logical or physical barrier that monitors and controls incoming and outgoing network traffic controlled via predefined rules.
- **14.** Firmware refers to Software embedded in electronic devices that provide control, monitoring and data manipulation of engineered products and systems. These are normally self-contained and not accessible to user manipulation.
- **15.** **Host** refers to general purpose device running an operating system capable of hosting one or more software applications, data stores or functions from one or more suppliers
- **16.** Identifier refers to A pattern of symbols unique within a secure domain that represents or identifies the name of an entity claiming or requesting identity.
- **17.** **Integrity** refers to property of protecting the accuracy and completeness of assets.
- **18.** **Interface** refers to a logical entry point that provides access to a module for logical information flow.
- **19.** **Least Privilege** refers to basic principle that holds that users (humans, software processes or devices) should be assigned the fewest privileges consistent with their assigned duties and functions.
- **20.** **Malicious Code** refers to software used or created to disrupt computer operation.
- **21.** **Mobile Code** refers to program transferred between assets that can be executed without explicit installation by the recipient.
- **22.** Network device refers to device that facilitates data flow between devices, or restricts the flow of data, but does not directly interact with a control process.
- **23.** **Non-repudiation** refers to ability to prove the occurrence of a claimed event or action and its originating entities.
- **24.** Patches refers to software designed to update installed software or supporting data to address security vulnerabilities and other bugs or to improve operating systems or applications.
- **25.** Protocol refers to a common set of rules and signals used by computers on a network to communicate.
- **26.** Recovery refers to Maintain a resilience plan and develop and implement appropriate activities to restore functions or services that have been compromised by cyber security events. The recovery function supports timely return to normal operation to reduce the impact of cyber security events.
- **27.** **Remote Access** refers to access to a component by any user (human, software process or device) communicating from outside the perimeter of the zone being addressed.
- **28.** **Removable External Data Storage(REDS)** source refers to user removable non-network data source, including, but not limited to compact discs, memory sticks and Bluetooth devices.
- **29.** **Secret** refers to A protected information state from being known by a system object except for the purpose of knowing the information.
- **30.** **Security Level** refers to level corresponding to the required set of countermeasures and inherent security properties of devices and systems for a zone or conduit based on assessment of risk for the zone or conduit.
- **31.** **Session** refers to semi-permanent, stateful and interactive information interchange between two or more communicating components.
- **32.** **Switch** refers to a network infrastructure device that is used to interconnect nodes within a network.
- **33.** **Untrusted** refers to not meeting predefined requirements to ensure that an operation, data transaction source, network or software process can be relied upon to behave as expected.
- **34.** **User** refers to individuals, organizational objects, or automated processes that access the system, whether authorized or not.
- **35.** Update refer to A gradual change to hardware or software to address a security vulnerability, bug, reliability, or operational problem.
- **36.** Upgrade refer to A gradual hardware or software change to add new functionality.
- **37.** Zone refer to A set of entities representing the division of a system based on functional, logical, and physical (including location) relationships.

#### 103. Equivalence

The equivalence of alternative and novel features which deviate from or are not directly applicable to the Guidance is to be in accordance with **Pt 1**, **Ch 1**, **104**. of **Rules for the Classification of Steel Ships**. *(2020)*

#### 104. Exclusion from the Guidance

The Society cannot assume responsibility for other technical characteristics for cyber-physical systems not covered by this Guidance. However, the Society may advise on such matters upon inquiry.

#### 105. References (2023)

For the purpose of application of the requirements of this Guidance, the following identified standards can be used and other industry standars my be considered:


### Section 2 Procedures for Certification (2023)

#### 201. Certification application

- **1.** The applicant is, in principle, to be the manufacturer of the computer-based systems and/or that component. However, the applicant, where deemed appropriate by the Society, need not always be the manufacturer of the computer-based systems and/or that component.
- **2.** The manufacturer wishing to obtain a conformity certification is to submit a copy of the application of conformity certification of the Society, together with three copies of the required data for approval and two copies of the required data for reference, to the Society. However, the required data previously submitted to the Society, according to the Technical Rules, may be exempted from submission.
- **3.** The Society may require the submission of the data specified in **4.** where deemed necessary by the Society.
- **4.** **Document for approval**
  - **(1)** Specification of cyber security functions
    - **(A)** Description of how the system meets the applicable requirements
    - **(B)** Description of items whose cyber security requirements are not related to components of the system.(If applicable)
    - **(C)** Intercomponent authentication mechanism data.(If applicable)
  - **(2)** Network topology diagram
    - **(A)** Source and Destination IP addresses.(If applicable)
    - **(B)** Physical connection method.(e.g. Ethernet, RS-232, RS-422, etc.)
  - **(3)** System drawings
    - **(A)** Physical interface of each component.(network port, serial port)
    - **(B)** Each component's wireless interface.(e.g. WIFI, cellular, Bluetooth, mobile hotspot, etc.) (if applicable)
  - **(4)** List of assets
    - **(A)** Name of component
    - **(B)** Brand/Manufacturer (Supplier)
    - **(C)** Model or reference number (some units may contain multiple reference numbers)
    - **(D)** Operating system current version and embedded firmware (software version) and implementation date
  - **(5)** Cyber security conformity test procedures
    - **(A)** Necessary test setup
    - **(B)** Initial condition
    - **(C)** Test methodology
    - **(D)** Test equipment
    - **(E)** Acceptance criteria
  - **(6)** Report of vulnerability scanning
- **5.** **Document for reference**
  - **(1)** Manual for user and/or operator

#### 202. Document review

The Society examines the conformity test program, drawings and data and where deemed appropriate, those are to be approved and returned to the manufacturers.

#### 203. Cyber security conformity test

- **1.** After completion of the document reviews specified in **202.**, the cyber security conformity tests are to be carried out for the test products in the presence of the Surveyor in accordance with the approved conformity test program and test method as deemed appropriate by the Society.
- **2.** Products which have been failed to pass the cyber security conformity tests specified in **1.** should not be retested without revision of drawings and/or specifications. If, following analysis of the experimental data from tests, it is found that the failure of conformity tests have been caused by the poor test conditions, etc., retest without revision may be permitted subject to the Society's approval.
- **3.** In principle, the conformity tests are to be carried out at the manufacturing sites. However, the test may be done outside of manufacturing sites subject to the Society's approval.
- **4.** The conformity tests may be partly or wholly omitted, subject to the approval by the Society, in cases where the manufacturer has been approved by other Classification Society or an inspection organization recognized by the Society.
- **5.** After completion of the conformity tests, the manufacturer is to submit three copies of the test records to the Society.

#### 204. Plant audit

This is to comply with the requirements in **Ch 3 105. of Guidance for Approval of Manufacturing Process and Type Approval, Etc.** Where type approval of equipment is carried out simultaneously or already done, plant audit may be omitted.

#### 205. Notification and announcement of approval

This is to comply with the requirements in **Ch 3 106. of Guidance for Approval of Manufacturing Process and Type Approval, Etc.**

#### 206. Changes in the approved contents

This is to comply with the requirements in **Ch 3 107. of Guidance for Approval of Manufacturing Process and Type Approval, Etc.**

#### 207. Validity and renewal of approval certificate

- **1.** The approval certificate will be valid within three years from the date of issue. In case where the approval certificate is renewed in accordance with the requirements specified in the preceding **206.**, the expiration date will not be changed.
- **2.** This is to comply with the requirements in **Ch 3 108. of Guidance for Approval of Manufacturing Process and Type Approval, Etc.** However, the renewed approval certificate will be valid within three years from the expiry date of old approval certificate.

#### 208. Confirmation test and/or occasional plant audit

This is to comply with the requirements in **Ch 3 109. of Guidance for Approval of Manufacturing Process and Type Approval, Etc.**

#### 209. Suspension or withdrawal of approval

This is to comply with the requirements in **Ch 3 110. of Guidance for Approval of Manufacturing Process and Type Approval, Etc.** ![](images/image3.png)
