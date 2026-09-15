# Rules and Guidance for the Classification of Mobile Offshore Drilling Units

> RULES AND GUIDANCE FOR OFFSHORE STRUCTURES / RB-13-E / 2025 / EN / Guidance

## CHAPTER 6 ELECTRICAL EQUIPMENT AND CONTROL SYSTEM

### Section 1 Electrical Equipment

#### 101. General

- **1.** Electrical systems and equipment are to comply with the Rules and API RP 14FZ.
- **2.** Compliance with industry standards, such as the following, will be specially considered.
  - **(1)** API RP 2003
  - **(2)** IEEE Std. 242
  - **(3)** IEEE C37.06.1
  - **(4)** IEEE C37.20.6
  - **(5)** IEEE Std. 45
  - **(6)** IEEE Std. 142
  - **(7)** NFPA 70
  - **(8)** NFPA 496
  - **(9)** API RP 500
  - **(10)** API RP 505
- **3.** The Society is prepared to consider other industry standards and practices for electrical equipment, on a case-by-case basis, with justifications through novel features and comparative analyses to be provided to demonstrate equivalent level of safety to the recognized standards as listed in this Annex, performed in accordance with **Ch 1, Sec 1, 103.**
- **4.** All electrical components are to be designed to meet safe operating conditions by accounting for maximum and minimum temperatures and vibrations expected during service.
- **5.** Electrical equipment installed in a hazardous area is to be tested in works having the adequate apparatus for testing and inspection and to be type approved by the Society.


### Section 2 Control Systems

#### 201. General

- **1.** The following requirements are to apply to well control systems, drilling systems and control systems.
  - **(1)** The control system (hydraulic, pneumatic, electric, electro-hydraulic, acoustic, etc.) is to be designed where no single control system component failure is to lead to a failure of the controlled system or loss of control.
  - **(2)** Transfer between control stations is to comply with the following requirements.
    - **(A)** Transfer between control stations only applies to drilling control systems and does not apply to BOP, EDS, choke and kill, and diverter control systems.
    - **(B)** Transfers between control stations are to comply with the following.
      - **(a)** When control of the system or equipment is possible from more than one control location, control is to be possible only from one control location at a time.
      - **(b)** Clear method to transfer control between stations is to be provided.
      - **(c)** At each control location, there is to be an indicator showing which location is in control.
  - **(3)** Maximum control system voltages: 250 VAC 50 Hz or 60 Hz or *d.c*. voltage is to be the highest voltage in any of the control system panels.
  - **(4)** All safety functions are to be provided with visual and audible indicators.
- **2.** **Logic circuit features**
  - **(1)** Logic circuit is to comply with the following principles:
    - **(A)** When logic circuits are used for sequential startup or for operating individual components, indicators are to be provided at the control console to show the successful completion of the sequence of operations by the logic circuit and start-up and operation of the component. If some particular step is not carried out during the sequence, the sequence is to stop at this point.
    - **(B)** Manual override is to be fitted in vital functions to permit control in the case of failure of a logic circuit.

#### 202. Control systems for well control equipment

- **1.** Control systems for well control include the BOP, EDS, choke and kill and diverter control systems. These control systems are to comply with the following requirements:
  - **(1)** The control system (hydraulic, pneumatic, electric, electro-hydraulic, acoustic, etc.) is to be designed where no single control system component failure is to lead to a failure of the controlled system, loss of control or loss of well control.
  - **(2)** The control system and components are to be in compliance with API Spec 16C, API Spec 16D and with applicable recommended practices such as API RP 53, API RP 59, and API RP 64.
  - **(3)** **Ch 4, 202. 3**, **203. 9** and **204. 5** are to apply to control system requirements for individual well control systems and/or equipment.
  - **(4)** FMEA, FMECA or similar analysis is also to be conducted to determine compliance with (1) to (3) and **Ch 4, Sec 2.**

#### 203. Electrical Control Systems and Computer-Based Systems

- **1.** **Electrical control systems**
  - **(1)** Electrical control systems are to comply with **Pt 6, Ch 2, 204. 4** of **Rules for the Classification of Steel Ships**.
  - **(2)** In addition, electrical control systems are to comply with **204.**
- **2.** **Computer-based Systems**
  - **(1)** Computer-based systems are to comply with **Pt 6, Ch 2, 201. 7**.
  - **(2)** In addition, computer-based systems are to comply with the following.
    - **(A)** **Fail Safe** Computer-based systems are to be designed such that any of the system's components will not cause unsafe operation of the system or equipment being controlled.
    - **(B)** **Failure Modes and Effects Analysis (FMEA)** An FMEA is to be used to determine that any component failure will not result in the complete loss of control, the shutdown of the system or equipment being controlled, or other unsafe situation.
    - **(C)** **Failure Mode, Effects and Criticality Analysis (FMECA)** An FMECA is an extension of the FMEA to include a criticality analysis that is used to identify the probability of failure modes against the severity of their consequences.
    - **(D)** **Safety Integrity**
      - **(a)** When computer-based systems have safety-related control functions and the associated failure modes identified in the FMEA/FMECA result in an undesirable situation, special consideration may be given, provided the appropriate level of safety integrity has been provided.
      - **(b)** The appropriate level is to be determined by the application of recognized industry standard, such as the IEC 61508 Series or the ANSI/ISA 84 Series.
      - **(c)** Documentation in accordance with the relevant industry standard is to be submitted for review to justify the appropriate safety integrity levels.

#### 204. Safety systems

- **1.** Means are to be provided to indicate the cause of the safety action.
- **2.** Alarms are to be given at each control location, including any local manual control positions, upon the activation of a safety system.
- **3.** Drilling systems or equipment shutdown by a safety system is to be designed not to restart automatically, unless first actuated by a manual reset.
- **4.** Systems are to have the following:
  - **(1)** Redundant processor, memory, and networks
  - **(2)** Local and remote I/O modules are to fail in a predetermined fashion when there is loss of communications with the CPU.
  - **(3)** Input and Output points are to be diagnostic type, where the program will read the diagnostic status of the I/O and perform safe actions. The program is to notify the operator if a point fails.
- **5.** All shutdowns are to be executed in a predetermined logical manner, as specified in the "Shutdown Logic", and are to indicate or execute actions to:
  - **(1)** Limit the severity of the incident
  - **(2)** Protect personnel
  - **(3)** Limit environmental impact
  - **(4)** Escape, muster, and evacuation process
- **6.** Shutdown is not to result in adverse cascade effects, which result from activation of other protection devices to maintain the facility in a safe condition.
- **7.** The shutdown systems are to be designed to provide that any ongoing operations can be terminated safely when a shutdown is activated.
- **8.** Adequate measure is to be provided to prevent accidental unlatching of the wellhead connector, emergency disconnect, and LMRP, such as two-hand function, two-step action, protective cover or equivalent.
- **9.** Control panels are to be clearly labeled. ![](images/image13.png)
