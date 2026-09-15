# Guidance for Cyber Resilience of Ships and Systems

> OTHER RULES AND GUIDANCE / GC-44-E / 2025 / EN / Guidance

## CHAPTER 1 General

### Section 1 General

#### 101. Aim and purpose

- **1.** The aim of this Guidance is to provide a minimum set of requirements for Cyber Resilience of ships, with the purpose of providing technical means to stakeholders which would lead to cyber resilient ships.
- **2.** This Guidance targets the ship as a collective entity for Cyber Resilience and is intended as a base for the complementary application of other industry standards addressing Cyber Resilience of on-board systems, equipment and components.
- **3.** Minimum requirements for Cyber Resilience of on-board systems and equipment are given in **Ch 3.**

#### 102. Application

- **1.** The requirements of this Guidance shall apply to the ships intended to be registered and maintained under this Society in accordance with **Pt 1** of Rules of the Classification of Steel Ships(hereafter referred to as the Class Rules).
- **2.** The minimum requirements for Cyber Resilience in **Ch 2** of this Guidance shall apply to ships requiring the Classification Survey during Construction.
- **3.** The minimum requirements for Cyber Resilience in **Ch 3** of this Guidance shall apply to on-board systems and equipment in the ship subject to **Ch 2.**
- **4.** The additional requirements in **Ch 4** of this Guidance shall apply to the cyber security management system of ships upon the request of the shipowner.
- **5.** The relevant requirements in **Pt 6, Ch 2 of the Class Rules** in addition to the requirements in this Guidance shall be satisfied.
- **6.** The cyber incidents considered in this Guidance are events resulting from any offensive manoeuvre that targets the operational technology (OT) systems onboard ships as defined in **Sec 2**.
- **7.** Items not specified in this Guidance shall satisfy the relevant requirements in the Class Rules.

#### 103. Scope of applicability

- **1.** Vessels in scope
  - **(1)** Passenger ships (including passenger high-speed craft) engaged in international voyages
  - **(2)** Cargo ships of 500 GT and upwards engaged in international voyages
  - **(3)** High speed craft of 500 GT and upwards engaged in international voyages
  - **(4)** Mobile offshore drilling units of 500 GT and upwards
  - **(5)** Self-propelled mobile offshore units engaged in construction (i.e. wind turbine installation maintenance and repair, crane units, drilling tenders, accommodation, etc)
    (Note) This Guidance may be used as non-mandatory guidance to the following.
    1) Ships of war, troopships and naval vessel
    2) Cargo ships less than 500 GT
    3) Vessels not propelled by mechanical means
    4) Wooden ships of primitive build
    5) Passenger yachts (passengers not more than 12)
    6) Pleasure yachts not engaged in trade
    7) Fishing vessels
    8) Site specific offshore installations (i.e. FPSOs, FSUs, etc.)
- **2.** **Systems in scope**
  - **(1)** Operational Technology (OT) systems onboard ships, i.e. those computer based systems (hereafter referred to as CBS) using data to control or monitor physical processes that can be vulnerable to cyber incidents and, if compromised, could lead to dangerous situations for human safety, safety of the vessel and/or threat to the environment. In particular, the CBSs used for the operation of the following ship functions and systems, if present onboard, shall be considered:
    1(D) Electrical power generation and distribution
    - **(A)** Propulsion
    - **(B)** Steering
    - **(C)** Anchoring and mooring
    - **(E)** Fire detection and extinguishing systems
    - **(F)** Bilge and ballast systems, loading computer
    - **(G)** Watertight integrity and flooding detection
    - **(H)** Lighting (e.g. emergency lighting, low locations, navigation lights, etc.)
    - **(I)** Any required safety system whose disruption or functional impairing may pose risks to ship operations (e.g. emergency shutdown system, cargo safety system, pressure vessel safety system, gas detection system, etc.)
  - **(2)** Navigation and communication system
    - **(A)** Navigational systems required by statutory regulations
    - **(B)** Internal and external communication systems required by the Class Rules and statutory regulations
  - **(3)** Any Internet Protocol (IP)-based communication interface from CBSs in scope of this Guidance to other systems.
    (Note) Examples of such systems are, but not limited to, the following:
    1) passenger or visitor servicing and management systems
    2) passenger-facing networks
    3) administrative networks
    4) crew welfare systems
    5) any other systems connected to OT systems, either permanently or temporarily (e.g. during maintenance)
- **3.** **Exclusion of a system from the application**
  A CBS may be excluded from the application scope of this Guidance on condition that a risk assessment is performed for the CBS in accordance with **Sec 3** and it verified by this Society that it is found to meet the acceptance criteria of **304**.

#### 104. Class notations

Ships complying with the Guidance will be assigned with an additional following notation

- **1.** **Cyber Resilience**: ships having Cyber Resilience throughout the ships’ lifecycle in accordance with the relevant requirements in **Ch 2**.
- **2.** **Cyber Resilience(Managed)**: Ships implementing cyber security management system based on cyber risk management process in accordance with the additional requirements in **Ch 4** in addition to the requirements in **Ch 2**.

#### 105. System Category

System categories are defined in **Pt 6, Ch 2, Sec 4** of the Class Rules on the basis of the consequences of a system failure to human safety, safety of the vessel and/or threat to the environment.

#### 106. Equivalence

For navigation and radiocommunication systems, the application of IEC 61162-460 or other equivalent standards in lieu of the required security capabilities in **Ch 3, Sec 4** may be accepted by this Society, on the condition that requirements in **Ch 2** are complied with.

#### 107. Reference

Refer to the following additional IACS documents and international standards for computer-based systems and Cyber Resilience.

- **1.** **IACS UR E22 Rev.3**: Computer-based systems
- **2.** **IACS UR E26 Rev.1**: Cyber resilience of ships
- **3.** **IACS UR E27 Rev.1**: Cyber resilience of on-board systems and equipment
- **4.** **IACS Rec.166**: Cyber resilience
- **5.** **IEC 62443-3-3 (2013)**: Industrial communication networks – Network and system security – Part 3-3: System security requirements and security levels
- **6.** **IEC 62443-4-1 (2018)**: Security for industrial automation and control systems – Part 4-1: Secure product development lifecycle requirements


### Section 2 Definitions and abbreviation

#### 201. Definitions

- **1.** **Annual survey**: See **Pt 1, Ch 2, Sec 2** of the Class Rules
- **2.** **Attack Surface**: The set of all possible points where an unauthorized user can access a system, cause an effect on or extract data from. The attack surface comprises two categories: digital and physical. The digital attack surface encompasses all the hardware and software that connect to an organization’s network. These include applications, code, ports, servers and websites. The physical attack surface comprises all endpoint devices that an attacker can gain physical access to, such as desktop computers, hard drives, laptops, mobile phones, removable drives and carelessly discarded hardware.
- **3.** **Authentication**: Provision of assurance that a claimed characteristic of an entity is correct.
- **4.** **Availability**: property of ensuring timely and reliable access to and use of control system information and functionality
- **5.** **Compensating countermeasure**: An alternate solution to a countermeasure employed in lieu of or in addition to inherent security capabilities to satisfy one or more security requirements.
- **6.** **Computer Based System(CBS)**: A programmable electronic device, or interoperable set of programmable electronic devices, organized to achieve one or more specified purposes such as collection, processing, maintenance, use, sharing, dissemination, or disposition of information. CBSs onboard include IT and OT systems. A CBS may be a combination of subsystems connected via network. Onboard CBSs may be connected directly or via public means of communications (e.g. Internet) to ashore CBSs, other vessels’ CBSs and/or other facilities.
- **7.** **Conduit**: Logical grouping of communication channels, connecting two or more zones, that share common security requirements
- **8.** **Computer Network**: A connection between two or more computers for the purpose of communicating data electronically by means of agreed communication protocols.
- **9.** **Confidentiality**: Property of preserving authorized restrictions on information access and disclosure.
- **10.** **Control**: Means of managing risk, including policies, procedures, guidelines, practices or organizational structures, which can be administrative, technical, management, or legal in nature.
- **11.** **Cyber incident**: An event resulting from any offensive manoeuvre, either intentional or unintentional, that targets or affects one or more CBS onboard, which actually or potentially results in adverse consequences to an onboard system, network and computer or the information that they process, store or transmit, and which may require a response action to mitigate the consequences. Cyber incidents include unauthorized access, misuse, modification, destruction or improper disclosure of the information generated, archived or used in onboard CBS or transported in the networks connecting such systems. Cyber incidents do not include system failures.
- **12.** **Cyber resilience**: The capability to reduce the occurrence and mitigating the effects of cyber incidents arising from the disruption or impairment of operational technology (OT) used for the safe operation of a ship, which potentially lead to dangerous situations for human safety, safety of the vessel and/or threat to the environment.
- **13.** **Defence in depth**: Information Security strategy integrating people, technology, and operations capabilities to establish variable barriers across multiple layers and missions of the organization.
- **14.** **Essential services**: Services for propulsion and steering, and safety of the ship. Essential services comprise "Primary Essential Services" and "Secondary Essential Services": Primary Essential Services are those services which need to be in continuous operation to maintain propulsion and steering; Secondary Essential Services are those services which need not necessarily be in continuous operation to maintain propulsion and steering but which are necessary for maintaining the vessel’s safety.
- **15.** **Firewall**: A logical or physical barrier that monitors and controls incoming and outgoing network traffic controlled via predefined rules.
- **16.** **Firmware**: Software embedded in electronic devices that provide control, monitoring and data manipulation of engineered products and systems. These are normally self-contained and not accessible to user manipulation.
- **17.** **Hardening**: Hardening is the practice of reducing a system's vulnerability by reducing its attack surface.
- **18.** **Information Technology (IT)**: Devices, software and associated networking focusing on the use of data as information, as opposed to Operational Technology (OT).
- **19.** **Integrated system**: A system combining a number of interacting sub-systems and/or equipment organized to achieve one or more specified purposes.
- **20.** **Integrity**: Property of protecting the accuracy and completeness of assets.
- **21.** **Logical network segment**: The same as “Network segment”, but where two or more logical network segments share the same physical components.
- **22.** **Network**: A connection between two or more computers for the purpose of communicating data electronically by means of agreed communication protocols.
- **23.** **Network segment**: In the context of this Guidance, a network segment is an OSI layer-2 Ethernet segment (a broadcast domain). (Note) TCP/IP: Network address plan is prefixed by their IP addresses and the network mask. Communication between network segments is only possible by the use of routing service at network layer (OSI Layer 3).
- **24.** **Network switch (Switch)**: A device that connects devices together on a computer network, by using packet switching to receive, process and forward data to the destination device.
- **25.** **Offensive cyber manoeuvre**: Actions that result in denial, degradation, disruption, destruction, or manipulation of OT or IT systems.
- **26.** **Operational Technology (OT)**: Devices, sensors, software and associated networking that monitor and control onboard systems. Operational technology systems may be thought of as focusing on the use of data to control or monitor physical processes.
- **27.** **OT system**: Computer based systems, which provide control, alarm, monitoring, safety or internal communication functions.
- **28.** **Patches**: Software designed to update installed software or supporting data to address security vulnerabilities and other bugs or improve operating systems or applications
- **29.** **Physical network segment**: The same as “Network segment”, but where physical components are not shared by other network segments.
- **30.** **Protocol**: A common set of rules and signals that computers on the network use to communicate. Protocols allow to perform data communication, network management and security. Onboard networks usually implement protocols based on TCP/IP stacks or various field buses.
- **31.** **Recovery**: Develop and implement the appropriate activities to maintain plans for resilience and to restore any capabilities or services that were impaired due to a cyber security event. The Recovery function support s timely return to normal operations to reduce the impact from a cyber security event.
- **32.** **Security zone**: A collection of CBSs in the scope of applicability of this Guidance that meet the same security requirements. Each zone consists of a single interface or a group of interfaces, to which an access control policy is applied.
- **33.** **Shipowner/Company**: The owner of the ship or any other organization or person, such as the manager, agent or bareboat charterer, who has assumed the responsibility for operation of the ship from the shipowner and who on assuming such responsibilities has agreed to take over all the attendant duties and responsibilities. The shipowner could be the Shipyard or systems integrator during initial construction. After vessel delivery, the shipowner may delegate some responsibilities to the vessel management company.
- **34.** **Special survey**: See **Pt 1, Ch 2, Sec 4** of the Class Rules.
- **35.** **Supplier**: A manufacturer or provider of hardware and/or software products, system components or equipment (hardware or software) comprising of the application, embedded devices, network devices, host devices etc. working together as system or a subsystem. The supplier is responsible for providing programmable devices, sub-systems or systems to the systems integrator.
- **36.** **System**: Combination of interacting programmable devices and/or sub-systems organized to achieve one or more specified purposes.
- **37.** **System Categories (I, II, III)**: System categories based on their effects on system functionality, which are defined in **Pt 6, Ch 2 Sec 4** of the Class Rules.
- **38.** **Systems Integrator**: The specific person or organization responsible for the integration of systems and products provided by suppliers into the system invoked by the requirements in the ship specifications and for providing the integrated system. The systems integrator may also be responsible for integration of systems in the ship. Until vessel delivery, this role shall be taken by the Shipyard unless an alternative organization is specifically contracted/assigned this responsibility.
- **39.** **Untrusted network**: Any network outside the scope of applicability of this Guidance.

#### 202. Abbreviation

- **1.** **AS**: Annual Survey
- **2.** **ACL**: Access Control List
- **3.** **CBS**: Computer Based System
- **4.** **COTS**: Commercial-Off-The-Shelf
- **5.** **DoS**: Denial of Service
- **6.** **HMI**: Human-Machine Interface
- **7.** **IDS**: Intrusion Detection System
- **8.** **IPS**: Intrusion Prevention System
- **9.** **IT**: Information Technology
- **10.** **MoC**: Management of Change
- **11.** **OT**: Operational Technology
- **12.** **TCP/IP**: Transmission Control Protocol/Internet Protocol
- **13.** **SDLC**: Secure Development Life-Cycle
- **14.** **SS**: Special Survey


### Section 3 Risk assessment for exclusion of CBS from the application of requirements

#### 301. Requirement

- **1.** A risk assessment shall be carried out in case any of the CBSs falling under the scope of applicability of this Guidance is excluded from the application of relevant requirements. The risk assessment shall provide evidence of the acceptable risk level associated to the excluded CBSs.

#### 302. Rationale

- **1.** Exclusion of a CBS falling under the scope of applicability of this Guidance from the application of relevant requirements needs to be duly justified and documented. Such exclusion can be accepted by this Society only if evidence is given that the risk level associated to the operation of the CBS is under an acceptable threshold by means of specific risk assessment.
- **2.** The risk assessment shall be based on available knowledge bases and experience on similar designs, if any, considering the CBS category, connectivity and the functional requirements and specifications of the ship and of the CBS. Cyber threat information from internal and external sources may be used to gain a better understanding of the likelihood and impact of cybersecurity events.

#### 303. Requirement details

- **1.** Risk assessment shall be made and kept up to date by the System integrator during the design and building phase considering possible variations of the original design and newly discovered threats and/or vulnerabilities not known from the beginning.
- **2.** During the operational life of the ship, the shipowner shall update the risk assessment considering the constant changes in the cyber scenario and new weaknesses identified in CBS onboard in a process of continuous improvement. Should new risks be identified, the shipowner shall update existing, or implement new risk mitigation measures.
- **3.** Should the changes in the cyber scenario be such as to elevate the risk level associated to the CBS under examination above the acceptable risk threshold, the shipowner shall inform this Society and submit the updated risk assessment for evaluation.
- **4.** The envisaged operational environments for the CBS under examination shall be analyzed in the risk assessment to discern the likelihood of cyber incidents and the impact they could have on the human safety, the safety of the vessel or the marine environment, taking into account the category of the CBS. The attack surface shall be analyzed, taking into account the connectivity of the CBS, possible interfaces for portable devices, logical access restrictions, etc.
- **5.** Emerging risks related to the specific configuration of the CBS under examination shall be also identified. In the risk assessment, the following elements shall be considered:
  - **(1)** Asset vulnerabilities;
  - **(2)** Threats, both internal and external;
  - **(3)** Potential impacts of cyber incidents affecting the asset on human safety, safety of the vessel and/or threat to the environment;
  - **(4)** Possible effects related to integration of systems, or interfaces among systems, including systems not onboard (e.g. if remote access to onboard systems is provided).

#### 304. Acceptance criteria

- **1.** Exclusion of a CBS falling under the scope of applicability of this Guidance from the application of relevant requirements can be accepted by this Society only if assurance is given that the operation of the CBS has no impact on the safety of operations regarding cyber risk.
- **2.** The said exclusion may be accepted for a CBS which does not fully meet the additional criteria listed below but is provided with a rational explanation together with evidence and is found satisfactory by this Society. This Society may also require submittal of additional documents to consider the said exclusion.
- **3.** The following criteria shall be met to exclude a system from the scope of applicability of this Guidance.
  - **(1)** The CBS shall be isolated. (i.e, have no IP-network connections to other systems or networks)
  - **(2)** The CBS shall have no accessible physical interface ports. Unused interfaces shall be logically disabled. It shall not be possible to connect unauthorised devices to the CBS.
  - **(3)** The CBS must be located in areas to which physical access is controlled.
  - **(4)** The CBS shall not be an integrated control system serving multiple ship functions as specified in the scope of applicability of this Guidance. (see **103**)
- **4.** The following additional criteria should be considered for the evaluation of risk level acceptability:
  - **(1)** The CBS should not serve ship functions of category III.
  - **(2)** Known vulnerabilities, threats, potential impacts deriving from a cyber incident affecting the CBS have been duly considered in the risk assessment.
  - **(3)** The attack surface for the CBS is minimized, having considered its complexity, connectivity, physical and logical access points, including wireless access points. ![](images/image3.png)
