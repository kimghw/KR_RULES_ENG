# Guidance for Autonomous Ships

> OTHER RULES AND GUIDANCE / GC-28-E / 2025 / EN / Guidance

## CHAPTER 1 GENERAL

### Section 1 General

#### 101. Background

- **1.** Due to the development of various digital technologies and automation technologies, research and development on autonomous navigation technology that can recognize the surrounding situation and autonomously operate, logic system to make decisions, integrated sensor system, data communication function etc. are being conducted all over the world.
- **2.** Considering the current status of the maritime industry and related information and communication technology development, autonomous operation can improve the safety and reliability of the maritime industry and enable efficient and economical operation of the ship.
- **3.** While the maritime industry is becoming increasingly digitalized and automated due to development of information and communication technologies, the need to prevent or mitigate risks is also being identified by identifying new hazards as a result in advance.

#### 102. Purpose

- **1.** The purpose of this guidance is to ensure the safety and reliability of autonomous ships or systems and functions necessary for autonomous operation. *(2021)*

#### 103. Application

- **1.** This Guidance applies to the ships classed with or intended to be registered under the Society by applying for the class notation for the level of autonomy. *(2024)*
- **2.** If an autonomous navigation system of AL3 or higher, which can directly affect the safety of the ship, is permanently installed, an additional notation shall be assigned. *(2024)*
- **3.** This guidance provides key recommendations on the design or operation of systems that can be used to enhance ship autonomy at sea.
- **4.** This guidance apply to autonomous ships on the surface of the water, not unmanned underwater vehicle.
- **5.** The configuration of the autonomous system presented in this guidance can be changed according to the purpose of operation.
- **6.** In applying this guidance, it is based on the satisfaction of all international conventions, national laws and domestic law of ports applicable to the ship, regardless of autonomous level.
- **7.** Items not specified in this Guidance are to be in accordance with each relevant requirement of **Rules for the Classification of Steel Ships**.
- **8.** Autonomous ships applying this guidance may conduct risk assessments or review reliability of autonomous ships or systems if the Society deems necessary. *(2021)*
- **9.** Autonomous ships applying this guidance are to obtain cybersecurity certification appropriate for the ship. Equipment and systems that are additionally installed for the operation of autonomous ships shall be subject to type approval in accordance with Ch 3, Sec 23 of the Guidance for Approval of Manufacturing Process and Type Approval, etc. *(2023)*
- **10.** Items not included in this Guidance may comply with ISO, IEC, KS or equivalent recognized standards by the appropriate consideration of the Society.

#### 104. Definitions

The definitions of terms are to follow **Rules for the Classification of Steel Ships**, unless otherwise specified in this Guidance.

- **1.** **"Autonomous Ships"** means ships that supports decision-making through the autonomous system and can be substituted by the system in whole or in part for the control and management of the ship. Autonomous ships can be operated manned, unmanned or remotely operated. *(2021)*
- **2.** **"Operator"** means a person engaged in the control and management of ships onboard or offshore.
- **3.** **"Data Acquisition and Analysis systems"** means a system for recognizing the external conditions of ships related to marine objects/ships and marine environment and the internal conditions related to ship operation/movement.
- **4.** **"Autonomous Navigation Systems"** means a system that establishes a route plan and a steering plan for economical navigation and prevention of collision/grounding considering the internal and external conditions and controls the propulsion device and steering device of the ship in accordance with the established route plan and steering plan.
- **5.** **"Communication Systems"** means systems involved in communication between information objects.
- **6.** **"Outboard Support Systems"** means a systems that monitors and controls the operational information of an autonomous ship.
- **7.** **"Decision-making Support Systems"** means systems that can support decision-making of ship operators, and these systems can be composed of a combination of various systems. *(2021)*
- **8.** **"Cyber security"** means activities or process, capability, etc. to assure confidentiality, integrity and applicability of the organization’s assets and information contained in the assets.
- **9.** **"Confidentiality"** means the property that information is not disclosed to system entities (users, processes, devices) unless they have been authorized to access the information.
- **10.** **"Integrity"** means the property whereby an entity has not been modified in an unauthorized manner.
- **11.** **"Availability"** means the property of being accessible and useable upon demand by an authorized entity.

#### 105. Level of autonomy (2021)

- **1.** The level of autonomy is determined by the degree to which the system of off-board remote operation replaces the onboard operator for the following functions. Table 1 shows the level of autonomy by these functions.
  - **(1)** Data acquisition/analysis
  - **(2)** Decision-making
  - **(3)** Action

    | Level of autonomy | Data acquisition/analysis | Decision-making | Action |
    | --- | --- | --- | --- |
    | AL 1 | System and/or Operator | Operator | Operator |
    | AL 2 | System/Remote | Operator<br>(System/Remote)<sup>(1)</sup> | Operator |
    | AL 3 | System/Remote | System/Remote<br>(Operator)<sup>(2)</sup> | System<br>/Remote |
    | AL 4 | System | System<sup>(3)</sup> | System<sup>(3)</sup> |
    | AL 5 | System | System | System |
    | (Notes)<br>(1) The operator's decision-making is supported through system or remote operation, but the onboard operator makes the final decision. *(2021)*<br>(2) Operator confirmation of decision-making is required.<br>(3) Operators are constantly monitored for decision-making and action. |   |   |   |
- **2.** Each autonomy level can be defined as follows:
  - **(1)** AL 1: Data acquisition/analysis can be performed by the operator and the system, but decision-making and action based on the collected information are performed by the operator.
  - **(2)** AL 2: Data is collected/analyzed through system or off-board remote operation and decision-making and action are performed by the operator. The system supports operator’s decision-making. The operator's decision-making is supported through system or off-board remote operation.
  - **(3)** AL 3: Data acquisition/analysis, decision-making and action are performed through system or off-board remote operation. However, the operator's confirmation of the decision-making by the system is required, and if the operator confirmation is not preceded, the decision-making is withdrawn. In case of system failure or remote operation is not working well, an operator's response is required.
  - **(4)** AL 4: Data acquisition/analysis, decision-making and action are performed by the system. The operator always monitors the information about the decision-making and action by the system. System responses to abnormal operating scenarios (system failures, etc.) are possible.
  - **(5)** AL 5: As a complete autonomous level, all functions such as data acquisition/analysis, decision-making and action are performed by the system and the operator monitors the emergency situation. System responses to abnormal operating scenarios (system failures, etc.) are possible.

#### 106. Class notations

- **1.** The scope and autonomy level of this Guidance for autonomous ships is basically made at the request of the owner, but may be finally determined through a risk assessment. *(2021)*
- **2.** Autonomous ships to which this Guidance applies may be assigned notation at autonomy level of **105**, depending on the application of the autonomous system specified in **Ch 2**, **103**. **1** to **5**. For example, a ship with an autonomous systems as defined in **Ch 2**, **103**. **1** may be assigned "AL1".
- **3.** Notwithstanding the above 2, in case of request from the shipowner, shipyard, etc., an appropriate level of AL can be assigned to a specific individual system and special features can be specified. Example: AL level (special feature) *(2021)*

#### 107. Equivalency

The equivalence of alternative and novel features which deviate from or are not directly applicable to the Guidance is to be in accordance with **Pt 1**, **Ch 1**, **105**. of **Rules for the Classification of Steel Ships**. *(2020)*

#### 108. Modification of requirements

Since autonomous ships technologies are under development, the requirements of this Guidance may need to be supported by additional information and requirements, on a case by case basis. Designs that are not in compliance with this Guidance may be approved after evaluation by the Society, provided that it can be demonstrated that the design represents an equal or better level of safety. For ships with special limitations for their service or purpose, the requirements in this Guidance may be modified within an extent considered appropriate by this Society. *(2023)*


### Section 2 Operation Plan

#### 201. General

- **1.** The developer shall submit an operation plan for the ship.
- **2.** The operation plan documents the owner’s intention to operate the autonomous ship and the operational requirements for it, and shall specify at least the following information according to the purpose and function of the autonomous ship.
  - **(1)** Operational information
    - **(A)** Purpose of operation
    - **(B)** Operation scope: Operating sea, sea conditions, conditions required for safe operation of the ship and the shipboard system (eg, communication network performance requirements and data quality requirements for communication systems)
  - **(2)** System information
    - **(A)** Level of autonomy
    - **(B)** Modularization and configuration details
  - **(3)** Hazard information
    - **(A)** Operation scenario (normal/abnormal)
    - **(B)** Hazards and mitigation measures
- **3.** The operation plan shall specify the operation scope to ensure safe operation of the system or ship.
- **4.** The system or ship shall operate only within the its operation scope. The ship shall be equipped with a device to check for deviations from all specified operation scopes and shall be recorded at all times during operation. Records shall be available at any time and shall be considered outside the specified operation scope if the recorded contents can not be verified.
- **5.** The operation plan shall specify the possible hazards and their mitigation measures in the operational scenarios. Even if the system or ship is operated within the specified operation scope, if there is a situation that harms the safety of the ship due to risks not presented in the operation plan, the responsibility lies with the developers who have not reviewed the expected risk situations in the operational environment and have not prepared mitigation measures for them.


### Section 3 Cyber security

#### 301. General

- **1.** The development of automated technologies based on information and communication technologies and the development of autonomous technologies are also increasing the cyber risk on the network. Especially for autonomous ships, such risks are further increased.
- **2.** Systems and ships for autonomous navigation are required to prevent and detect such cyber threats in advance and to provide cyber security technologies to respond to cyber attacks. Therefore, on-board systems of autonomous ship shall be certified and maintained for cybersecurity in order to demonstrate the availability, confidentiality and integrity of the system.
- **3.** The regulations related to cyber security shall be in accordance with the respective requirements of the **Guidance for Maritime Cyber Security System**. Additional considerations and requirements may be required if there are separate requirements in accordance with international regulations, such as IMO, in addition to the requirements of the **Guidance for Maritime Cyber Security System**, or where the Society is deemed necessary by the development of information technology and operational technologies.

#### 302. Application

- **1.** If a communication network is established between the ship and the off-board support system, it shall be protected from unauthorized attack and data access.
- **2.** A cybersecurity control system shall be in place to mitigate the risks of unauthorized attack and data access during the design, manufacture and installation of the ship system.
- **3.** System security performance shall consider both normal and abnormal operating scenarios and shall consider the impact of system security failures on safety functions.
- **4.** The applicable system security procedures shall mitigate the cyber security-related risks that may arise during the design, procurement, production, installation and commissioning of the system and at least take into account the following:
  - **(1)** Risk management
  - **(2)** Access control
  - **(3)** Physical security
  - **(4)** Incident response and recovery
  - **(5)** Outside parties’ security
  - **(6)** Data security
  - **(7)** Log management
  - **(8)** Software development and testing
  - **(9)** System management
  - **(10)** Patch management
  - **(11)** Encryption
  - **(12)** Malicious code response
  - **(13)** Network management ![](images/image3.png)
