# Guidance for Conformity Certification of Maritime Equipment Cyber Security

> OTHER RULES AND GUIDANCE / GC-31-E / 2025 / EN / Guidance

## CHAPTER 2 COMMON REQUIREMENTS FOR EQUIPMENT CYBER SECURITY (2023)

### Section 1 General

#### 101. General

- **1.** The common requirements for equipment cyber security are defined as shown in Table 1 based on the foundational requirements of IEC 62443-4-2.

  | Common Requirement | Definition |
  | --- | --- |
  | Identification and authentication control | Identify and authenticate all users (humans, software processes and devices), and allow them access to the system or assets. |
  | Use control | Enforce the assigned privileges of an authenticated user (human, software process or device) to perform the requested action on the application or device and monitor the use of these privileges. |
  | System integrity | Ensure the integrity of the application or device to prevent unauthorized manipulation. |
  | Data confidentiality | Ensure the confidentiality of information on communication channels and in data repositories to prevent unauthorized disclosure. |
  | Restricted data flow | Segment the control system via zones and conduits to limit the unnecessary flow of data. |
  | Timely response to events | Respond to security violations by notifying the proper authority, reporting needed evidence of the violation and taking timely corrective action when incidents are discovered. |
  | Resource availability | Ensure the availability of the application or device against the degradation or denial of essential services. |
- **2.** The security level (SL) is defined as shown in Table 2, and Unless expressly specified otherwise, in order for a component to comply with high security level requirements, it should comply with all of the lower security level requirements.

  | Security Level | Definition |
  | --- | --- |
  | SL 1 | Prevent the unauthorized disclosure of information via eavesdropping or casual<br>exposure. |
  | SL 2 | Prevent the unauthorized disclosure of information to an entity actively searching for it using simple means with low resources, generic skills and low motivation. |
  | SL 3 | Prevent the unauthorized disclosure of information to an entity actively searching for it using sophisticated means with moderate resources, IACS specific skills and moderate motivation. |
  | SL 4 | Prevent the unauthorized disclosure of information to an entity actively sea rching for it using sophisticated means with extended resources, IACS specific skills and high motivation. |


### Section 2 Identification and authentication

#### 201. Human user identification and authentication (2021)

- **1.** Components should provide the capability to identify and authenticate all human users according to ISA 62443-3-3 SR 1.1 on all interfaces capable of human user access. However, User identification and authentication should not hamper fast, local emergency actions.
- **2.** Components should provide the capability to uniquely identify and authenticate all human users.
- **3.** Components should provide the capability to employ multifactor authentication for all human user access to the component.
- **4.** **Requirements for SLs**
  - **(1)** SL 1 : **201. 1**
  - **(2)** SL 2 : **201. 2**
  - **(3)** SL 3 : **201. 3**
  - **(4)** SL 4 : **201. 3**

#### 202. Software process and device identification and authentication

- **1.** Components should provide the capability to identify itself and authenticate to any other component (software application, embedded devices, host devices and network devices), according to ISA 62443-3-3 SR 1.2. *(2021)*
- **2.** Components should provide the capability to uniquely identify and authenticate itself to any other component.
- **3.** **Requirements for SLs**
  - **(1)** SL 1 : Not applicable
  - **(2)** SL 2 : **202. 1**
  - **(3)** SL 3 : **202. 2**
  - **(4)** SL 4 : **202. 2**

#### 203. Account management

- **1.** Components should provide the capability to support the management of all accounts directly or integrated into a system that manages accounts according to ISA 62443-3-3 SR 1.3. *(2021)*
- **2.** **Requirements for SLs**
  - **(1)** SL 1 : **203. 1**
  - **(2)** SL 2 : **203. 1**
  - **(3)** SL 3 : **203. 1**
  - **(4)** SL 4 : **203. 1**

#### 204. Identifier management

- **1.** Components should provide the capability to integrate into a system that supports the management of identifiers and/or provide the capability to support the management of identifiers directly according to ISA 62443-3-3 SR 1.4. *(2021)*
- **2.** **Requirements for SLs**
  - **(1)** SL 1 : **204. 1**
  - **(2)** SL 2 : **204. 1**
  - **(3)** SL 3 : **204. 1**
  - **(4)** SL 4 : **204. 1**

#### 205. Authenticator management

- **1.** Components should provide the capability to:
  - **(1)** support the use of initial authenticator content;
  - **(2)** support the recognition of changes to default authenticators made at installation time;
  - **(3)** function properly with periodic authenticator change/refresh operation; and
  - **(4)** protect authenticators from unauthorized disclosure and modification when stored, used and transmitted.
- **2.** The authenticators on which the component rely should be protected via hardware mechanisms like OTP memory.
- **3.** **Requirements for SLs**
  - **(1)** SL 1 : **205. 1**
  - **(2)** SL 2 : **205. 1**
  - **(3)** SL 3 : **205. 2**
  - **(4)** SL 4 : **205. 2**

#### 206. Strength of password-based authentication

- **1.** For components that utilize password-based authentication, those components should provide or integrate into a system that provides the capability to enforce configurable password strength according to internationally recognized and proven password guidelines.
- **2.** Components should provide, or integrate into a system that provides, the capability to enforce password minimum and maximum lifetime restrictions for all users.
- **3.** Components should provide, or integrate into a system that provides, the capability to protect against any given human user account from reusing a password for a configurable number of generations. In addition, the component should provide the capability to enforce password minimum and maximum lifetime restrictions for human users. These capabilities should conform to commonly accepted security industry practices.
- **4.** Components should provide the capability to prompt the user to change their password upon a configurable time prior to expiration.
- **5.** **Requirements for SLs**
  - **(1)** SL 1 : **206. 2**
  - **(2)** SL 2 : **206. 2**
  - **(3)** SL 3 : **206. 3**
  - **(4)** SL 4 : **206. 4**

#### 207. Public key infrastructure certificates

- **1.** When public key infrastructure (PKI) is utilized, the component should provide or integrate into a system that provides the capability to interact and operate in accordance with ISA 62443-3-3 SR 1.8**.** *(2021)*
- **2.** **Requirements for SLs**
  - **(1)** SL 1 : Not applicable
  - **(2)** SL 2 : **207. 1**
  - **(3)** SL 3 : **207. 1**
  - **(4)** SL 4 : **207. 1**

#### 208. Strength of public key-based authentication

- **1.** For components that utilize public-key-based authentication, those components should provide directly or integrate into a system that provides the capability within the same environment to:
  - **(1)** validate certificates by checking the validity of the signature of a given certificate;
  - **(2)** validate the certificate chain or, in the case of self-signed certificates, by deploying leaf certificates to all hosts that communicate with the subject to which the certificate is issued;
  - **(3)** validate certificates by checking a given certificate’s revocation status;
  - **(4)** establish user (human, software process or device) control of the corresponding private key;
  - **(5)** map the authenticated identity to a user (human, software process or device); and
  - **(6)** ensure that the algorithms and keys used for the public key authentication comply with **503.**
- **2.** Components should provide the capability to protect critical, long-lived private keys via hardware mechanisms.
- **3.** **Requirements for SLs**
  - **(1)** SL 1 : Not applicable
  - **(2)** SL 2 : **208. 1**
  - **(3)** SL 3 : **208. 2**
  - **(4)** SL 4 : **208. 2**

#### 209. Authenticator feedback

- **1.** When a component provides an authentication capability the component should provide the capability to obscure feedback of authenticator information during the authentication process.
- **2.** **Requirements for SLs**
  - **(1)** SL 1 : **209. 1**
  - **(2)** SL 2 : **209. 1**
  - **(3)** SL 3 : **209. 1**
  - **(4)** SL 4 : **209. 1**

#### 210. Unsuccessful login attempts

- **1.** When a component provides an authentication capability the component should provide the capability to enforce a limit of a configurable number of consecutive invalid access attempts by any user (human, software process or device) during a configurable time period and deny access for a specified period of time or until unlocked by an administrator when this limit has been reached.
- **2.** **Requirements for SLs**
  - **(1)** SL 1 : **210. 1**
  - **(2)** SL 2 : **210. 1**
  - **(3)** SL 3 : **210. 1**
  - **(4)** SL 4 : **210. 1**

#### 211. System use notification

- **1.** When a component provides local human user access/HMI, it should provide the capability to display a system use notification message before authenticating. The system use notification message should be configurable by authorized personnel.
- **2.** **Requirements for SLs**
  - **(1)** SL 1 : **211. 1**
  - **(2)** SL 2 : **211. 1**
  - **(3)** SL 3 : **211. 1**
  - **(4)** SL 4 : **211. 1**

#### 212. Strength of symmetric key-based authentication

- **1.** For components that utilize symmetric keys, the component should provide the capability to:
  - **(1)** establish the mutual trust using the symmetric key
  - **(2)** store securely the shared secret (the authentication is valid as long as the shared secret remains secret)
  - **(3)** restrict access to the shared secret
  - **(4)** ensure that the algorithms and keys used for the symmetric key authentication comply with **503.**
- **2.** Components should provide the capability to protect critical, long lived symmetric keys via hardware mechanisms.
- **3.** **Requirements for SLs**
  - **(1)** SL 1 : Not applicable
  - **(2)** SL 2 : **212. 1**
  - **(3)** SL 3 : **212. 2**
  - **(4)** SL 4 : **212. 2**


### Section 3 Use Control

#### 301. Authorization enforcement

- **1.** Components should provide an authorization enforcement mechanism for all identified and authenticated users based on their assigned responsibilities.
- **2.** Components should provide an authorization enforcement mechanism for all users based on their assigned responsibilities and least privilege.
- **3.** Components should, directly or through a compensating security mechanism, provide for an authorized role to define and modify the mapping of permissions to roles for all human users.
- **4.** Components should support a supervisor manual override for a configurable time or sequence of events.
- **5.** Components should support dual approval when action can result in serious impact on the industrial process. However, dual approval mechanisms should not be employed when an immediate response is necessary to safeguard health, safety and environment consequences, for example, emergency shutdown of an industrial process
- **6.** **Requirements for SLs**
  - **(1)** SL 1 : **301. 1**
  - **(2)** SL 2 : **301. 3**
  - **(3)** SL 3 : **301. 4**
  - **(4)** SL 4 : **301. 5**

#### 302. Wireless use

- **1.** If a component supports usage through wireless interfaces it should provide the capability to integrate into the system that supports usage authorization, monitoring and restrictions according to commonly accepted industry practices.
- **2.** **Requirements for SLs**
  - **(1)** SL 1 : **302. 1**
  - **(2)** SL 2 : **302. 1**
  - **(3)** SL 3 : **302. 1**
  - **(4)** SL 4 : **302. 1**

#### 303. Session lock

- **1.** If a component provides a human user interface, whether accessed locally or via a network, the component should provide the capability
  - **(1)** to protect against further access by initiating a session lock after a configurable time period of inactivity or by manual initiation by the user (human, software process or device); and
  - **(2)** for the session lock to remain in effect until the human user who owns the session, or another authorized human user, re-establishes access using appropriate identification and authentication procedures.
- **2.** **Requirements for SLs**
  - **(1)** SL 1 : **303. 1**
  - **(2)** SL 2 : **303. 1**
  - **(3)** SL 3 : **303. 1**
  - **(4)** SL 4 : **303. 1**

#### 304. Remote session termination

- **1.** If a component supports remote sessions, the component should provide the capability to terminate a remote session either automatically after a configurable time period of inactivity, manually by a local authority, or manually by the user (human, software process or device) who initiated the session.
- **2.** **Requirements for SLs**
  - **(1)** SL 1 : Not applicable
  - **(2)** SL 2 : **304. 1**
  - **(3)** SL 3 : **304. 1**
  - **(4)** SL 4 : **304. 1**

#### 305. Concurrent session control

- **1.** Components should provide the capability to limit the number of concurrent sessions per interface for any given user (human, software process or device).
- **2.** **Requirements for SLs**
  - **(1)** SL 1 : Not applicable
  - **(2)** SL 2 : Not applicable
  - **(3)** SL 3 : **305. 1**
  - **(4)** SL 4 : **305. 1**

#### 306. Auditable events

- **1.** Components should provide the capability to generate audit records relevant to security for the following categories:
  - **(1)** access control
  - **(2)** request errors
  - **(3)** system events
  - **(4)** backup and restore event
  - **(5)** configuration changes
  - **(6)** audit log events
- **2.** Individual audit records should include:
  - **(1)** timestamp
  - **(2)** source (originating device, software process or human user account)
  - **(3)** category
  - **(4)** type
  - **(5)** event ID
  - **(6)** event result
- **3.** **Requirements for SLs**
  - **(1)** SL 1 : **306. 2**
  - **(2)** SL 2 : **306. 2**
  - **(3)** SL 3 : **306. 2**
  - **(4)** SL 4 : **306. 2**

#### 307. Audit storage capacity

- **1.** Components should provide the capability to allocate audit record storage capacity according to commonly recognized recommendations for log management and provide mechanisms to protect against a failure of the component when it reaches or exceeds the audit storage capacity.
- **2.** Components should provide the capability to issue a warning when the allocated audit record storage reaches a configurable threshold.
- **3.** **Requirements for SLs**
  - **(1)** SL 1 : **307. 1**
  - **(2)** SL 2 : **307. 1**
  - **(3)** SL 3 : **307. 2**
  - **(4)** SL 4 : **307. 2**

#### 308. Response to audit processing failures

- **1.** Components should provide the following capability to protect against the loss of essential services and functions in the event of an audit processing failure and to support appropriate actions in response to an audit processing failure according to commonly accepted industry practices and recommendations.
- **2.** **Requirements for SLs**
  - **(1)** SL 1 : **308. 1**
  - **(2)** SL 2 : **308. 1**
  - **(3)** SL 3 : **308. 1**
  - **(4)** SL 4 : **308. 1**

#### 309. Timestamps

- **1.** Components should provide the capability to create timestamps (including date and time) for use in audit records.
- **2.** Components should provide the capability to create timestamps that are synchronized with a system wide time source.
- **3.** The time synchronization mechanism should provide the capability to detect unauthorized alteration and cause an audit event upon alteration.
- **4.** **Requirements for SLs**
  - **(1)** SL 1 : **309. 1**
  - **(2)** SL 2 : **309. 2**
  - **(3)** SL 3 : **309. 2**
  - **(4)** SL 4 : **309. 3**

#### 310. Non-repudiation

- **1.** If a component provides a human user interface, the component shall provide the capability to determine whether a given human user took a particular action. Elements that are not able to support such capability shall be listed in component documents.
- **2.** Components shall provide the capability to determine whether a given user (human, software process or device) took a particular action.
- **3.** **Requirements for SLs**
  - **(1)** SL 1 : **310. 1**
  - **(2)** SL 2 : **310. 1**
  - **(3)** SL 3 : **310. 1**
  - **(4)** SL 4 : **310. 2**

#### 311. Use control for portable and mobile devices

- **1.** When components supports use of portable and mobile devices, the system should include the capability to;
  - **(1)** Limit the use of portable and mobile devices only to those permitted by design
  - **(2)** Restrict code and data transfer to/from portable and mobile devices
    Note : Port limits / blockers (and silicone) could be accepted for a specific system
- **2.** Requirements for SLs
  - **(1)** SL 1 : **311. 1**
  - **(2)** SL 2 : **311. 1**
  - **(3)** SL 3 : **311. 1**
  - **(4)** SL 4 : **311. 1**


### Section 4 System Integrity

#### 401. Communication integrity

- **1.** Components should provide the capability to protect integrity of transmitted information.
- **2.** Components should provide the capability to verify the authenticity of received information during communication.
- **3.** **Requirements for SLs**
  - **(1)** SL 1 : **401. 1**
  - **(2)** SL 2 : **401. 2**
  - **(3)** SL 3 : **401. 2**
  - **(4)** SL 4 : **401. 2**

#### 402. Security functionality verification

- **1.** Components should provide the capability to support verification of the intended operation of security functions according to ISA 62443-3-3 SR 3.3. *(2021)*
- **2.** Components should provide the capability to support verification of the intended operation of security functions during normal operations.
- **3.** **Requirements for SLs**
  - **(1)** SL 1 : **402. 1**
  - **(2)** SL 2 : **402. 1**
  - **(3)** SL 3 : **402. 1**
  - **(4)** SL 4 : **402. 2**

#### 403. Software and information integrity

- **1.** Components should provide the capability to perform or support integrity checks on software, configuration and other information as well as the recording and reporting of the results of these checks or be integrated into a system that can perform or support integrity checks.
- **2.** Components should provide the capability to perform or support authenticity checks on software, configuration and other information as well as the recording and reporting of the results of these checks or be integrated into a system that can perform or support authenticity checks.
- **3.** If the component is performing the integrity check, it should be capable of automatically providing notification to a configurable entity upon discovery of an attempt to make an unauthorized change.
- **4.** **Requirements for SLs**
  - **(1)** SL 1 : **403. 1**
  - **(2)** SL 2 : **403. 2**
  - **(3)** SL 3 : **403. 3**
  - **(4)** SL 4 : **403. 3**

#### 404. Input validation

- **1.** Components should validate the syntax, length and content of any input data that is used as an industrial process control input or input via external interfaces that directly impacts the action of the component.
- **2.** **Requirements for SLs**
  - **(1)** SL 1 : **404. 1**
  - **(2)** SL 2 : **404. 1**
  - **(3)** SL 3 : **404. 1**
  - **(4)** SL 4 : **404. 1**

#### 405. Deterministic output

- **1.** Components that physically or logically connect to an automation process should provide the capability to set outputs to a predetermined state if normal operation as defined by the component supplier cannot be maintained.
- **2.** **Requirements for SLs**
  - **(1)** SL 1 : **405. 1**
  - **(2)** SL 2 : **405. 1**
  - **(3)** SL 3 : **405. 1**
  - **(4)** SL 4 : **405. 1**

#### 406. Error handling

- **1.** Components should identify and handle error conditions in a manner that does not provide information that could be exploited by adversaries to attack the components.
- **2.** **Requirements for SLs**
  - **(1)** SL 1 : Not applicable
  - **(2)** SL 2 : **406. 1**
  - **(3)** SL 3 : **406. 1**
  - **(4)** SL 4 : **406. 1**

#### 407. Session integrity

- **1.** Components should provide mechanisms to protect the integrity of communications sessions including:
  - **(1)** the capability to invalidate session identifiers upon user logout or other session termination (including browser sessions)
  - **(2)** the capability to generate a unique session identifier for each session and recognize only session identifiers that are system-generated
  - **(3)** the capability to generate unique session identifiers with commonly accepted sources of randomness
- **2.** **Requirements for SLs**
  - **(1)** SL 1 : Not applicable
  - **(2)** SL 2 : **407. 1**
  - **(3)** SL 3 : **407. 1**
  - **(4)** SL 4 : **407. 1**

#### 408. Protection of audit information

- **1.** Components should protect audit information, audit logs, and audit tools (if present) from unauthorized access, modification and deletion.
- **2.** Components should provide the capability to store audit records on hardware-enforced write-once media.
- **3.** **Requirements for SLs**
  - **(1)** SL 1 : Not applicable
  - **(2)** SL 2 : **408. 1**
  - **(3)** SL 3 : **408. 1**
  - **(4)** SL 4 : **408. 2**


### Section 5 Data Confidentiality

#### 501. Communication integrity

- **1.** Components should provide the capability to protect the confidentiality of information at rest for which explicit read authorization is supported and support the protection of the confidentiality of information in transit as defined in ISA 62443-3-3 SR 4.1. *(2021)*
- **2.** **Requirements for SLs**
  - **(1)** SL 1 : **501. 1**
  - **(2)** SL 2 : **501. 1**
  - **(3)** SL 3 : **501. 1**
  - **(4)** SL 4 : **501. 1**

#### 502. Information persistence

- **1.** Components should provide the capability to erase all information, for which explicit read authorization is supported, from components to be released from active service and/or decommissioned.
- **2.** Components should provide the capability to protect against unauthorized and unintended information transfer via volatile shared memory resources.
- **3.** Components should provide the capability to verify that the erasure of information occurred.
- **4.** **Requirements for SLs**
  - **(1)** SL 1 : Not applicable
  - **(2)** SL 2 : **502. 1**
  - **(3)** SL 3 : **502. 3**
  - **(4)** SL 4 : **502. 3**

#### 503. Use of cryptography

- **1.** If cryptography is required, the component should use cryptographic security mechanisms according to internationally recognized and proven security practices and recommendations.
- **2.** **Requirements for SLs**
  - **(1)** SL 1 : **503. 1**
  - **(2)** SL 2 : **503. 1**
  - **(3)** SL 3 : **503. 1**
  - **(4)** SL 4 : **503. 1**


### Section 6 Restricted Data Flow

#### 601. Network segmentation

- **1.** Components should support a segmented network to support zones and conduits, as needed, to support the broader network architecture based on logical segmentation and criticality.
- **2.** **Requirements for SLs**
  - **(1)** SL 1 : **601. 1**
  - **(2)** SL 2 : **601. 1**
  - **(3)** SL 3 : **601. 1**
  - **(4)** SL 4 : **601. 1**


### Section 7 Timely Response to Events

#### 701. Audit log accessibility

- **1.** Components should provide the capability for authorized humans and/or tools to access audit logs on a read-only basis.
- **2.** Components should provide programmatic access to audit records by either using an application programming interface (API) or sending the audit records to a centralized system.
- **3.** **Requirements for SLs**
  - **(1)** SL 1 : **701. 1**
  - **(2)** SL 2 : **701. 1**
  - **(3)** SL 3 : **701. 2**
  - **(4)** SL 4 : **701. 2**

#### 702. Continuous monitoring

- **1.** Components should provide the capability to be continuously monitored using commonly accepted security industry practices and recommendations to detect, characterize and report security breaches in a timely manner.
- **2.** **Requirements for SLs**
  - **(1)** SL 1 : Not applicable
  - **(2)** SL 2 : **702. 1**
  - **(3)** SL 3 : **702. 1**
  - **(4)** SL 4 : **702. 1**


### Section 8 Resource Availability

#### 801. Denial of service(DoS) protection

- **1.** Components should provide the capability to maintain essential functions when operating in a degraded mode as the result of a DoS event.
- **2.** Components should provide the capability to mitigate the effects of information and/or message flooding types of DoS events.
- **3.** **Requirements for SLs**
  - **(1)** SL 1 : **801. 1**
  - **(2)** SL 2 : **801. 2**
  - **(3)** SL 3 : **801. 2**
  - **(4)** SL 4 : **801. 2**

#### 802. Resource management

- **1.** Components should provide the capability to limit the use of resources by security functions to protect against resource exhaustion.
- **2.** **Requirements for SLs**
  - **(1)** SL 1 : **802. 1**
  - **(2)** SL 2 : **802. 1**
  - **(3)** SL 3 : **802. 1**
  - **(4)** SL 4 : **802. 1**

#### 803. System backup

- **1.** Components should provide the capability to participate in system level backup operations in order to safeguard the component state (user- and system-level information). The backup process should not affect the normal component operations.
- **2.** Components should provide the capability to validate the integrity of backed up information prior to the initiation of a restore of that information.
- **3.** **Requirements for SLs**
  - **(1)** SL 1 : **803. 1**
  - **(2)** SL 2 : **803. 2**
  - **(3)** SL 3 : **803. 2**
  - **(4)** SL 4 : **803. 2**

#### 804. System recovery and reconstitution

- **1.** Components should provide the capability to be recovered and reconstituted to a known secure state after a disruption or failure.
- **2.** **Requirements for SLs**
  - **(1)** SL 1 : **804. 1**
  - **(2)** SL 2 : **804. 1**
  - **(3)** SL 3 : **804. 1**
  - **(4)** SL 4 : **804. 1**

#### 805. Network and security configuration settings

- **1.** Components should provide the capability to be configured according to recommended network and security configurations as described in guidelines provided by the system supplier. The component should provide an interface to the currently deployed network and security configuration settings.
- **2.** Components should provide the capability to generate a report listing the currently deployed security settings in a machine-readable format.
- **3.** **Requirements for SLs**
  - **(1)** SL 1 : **805. 1**
  - **(2)** SL 2 : **805. 1**
  - **(3)** SL 3 : **805. 2**
  - **(4)** SL 4 : **805. 2**

#### 806. Least functionality

- **1.** Components should provide the capability to specifically restrict the use of unnecessary functions, ports, protocols and/or services.
- **2.** **Requirements for SLs**
  - **(1)** SL 1 : **806. 1**
  - **(2)** SL 2 : **806. 1**
  - **(3)** SL 3 : **806. 1**
  - **(4)** SL 4 : **806. 1**

#### 807. System component inventory

- **1.** Components should provide the capability to support a system component inventory according to ISA 62443-3-3 SR 7.8.
- **2.** **Requirements for SLs**
  - **(1)** SL 1 : Not applicable
  - **(2)** SL 2 : **807. 1**
  - **(3)** SL 3 : **807. 1**
  - **(4)** SL 4 : **807. 1** ![](images/image4.png)
