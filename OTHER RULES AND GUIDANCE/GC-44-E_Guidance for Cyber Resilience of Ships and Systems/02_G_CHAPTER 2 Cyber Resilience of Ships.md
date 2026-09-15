# Guidance for Cyber Resilience of Ships and Systems

> OTHER RULES AND GUIDANCE / GC-44-E / 2025 / EN / Guidance

## CHAPTER 2 Cyber Resilience of Ships

### Section 1 General

141414141414**101. Introduction**

#### 102. Application

- **1.** The requirements of this Chapter apply to ships in the application scope according to **Ch 1, 103. 1** during the ship's entire life cycle.
- **2.** On-board systems and equipment in the application scope of this Chapter shall meet the minimum requirements of **Ch 3** in addition to this Chapter.
- **3.** Unless expressly specified otherwise, CBS and network referred to in this Chapter mean the CBS and network in the application scope of the Guidance according to **Ch 1, 103. 2.**


### Section 2 Classification Survey

#### 201. General

The classification survey shall be carried out by this Society by assessment of documentation and survey in the relevant phases as specified in this Section.

- **1.** **Documentation to be submitted**
  - **(1)** Documentation to be submitted by suppliers to this Society is specified in **Ch 3**. The approved versions of this documentation shall also be provided by the suppliers to the systems integrator as specified in **Ch 3, 202. 3**. (see **Table 3.2.1**)
  - **(2)** Documents to be provided by the systems integrator are listed in **202. 1** and **202. 2**. (see **Table 2.2.1**)
  - **(3)** Documents to be provided by the shipowner are listed in **203. 1** (see **Table 2.2.1**)
- **2.** **Provision documentation to a shipowner**
  Upon delivery of the ship, the systems integrator shall provide below documentation to the shipowner.
  - **(1)** Documentation of the CBSs provided by the suppliers (see **Ch 3 202**)
  - **(2)** Documentation produced by the systems integrator (see **202. 1, 202. 2** and **Table 2.2.1**)

    | Document | Ref. | Systems integrator |   |   | Shipowner |   |   |   |
    | --- | --- | --- | --- | --- | --- | --- | --- | --- |
    | Document | Ref. | Design | Cons. | Onboard Test | Oper. | 1st AS | AS | SS |
    | Approved supplier documentation | **Ch 3, 201** |   | M | M | M |   |   |   |
    | Zones and conduit diagram | **202.1** (1) | A | M | M | M |   |   |   |
    | Cyber security design description | **202.1** (1) | A | M | M | M |   |   |   |
    | Vessel asset inventory | **202.1** (1) | A | M | M | M |   |   |   |
    | Risk assessment for the exclusion of CBS^1) | **202.1** (1) | A | M | M | M |   |   |   |
    | Description of compensating countermeasures^1) | **202.1** (1) | A | M | M | M |   |   |   |
    | Ship Cyber Resilience test procedure | **202.2** (2) |   | A | S | M |   |   | S |
    | Ship cyber security and resilience program<br>- Management of change (MoC)<br>- Management of software updates<br>- Management of firewalls<br>- Management of malware protection<br>- Management of access control<br>- Management of confidential information<br>- Management of remote access<br>- Management of mobile and portable devices<br>- Detection of security anomalies<br>- Verification of security functions<br>- Incident response plans<br>- Recovery plans | **203.2** (1)<br>**401.1** (5)<br>**401.1** (5)<br>**402.1** (5)<br>**402.3** (5)<br>**402.4** (5)<br>**402.4** (5)<br>**402.6** (5)<br>**402.7** (5)<br>**403.1** (5)<br>**403.2** (5)<br>**404.1** (5)<br>**405.1** (5) |   |   |   | M | A & S | S |   |
    | 1. **^1)** If applicable<br>2. A (Approval): The stakeholder shall submit the document to this Society for verification and approval of compliance with requirements in this Chapter.<br>3. M (Maintain): The stakeholder shall keep the document updated in accordance with procedure for management of change (MoC). Updated document and change management records shall be submitted to the Class society as per **Pt 6, Ch 2, Sec 4** of the Class Rules.<br>4. S (Survey): The stakeholder shall demonstrate compliance to the this Society in accordance with the approved document. |   |   |   |   |   |   |   |   |
- **3.** **Kinds of surveys**
  Kinds of surveys for the Cyber Resilience of ships are as follows:
  - **(1)** Classification Survey during Construction (hereafter referred to as "Classification Survey")Classification Survey is carried out when there is the application for Classification Survey under construction, and includes document approval and on-board test during the following phases:
    - **(A)** Design phase
    - **(B)** Construction phase
    - **(C)** On-board test phase
  - **(2)** Survey for maintaining Classification (hereafter referred to as "Classification Maintenance Survey")Classification Maintenance Survey shall be carried out to maintain classification after delivery of a ship, and includes the following surveys:
    - **(A)** Annual Surveys
      - **(a)** 1st Annual Survey1st annual survey shall be carried out at intervals specified in **Pt 1, Ch 2, Sec 2.**
      - **(b)** Subsequent SurveysSubsequent Surveys shall be carried from at 2nd Annual Survey to at 4th Annual Survey at intervals specified in **Pt 1, Ch 2, Sec 2.**
    - **(B)** Special SurveysSpecial Surveys shall be carried out at intervals specified in **Pt 1, Ch 2, Sec 4.**
    - **(C)** Occasional SurveysOccasional Surveys shall be carried out at intervals specified in **Pt 1, Ch 2, Sec 10.**

#### 202. Classification Survey

- **1.** **During Design and Construction phase**
  - **(1)** Approval Documents and data
    - **(A)** Zone and conduit diagramThe content of this document is specified in **402. 1** (4) (A).
    - **(B)** Cyber security design description (CSDD)The content of this document is specified in subsections “Design phase” for each requirement in **Sec 4**.
    - **(C)** Vessel asset inventoryThe content of this document is specified in **401. 1**.
    - **(D)** Risk assessment for the exclusion of CBSs The content of this document is specified in **Ch 1, Sec 3.**
    - **(E)** Description of compensating countermeasuresIf any CBS has been approved with compensating countermeasures in lieu of a requirement in **Ch 3**, this document shall specify the respective CBS, the lacking security capability, as well as provide a detailed description of the compensating countermeasures. See also **Ch 3, 301. 3** requiring that the supplier describes such compensating countermeasures in the system documentation.
  - **(2)** The supplier shall demonstrate compliance to this Society by following the certification process specified in **Ch 3, Sec 2.**
  - **(3)** The systems integrator shall demonstrate compliance by submitting documents in the above (1) to this Society for assessment.
  - **(4)** During the design and construction phases, modifications to the design shall be carried out in accordance with the management of change (MoC) requirements in **Pt 6, Ch 2, Sec 4** of the Class Rules.
- **2.** **On-board Test**
  Before final on-board testing of the ship, the systems integrator shall:
  - **(2)** Ship cyber resilience test procedure
    - **(A)** The content of this document is specified for the On-board test phase in each subsection “Classification Survey” in **Sec 4**.
    - **(B)** On-board test of CBSs
      - **(a)** For each CBS, the required inherent security capabilities and configuration thereof are verified and tested in the certification process of each CBS. (see **Ch 3**)
      - **(b)** Testing of such security functions may be omitted if specified in the respective subsection "on-board test phase", on the condition that these security functions have been successfully tested during the certification of the CBS as per **Ch 3**.
      - **(c)** Nevertheless, all tests shall be included in the ship cyber resilience test procedure and the decision to omit tests will be taken by this Society.
      - **(d)** Tests may generally not be omitted if findings/comments are carried over from the certification process to the on-board test phase, if the respective requirements have been met by compensating countermeasures, or due to other reasons such as modifications of the CBS after the certification process.
    - **(C)** The ship cyber resilience test procedure shall also specify how to test any compensating countermeasures described in **202. 1** (1) (E).
    - **(D)** The Ship cyber resilience test procedure shall include means to update status and record findings during the testing, and specify the following information:
      - **(a)** Necessary test setup (i.e. to ensure the test can be repeated with the same expected result)
      - **(b)** Test equipment
      - **(c)** Initial condition(s)
      - **(d)** Test methodology, detailed test steps
      - **(e)** Expected results and acceptance criteria
    - **(E)** Before submitting the Ship cyber resilience test procedure to this Society, the systems integrator shall verify that the information is updated and placed under change management;
      - **(a)** It is aligned with the latest configurations of CBSs and networks connecting such systems together onboard the ship and to other CBSs not onboard (e.g., ashore).
      - **(b)** The tests documented are sufficiently detailed as to allow verification of the installation and operation of measures adopted for the fulfilment of relevant requirements on the final configuration of CBSs and networks onboard.
    - **(F)** The systems integrator shall document verification tests or assessments of security controls and measures in the fully integrated ship, maintaining change management for configurations, and noting in the documented test results where safety conditions may be affected by specific circumstances or failures addressed in the Ship cyber resilience test procedure.
    - **(G)** The testing shall be carried out on board in accordance with the approved Ship cyber resilience test procedure after other commissioning activities for the CBSs are completed.
    - **(H)** This Society may request the execution of additional tests if deemed necessary.

#### 203. Classification Maintenance Survey

- **1.** **General**
  - **(1)** After the ship has been delivered to the shipowner, the shipowner shall manage technical and organisational security countermeasures by establishing and implementing processes as specified in this Chapter.
  - **(2)** Modifications to the CBS shall be carried out in accordance with the management of change (MoC) requirements in **Pt 6, Ch 2, Sec 4** of the Class Rules. This includes keeping documentation of the CBSs up to date.
  - **(3)** The shipowner, with the support of suppliers, shall keep the Ship cyber resilience test procedure up to date and aligned with the CBSs onboard the ship and the networks connecting such systems to each other and to other CBSs not onboard (e.g. ashore). The shipowner shall update the Ship cyber resilience test procedure considering the changes occurred on CBSs and networks onboard, possible emerging risks related to such changes, new threats, new vulnerabilities and other possible changes in the ship’s operational environment.
  - **(4)** The shipowner shall prepare and implement operational procedures, provide periodic training and carry out drills for the onboard personnel and other concerned personnel ashore to familiarize them with the CBSs onboard the ship and the networks connecting such systems to each other and to other CBSs not onboard (e.g. ashore), and to properly manage the measures adopted for the fulfilment of requirements.
  - **(5)** The shipowner, with the support of supplier, shall keep the measures adopted for the fulfilment of requirements up to date, e.g. by periodic maintenance of hardware and software of CBSs onboard the ship and the networks connecting such systems.
  - **(6)** The shipowner shall retain onboard a copy of results of execution of tests and an updated Ship cyber resilience test procedure and make them available to this Society.
- **2.** **Annual survey**
  - **(1)** First Annual Survey
    - **(A)** In due time(6 months in advance of the initial annual survey as possible) before the first Annual Survey of the ship, the shipowner shall submit to this Society a Ship cyber security and resilience program documenting management of cyber security and cyber resilience of the CBSs.
    - **(B)** The Ship cyber security and resilience program shall include policies, procedures, plans and/or other information documenting the processes/activities specified in subsections “Classification Maintenance Survey” in Sec 4.
    - **(C)** After this Society has approved the Ship cyber security and resilience program, the shipowner shall in the first annual survey demonstrate compliance by presenting records or other documented evidence of implementation of the processes described in the approved Ship cyber security and resilience program.
    - **(D)** When the vessel management company is changed, additional approval of the Ship cyber security and resilience program may be requested by this Society if deemed necessary.
  - **(2)** Subsequent Annual SurveysIn the subsequent annual surveys of the ship, the shipowner shall upon request by this Society demonstrate implementation of the Ship cyber security and resilience program.
- **3.** **Special survey**
  Upon renewal of the ship’s classification certificate, the shipowner shall carry out testing witnessed by this Society in accordance with the Ship cyber resilience test procedure. Certain security safeguards shall be demonstrated at Special survey whereas other need only be carried out upon request by this Society based on modifications to the CBSs as specified in subsections “Classification Maintenance Survey” in **Sec 4.**


### Section 3 Goals and organization of requirements

#### 301. Primary goal

- **1.** The primary goal is to support safe and secure shipping, which is operationally resilient to cyber risks.
- **2.** Safe and secure shipping can be achieved through effective cyber risk management system. To support safe and secure shipping resilient to cyber risk, the following sub-goals for the management of cyber risk are defined in the five functional elements listed in **302**.

#### 302. Sub-goals per functional element

- **1.** The following sub-goals and relevant functional elements should be concurrent and considered as parts of a single comprehensive risk management framework.
  **Table 2.3.1 Sub-goals per functional element**

  | **No.** | **Functional element** | **Goal** | **Content** |
  | --- | --- | --- | --- |
  | **1** | **Identify** | The requirements for the ‘Identify’ functional element are aimed at identifying:<br>1) The CBSs onboard, their interdependencies and the relevant information flows;<br>2) The key resources involved in their management, operation and governance, their roles and responsibilities. | Develop an organizational understanding to manage cybersecurity risk to onboard systems, people, assets, data, and capabilities. |
  | **2** | **Protect** | The requirements for the Protect functional element are aimed at the development and implementation of appropriate safeguards supporting the ability to limit or contain the impact of a potential incident. | Develop and implement appropriate safeguards to protect the ship against cyber incidents and maximize continuity of shipping operations. |
  | **3** | **Detect** | The requirements for the Detect functional element are aimed at the development and implementation of appropriate means supporting the ability to reveal and recognize anomalous activity on CBSs and networks onboard and identify cyber incidents. | Develop and implement appropriate measures to detect and identify the occurrence of a cyber incident onboard. |
  | **4** | **Respond** | The requirements for the Respond functional element are aimed at the development and implementation of appropriate means supporting the ability to minimize the impact of cyber incidents, containing the extension of possible impairment of CBSs and networks onboard. | Develop and implement appropriate measures and activities to take action regarding a detected cyber incident onboard. |
  | **5** | **Recover** | The requirements for the Recover functional element are aimed at the development and implementation of appropriate means supporting the ability to restore CBSs and networks onboard affected by cyber incidents. | Develop and implement appropriate measures and activities to restore any capabilities or services necessary for shipping operations that were impaired due to a cyber incident. |

#### 303. Organization of requirements

- **1.** The requirements are organized according to a goal-based approach. Functional/technical requirements are given for the achievement of specific sub-goals of each functional element. The requirements are intended to allow a uniform implementation by stakeholders and to make them applicable to all types of vessels, in such a way as to enable an acceptable level of resilience and apply to all classed vessels/units regardless of operational risks and complexity of OT systems.
- **2.** For each requirement, a rationale is given.
- **3.** **3**. A summary of actions to be carried out and documentation to be made available is also given in **Table 2.2.1** for each phase of the ship’s life and relevant stakeholders participating to such phase.
- **4.** **Sec 4** contains the requirements to be satisfied in order to achieve the primary goal defined in **301**, organized according to the five functional elements identified in **302**.

#### 304. Stakeholders

- **1.** The requirements shall be fulfilled by the stakeholders involved in the design, building and operation of the ship. Among them, the following stakeholders can be identified (see also **Ch 1, Sec 2** for definitions):
  - **(1)** Shipowner/Company
  - **(2)** Systems integrator
  - **(3)** Supplier
  - **(4)** This Classification Society
- **2.** Whilst the above requirements may be fulfilled by these stakeholders, for the purposes of this Chapter, responsibility to fulfill them will lie with the stakeholder who has contracted with this Society.


### Section 4 Requirements for Cyber Resilience of ships

#### 401. Identify

- **1.** **Vessel asset inventory**
  - **(1)** RequirementAn inventory of hardware and software (including application programs, operating systems, if any, firmware and other software components) of the CBSs and of the networks connecting such systems to each other and to other CBSs onboard or ashore shall be provided and kept up to date during the entire life of the ship.
  - **(2)** Requirement details
    - **(A)** The vessel asset inventory shall include at least the CBSs indicated in **Ch 1, 103. 2**, if present onboard.
    - **(B)** The inventory shall be kept updated during the entire life of the ship. Software and hardware modifications potentially introducing new vulnerabilities or modifying functional dependencies or connections among systems shall be recorded in the inventory.
    - **(C)** If confidential information is included in the inventory (e.g. IP addresses, protocols, port numbers), special measures shall be adopted to limit the access to such information only to authorized people.
    - **(D)** HardwareFor all hardware devices, the vessel asset inventory shall include at least the information in **Ch 3, 301. 1.** In addition, the vessel asset inventory may specify system category and security zone associated with the CBS.
    - **(E)** Software
      - **(a)** For all software(e.g., application program, operating system, firmware), the vessel asset inventory shall include at least the information in **Ch 3, 301. 1.**
      - **(b)** The software of the CBSs shall be maintained and updated in accordance with the shipowner's process for management of software maintenance and update policy in the Ship cyber security and resilience program, see **203**.
  - **(3)** RationaleThe inventory of CBSs onboard and relevant software used in OT systems, is essential for an effective management of Cyber Resilience of the ship, the main reason being that every CBS becomes a potential point of vulnerability. Cyber criminals can exploit unaccounted and out-of-date hardware and software to hack systems. Moreover, managing CBS assets enables Companies understand the criticality of each system to ship safety objectives.
  - **(4)** Classification Survey
    Vessel asset inventory is updated and completed at delivery
    CBSs are correctly represented by the vessel asset inventory
    Software of the CBSs has been kept updated, e.g. by vulnerability scanning or by checking the software versions of CBSs while switched on.
    - **(A)** Design phase
      - **(a)** The systems integrator shall submit vessel asset inventory to this Society. (refer to **202. 1** (1))
      - **(b)** The vessel asset inventory shall incorporate the asset inventories of all individual CBSs. Any equipment delivered by the systems integrator shall also be included in the vessel asset inventory.
    - **(B)** Construction phaseThe systems integrator shall keep the vessel asset inventory updated.
    - **(C)** On-board test phase
      - **(a)** The systems integrator shall submit Ship cyber resilience test procedure(refer to **202. 2** (2) and demonstrate to this Society that:
  - **(5)** Classification Maintenance Survey
    Management of change (**203. 1**)
    Hardware and software modifications (**401.1** (2))
    Vulnerabilities and cyber risks (401. 1 (2) and 401. 1 (3))
    Security patching (402. 6 (2) (E))
    - **(A)** General
      - **(a)** For general requirements to surveys in the operation phase, see **203**.
      - **(b)** The shipowner shall in the Ship cyber security and resilience program describe the process of management of change (MoC) for the CBSs, addressing at least the following requirements in this Chapter:
      - **(c)** The shipowner shall in the Ship cyber security and resilience program also describe the management of software updates, addressing at least the following requirements in this Chapter:
    - **(B)** First annual surveyThe shipowner shall present to this Society records or other documented evidence demonstrating implementation of the Ship cyber security and resilience program, i.e., that:
      - **(a)** The approved management of change process has been adhered to.
      - **(b)** Known vulnerabilities and functional dependencies have been considered for the software in the CBSs.
      - **(c)** The Vessel asset inventory has been kept updated.
    - **(C)** Subsequent annual surveysThe shipowner shall upon request by this Society demonstrate implementation of the Ship cyber security and resilience program by presenting records or other documented evidence as specified for the first annual survey.
    - **(D)** Special SurveyThe shipowner shall demonstrate to this Society the activities in 401. 1 (4) (C) as per the Ship cyber resilience test procedure.

#### 402. Protect

- **1.** **Security Zones and Network Segmentation**
  - **(1)** Requirement
    - **(A)** All CBSs shall be grouped into security zones with well-defined security policies and security capabilities.
    - **(B)** Security zones shall either be isolated (i.e. air gapped) or connected to other security zones or networks by means providing control of data communicated between the zones (e.g. firewalls/routers, simplex serial links, TCP/IP diodes, dry contacts, etc.)
    - **(C)** Only explicitly allowed traffic shall traverse a security zone boundary.
  - **(2)** Requirement details
    - **(A)** A security zone may contain multiple CBSs and networks, all of which shall comply with applicable security requirements given in this Chapter and Ch 3.
    - **(B)** The network(s) of a security zone shall be logically or physically segmented from other zones or networks. See also 402. 6 (2).
    - **(C)** CBSs providing required safety functions shall be grouped into separate security zones and shall be physically segmented from other security zones.
    - **(D)** Navigational and communication systems shall not be in the same security zone as machinery or cargo systems. If navigation and/or radio-communication systems are approved in accordance with other equivalent standard(s) (see Ch 3, 102. 2), these systems should be in a dedicated security zone.
    - **(E)** Wireless devices shall be in dedicated security zones. See also 402. 5.
    - **(F)** Systems, networks, or CBSs outside the scope of applicability of this Chapter are considered untrusted networks and shall be physically segmented from security zones required by this Chapter. Alternatively, it is accepted that such systems are part of a security zone if these OT systems meet the same requirements as demanded by the zone.
    - **(G)** It shall be possible to isolate a security zone without affecting the primary functionality of the CBSs in the zone, see also 404. 3.
  - **(3)** Rationale
    While networks may be protected by firewall perimeter and include Intrusion Detection Systems(IDS) or Intrusion Prevention Systems(IPS) to monitor traffic coming in, breaching that perimeter is always possible. Network segmentation makes it more difficult for an attacker to perpetrate an attack throughout the entire network.
    The main benefits of security zones and network segmentation are to reduce the extent of the attack surface, prevent attackers from achieving lateral movement through systems, and improve network performance. The concept of allocating the CBSs into security zones allows grouping the CBSs in accordance with their risk profile.
  - **(4)** Classification Survey
    Clear indication of the security zones
    Simplified illustration of each CBS, and indication of the security zone in which the CBS is allocated, and indication of physical location of the CBS/equipment.
    Reference to the approved version of the CBS system topology diagrams provided by the suppliers (**Ch 3, 301. 2**)
    Illustration of network communication between systems in a security zone
    Illustration of any network communication between systems in different security zones (conduits).
    Illustration of any communication between systems in a security zone and untrusted networks (conduits).
    A short description of the CBSs allocated to the security zone. It shall be possible to identify each CBS in the Zones and conduit diagram.
    Network communication between CBSs in the same security zone. The description shall include purpose and characteristics (i.e. protocols and data flows) of the communication.
    Network communication between CBSs in different security zones. The description shall include purpose and characteristics (i.e. protocols and data flows) of the communication. The description shall also include zone boundary devices and specify the traffic that is permitted to traverse the zone boundary (e.g. firewall rules).
    Any communication between CBSs in security zones and untrusted networks. The description shall include discrete signals, serial communication, and the purpose and characteristics (i.e. protocols and data flows) of IP-based network communication. The description shall also include zone boundary devices and specify the traffic that is permitted to traverse the zone boundary (e.g. firewall rules).
    - **(A)** Design phase
      - **(a)** The systems integrator shall submit Zones and conduit diagram and the Cyber security design description, see **202. 1** (1).
      - **(b)** The Zones and conduit diagram shall illustrate the CBSs, how they are grouped into security zones, and include the following information:
      - **(c)** The systems integrator shall include the following information in the Cyber security design description:
    - **(B)** Construction phaseThe systems integrator shall keep the Zones and conduit diagram updated.
    - **(C)** On-board test phaseThe systems integrator shall submit Ship cyber resilience test procedure (refer to **202. 2** (2) and demonstrate to this Society that:
      - **(a)** The security zones on board are implemented in accordance with the approved documents (i.e. zones and conduit diagram, cyber security design description, asset inventory, and relevant documents provided by the supplier). This may be done by e.g., inspection of the physical installation, network scanning and/or other methods providing the Surveyor assurance that the installed equipment is grouped in security zones according to the approved design.
      - **(b)** Security zone boundaries allow only the traffic that has been documented in the approved Cyber security description. This may be done by e.g., evaluation of firewall rules or port scanning.
  - **(5)** Classification Maintenance Survey
    Principle of Least Functionality (**402. 2** (1))
    Explicitly allowed traffic (**402. 1** (1))
    Protection against denial of service (DoS) events (**402. 2** (1))
    Inspection of security audit records (**403. 1** (2))
    - **(A)** General
      - **(a)** For general requirements to surveys in the operation phase, see **203**.
      - **(b)** The shipowner shall in the Ship cyber security and resilience program describe the management of security zone boundary devices (e.g., firewalls), addressing at least the following requirements in this Chapter:
    - **(B)** First annual surveyThe shipowner shall demonstrate to this Society that the Zones and conduit diagram has been kept updated and present records or other documented evidence demonstrating implementation of the Ship cyber security and resilience program, i.e., that security zone boundaries are managed in accordance with the above requirements.
    - **(C)** Subsequent annual surveysThe shipowner shall upon request by this Society demonstrate implementation of the Ship cyber security and resilience program by presenting records or other documented evidence as specified for the first annual survey.
    - **(D)** Special surveyThe shipowner shall demonstrate to this Society the activities in **402. 1** (4) (C) as per the Ship cyber resilience test procedure.
- **2.** **Network protection safeguards**
  - **(1)** Requirement
    - **(A)** Security zones shall be protected by firewalls or equivalent means as specified in **402. 1**.
    - **(B)** The networks shall also be protected against the occurrence of excessive data flow rate and other events which could impair the quality of service of network resources.
    - **(C)** The CBSs shall be implemented in accordance with the principle of Least Functionality, i.e. configured to provide only essential capabilities and to prohibit or restrict the use of non-essential functions, where unnecessary functions, ports, protocols and services are disabled or otherwise prohibited.
  - **(2)** Requirement details
    - **(A)** The design of network shall include means to meet the intended data flow through the network and minimize the risk of denial of service (DoS) and network storm/high rate of traffic.
    - **(B)** Estimation of data flow rate shall at least consider the capacity of network, data speed requirement for intended application and data format.
  - **(3)** Rationale
    Network protection covers a multitude of technologies, rules and configurations designed to protect the integrity, confidentiality and availability of networks. The threat environment is always changing, and attackers are always trying to find and exploit vulnerabilities.
    There are many layers to consider when addressing network protection. Attacks can happen at any layer in the network layers model, so network hardware, software and policies must be designed to address each area.
    While physical and technical security controls are designed to prevent unauthorized personnel from gaining physical access to network components and protect data stored on or in transit across the network, procedural security controls consist of security policies and processes that control user behaviour.
  - **(4)** Classification Survey
    - **(A)** Design phase: No requirements.
    - **(B)** Construction phase: No requirements.
    - **(C)** On-board test phase
      - **(a)** The systems integrator shall submit Ship cyber resilience test procedure (refer to **202. 2** (2) and demonstrate the following to this Society:
      - **(i)** Test denial of service (DoS) attacks targeting zone boundary protection devices, as applicable.
        - **(ii)** Test denial of service (DoS) to ensure protection against excessive data flow rate, originating from inside each network segment. Such denial of service (DoS) tests shall cover flooding of network (i.e., attempt to consume the available capacity on the network segment), and application layer attack (i.e., attempt to consume the processing capacity of selected endpoints in the network)
        - **(iii)** Test e.g. by analytic evaluation and port scanning that unnecessary functions, ports, protocols and services in the CBSs have been removed or prohibited in accordance with hardening guidelines provided by the suppliers, see **Ch 3, 203. 5** (7) and **Ch 3, 502. 7**.
      - **(b)** The tests in the above (ii) and (iii) may be omitted if performed during the certification of CBSs as per **202. 2** (2)
  - **(5)** Classification Maintenance Survey
    For general requirements to surveys in the operation phase, see section 203.
    - **(A)** Special surveySubject to modifications of the CBSs, the shipowner shall demonstrate to this Society the activities in **402. 2** (4) (C) as per the Ship cyber resilience test procedure.
- **3.** **Antivirus, antimalware, antispam and other protections from malicious code**
  - **(1)** RequirementCBSs shall be protected against malicious code such as viruses, worms, trojan horses, spyware, etc.
  - **(2)** Requirement details
    - **(A)** Malware protection shall be implemented on CBSs. On CBSs having an operating system for which industrial-standard anti-virus and anti-malware software is available and maintained up-to-date, anti-virus and/or anti-malware software shall be installed, maintained and regularly updated, unless the installation of such software impairs the ability of CBS to provide the functionality and level of service required (e.g. for system Cat.II and Cat.III CBSs performing real-time tasks).
    - **(B)** On CBSs where anti-virus and anti-malware software cannot be installed, malware protection shall be implemented in the form of operational procedures, physical safeguards, or according to manufacturer’s recommendations.
  - **(3)** Rationale
    A virus or any unwanted program that enters a user’s system without his/her knowledge can self-replicate and spread, perform unwanted and malicious actions that end up affecting the system’s performance, user’s data/files, and/or circumvent data security measures.
    Anti-virus, anti-malware, anti-spam software will act as a closed door with a security guard fending off the malicious intruding viruses performing a prophylactic function. It detects potential virus and then works to remove it, mostly before the virus gets to harm the system.
    Common means for malicious code to enter CBSs are electronic mail, electronic mail attachments, websites, removable media (for example, universal serial bus (USB) devices, diskettes or compact disks), PDF documents, web services, network connections and infected laptops.
  - **(4)** Classification Survey
    Approved anti-malware software or other compensating countermeasures is effective (test e.g., with a trustworthy anti-malware test file).
    - **(A)** Design phaseThe systems integrator shall include the following information in the Cyber security design description:
      - **(a)** For each CBS, summary of the approved mechanisms provided by the supplier for protection against malicious code or unauthorized software.
      - **(b)** For CBSs with anti-malware software, information about how to keep the software updated.
      - **(c)** Any operational conditions or necessary physical safeguards to be implemented in the shipowner’s management system.
    - **(B)** Construction phaseThe systems integrator shall ensure that malware protection is kept updated during the construction phase.
    - **(C)** On-board test phase
      - **(a)** The systems integrator shall submit Ship cyber resilience test procedure (refer to **202. 2** (2) and demonstrate the following to this Society:
      - **(b)** The above tests may be omitted if performed during the certification of CBSs as per **202. 2** (2)
  - **(5)** Classification Maintenance Survey
    Maintenance/update (**402. 3** (2))
    Operational procedures, physical safeguards (402.3 (2))
    Use of mobile, portable, removable media (**402. 4** (2) (D) and **402. 7** (2))
    Access control (**402. 4**)
    - **(A)** General
      - **(a)** For general requirements to surveys in the operation phase, see **203**.
      - **(b)** The shipowner shall in the Ship cyber security and resilience program describe the management of malware protection, addressing at least the following requirements in this Chapter:
    - **(B)** First annual surveyThe shipowner shall present to this Society records or other documented evidence demonstrating implementation of the Ship cyber security and resilience program, i.e., that:
      - **(a)** Any anti-malware software has been maintained and updated.
      - **(b)** Procedures for use of portable, mobile or removable devices have been followed.
      - **(c)** Policies and procedures for access control have been followed.
      - **(d)** Physical safeguards are maintained.
    - **(C)** Subsequent annual surveysThe shipowner shall upon request by this Society demonstrate implementation of the Ship cyber security and resilience program by presenting records or other documented evidence as specified for the first annual survey.
    - **(D)** Special surveyThe shipowner shall demonstrate to this Society the activities in section 402.3.(4).(C) as per the Ship cyber resilience test procedure.
- **4.** **Access control**
  - **(1)** Requirement
    - **(A)** CBSs and networks shall provide physical and/or logical/digital measures to selectively limit the ability and means to communicate with or otherwise interact with the system itself, to use system resources to handle information, to gain knowledge of the information the system contains or to control system components and functions.
    - **(B)** Such measures shall be such as not to hamper the ability of authorized personnel to access CBS for their level of access according to the least privilege principle.
  - **(2)** Requirement detailsAccess to CBSs and networks in the scope of applicability of this Chapter and all information stored on such systems shall only be allowed to authorized personnel, based on their need to access the information as a part of their responsibilities or their intended functionality.
    (Note) CBSs shall identify and authenticate human users as per item no.1 in Table 3.4.1 of Ch 3. In other words, it is not necessary to “uniquely” identify and authenticate all human users.
    - **(A)** Physical access controlCBSs of Cat.II and Cat.III shall generally be located in rooms that can normally be locked or in controlled space to prevent unauthorized access, or shall be installed in lockable cabinets or consoles. Such locations or lockable cabinets/consoles shall be however easy to access to the crew and various stakeholders who need to access to CBSs for installation, integration, operation, maintenance, repair, replacement, disposal etc. so as not to hamper effective and efficient operation of the ship.
    - **(B)** Physical access control for visitorsVisitors such as authorities, technicians, agents, port and terminal officials, and shipowner representatives shall be restricted regarding access to CBSs onboard whilst on board, e.g. by allowing access under supervision.
    - **(C)** Physical access control of network access points
      - **(a)** Access points to onboard networks connecting Cat.II and/or Cat.III CBSs shall be physically and/or logically blocked except when connection occurs under supervision or according to documented procedures, e.g. for maintenance.
      - **(b)** Independent computers isolated from all on-board networks, or other networks, such as dedicated guest access networks, or networks dedicated to passenger recreational activities, shall be used in case of occasional connection requested by a visitor (e.g. for printing documents).
    - **(D)** Removable media controlsA policy for the use of removable media devices shall be established, with procedures to check removable media for malware and/or validate legitimate software by digital signatures and watermarks and scan prior to permitting the uploading of files onto a ship’s system or downloading data from the ship’s system. See also 402. 7.
    - **(E)** Management of credentials
      - **(a)** CBSs and relevant information shall be protected with file system, network, application, or database specific Access Control Lists (ACL). Accounts for onboard and onshore personnel shall be left active only for a limited period according to the role and responsibility of the account holder and shall be removed when no longer needed.
      - **(b)** On-board CBSs shall be provided with appropriate access control that fits to the policy of their Security Zone but does not adversely affect their primary purpose. CBSs which require strong access control may need to be secured using a strong encryption key or multi-factor authentication.
      - **(c)** Administrator privileges shall be managed in accordance with the policy for access control, allowing only authorized and appropriately trained personnel full access to the CBS, who as part of their role in the company or onboard need to log on to systems using these privileges.
    - **(F)** Least privilege principle
      - **(a)** Any human user allowed to access CBS and networks in the scope of applicability of this Chapter shall have only the bare minimum privileges necessary to perform its function.
      - **(b)** The default configuration for all new account privileges shall be set as low as possible. Wherever possible, raised privileges shall be restricted only to moments when they are needed, e.g. using only expiring privileges and one-time-use credentials. Accumulation of privileges over time shall be avoided, e.g. by regular auditing of user accounts.
  - **(3)** Rationale
    Attackers may attempt to access the ship’s systems and data from either onboard the ship, within the company, or remotely through connectivity with the internet. Physical and logical access controls to cyber assets, networks etc. should then be implemented to ensure safety of the ship and its cargo.
    Physical threats and relevant countermeasures are also considered in the ISPS Code. Similarly, the ISM Code contains guidelines to ensure safe operation of ships and protection of the environment. Implementation of ISPS and ISM Codes may imply inclusion in the Ship Security Plan (SSP) and Safety Management System (SMS) of instructions and procedures for access control to safety critical assets.
  - **(4)** Classification Survey
    The systems integrator shall prevent unauthorized access to the CBSs during the construction phase.
    - **(A)** Design phaseThe systems integrator shall include the following information in the Cyber security design description:
      - **(a)** Location and physical access controls for the CBSs. Devices providing Human Machine Interface (HMI) for operators needing immediate access need not enforce user identification and authentication provided they are located in an area with physical access control. Such devices shall be specified.
    - **(B)** Construction phase
    - **(C)** On-board test phaseThe systems integrator shall submit Ship cyber resilience test procedure (refer to **202. 2** (2) and demonstrate the following to this Society:
      - **(a)** Components of the CBSs are located in areas or enclosures where physical access can be controlled to authorized personnel.
      - **(b)** User accounts are configured according to the principles of segregation of duties and least privilege and that temporary accounts have been removed (may be omitted based on certification of CBSs as per **202. 2** (2)
  - **(5)** Classification Maintenance Survey
    - Physical access control (402. 4 (2) (A))
    - Physical access control for visitors (402. 4 (2) (B))
    - Physical access control of network access points (402. 4 (2) (C))
    - Management of credentials (402. 4 (2) (E))
    - Least privilege policy (402. 4 (2) (F))
    - Confidential information (401. 1 (2))
    - Information allowed to authorized personnel (402. 4 (2))
    - Information transmitted on the wireless network (402. 5 (2))
    - **(A)** General
      - **(a)** For general requirements to surveys in the operation phase, see **203**.
      - **(b)** The shipowner shall in the Ship cyber security and resilience program describe the management of logical and physical access, addressing at least the following requirements in this Chapter:
      - **(c)** The shipowner shall in the Ship cyber security and resilience program describe the management of confidential information, addressing at least the following requirements in this Chapter:
    - **(B)** First annual surveyThe shipowner shall present to this Society records or other documented evidence demonstrating implementation of the Ship cyber security and resilience program, i.e., that:
      - **(a)** Personnel are authorized to access the CBSs in accordance with their responsibilities.
      - **(b)** Only authorised devices are connected to the CBSs.
      - **(c)** Visitors are given access to the CBSs according to relevant policies and procedures.
      - **(d)** Physical access controls are maintained and applied.
      - **(e)** Credentials, keys, secrets, certificates, relevant CBS documentation, and other sensitive information is managed and kept confidential according to relevant policies and procedures.
    - **(C)** Subsequent annual surveysThe shipowner shall upon request by this Society demonstrate implementation of the Ship cyber security and resilience program by presenting records or other documented evidence as specified for the first annual survey.
- **5.** **Wireless communication**
  - **(1)** RequirementWireless communication networks in the scope of this Chapter shall be designed, implemented and maintained to ensure that:
    - **(A)** Cyber incidents will not propagate to other control systems
    - **(B)** Only authorised human users will gain access to the wireless network
    - **(C)** Only authorised processes and devices will be allowed to communicate on the wireless network
    - **(D)** Information in transit on the wireless network cannot be manipulated or disclosed
  - **(2)** Requirement details
    - **(A)** Cryptographic mechanisms such as encryption algorithms and key lengths in accordance with industry standards and best practices shall be applied to ensure integrity and confidentiality of the information transmitted on the wireless network.
    - **(B)** Devices on the wireless network shall only communicate on the wireless network (i.e. they shall not be “dual-homed”)
    - **(C)** Wireless networks shall be designed as separate segments in accordance with **402. 1** and protected as per **402. 2**.
    - **(D)** Wireless access points and other devices in the network shall be installed and configured such that access to the network can be controlled.
    - **(E)** The network device or system utilizing wireless communication shall provide the capability to identify and authenticate all users (humans, software processes or devices) engaged in that communication.
  - **(3)** Rationale
    - **(A)** Wireless networks give rise to additional or different cybersecurity risks than wired networks. This is mainly due to less physical protection of the devices and the use of the radio frequency communication.
    - **(B)** Inadequate physical access control may lead to unauthorised personnel gaining access to the physical devices, which in turn could lead to circumventing logical access restrictions or deployment of rogue devices on the network.
    - **(C)** Signal transmission by radio frequency introduces risks related to jamming as well as eavesdropping which in turn could cater for attacks such as Piggybacking or Evil twin attacks (see https://us-cert.cisa.gov/ncas/tips/ST05-003).
  - **(4)** Classification Survey
    Only authorised devices can access the wireless network.
    Secure wireless communication protocol is used as per approved documentation by the respective supplier (demonstrate e.g. by use of a network protocol analyser tool).
    - **(A)** Design phaseThe systems integrator shall include the following information in the Cyber security design description:
      - **(a)** Description of wireless networks in the scope of applicability of this Chapter and how these are implemented as separate security zones. The description shall include zone boundary devices and specify the traffic that is permitted to traverse the zone boundary (e.g. firewall rules)
    - **(B)** Construction phaseThe systems integrator shall prevent unauthorised access to the wireless networks during the construction phase.
    - **(C)** On-board test phase
      - **(a)** The systems integrator shall submit Ship cyber resilience test procedure (refer to **202. 2** (2) and demonstrate the following to this Society:
      - **(b)** The above tests may be omitted if performed during the certification of CBSs as per **202. 2** (2)
  - **(5)** Classification Maintenance Survey
    - **(A)** For general requirements to surveys in the operation phase, see section 203.
    - **(B)** Special surveySubject to modifications of the wireless networks, the shipowner shall demonstrate to this Society the activities in **402. 5** (4) (C) as per the Ship cyber resilience test procedure.
- **6.** **Remote access control and communication with untrusted networks**
  - **(1)** RequirementCBSs shall be protected against unauthorized access and other cyber threats from untrusted networks.
  - **(2)** Requirement details
    - **(A)** User’s manual shall be delivered for control of remote access to onboard IT and OT systems. Clear guidelines shall identify roles and permissions with functions.
    - **(B)** For CBSs in the scope of applicability of this Chapter, no IP address shall be exposed to untrusted networks.
    - **(C)** Communication with or via untrusted networks requires secure connections (e.g. tunnels) with endpoint authentication, protection of integrity and authentication and encryption at network or transport layer. Confidentiality shall be ensured for information that is subject to read authorization.
    - **(D)** DesignCBSs in the scope of applicability of this Chapter shall:
      - **(a)** have the capability to terminate a connection from the onboard connection endpoint. Any remote access shall not be possible until explicitly accepted by a responsible role on board.
      - **(b)** be capable of managing interruptions during remote sessions so as not to compromise the safe functionality of OT systems or the integrity and availability of data used by OT systems.
      - **(c)** provide a logging function to record all remote access events and retain for a period of time sufficient for offline review of remote connections, e.g. after detection of a cyber incident.
    - **(E)** Additional requirements for remote maintenanceWhen remote access is used for maintenance, the following requirements shall be complied with in addition to those in **402. 6** (2) (D):
      - **(a)** Documentation shall be provided to show how they connect and integrate with the shore side.
      - **(b)** Security patches and software updates shall be tested and evaluated before they are installed to ensure they are effective and do not result in side effects or cyber events that cannot be tolerated. A confirmation report from the software supplier towards above shall be obtained, prior to undertaking remote update.
      - **(c)** Suppliers shall provide plans for- and make security updates available to the shipowner, see Ch 3, 502. 2 and Ch 3, 502. 3 and Ch 3, 502. 4.
      - **(d)** At any time, during remote maintenance activities, authorized personnel shall have the possibility to interrupt and abort the activity and roll back to a previous safe configuration of the CBS and systems involved.
      - **(e)** Multi-factor authentication is required for any access by human users to CBS’s in scope from an untrusted network.
      - **(f)** After a configurable number of failed remote access attempts, the next attempt shall be blocked for a predetermined length of time.
      - **(g)** If the connection to the remote maintenance location is disrupted for some reason, access to the system shall be terminated by an automatic logout function.
  - **(3)** RationaleOnboard CBSs have become increasingly digitalized and connected to the internet to perform a wide variety of legitimate functions. The use of digital systems to monitor and control onboard CBSs makes them vulnerable to cyber incidents. Attackers may attempt to access onboard CBSs through connectivity with the internet and may be able to make changes that affect a CBS’s operation or even achieve full control of the CBS, or attempt to download information from the ship’s CBS. In addition, since use of legacy IT and OT systems that are no longer supported and/or rely on obsolete operating systems affects Cyber Resilience, special care should be put to relevant hardware and software installations on board to help maintain a sufficient level of Cyber Resilience when such systems can be remotely accessed, also keeping in mind that not all cyber incidents are a result of a deliberate attack.
  - **(4)** Classification Survey
    - **(A)** Design phaseThe systems integrator shall include the following information in the Cyber security design description:
      - **(a)** Identification of each CBS in the scope of applicability of this Chapter that can be remotely accessed or that otherwise communicates through the security zone boundary with untrusted networks.
      - **(b)** For each CBS, a description of compliance with requirements in 402. 6. (2), as applicable.
    - **(B)** Construction phaseThe systems integrator shall ensure that any communication with untrusted networks is only temporarily enabled and used in accordance with the requirements of this section.
    - **(C)** On-board test phaseThe systems integrator shall submit Ship cyber resilience test procedure (refer to **202. 2** (2) and demonstrate the following to this Society:
      - **(a)** Communication with untrusted networks is secured in accordance with Ch 3, 402. and that the communication protocols cannot be negotiated to a less secure version (demonstrate e.g., by use of a network protocol analyzer tool).
      - **(b)** Remote access requires multifactor authentication of the remote user.
      - **(c)** A limit of unsuccessful login attempts is implemented, and that a notification message is provided for the remote user before session is established.
      - **(d)** Remote connections must be explicitly accepted by responsible personnel on board.
      - **(e)** Remote sessions can be manually terminated by personnel on board or that the session will automatically terminate after a period of inactivity.
      - **(f)** Remote sessions are logged (see Ch 3, 401. item no.13).
      - **(g)** Instructions or procedures are provided by the respective product suppliers (see Ch 3, 301. 3).
  - **(5)** Classification Maintenance Survey
    - User's manual (402. 6 (2))
    - Roles and permissions (402. 6 (2))
    - Patches and updates (402. 6 (2) (E))
    - Confirmation prior to undertaking remote software update (402. 6 (2) (E))
    - Interrupt, abort, roll back (402. 6 (2) (E))
    - **(A)** General
      - **(a)** For general requirements to surveys in the operation phase, see section 203.
      - **(b)** The shipowner shall in the Ship cyber security and resilience program describe the management of remote access and communication with/via untrusted networks, addressing at least the following requirements in this Chapter:
    - **(B)** First annual surveyThe shipowner shall present to this Society records or other documented evidence demonstrating implementation of the Ship cyber security and resilience program, i.e., that:
      - **(a)** Remote access sessions have been recorded or logged and carried out as per relevant policies and user manuals.
      - **(b)** Installation of security patches and other software updates have been carried out in accordance with Management of change procedures and in cooperation with the supplier.
    - **(C)** Subsequent Annual surveyThe shipowner shall upon request by this Society demonstrate implementation of the Ship cyber security and resilience program by presenting records or other documented evidence as specified for the first annual survey.
    - **(D)** Special surveyThe shipowner shall demonstrate to this Society the activities in **402. 6** (4) (C) as per the Ship cyber resilience test procedure.
- **7.** **Use of Mobile and Portable Devices**
  - **(1)** RequirementThe use of mobile and portable devices in CBSs shall be limited to only necessary activities and be controlled in accordance with **Ch 3, 401.** item no.10. For any CBS that cannot fully meet these requirements, the interface ports shall be physically blocked.
  - **(2)** Requirement detailsMobile and portable devices shall only be used by authorised personnel. Only authorised devices may be connected to the CBSs. All use of such devices shall be in accordance with the shipowner's policy for use of mobile and portable devices, taking into account the risk of introducing malware in the CBS.
  - **(3)** RationaleIt is generally known that CBSs can be impaired due to malware infection via a mobile or a portable device. Therefore, connection of mobile and portable devices should be carefully considered. In addition, mobile equipment that is required to be used for the operation and maintenance of the ship should be under the control of the shipowner.
  - **(4)** Classification Survey
    - **(A)** Design phaseThe systems integrator shall include the following information in the Cyber security design description:
      - **(a)** Any CBSs in the scope of applicability that do not meet the requirements in **Ch 3, 401.** item no.10, i.e., that shall have protection of interface ports by physical means such as port blockers.
    - **(B)** Construction phaseThe systems integrator shall ensure that use of physical interface ports in the CBSs is controlled in accordance with **Ch 3, 401.** item no.10, and that any use of such devices follows procedures to prevent malware from being introduced in the CBS.
    - **(C)** On-board test phaseThe systems integrator shall submit Ship cyber resilience test procedure (refer to **202. 2** (2) and demonstrate to this Society that capabilities to control use of mobile and portable devices are implemented correctly, the following countermeasures shall be demonstrated as relevant:
      - **(a)** Use of mobile and portable devices is restricted to authorised users.
      - **(b)** Interface ports can only be used by specific device types.
      - **(c)** Files cannot be transferred to the system from such devices.
      - **(d)** Files on such devices will not be automatically executed (by disabling autorun)
      - **(e)** Network access is limited to specific MAC or IP addresses.
      - **(f)** Unused interface ports are disabled.
      - **(g)** Unused interface ports are physically blocked.
  - **(5)** Classification Maintenance Survey
    - Policy and procedures (402. 4 (2) (D))
    - Physical block of interface ports (402. 7 (1))
    - Use by authorized personnel (402. 7 (2))
    - Connect only authorized devices (402. 7 (2))
    - Consider risk of introducing malware (402. 7 (2))
    - **(A)** General
      - **(a)** For general requirements to surveys in the operation phase, see **203**.
      - **(b)** The shipowner shall in the Ship cyber security and resilience program describe the management of mobile and portable devices, addressing at least the following requirements in this Chapter:
    - **(B)** First annual surveyThe shipowner shall present to this Society records or other documented evidence demonstrating implementation of the Ship cyber security and resilience program, i.e., that:
      - **(a)** The use of mobile, portable or removable media is restricted to authorised personnel and follows relevant policies and procedures.
      - **(b)** Only authorised devices are connected to the CBSs.
      - **(c)** Means to restrict use of physical interface ports are implemented as per approved design documentation.
    - **(C)** Subsequent annual surveysThe shipowner shall upon request by this Society demonstrate implementation of the Ship cyber security and resilience program by presenting records or other documented evidence as specified for the first annual survey.
    - **(D)** Special surveyThe shipowner shall demonstrate to this Society the activities in **402. 7** (4) (C) as per the Ship cyber resilience test procedure.

#### 403. Detect

- **1.** **Network operation monitoring**
  - **(1)** RequirementNetworks in scope of this Chapter shall be continuously monitored, and alarms shall be generated if malfunctions or reduced/degraded capacity occurs.
  - **(2)** Requirement details
    - **(A)** Measures to monitor networks in the scope of applicability of this Chapter shall have the following capabilities:
      - **(a)** Monitoring and protection against excessive traffic
      - **(b)** Monitoring of network connections
      - **(c)** Monitoring and recording of device management activities
      - **(d)** Protection against connection of unauthorized devices
      - **(e)** Generate alarm if utilization of the network’s bandwidth exceeds a threshold specified as abnormal by the supplier. See Pt 6, Ch 2, 407. of the Class Rules.
    - **(B)** Intrusion detection systems (IDS) may be implemented, subject to the following:
      - **(a)** The IDS shall be qualified by the supplier of the respective CBS
      - **(b)** The IDS shall be passive and not activate protection functions that may affect the performance of the CBS
      - **(c)** Relevant personnel should be trained and qualified for using the IDS
  - **(3)** RationaleCyber-attacks are becoming increasingly sophisticated, and attacks that target vulnerabilities that were unknown at the time of construction could result in incidents where the vessel is ill-prepared for the threat. To enable an early response to attacks targeting these types of unknown vulnerabilities, technology capable of detecting unusual events is required. A monitoring system that can detect anomalies in networks and that can use post-incident analysis provides the ability to appropriately respond and further recover from a cyber event.
  - **(4)** Classification Survey
    Test that disconnected network connections will activate alarm and that the event is recorded.
    Test that abnormally high network traffic is detected, and that alarm and audit record is generated. This test may be carried on together with the test in **404. 4** (2).
    Demonstrate that the CBS will respond in a safe manner to network storm scenarios, considering both unicast and broadcast messages (see also **402. 2** (2) (C))
    Demonstrate generation of audit records (logging of security-related events)
    If Intrusion detection systems are implemented, demonstrate that this is passive and will not activate protection functions that may affect intended operation of the CBSs.
    - **(A)** Design phase: no requirements.
    - **(B)** Construction phase: no requirements.
    - **(C)** On-board test phase
      - **(a)** The systems integrator shall specify in the Ship cyber resilience test procedure and demonstrate to this Society the network monitoring and protection mechanisms in the CBSs.
      - **(b)** The above tests may be omitted if performed during the certification of CBSs as per **202. 2** (2).
      - **(c)** Any Intrusion detection systems in the CBSs in scope of applicability to be implemented shall be subject to verification by this Society. Relevant documentation shall be submitted for approval, and survey/tests shall be carried out on board.
  - **(5)** Classification Maintenance Survey
    - Reveal and recognize anomalous activity (403)
    - Inspection of security audit records (403. 1 (2))
    - Instructions or procedures to detect incidents (404. 1 (1))
    - **(A)** General
      - **(a)** For general requirements to surveys in the operation phase, see section 203.
      - **(b)** The shipowner shall in the Ship cyber security and resilience program describe the management activities to detect anomalies in the CBSs and networks, addressing at least the following requirements in this Chapter:
      - **(c)** The above activities may be addressed together with incident response in **404. 1**.
    - **(B)** First annual surveyThe shipowner shall present to this Society records or other documented evidence demonstrating implementation of the Ship cyber security and resilience program, i.e., that:
      - **(a)** The CBSs are routinely monitored for anomalies by inspection of security audit records and investigation of alerts in the CBSs.
    - **(C)** Subsequent annual surveysThe shipowner shall upon request by this Society demonstrate implementation of the Ship cyber security and resilience program by presenting records or other documented evidence as specified for the first annual survey.
    - **(D)** Special surveySubject to modifications of the CBSs, the shipowner shall demonstrate to this Society the activities in **403. 1** (4) (C) as per the Ship cyber resilience test procedure.
- **2.** **Verification and diagnostic functions of CBS and networks**
  - **(1)** RequirementCBSs and networks in the scope of applicability of this Chapter shall be capable to check performance and functionality of security functions required by this Chapter. Diagnostic functions shall provide adequate information on CBSs integrity and status for the use of the intended user and means for maintaining their functionality for a safe operation of the ship.
  - **(2)** Requirement detailsCBSs and networks diagnostics functionality shall be available to verify the intended operation of all required security functions during test and maintenance phases of the ship.
  - **(3)** Rationale
    The ability to verify intended operation of the security functions is important to support management of Cyber Resilience in the lifetime of the ship. Tools for diagnostic functions may comprise automatic or manual functions such as self-diagnostics capabilities of each device, or tools for network monitoring (such as ping, traceroute, ipconfig, netstat, nslookup, Wireshark, nmap, etc.). It should be noted however that execution of diagnostic functions may sometimes impact the operational performance of the CBS.
  - **(4)** Classification Survey
    - **(A)** Design phase: no requirements.
    - **(B)** Construction phase: no requirements.
    - **(C)** On-board test phase
      - **(a)** The systems integrator shall submit Ship cyber resilience test procedure (refer to 202. 2 (2) and demonstrate to this Society the effectiveness of the procedures for verification of security functions provided by the suppliers.
      - **(b)** The above tests may be omitted if performed during the certification of CBSs as per 202. 2 (2).
  - **(5)** Classification Maintenance Survey
    - Test and maintenance periods (403. 2 (2))
    - Periodic maintenance (203. 3)
    The security functions in the CBSs are periodically tested or verified.
    - **(A)** General
      - **(a)** For general requirements to surveys in the operation phase, see 203.
      - **(b)** The shipowner shall in the Ship cyber security and resilience program describe the management activities to verify correct operation of the security functions in the CBSs and networks, addressing at least the following requirements in this Chapter:
    - **(B)** First annual surveyThe shipowner shall present to this Society records or other documented evidence demonstrating implementation of the Ship cyber security and resilience program, i.e., that:
    - **(C)** Subsequent annual surveysThe shipowner shall upon request by this Society demonstrate implementation of the Ship cyber security and resilience program by presenting records or other documented evidence as specified for the first annual survey.

#### 404. Respond

- **1.** **Incident response plan**
  - **(1)** RequirementAn incident response plan shall be developed by the shipowner covering relevant contingencies and specifying how to react to cyber security incidents. The Incident response plan shall contain documentation of a predetermined set of instructions or procedures to detect, respond to, and limit consequences of incidents against CBSs.
  - **(2)** Requirement details
    - **(A)** The various stakeholders involved in the design and construction phases of the ship shall provide information to the shipowner for the preparation of the Incident Response Plan to be placed onboard at the first annual Survey. The Incident Response Plan shall be kept up-to-date (e.g. upon maintenance) during the operational life of the ship.
    - **(B)** The Incident response plan shall provide procedures to respond to detected cyber incidents on networks by notifying the proper authority, reporting needed evidence of the incidents and taking timely corrective actions, to limit the cyber incident impact to the network segment of origin.
    - **(C)** The incident response plan shall, as a minimum, include the following information:
      - **(a)** Breakpoints for the isolation of compromised systems;
      - **(b)** A description of alarms and indicators signalling detected ongoing cyber events or abnormal symptoms caused by cyber events;
      - **(c)** A description of expected major consequences related to cyber incidents;
      - **(d)** Response options, prioritizing those which do not rely on either shut down or transfer to independent or loc1al control, if any.
      - **(e)** Independent and local control information for operating independently from the system that failed due to the cyber incident, as applicable;
    - **(D)** The Incident response plan shall be kept in hard copy in the event of complete loss of electronic devices enabling access to it.
  - **(3)** Rationale
    An incident response plan is an instrument aimed to help responsible persons respond to cyber incidents. As such, the Incident response plan is as effective as it is simple and carefully designed. When developing the Incident response plan, it is important to understand the significance of any cyber incident and prioritize response actions accordingly.
    Means for maintaining as much as possible the functionality and a level of service for a safe operation of the ship, e.g. transfer active execution to a standby redundant unit, should also be indicated. Designated personnel ashore should be integrated with the ship in the event of a cyber incident.
  - **(4)** Classification Survey
    References to information provided by the suppliers (see **Ch 3, 301. 8**) that may be applied by the shipowner to establish plans for incident response.
    - **(A)** Design phaseThe systems integrator shall include the following information in the Cyber security design description:
    - **(B)** Construction phase: no requirements.
    - **(C)** On-board test phase: no requirements.
  - **(5)** Classification Maintenance Survey
    Description of who, when and how to respond to cyber incidents in accordance with requirements of **404. 1**.
    Procedures or instructions for local/manual control in accordance with requirements in **404. 2**.
    Procedures or instructions for isolation of security zones in accordance with requirements in **404. 3**.
    Description of expected behaviour of the CBSs in the event of cyber incidents in accordance with requirements in **404. 4**.
    - **(A)** General
      - **(a)** For general requirements to surveys in the operation phase, see **203**.
      - **(b)** The shipowner shall in the Ship cyber security and resilience program describe incident response plans. The plans shall cover the CBSs in scope of applicability of this Chapter and shall address at least the following requirements in this Chapter:
    - **(B)** First annual surveyThe shipowner shall present to this Society records or other documented evidence demonstrating implementation of the Ship cyber security and resilience program, i.e., that:
      - **(a)** The incident response plans are available for the responsible personnel onboard.
      - **(b)** Procedures or instructions for local/manual controls are available for responsible personnel onboard.
      - **(c)** Procedures or instructions for disconnection/isolation of security zones are available for responsible personnel onboard.
      - **(d)** Any cyber incidents have been responded to in accordance with the incident response plans.
    - **(C)** Subsequent annual surveysThe shipowner shall upon request by this Society demonstrate implementation of the Ship cyber security and resilience program by presenting records or other documented evidence as specified for the first annual survey.
- **2.** **Local, independent and/or manual operation**
  - **(1)** RequirementAny CBS needed for local backup control as required by **Pt 6, Ch, 2, 201. 4** of the Class Rules shall be independent of the primary control system. This includes also necessary Human Machine Interface (HMI) for effective local operation.
  - **(2)** Requirement details
    - **(A)** The CBS for local control and monitoring shall be self-contained and not depend on communication with other CBS for its intended operation.
    - **(B)** If communication to the remote control system or other CBS’s is arranged by networks, segmentation and protection safeguards as described in **402. 1** and **402. 2** shall be implemented. This implies that the local control and monitoring system shall be considered a separate security zone. Notwithstanding the above, special considerations can be given to CBSs with different concepts on case by case basis.
    - **(C)** The CBS for local control and monitoring shall otherwise comply with requirements in this Chapter.
  - **(3)** RationaleIndependent local controls of machinery and equipment needed to maintain safe operation is a fundamental principle for manned vessels. The objective of this requirement has traditionally been to ensure that personnel can cope with failures and other incidents by performing manual operations in close vicinity of the machinery. Since incidents caused by malicious cyber events should also be considered, this principle of independent local control is no less important.
  - **(4)** Classification Survey
    - **(A)** Design phaseThe systems integrator shall include the following information in the Cyber security design description:
      - **(a)** Description of how the local controls specified in **Pt 6, Ch, 2, 201. 4** of the Class Rules are protected from cyber incidents in any connected remote or automatic control systems.
    - **(B)** Construction phaseNo requirements.
    - **(C)** On-board test phase
      - **(a)** The systems integrator shall submit Ship cyber resilience test procedure (refer to 202. 2 (2)) and demonstrate to this Society that the required local controls in the scope of applicability of this Chapter needed for safety of the ship can be operated independently of any remote or automatic control systems.
      - **(b)** The tests shall be carried out by disconnecting all networks from the local control system to other systems/devices.
      - **(c)** The above tests may be omitted if performed during the certification of CBSs as per 202. 2 (2).
  - **(5)** Classification Maintenance SurveyFor general requirements to surveys in the operation phase, see **203**.
    - **(A)** Special surveySubject to modifications of the CBSs, the shipowner shall demonstrate to this Society the activities in **404. 2** (4) (C) as per the Ship cyber resilience test procedure.
- **3.** **Network isolation**
  - **(1)** RequirementIt shall be possible to terminate network-based communication to or from a security zone.
  - **(2)** Requirement details
    - **(A)** Where the Incident Response Plan indicates network isolation as an action to be done, it shall be possible to isolate security zones according to the indicated procedure, e.g. by operating a physical ON/OFF switch on the network device or similar actions such as disconnecting a cable to the router/firewall.
    - **(B)** There shall be available instructions and clear marking on the device that allows the personnel to isolate the network in an efficient manner.
    - **(C)** Individual system’s data dependencies that may affect function and correct operation, including safety, shall be identified, clearly showing where systems must have compensations for data or functional inputs if isolated during a contingency.
  - **(3)** RationaleIn the event that a security breach has occurred and is detected, it is likely that the incident response plan includes actions to prevent further propagation and effects of the incident. Such actions could be to isolate network segments and control systems supporting essential functions.
  - **(4)** Classification Survey
    - **(A)** Design phaseThe systems integrator shall include the following information in the Cyber security design description:
      - **(a)** specification of how to isolate each security zone from other zones or networks. The effects of such isolation shall also be described, demonstrating that the CBSs in a security zone do not rely on data transmitted by IP-networks from other zones or networks.
    - **(B)** Construction phase: no requirements.
    - **(C)** On-board test phase
      - **(a)** The systems integrator shall submit Ship cyber resilience test procedure (refer to 202. 2 (2)) and demonstrate to this Society by disconnecting all networks traversing security zone boundaries, that the CBSs in the security zone will maintain adequate operational functionality without network communication with other security zones or networks.
      - **(b)** The above tests may be omitted if performed during the certification of CBSs as per 202. 2 (2).
  - **(5)** Classification Maintenance SurveyFor general requirements to surveys in the operation phase, see 203.
    - **(A)** Special surveySubject to modifications of the CBSs, the shipowner shall demonstrate to this Society the activities in **404. 3** (4) (C) as per the Ship cyber resilience test procedure.
- **4.** **Fallback to a minimal risk condition**
  - **(1)** RequirementIn the event of a cyber incident impairing the ability of a CBS or network to provide its intended service, the affected system or network shall fall back to a minimal risk condition, i.e. bring itself in a stable, stopped condition to reduce the risk of possible safety issues.
  - **(2)** Requirement details
    - **(A)** As soon as a cyber incident affecting the CBS or network is detected, compromising the system’s ability to provide the intended service as required, the system shall fall back to a condition in which a reasonably safe state can be achieved. Fall-back actions may include:
      - **(a)** bringing the system to a complete stop or other safe state;
      - **(b)** disengaging the system;
      - **(c)** transferring control to another system or human operator;
      - **(d)** other compensating actions.
    - **(B)** Fall-back to minimum risk conditions shall occur in a time frame adequate to keep the ship in a safe condition.
    - **(C)** The ability of a system to fall back to a minimal risk condition shall be considered from the design phase by the supplier and the systems integrator.
  - **(3)** Rationale
    The ability of a CBS and integrated systems to fallback to one or more minimal risk conditions to be reached in case of unexpected or unmanageable failures or events is a safety measure aimed to keep the system in a consistent, known and safe state.
    Fallback to a minimal risk condition usually implies the capability of a system to abort the current operation and signal the need for assistance, and may be different depending on the environmental conditions, the voyage phase of the ship (e.g. port depart/arrival vs. open sea passage) and the events occurred.
  - **(4)** Classification Survey
    - **(A)** Design phaseThe systems integrator shall include the following information in the Cyber security design description:
      - **(a)** Specification of safe state for the control functions in the CBSs.
    - **(B)** Construction phase: no requirements.
    - **(C)** On-board test phase
      - **(a)** The systems integrator shall submit Ship cyber resilience test procedure (refer to 202. 2 (2)) and demonstrate to this Society that CBSs in the scope of applicability of this Chapter respond to cyber incidents in a safe manner (as per 404. 4 (4) (A)), e.g. by maintaining its outputs to essential services and allowing operators to carry out control and monitoring functions by alternative means.
      - **(b)** The tests shall at least include denial of service (DoS) attacks and may be done together with related test in 403. 1 (4) (C).
      - **(c)** The above tests may be omitted if performed during the certification of CBSs as per 202. 2 (2).
  - **(5)** Classification Maintenance SurveyFor general requirements to surveys in the operation phase, see **203**.
    - **(A)** Special surveySubject to modifications of the CBSs, the shipowner shall demonstrate to this Society the activities in **404. 4** (4) (C) as per the Ship cyber resilience test procedure.

#### 405. Recover

- **1.** **Recovery plan**
  - **(1)** RequirementA recovery plan shall be made by the shipowner to support restoring CBSs to an operational state after a disruption or failure caused by a cyber incident. Details of where assistance is available and by whom shall be part of the recovery plan.
  - **(2)** Requirement details
    - **(A)** The various stakeholders involved in the design and construction phases of the ship shall provide information to the shipowner for the preparation of the recovery plan to be placed on-board at the first annual Survey. The recovery plan shall be kept up-to-date (e.g. upon maintenance) during the operational life of the ship.
    - **(B)** Recovery plans shall be easily understandable by the crew and external personnel and include essential instructions and procedures to ensure the recovery of a failed system and how to get external assistance if the support from ashore is necessary. In addition, software recovery medium or tools essential for recovery on board shall be available.
    - **(C)** When developing recovery plans, the various systems and subsystems involved shall be specified. The following recovery objectives shall also be specified:
      - **(a)** System recovery: methods and procedures to recover communication capabilities shall be specified in terms of Recovery Time Objective (RTO). This is defined as the time required to recover the required communication links and processing capabilities.
      - **(b)** Data recovery: methods and procedures to recover data necessary to restore safe state of OT systems and safe ship operation shall be specified in terms of Recovery Point Objective (RPO). This is defined as the longest period of time for which an absence of data can be tolerated.
    - **(D)** Once the recovery objectives are defined, a list of potential cyber incidents shall be created, and the recovery procedure developed and described. Recovery plans shall include, or refer to the following information;
      - **(a)** Instructions and procedures for restoring the failed system without disrupting the operation from the redundant, independent or local operation.
      - **(b)** Processes and procedures for the backup and secure storage of information.
      - **(c)** Complete and up-to-date logical network diagram.
      - **(d)** The list of personnel responsible for restoring the failed system.
      - **(e)** Communication procedure and list of personnel to contact for external technical support including system support vendors, network administrators, etc.
      - **(f)** Current configuration information for all components.
    - **(E)** The operation and navigation of the ship shall be prioritized in the plan in order to help ensure the safety of onboard personnel.
    - **(F)** Recovery plans in hard copy onboard and ashore shall be available to personnel responsible for cyber security and who are tasked with assisting in cyber incidents.
  - **(3)** Rationale
    Incident response procedures are an essential part of system recovery. Responsible personnel should consider carefully and be aware of the implications of recovery actions (such as wiping of drives) and execute them carefully. It should be noted, however, that some recovery actions may result in the destruction of evidence that could provide valuable information on the causes of an incident.
    Where appropriate, external cyber incident response support should be obtained to assist in preservation of evidence whilst restoring operational capability.
  - **(4)** Classification Survey
    - **(A)** Design phaseThe systems integrator shall include the following information in the Cyber security design description:
      - **(a)** references to information provided by the suppliers (see **Ch 3, 301. 8**) that may be applied by the shipowner to establish plans to recover from cyber incidents.
    - **(B)** Construction phase: no requirements.
    - **(C)** On-board test phase
      - **(a)** The systems integrator shall submit Ship cyber resilience test procedure (refer to **202. 2** (2)) and demonstrate to this Society the effectiveness of the procedures and instructions provided by the suppliers to respond to cyber incidents as specified in **405. 2** and **405. 3**.
      - **(b)** The above tests may be omitted if performed during the certification of CBSs as per **202. 2** (2).
  - **(5)** Classification Maintenance Survey
    Description of who, when and how to restore and recover from cyber incidents in accordance with requirements in **405. 1**.
    Policy for backup addressing frequency, maintenance and testing of the backups, considering acceptable downtime, availability of alternative means for control, vendor support arrangements and criticality of the CBSs in accordance with requirements in **405. 2**.
    Reference to user manuals or procedures for backup, shutdown, reset, restore and restart of the CBSs in accordance with requirements in **405. 2** and **405. 3**.
    - **(A)** General
      - **(a)** For general requirements to surveys in the operation phase, see **203**.
      - **(b)** The shipowner shall in the Ship cyber security and resilience program describe incident recovery plans. The plans shall cover the CBSs in scope of applicability of this Chapter and shall address at least the following requirements in this Chapter:
    - **(B)** First annual surveyThe shipowner shall present to this Society records or other documented evidence demonstrating implementation of the Ship cyber security and resilience program, i.e., that:
      - **(a)** Instructions and/or procedures for incident recovery are available for the responsible personnel onboard.
      - **(b)** Equipment, tools, documentation, and/or necessary software and data needed for recovery is available for the responsible personnel onboard.
      - **(c)** Backup of the CBSs have been taken in accordance with the policies and procedures.
      - **(d)** Manuals and procedures for shutdown, reset, restore and restart are available for the responsible personnel on-board.
    - **(C)** Subsequent annual surveysThe shipowner shall upon request by this Society demonstrate implementation of the Ship cyber security and resilience program by presenting records or other documented evidence as specified for the first annual survey.
- **2.** **Backup and restore capability**
  - **(1)** RequirementCBSs and networks shall have the capability to support back-up and restore in a timely, complete and safe manner. Backups shall be regularly maintained and tested.
  - **(2)** Requirement details
    - **(A)** Restore capability
      - **(a)** CBSs shall have backup and restore capabilities to enable the ship to safely regain navigational and operational state after a cyber incident.
      - **(b)** Data shall be restorable from a secure copy or image.
      - **(c)** Information and backup facilities shall be sufficient to recover from a cyber incident.
    - **(B)** Backup
      - **(a)** CBSs and networks shall provide backup for data. The use of offline backups shall also be considered to improve tolerance against ransomware and worms affecting online backup appliances.
      - **(b)** Backup plans shall be developed, including scope, mode and frequency, storage medium and retention period.
  - **(3)** RationaleIn general, the purpose of a backup and restore strategy should protect against data loss and reconstruct the database after data loss. Typically, backup administration tasks include the following:
    - **(A)** Planning and testing responses to different kinds of failures;
    - **(B)** Configuring the database environment for backup and recovery;
    - **(C)** Setting up a backup schedule;
    - **(D)** Monitoring the backup and recovery environment;
    - **(E)** Creating a database copy for long-term storage;
    - **(F)** Moving data from one database or one host to another, etc.
  - **(4)** Classification Survey
    - **(A)** Design phase: no requirements.
    - **(B)** Construction phase: no requirements.
    - **(C)** On-board test phase
      - **(a)** The systems integrator shall submit Ship cyber resilience test procedure (refer to 202. 2 (2)) and demonstrate to this Society the procedures and instructions for backup and restore provided by the suppliers for CBSs in the scope of applicability of this Chapter.
      - **(b)** The above tests may be omitted if performed during the certification of CBSs as per 202. 2 (2).
  - **(5)** Classification Maintenance SurveyFor general requirements to surveys in the operation phase, see 203.
    - **(A)** Special surveySubject to modifications of the CBSs, the shipowner shall demonstrate to this Society the activities in **405. 2** (4) (C) as per the Ship cyber resilience test procedure.
- **3.** **Controlled shutdown, reset, roll-back and restart**
  - **(1)** Requirement
    - **(A)** CBS and networks shall be capable of controlled shutdown, reset to an initial state, roll-back to a safe state and restart from a power-off condition in such state, in order to allow fast and safe recovery from a possible impairment due to a cyber incident.
    - **(B)** Suitable documentation on how to execute the above-mentioned operations shall be available to on-board personnel.
  - **(2)** Requirement details
    - **(A)** CBS and networks shall be capable of:
      - **(a)** controlled shutdown allowing other connected systems to commit/rollback pending transactions, terminating processes, closing connections, etc. leaving the entire integrated system in a safe, consistent and known state.
      - **(b)** resetting themselves, instructing the system to go through the process of shutting down, clear memory and reset devices to their initialized state.
      - **(c)** rolling back to a previous configuration and/or state, to restore system integrity and consistency.
      - **(d)** restarting and reloading a fresh image of all the software and data (e.g. after a rollback operation) from a read-only source. Restart time shall be compatible with the system’s intended service and shall not bring other connected systems, or the integrated system it is part of, to an inconsistent or unsafe state.
    - **(B)** Documentation shall be available to onboard personnel on how to execute the above-mentioned operations in case of a system affected by a cyber incident.
  - **(3)** Rationale
    Controlled shutdown consists in turning a CBS or network off by software function allowing other connected systems to commit/rollback pending transactions, terminating processes, closing connections, etc. leaving the entire integrated system in a safe and known state. Controlled shutdown is opposed to hard shutdown, which occurs for example when the computer is forcibly shut down by interruption of power.
    While in the case of some cyber incidents hard shutdowns may be considered as a safety precaution, controlled shutdown is preferable in case of integrated systems to keep them in a consistent and known state with predictable behaviour. When standard shutdown procedures are not done, data or program and operating system files corruption may occur. In case of OT systems, the result of corruption can be instability, incorrect functioning or failure to provide the intended service.
    The reset operation would typically kick off a soft boot, instructing the system to go through the process of shutting down, clear memory and reset devices to their initialized state. Depending on system considered, the reset operation might have different effects.
    Rollback is an operation which returns the system to some previous state. Rollbacks are important for data and system integrity, because they mean that the system data and programs can be restored to a clean copy even after erroneous operations are performed. They are crucial for recovering from crashes ad cyber incidents, restoring the system to a consistent state.
    Restarting a system and reloading a fresh image of all the software and data (e.g. after a rollback operation) from a read-only source appears to be an effective approach to recover from unexpected faults or cyber incidents. Restart operations should be however controlled in particular for integrated systems, where unexpected restart of a single component can result in inconsistent system state or unpredictable behaviour.
  - **(4)** Classification Survey
    - **(A)** Design phaseThe systems integrator shall include the following information in the Cyber security design description:
      - **(a)** references to product manuals or procedures describing how to safely shut down, reset, restore and restart the CBSs.
    - **(B)** Construction phase: No requirements.
    - **(C)** On-board test phase
      - **(a)** The systems integrator shall submit Ship cyber resilience test procedure (refer to 202. 2 (2)) and demonstrate to this Society that manuals or procedures are established for shutdown, reset and restore of the CBSs. These manuals/procedures shall be provided to the shipowner.
      - **(b)** The above tests may be omitted if performed during the certification of CBSs as per 202. 2 (2).
  - **(5)** Classification Maintenance SurveyFor general requirements to surveys in the operation phase, see 203.
    - **(A)** Special surveySubject to modifications of the CBSs, the shipowner shall demonstrate to this Society the activities in **405. 3** (4) (C) as per the Ship cyber resilience test procedure. ![](images/image3.png)
