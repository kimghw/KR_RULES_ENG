# GUIDANCE FOR MARITIME CYBER SECURITY SYSTEM

> OTHER RULES AND GUIDANCE / GC-24-E / 2025 / EN / Guidance

## CHAPTER 4 REQUIREMENTS FOR CS SYSTEM OF THE SHIP

### Section 1 General

#### 101. General

- **1.** This chapter defines the requirements and organization procedures of information technology and operation technology for cyber security system of the ship.
- **2.** This chapter describes the essential requirements related to cyber security within the organization's information technology and operation technology areas for compliance with cyber security system and specifies the competencies of the members within the organization.


### Section 2 CS Ready

#### 201. Risk management

- **1.** External environmental factors affecting the environments of information technology and operation technology in ships should be identified and cataloged as threats.
- **2.** Risk management plans including risk assessment methods and procedures should be established to manage cyber security risks.
- **3.** The ship should diagnose the vulnerability of its assets related to cyber security.
- **4.** Risk assessment should be carried out linking the threat identification and vulnerability diagnosis results to all assets related to cyber security.
- **5.** Priorities for risk level should be determined according to risk assessment and improvement actions should be taken.

#### 202. Asset management

All assets to be protected, such as systems, facilities, data, etc. should be established and classified.

#### 203. Access Control

- **1.** Users who can connect to the system should be given minimum privileges and listed and managed.
  - **(1)** The system should provide the capabilities to authenticate users.
  - **(2)** The privileges of the general user and the administrator should be differentiated and the authority standard for each task should be defined.
  - **(3)** The system should provide the capability to support the management of all privileges by authorized users, including adding, modifying and removing privileges.
- **2.** A security function should be established to clarify the responsibility for each user account(ID) and to maintain the confidentiality.
  - **(1)** The system should provide the capability to enforce configurable password strength based on minimum length and variety of character types.
  - **(2)** The system should provide the capability to obscure feedback of authentication information during the authentication process.
  - **(3)** The system should provide the capability to enforce a limit of a configurable number of consecutive invalid access attempts.
  - **(4)** The system should provide the capability to display a system use notification message before authenticating.
  - **(5)** The system may provide the capability to employ multi-factor authentication depending on importance of the system.
- **3.** Access record of users to the system should be retained for at least six months and reviewed periodically.

#### 204. Physical Security

- **1.** If a device such as CCTV is installed to monitor the protected area, it is necessary to classify the users through the authentication means and block the connection of unauthorized persons.
- **2.** The main system should manage the authority of the person who has physical and logical access separately and control the access of the unauthorized person.
- **3.** Equipment essential for major system operation such as communication lines should be protected from physical attack and periodic inspection should be carried out.
- **4.** The ship should control its internal assets and network connections through portable storage media such as USB by using the methods like physical port locking and unused port inactivation.
- **5.** External devices accessing the system (portable storage media, smart phones, etc.) should be prevented and controlled from automatic execution.

#### 205. Incident response and recovery

- **1.** The operating system in the ship should have an emergency operation function so that it can be operated even in case of an emergency.
  - **(1)** The emergency power supply system, etc. should always be operable for system operation.
  - **(2)** The system should provide the capabilities to recover to a secure state after disruption or failure.
- **2.** In case of an incident, relevant functions should be provided and the incident response and recovery manual for should be documented so that the system can be operated safely and continuously.

#### 206. Data Security

- **1.** Data should be limited in user access according to its importance, and physical and logical access control should be performed.
- **2.** An environment in which data can be communicated in an encrypted manner should be established.
- **3.** Encryption standards for data protection should be established and planned.
- **4.** Data classified as important should be encrypted and stored.

#### 207. Log Management

- **1.** Categorizing the system-specific logs by type, the necessary logs should be stored securely for a certain period of time.
- **2.** When storing logs, it should be confirmed whether or not the log data integrity is maintained.
- **3.** The system in which the logs are stored should be physically and logically controlled to prevent unauthorized access.
- **4.** Software and hardware operated in the ship should be synchronized at the same time.
- **5.** Monitoring should be performed to prevent the excess of system performance and capacity, and in the event of a failure, prompt action should be taken.

#### 208. System Management

- **1.** It should be ensured whether unauthorized interfaces, ports, or services exist in the system.
- **2.** When transferring file information in the operating system, it is necessary to confirm whether information provision standard is defined and applied.
- **3.** When introducing cyber security assets, the default value should be newly set or changed according to the security policy or change management standard of the ship, and the use of the assets should be prohibited before the security setting is changed.
- **4.** Before changing the system, the relevant data should be backed up in case of system failure.
- **5.** All software accessing cyber security assets should be configured not to run automatically.
- **6.** Change management records for hardware and software should be kept and managed.
- **7.** The system should provide the capability to create audit log.
  - **(1)** The system should allocate sufficient audit record storage.
  - **(2)** The system should protect audit information from unauthorized access, modification and deletion.
  - **(3)** The system should provide the capability for authorized users to access audit logs on a read-only basis.

#### 209. Patch Management

- **1.** The ship should select the patch priority in the system patch, execute the patch through the approved procedure, and list the known vulnerabilities and obstacles before the patch.
- **2.** If the automatic patching tool is not available or if the system is incompatible, the system should be managed separately.
- **3.** Patch versions for each system should be recorded and managed.

#### 210. Malicious Code Response

Controls to protect networks, information systems, operating systems, and terminals from malicious code should be provided.

#### 211. Network Management

- **1.** Vulnerabilities of network equipment should be periodically checked so that it does not affect other networks due to communication channel flaws.
- **2.** To protect the internal network, an intrusion prevention system should be installed and operated to block external unauthorized access, and should be managed continuously.
- **3.** The wireless network environment should be configured separately from the wireless network that can be accessed by outside parties.
- **4.** The operating system should be restricted from being accessed through the wireless network.
- **5.** The internal and external communication interfaces of the systems should be controlled to limit the connection. Connection limitation devices include proxies, gateways, routers, firewall, unidirectional gateways and VPN.
- **6.** The networks of IT systems and OT systems should be operated separately.
- **7.** When connecting to a system via an external network, a secure connection method using an enhanced authentication technique should be applied.
- **8.** It should have a graphical network flow that can identify the network path.
- **9.** When building network related equipment, it is necessary to remove the default value and activate the security related function, which may be requested by the supplier if necessary.
- **10.** When establishing a communication line, the communication path, connection priority, and protocol should be defined in advance to minimize the defect, and the service level agreement, etc. should be included in the supplier contract.

#### 212. Software Quality Management

- **1.** It is the responsibility of the ship builders to manage software quality and the achievement of this responsibility should be supported by system integrators updating the software registry. The software registry should contain:
  - **(1)** List and versions of software installed in cyber security systems
  - **(2)** Results of security audit
- **2.** Software quality system should include the following materials as a minimum:
  - **(1)** Having a specific procedure for verification of software code at the level of systems, sub-systems and programmable devices and modules
  - **(2)** Having schedules including required submittal of documentation, a test event, a technical design review meeting, etc.
  - **(3)** Having a specific procedure for software modification and installation on board the ship defining interactions with stakeholder

#### 213. Cyber security Test

- **1.** Cyber security test such as FAT, SAT, etc. should confirm whether security functions of the system are properly implemented. These security functions should include all items necessary to the requirement specified in this Guidance.
- **2.** It should be verified through vulnerability diagnosis and/or penetration tests whether security functions reflecting the cyber risk assessment are properly implemented


### Section 3 Ship Cyber Security Compliance 0 or CS0 (2022)

#### 301. Case review

The ship should share with the crews without delay any information on changes in external environmental factors such as cyber security threats and cases.

#### 302. Security policy

- **1.** The ship should have, review and manage a cyber security policy that specifies the operational methods, procedures and responsibilities for security operations.
- **2.** The ship should designate and assign responsibility and authority to the personnel who have competencies related to security activities.

#### 303. Security training

- **1.** The personnel involved in security activities should conduct security training at least once a year in accordance with the security training plan.

#### 304. Risk management

- **1.** External environmental factors affecting the environments of internal information technology and operational technology should be identified and cataloged as threats.
- **2.** Risk management plans including risk assessment methods and procedures should be established to manage cyber security risks.
- **3.** Risk assessment should be periodically carried out by linking the threat identification and vulnerability diagnosis results to assets related to cyber security.

#### 305. Asset management

- **1.** All assets to be protected, such as systems, facilities, data, etc. should be established and classified.
- **2.** The ship should designate the person responsible for each asset, such as the equipment and facilities requiring security, and define the role.

#### 306. Physical Security

- **1.** The ship should establish policies that define the physical security standards for system equipment, facilities, and so on.
- **2.** The ship should provide physical controls to access protected areas containing assets only to authorized persons.
- **3.** The ship should control its internal assets and network connections through portable storage media such as USB.
- **4.** Clean desk operation and terminal screen protection policy of the area where documents and portable storage media are stored should be prepared and applied.

#### 307. Incident Response and Recovery

- **1.** The ship should establish cyber incident response and recovery policy, including the types of cyber incidents and their corresponding methods and procedures.
- **2.** The ship should define the roles and responsibilities of the organization or persons responsible for immediate response and recovery activities to system operation and security issues. In addition, an emergency communication system should be established to enable rapid communication with internal and external stakeholder, and the emergency communication network should be updated and managed.
- **3.** In case of an incident, relevant functions should be provided and the manual should be documented so that the main system can be operated safely and continuously.

#### 308. Outside Parties’ Security

- **1.** The ship should establish a security policy for cyber security equipment and data of outside parties in order to prepare for security incidents by the outside parties.

#### 309. System Management

- **1.** Before changing the system, the relevant data should be backed up in case of system failure.
- **2.** Change management procedures should be established and records of implementation shall be maintained.

#### 310. Patch Management

- **1.** The ship should establish a policy to apply the patch to the main system and perform the security patch according to the approved policy.
- **2.** Patch versions for each system should be recorded and managed.

#### 311. Mobile Security

- **1.** The ship should establish security policies to control the use of corporate mobile devices and crew owned mobile devices.

#### 312. Malicious code response

Malicious code control measures should be prepared to protect major systems. When software is installed, it should be updated periodically.

#### 313. Network Management

- **1.** When connecting to a system via an external network, a secure connection method using an enhanced authentication technique should be applied.
- **2.** It should have a graphical network flow that can identify the network path.

#### 314. Cyber security internal audit

- **1.** Cyber security internal audit procedure should be established and conducted periodically.
- **2.** The ship should periodically inspect and conduct security surveys while outsourcers perform business.


### Section 4 Ship Cyber Security Compliance 1 or CS1 (2022)

#### 401. Security training

- **1.** The ship should provide specialized training on security technologies to the personnel operating information technology and operation technology.

#### 402. Risk management

- **1.** The ship should periodically diagnose the vulnerability of its assets related to cyber security.
- **2.** Priorities for risk level should be determined according to risk assessment and improvement actions should be taken.
- **3.** The results of the risk assessment should be shared with stakeholder and be able to support improvement actions.

#### 403. Asset management

- **1.** Standards should be established for reusing all hardware assets, and countermeasures should be taken to ensure safe destruction if not reused.

#### 404. Access Control

- **1.** Access control policies should be established, including standards, principles, and procedures for operating system access rights.
- **2.** Users who can connect to the system should be given minimum privileges and listed and managed.
- **3.** The privileges of the general user and the administrator should be differentiated and the authority standard for each task should be defined.
- **4.** Access rights of users should be managed in a formal procedure according to the access control policy.
- **5.** A security function should be established to clarify the responsibility for each user account(ID) and to maintain the confidentiality.
- **6.** Private use of the Internet should be restricted to prevent unauthorized attack and data access through the use of personal e-mail, illegal site access.

#### 405. Physical Security

- **1.** The ship should monitor and track illegal intrusions when working on key assets in the protected area.
- **2.** If a device such as CCTV is installed to monitor the protected area, access control by unauthorized persons shall be implemented.
- **3.** The main system should manage the authority of the person who has physical and logical access separately and control the access of the unauthorized person.
- **4.** The ship should ensure that at least the same physical security as the existing system is applied when installing the new system.
- **5.** The ship should provide protective measures to prevent information leakage by theft or loss of portable equipment such as notebook computers.

#### 406. Incident Response and Recovery

- **1.** System design should reflect security requirements against operational failures.

#### 407. Outside Parties’ Security

- **1.** The ship should follow the approval procedure by the person in charge if the outside party should be granted the right to access the system.
- **2.** The outside parties should use the system in compliance with ship security requirements and perform the security function check before connecting the equipment owned by the outside parties to the system.

#### 408. Data Security

- **1.** For data stored in the ship or transmitted outside, the importance classification and management standards should be established in consideration of the impact in case of leakage or damage.
- **2.** Important data should be backed up in a separate space and stored securely.
- **3.** Data should be limited in user access according to its importance, and physical and logical access control should be performed.
- **4.** Data transmitted or stored should establish encryption application standards according to importance.
- **5.** Data classified as important should be encrypted and stored if necessary.

#### 409. Log Management

- **1.** Categorizing the system-specific logs by type, the necessary logs should be stored securely for a certain period of time.
- **2.** The system in which the logs are stored should be protected to prevent unauthorized access.

#### 410. System Management

- **1.** When introducing assets related to cyber security, the default value should be newly set or changed according to the security policy or change management standard of the ship, and the use of the assets should be prohibited before the security setting is changed.
- **2.** Before changing the system, the relevant data should be backed up in case of system failure.
- **3.** Installation of operating system software should be restricted by the security officer, and unauthorized software updates or update methods should not be applied
- **4.** All software accessing assets related to cyber security should be configured not to run automatically.

#### 411. Network Management

- **1.** To protect the internal network, an intrusion prevention system(firewall, etc.) should be installed and operated to block external unauthorized access, and should be managed continuously.
- **2.** The wireless network environment should be configured separately from the wireless network that can be accessed by outside parties.
- **3.** The operating system should be restricted from being accessed through the wireless network. If unavoidable, a secure connection method through enhanced authentication technology, etc. shall be applied.
- **4.** The ship internal and external communication interfaces of the information system or the operating system should be controlled to limit the connection.
- **5.** The networks of information systems and operating systems should be operated dividing it physically or logically.
- **6.** When building network related equipment, it is necessary to remove the default value and activate the security related function, which may be requested by the supplier if necessary.


### Section 5 Ship Cyber Security Compliance 2 or CS2

#### 501. Establishment of threat information collection system

The ship should review the change in external environment factors such as cyber security threats and cases and reflect them in the ship’s policy.

#### 502. Continuous management of security policy and manual

- **1.** The cyber security guidelines and manuals should be periodically reviewed to meet ship's policy and requirements of flag stats or IMO, etc. and the amendments should be recorded and managed.
- **2.** The ship should document the policies and guidelines taking into account the procedures and standards to be referenced.

#### 503. Special security training

The enhanced security training plans should be established in consideration of internal and external environment factors and change of the assets, etc.

#### 504. Abnormal signs detection

- **1.** The ship should periodically review whether changes in authority have been properly made in accordance with changes in the user's job.
- **2.** An intrusion detection function should be provided to detect unauthorized access or anomalies to the system.
- **3.** In case of a system with remote access, the safe functional requirements should be reflected and the function's safety should be checked periodically.
- **4.** Network access control technology should be applied to all communication methods including existing network, remote and wireless network.
- **5.** If the equipment with data is discarded, the stored data should be deleted in a non-reproducible manner.

#### 505. Physical control improvement in ships

- **1.** In case of CCTVs are installed in security areas in the ship, the performance of CCTVs should be periodically examined.
- **2.** In case of CCTVs are installed in security areas in the ship, their communication network should be separated from that of main system.

#### 506. Response capability enhancement against cyber security incident

- **1.** The ship should classify the types of incidents according to the importance of tasks or duties and types of threats, and establish and maintain incident response procedures for each type.
- **2.** The ship should identify and take action against known major system vulnerabilities to prevent incidents caused by external attacks.
- **3.** The ship should monitor the signs related to the incident and take preliminary action considering the internal influence.
- **4.** The information generated when investigating and responding to the incident should be recorded and reported to management including its impact and action plan.
- **5.** The ship should have personnel, equipment or technology for incident response and analysis.
- **6.** The ship should designate the personnel to carry out the analysis of the cyber security incident investigation and be familiar with the relevant contents.
- **7.** The ship should define the severity of the cyber security incident in advance and take countermeasures according to the severity.
- **8.** The ship should define the scope of the investigation analysis by analyzing the related assets according to the degree of damage in the analysis of the investigation of the cyber security incident.
- **9.** All log data within the scope of the cyber security incident analysis should be investigated.
- **10.** The ship should periodically conduct simulated training or penetration test to check security and establish relevant plans.
- **11.** The scopes of simulated training or penetration test should be defined not to affect the operational continuity of the operating system.
- **12.** Penetration tests should be carried out according to a preliminary plan and all possible resources should be used for testing.

#### 507. Mobile security management

For controlling mobile device usage, technical security should be applied through automated control tools and anti-virus program for mobile.

#### 508. Change management

- **1.** The ship should record the change management history of system and manage the unusual so that the problems are not repeated.
- **2.** Pre-test should be performed considering system impact, business impact, and expected failure prior to system patching.

#### 509. Business continuity enhancement

- **1.** The system operation manual should be periodically reviewed for internal policies and linkages and linked to the risk management process.
- **2.** The ship should establish a disaster recovery plan for a contingency in order to maintain business continuity.


### Section 6 Ship Cyber Security Compliance 3 or CS3

#### 601. Unification of security system

The ship should monitor changes in related laws, standards, technical guides, etc. and incorporate them into its policies.

#### 602. Security engineering

Training to periodically test security-related issues learned through training should be conducted.

#### 603. Business continuity assurance

- **1.** The ship should periodically check and, if necessary, update the system for supporting incident response.
- **2.** The ship should continuously review and improve the contingency plans taking into account changes in internal and external environmental factors and assets, etc.
- **3.** Security requirements of the system for recovery should be applied, and regularly inspected and took actions.
- **4.** Recovery capability should be tested and virtual simulation should be periodically conducted to verify recovery plan.
- **5.** Before penetration test, vulnerability should be eliminated through preliminary evaluation.
- **6.** The results of penetration test should be reviewed and the effectiveness of the ship security should be measured and reported.
- **7.** The ship should provide relevant policies, research facilities, and technical tools for the analysis of cyber security incidents.

#### 604. Real-time monitoring capability enhancement

- **1.** Network access control techniques should be used to monitor abnormal communications and implement restriction measures.
- **2.** The ship should monitor the various traffic to the network in real time and recognize and response the abnormal behavior in advance.
- **3.** A real-time monitoring and response system should be established and operated to prevent infection and spread by malicious code that exploits new vulnerabilities.

#### 605. Cyber security audit

- **1.** The ship should establish a policy to carry out cyber security audits by the company and cyber security specialized organization.
- **2.** The ship should periodically establish and conduct cyber security audit plans by the company and cyber security specialized organization.

#### 606. Encryption key management

Encryption key should be managed by a procedure and stored in separate place in accordance with access control policy. ![](images/image4.png)

|   |
| --- |
| **GUIDANCE FOR MARITIME CYBER SECURITY SYSTEM**<br>Published by<br>**KR**<br>36, Myeongji ocean city 9-ro, Gangseo-gu,<br>BUSAN, KOREA<br>TEL : +82 70 8799 7114<br>FAX : +82 70 8799 8999<br>Website : http://www.krs.co.kr |
| CopyrightⒸ 2024, **KR**<br>Reproduction of this Rules and Guidance in whole or inn parts is prohibited without permission of the publisher.<br>CopyrightⒸ 2024, **KR**<br>Reproduction of this Rules and Guidance in whole or inn parts is prohibited without permission of the publisher. |
| CopyrightⒸ 2024, **KR**<br>Reproduction of this Rules and Guidance in whole or inn parts is prohibited without permission of the publisher. |
