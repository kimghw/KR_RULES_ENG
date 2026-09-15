# Guidance for Conformity Certification of Maritime Equipment Cyber Security

> OTHER RULES AND GUIDANCE / GC-31-E / 2025 / EN / Guidance

## CHAPTER 3 ADDITIONAL REQUIREMENTS FOR EQUIPMENT CYBER SECURITY (2023)

### Section 1 General

#### 101. General

- **1.** The additional requirements for equipment cyber security are defined as shown in Table 3 based on the component requirements of IEC 62443-4-2.

  | Additional Requirement | Definition |
  | --- | --- |
  | Software Application | Software programs executing on the infrastructure that are used to interface with the process or the control system itself<br>For example, configuration software and historian, etc. |
  | Embedded Device | Special purpose device running embedded software designed to directly monitor, control or actuate an industrial process<br>For example, PLC, IED(Intelligent Electronic Device), etc. |
  | Host Device | General purpose device running a general purpose operating system capable of hosting one or more applications, data stores or functions<br>For example, Operation workstation, Data historian, etc. |
  | Network Device | Device that facilitates data flow between devices, or restricts the flow of data, but does not directly interact with a control process<br>For example, Switch, Router, VPN terminator, etc. |


### Section 2 Additional Requirements for Software Application

#### 201. Mobile code

- **1.** In the event that a software application utilizes mobile code technologies, that application should provide the capability to enforce a security policy for the usage of mobile code technologies. The security policy should allow, at a minimum, the following actions for each mobile code technology used on the software application:
  - **(1)** Control execution of mobile code
  - **(2)** Control which users (human, software process, or device) are allowed to transfer mobile code to/from the application
  - **(3)** Control the execution of mobile code based on the results of an integrity check prior to the code being executed
- **2.** The application should provide the capability to enforce a security policy that allows the device to control execution of mobile code based on the results of an authenticity check prior to the code being executed.
- **3.** **Requirements for SLs**
  - **(1)** SL 1 : **201. 1**
  - **(2)** SL 2 : **201. 2**
  - **(3)** SL 3 : **201. 2**
  - **(4)** SL 4 : **201. 2**

#### 202. Protection from malicious code

- **1.** The application product supplier should qualify and document which protection from malicious code mechanisms are compatible with the application and note any special configuration requirements.
- **2.** **Requirements for SLs**
  - **(1)** SL 1 : **202. 1**
  - **(2)** SL 2 : **202. 1**
  - **(3)** SL 3 : **202. 1**
  - **(4)** SL 4 : **202. 1**


### Section 3 Additional Requirements for Embedded Device

#### 301. Mobile code

- **1.** In the event that an embedded device utilizes mobile code technologies, the embedded device should provide the capability to enforce a security policy for the usage of mobile code technologies. The security policy should allow, at a minimum, the following actions for each mobile code technology used on the embedded device:
  - **(1)** Control execution of mobile code
  - **(2)** Control which users (human, software process, or device) are allowed to transfer mobile code to the device
  - **(3)** Control the execution of mobile code based on the results of an integrity check prior to the code being executed
- **2.** The embedded device should provide the capability to enforce a security policy that allows the device to control execution of mobile code based on the results of an authenticity check prior to the code being executed.
- **3.** **Requirements for SLs**
  - **(1)** SL 1 : **1001. 1**
  - **(2)** SL 2 : **1001. 2**
  - **(3)** SL 3 : **1001. 2**
  - **(4)** SL 4 : **1001. 2**

#### 302. Use of physical diagnostic and test interfaces

- **1.** Embedded devices should protect against unauthorized use of the physical factory diagnostic and test interface(s).
- **2.** Embedded devices should provide active monitoring of the device’s diagnostic and test interface(s) and generate an audit log entry when attempts to access these interface(s) are detected.
- **3.** **Requirements for SLs**
  - **(1)** SL 1 : Not applicable
  - **(2)** SL 2 : **1002. 1**
  - **(3)** SL 3 : **1002. 2**
  - **(4)** SL 4 : **1002. 2**

#### 303. Protection from malicious code

- **1.** The embedded device should provide the capability to protect from installation and execution of unauthorized software.
- **2.** **Requirements for SLs**
  - **(1)** SL 1 : Not applicable
  - **(2)** SL 2 : **1003. 1**
  - **(3)** SL 3 : **1003. 1**
  - **(4)** SL 4 : **1003. 1**

#### 304. Support for updates

- **1.** The embedded device should support the ability to be updated and upgraded.
- **2.** The embedded device should validate the authenticity and integrity of any software update or upgrade prior to installation.
- **3.** **Requirements for SLs**
  - **(1)** SL 1 : **1004. 1**
  - **(2)** SL 2 : **1004. 2**
  - **(3)** SL 3 : **1004. 2**
  - **(4)** SL 4 : **1004. 2**

#### 305. Physical tamper resistance and detection

- **1.** The embedded device should provide tamper resistance and detection mechanisms to protect against unauthorized physical access into the device.
- **2.** The embedded device should be capable of automatically providing notification to a configurable set of recipients upon discovery of an attempt to make an unauthorized physical access. All notifications of tampering should be logged as part of the overall audit logging function.
- **3.** **Requirements for SLs**
  - **(1)** SL 1 : Not applicable
  - **(2)** SL 2 : **1005. 1**
  - **(3)** SL 3 : **1005. 2**
  - **(4)** SL 4 : **1005. 2**

#### 306. Provisioning product supplier roots of trust

- **1.** Embedded devices should provide the capability to provision and protect the confidentiality, integrity, and authenticity of product supplier keys and data to be used as one or more “roots of trust” at the time of manufacture of the device.
- **2.** **Requirements for SLs**
  - **(1)** SL 1 : Not applicable
  - **(2)** SL 2 : **1006. 1**
  - **(3)** SL 3 : **1006. 1**
  - **(4)** SL 4 : **1006. 1**

#### 307. Physical tamper resistance and detection

- **1.** Embedded devices should provide the capability to provision and protect the confidentiality, integrity, and authenticity of asset owner keys and data to be used as “roots of trust”; and support the capability to provision without reliance on components that may be outside of the device’s security zone.
- **2.** **Requirements for SLs**
  - **(1)** SL 1 : Not applicable
  - **(2)** SL 2 : **1007. 1**
  - **(3)** SL 3 : **1007. 1**
  - **(4)** SL 4 : **1007. 1**

#### 308. Integrity of the boot process

- **1.** Embedded devices should verify the integrity of the firmware, software, and configuration data needed for the component’s boot and runtime processes prior to use.
- **2.** Embedded devices should use the component’s product supplier roots of trust to verify the authenticity of the firmware, software, and configuration data needed for the component’s boot process prior to it being used in the boot process.
- **3.** **Requirements for SLs**
  - **(1)** SL 1 : **1008. 1**
  - **(2)** SL 2 : **1008. 2**
  - **(3)** SL 3 : **1008. 2**
  - **(4)** SL 4 : **1008. 2**


### Section 4 Additional Requirements for Host Device (2023)

#### 401. Mobile code

- **1.** In the event that a host device utilizes mobile code technologies, that host device should provide the capability to enforce a security policy for the usage of mobile code technologies. The security policy should allow, at a minimum, the following actions for each mobile code technology used on the host device:
  - **(1)** Control execution of mobile code
  - **(2)** Control which users (human, software process, or device) are allowed to upload mobile code to the host device
  - **(3)** Control the code execution based upon integrity checks on the mobile code and prior to the code being executed.
- **2.** The embedded device should provide the capability to enforce a security policy that allows the device to control execution of mobile code based on the results of an authenticity check prior to the code being executed.
- **3.** **Requirements for SLs**
  - **(1)** SL 1 : **1101. 1**
  - **(2)** SL 2 : **1101. 2**
  - **(3)** SL 3 : **1101. 2**
  - **(4)** SL 4 : **1101. 2**

#### 402. Use of physical diagnostic and test interfaces

- **1.** Embedded devices should protect against unauthorized use of the physical factory diagnostic and test interface(s).
- **2.** Embedded devices should provide active monitoring of the device’s diagnostic and test interface(s) and generate an audit log entry when attempts to access these interface(s) are detected.
- **3.** **Requirements for SLs**
  - **(1)** SL 1 : Not applicable
  - **(2)** SL 2 : **1102. 1**
  - **(3)** SL 3 : **1102. 2**
  - **(4)** SL 4 : **1102. 2**

#### 403. Protection from malicious code

- **1.** To provide protection from malicious codes, there should be a mechanism for host device qualified by the product supplier. The product supplier should document special configuration requirements related to protection against malicious codes.
- **2.** Host device should automatically report malware protection software and file version in use (as part of the full logging function)
- **3.** **Requirements for SLs**
  - **(1)** SL 1 : **1103. 1**
  - **(2)** SL 2 : **1103. 2**
  - **(3)** SL 3 : **1103. 2**
  - **(4)** SL 4 : **1103. 2**

#### 404. Support for updates

- **1.** The embedded device should support the ability to be updated and upgraded.
- **2.** The embedded device should validate the authenticity and integrity of any software update or upgrade prior to installation.
- **3.** **Requirements for SLs**
  - **(1)** SL 1 : **1104. 1**
  - **(2)** SL 2 : **1104. 2**
  - **(3)** SL 3 : **1104. 2**
  - **(4)** SL 4 : **1104. 2**

#### 405. Physical tamper resistance and detection

- **1.** The embedded device should provide tamper resistance and detection mechanisms to protect against unauthorized physical access into the device.
- **2.** The embedded device should be capable of automatically providing notification to a configurable set of recipients upon discovery of an attempt to make an unauthorized physical access. All notifications of tampering should be logged as part of the overall audit logging function.
- **3.** **Requirements for SLs**
  - **(1)** SL 1 : Not applicable
  - **(2)** SL 2 : **1105. 1**
  - **(3)** SL 3 : **1105. 2**
  - **(4)** SL 4 : **1105. 2**

#### 406. Provisioning product supplier roots of trust

- **1.** Host devices should provide the capability to provision and protect the confidentiality, integrity, and authenticity of product supplier keys and data to be used as one or more “roots of trust” at the time of manufacture of the device.
- **2.** **Requirements for SLs**
  - **(1)** SL 1 : Not applicable
  - **(2)** SL 2 : **1106. 1**
  - **(3)** SL 3 : **1106. 1**
  - **(4)** SL 4 : **1106. 1**

#### 407. Provisioning asset owner roots of trust

- **1.** Host devices should provide the capability to provision and protect the confidentiality, integrity, and authenticity of asset owner keys and data to be used as “roots of trust” and support the capability to provision without reliance on components that may be outside of the device’s security zone.
- **2.** **Requirements for SLs**
  - **(1)** SL 1 : Not applicable
  - **(2)** SL 2 : **1107. 1**
  - **(3)** SL 3 : **1107. 1**
  - **(4)** SL 4 : **1107. 1**

#### 408. Integrity of the boot process

- **1.** Host devices should verify the integrity of the firmware, software, and configuration data needed for component’s boot process prior to it being used in the boot process.
- **2.** Host devices should use the component’s product supplier roots of trust to verify the authenticity of the firmware, software, and configuration data needed for component’s boot process prior to it being used in the boot process.
- **3.** **Requirements for SLs**
  - **(1)** SL 1 : **1108. 1**
  - **(2)** SL 2 : **1108. 2**
  - **(3)** SL 3 : **1108. 2**
  - **(4)** SL 4 : **1108. 2**


### Section 5 Additional Requirements for Network Device (2023)

#### 501. Wireless access management

- **1.** A network device supporting wireless access management should provide the capability to identify and authenticate all users (humans, software processes or devices) engaged in wireless communication.
- **2.** The network device should provide the capability to uniquely identify and authenticate all users (humans, software processes or devices) engaged in wireless communication.
- **3.** **Requirements for SLs**
  - **(1)** SL 1 : **1201. 1**
  - **(2)** SL 2 : **1201. 2**
  - **(3)** SL 3 : **1201. 2**
  - **(4)** SL 4 : **1201. 2**

#### 502. Access via untrusted networks

- **1.** The network device supporting device access into a network should provide the capability to monitor and control all methods of access to the network device via untrusted networks.
- **2.** The network device should provide the capability to deny access requests via untrusted networks unless explicitly approved by an assigned role.
- **3.** **Requirements for SLs**
  - **(1)** SL 1 : **1202. 1**
  - **(2)** SL 2 : **1202. 1**
  - **(3)** SL 3 : **1202. 2**
  - **(4)** SL 4 : **1202. 2**

#### 503. Mobile code

- **1.** In the event that a network device utilizes mobile code technologies, the network device should provide the capability to enforce a security policy for the usage of mobile code technologies. The security policy should allow, at a minimum, the following actions for each mobile code technology used on the network device:
  - **(1)** Control execution of mobile code
  - **(2)** Control which users (human, software process, or device) are allowed to transfer mobile code from the network device
  - **(3)** Control the code execution based upon integrity checks on mobile code and prior to the code being executed
- **2.** The network device should provide the capability to enforce a security policy that allows the device to control execution of mobile code based on the results of an authenticity check prior to the code being executed.
- **3.** **Requirements for SLs**
  - **(1)** SL 1 : **1203. 1**
  - **(2)** SL 2 : **1203. 2**
  - **(3)** SL 3 : **1203. 2**
  - **(4)** SL 4 : **1203. 2**

#### 504. Use of physical diagnostic and test interfaces

- **1.** Network devices should protect against unauthorized use of the physical factory diagnostic and test interface(s).
- **2.** Network devices should provide active monitoring of the device’s diagnostic and test interface(s) and generate an audit log entry when attempts to access these interface(s) are detected.
- **3.** **Requirements for SLs**
  - **(1)** SL 1 : Not applicable
  - **(2)** SL 2 : **1204. 1**
  - **(3)** SL 3 : **1204. 2**
  - **(4)** SL 4 : **1204. 2**

#### 505. Protection from malicious code

- **1.** The network device should provide for protection from malicious code.
- **2.** **Requirements for SLs**
  - **(1)** SL 1 : **1205. 1**
  - **(2)** SL 2 : **1205. 1**
  - **(3)** SL 3 : **1205. 1**
  - **(4)** SL 4 : **1205. 1**

#### 506. Support for updates

- **1.** Network devices should support the ability to be updated and upgraded.
- **2.** Network devices should validate the authenticity and integrity of any software update or upgrade prior to installation.
- **3.** **Requirements for SLs**
  - **(1)** SL 1 : **1206. 1**
  - **(2)** SL 2 : **1206. 2**
  - **(3)** SL 3 : **1206. 2**
  - **(4)** SL 4 : **1206. 2**

#### 507. Physical tamper resistance and detection

- **1.** Network devices should provide tamper resistance and detection mechanisms to protect against unauthorized physical access into the device.
- **2.** Network devices should be capable of automatically providing notification to a configurable set of recipients upon discovery of an attempt to make an unauthorized physical access. All notifications of tampering should be logged as part of the overall audit logging function.
- **3.** **Requirements for SLs**
  - **(1)** SL 1 : Not applicable
  - **(2)** SL 2 : **1207. 1**
  - **(3)** SL 3 : **1207. 2**
  - **(4)** SL 4 : **1207. 2**

#### 508. Provisioning product supplier roots of trust

- **1.** Network devices should provide the capability to provision and protect the confidentiality, integrity, and authenticity of product supplier keys and data to be used as one or more “roots of trust” at the time of manufacture of the device.
- **2.** **Requirements for SLs**
  - **(1)** SL 1 : Not applicable
  - **(2)** SL 2 : **1208. 1**
  - **(3)** SL 3 : **1208. 1**
  - **(4)** SL 4 : **1208. 1**

#### 509. Provisioning asset owner roots of trust

- **1.** Network devices should provide the capability to provision and protect the confidentiality, integrity, and authenticity of asset owner keys and data to be used as “roots of trust” and support the capability to provision without reliance on components that may be outside of the device’s security zone.
- **2.** **Requirements for SLs**
  - **(1)** SL 1 : Not applicable
  - **(2)** SL 2 : **1209. 1**
  - **(3)** SL 3 : **1209. 1**
  - **(4)** SL 4 : **1209. 1**

#### 510. Integrity of the boot process

- **1.** Network devices should verify the integrity of the firmware, software, and configuration data needed for component’s boot process prior to it being used in the boot process.
- **2.** Network devices should use the component’s product supplier roots of trust to verity the authenticity of the firmware, software, and configuration data needed for component’s boot process prior to it being used in the boot process.
- **3.** **Requirements for SLs**
  - **(1)** SL 1 : **1210. 1**
  - **(2)** SL 2 : **1210. 2**
  - **(3)** SL 3 : **1210. 2**
  - **(4)** SL 4 : **1210. 2**

#### 511. Zone boundary protection

- **1.** A network device at a zone boundary should provide the capability to monitor and control communications at zone boundaries to enforce the compartmentalization defined in the risk-based zones and conduits model.
- **2.** The network component should provide the capability to deny network traffic by default and allow network traffic by exception.
- **3.** The network component should provide the capability to protect against any communication through the system boundary (also termed island mode).
- **4.** The network component should provide the capability to protect against any communication through the system boundary when there is an operational failure of the boundary protection mechanisms (also termed fail-close).
- **5.** **Requirements for SLs**
  - **(1)** SL 1 : **1211. 1**
  - **(2)** SL 2 : **1211. 2**
  - **(3)** SL 3 : **1211. 4**
  - **(4)** SL 4 : **1211. 4**

#### 512. General purpose, person-to-person communication restrictions

- **1.** A network device at a zone boundary should provide the capability to protect against general purpose, person-to-person messages from being received from users or systems external to the system.
- **2.** **Requirements for SLs**
  - **(1)** SL 1 : **1212. 1**
  - **(2)** SL 2 : **1212. 1**
  - **(3)** SL 3 : **1212. 1**
  - **(4)** SL 4 : **1212. 1** ![](images/image5.png)
