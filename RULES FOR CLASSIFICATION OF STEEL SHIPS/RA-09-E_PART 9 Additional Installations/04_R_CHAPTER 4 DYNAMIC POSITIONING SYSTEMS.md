# PART 9 Additional Installations

> RULES FOR CLASSIFICATION OF STEEL SHIPS / RA-09-E / 2025 / EN / Rules

## CHAPTER 4 DYNAMIC POSITIONING SYSTEMS

### Section 1 General

#### 101. General

- **1.** **Application** The requirements in this Chapter apply to the ships intended to be registered as ships provided with dynamic positioning systems(hereafter referred to as "DP system(s)").
- **2.** **Related requirements** In addition to complying with the requirements in this Chapter, those are to be applied respectively such as follows: For machinery installations, **Pt 5;** For electorial installations, **Pt 6, Ch 1;** For Automatic and remote control systems, **Pt 6, Ch 2.**
- **3.** **Classes of DP systems** DP systems are classified and defined by their worst case failure modes as follows:
  - **(1)** DPS(0), DPS(1)
    Loss of position and/or heading may occur in the event of a single fault.
  - **(2)** DPS(2)
    A loss of position and/or heading is not to occur in the event of a single failure in any active component or system. Normally static components will not be considered to fail where adequate protection from damage is demonstrated. Single failure criteria include:
    - **(A)** Any active component or system (generators, thrusters, switchboards, remote controlled valves, etc.).
    - **(B)** Any normally static component (cables, pipes, manual valves, etc.) which is not properly documented with respect to protection and reliability.
  - **(3)** DPS(3)
    A loss of position and/or heading is not to occur in the event of a single failure. A single failure includes:
    - **(A)** Items listed above for DPS(2), and any normally static component is assumed to fail.
    - **(B)** All components in any one watertight compartment, from fire or flooding.
    - **(C)** All components in any one fire sub-division, from fire or flooding.

#### 102. Definitions

Terms used in this Chapter are defined as follows:
Position reference system is to incorporate suitable position measurement techniques which may be by means of the followings.
- Acoustic device
- Radio
- Radar
- Inertial navigation
- Satellite navigation
- Taut wire
- or, other acceptable means depending on the service conditions for which the ship is intended
- Gyrocompass or equivalent means

#### 103. Drawings and data

- **1.** **General** In the case of the ships intended to be registered as ships provided with DP systems, the drawings and data to be submitted for approval before the commencement of work are generally as follows:
  - **(1)** Drawings
    - **(A)** Plans showing the construction and layout of the DP system
    - **(B)** In the case of the ships intended to be registered as ships provided with DPS(3), the following drawings are to be submitted for approval:
      - **(a)** Cable route layout drawing (apply to the ships intended to be registered as ships provided with DPS(3))
      - **(b)** Fire and flooding separation drawing (apply to the ships intended to be registered as ships provided with DPS(3))
    - **(C)** Plans with respect to the automatic and remote control of the DP system
      - **(a)** Functional block diagrams of the control system
      - **(b)** Functional block diagrams of the measuring system
      - **(c)** Details of monitoring functions of the control system and measuring system together with a description of the monitoring functions
      - **(d)** Details of the overall alarm system
      - **(e)** Details of the control stations, e.g. control panels and consoles, including the location of the control stations
    - **(D)** Electrical diagrams for control system and measuring system
  - **(2)** Data
    - **(A)** Equipment list of DP systems (Name of equipment, model, type, Manufacturer)
    - **(B)** Failure modes and effect analysis(FMEA) data (in the case of the ships intended to be registered as ships provided with DPS(2) or DPS(3))
    - **(C)** Operation manuals (including details of the DP system operation, installation of equipment, maintenance and fault finding procedures together with a section on the procedure to be adopted in emergency)
    - **(D)** Test schedules including the methods of testing and the test facilities
- **2.** **Reference data** For the ships intended to be registered as ships provided with DP systems, in addition to the requirements in **Par 1** above, the following data is to be submitted :
  - **(1)** Drawings
    - **(A)** Lines plan
    - **(B)** General arrangement
    - **(C)** Details of thruster arrangement
  - **(2)** Data
    - **(A)** Thruster power and thrusts
    - **(B)** Details of between thruster and thruster, between thruster and hull, and between thruster and current interaction
    - **(C)** Design maximum environmental conditions
    - **(D)** Details of sea current loads, wave drift forces and wind forces on ship
    - **(E)** Allocation logic of thrusters


### Section 2 Requirements of Dynamic Positioning Systems

#### 201. General

- **1.** The ships intended to be registered as ships provided with DP systems are to be provided DP systems specified in this Section.
- **2.** If external forces from mission-related systems (cable lay, pipe lay, mooring, etc.) have a direct impact on DP performance, the influence of these systems shall be considered and factored into the DP system design.
- **3.** The ships In order to meet the single failure criteria given in **101. 3**, redundancy of components will normally be necessary as follows:
  - **(1)** For DPS(2), redundancy of all active components; and
  - **(2)** For DPS(3), redundancy of all components and A-60 physical separation of the components.
- **4.** For DPS(3), full redundancy of the control systems may not be possible. (i.e. there may be a need for a single changeover system from the main computer system to the backup computer system). Such connections between otherwise redundant and separated systems may be accepted when these are operated so that they do not represent a possible failure propagation path during DP operations.
- **5.** For DPS(2) and DPS(3), connections between otherwise redundant and separated systems shall be kept to a minimum and made to fail to the safest condition. Failure in one system shall in no case be transferred to the other redundant system.
- **6.** The DP control station shall be arranged where the operator has a good view of the vessel's exterior limits and the surrounding area. Equipment that shall be located at the DP control station includes, but is not limited to:
  - **(1)** DP control and independent joystick control operator stations;
  - **(2)** Manual thruster levers;
  - **(3)** Mode change systems;
  - **(4)** Thruster emergency stops;
  - **(5)** Internal communications; and
  - **(6)** Position reference systems' HMI, when considered necessary.

#### 202. Requirements of dynamic positioning systems

- **1.** **Power system** ***(2024)***
  - **(1)** Electrical generating system
    For electrically driven thruster, the total capacity of electrical generating system is to be not less than the maximum DP load together with the maximum auxiliary load. This may be achieved by parallel operation of two or more generating sets provided that the requirements of **Pt 6, Ch 1, 202.** are complied with.
    - **(A)** Capacity of electrical generating system
    - **(B)** Continuity of electric source
      - **(a)** When the electrical power requirements are supplied by one generator set, on loss of power there is to be provision for automatic starting and connection to the switchboard of a standby set and automatic restarting of essential auxiliary services.
      - **(b)** In the event of failure of one or more generators, protection measures against blackout caused by overload are to be provided. *(2019)*
  - **(2)** Electrical supply for thruster auxiliaries, control computers and measuring system
    Thruster auxiliaries, control computers and measuring systems are to be served by individual circuits. Services that are duplicated are to be separated throughout their length as widely as is practical and without the use of common feeders, transformers, converters, protective devices or control circuits.
  - **(3)** Common source
    Where the electrical auxiliary services necessary for maintaining the ship normally in operational and habitable conditions, and the electrical service necessary for operating the DP thrusters are supplied from a common source, the following requirements are to be complied with:
    - **(A)** The voltage regulation and current sharing requirements defined in **Pt 6, Ch 1, 305. 4** and **5** or **306. 2** and **4** are to be maintained over the full range of power factors that may occur in service.
    - **(B)** Where silicon controlled converters (inverter, cycloconverter, rectifier, etc.) are used to feed the thruster motor and the instantaneous value of the line-to-line voltage wave-form on the *a.c.* auxiliary system busbars deviates by more than 10 percent of the maximum value of the fundamental harmonic, the electrical auxiliary services necessary for maintaining the ship normally in operational and habitable conditions are to be capable of withstanding the additional temperature rise due to the harmonic distortion. Control systems, alarms and safety equipment are to operate satisfactorily with the maximum supply system waveform distortion, or be provided with suitably filtered or converted supplies.
    - **(C)** When the control system incorporates volatile memory, it is to be supplied via uninterruptible power supply. An uninterruptible power supply (UPS) is to be provided for each DP-computer system to ensure that any power failure will not affect more than one computer. UPS battery capacity is to provide a minimum of 30 minutes operation following a mains supply failure.
  - **(4)** Number and rating of transformers
    The number and ratings of power transformers are to be sufficient to ensure full load operation of the DP system even when one transformer is out of service.
  - **(5)** Alarm for electrical generating system
    An alarm is to be initiated at the DP control stations when the total electrical load of all operating thruster units exceeds a preset percentage of the running generators capacity. This alarm is to be adjustable between 50 and 100 percent of the full load capacity having regard to the number of electrical generators in service.
- **2.** **Thruster system**
  - **(1)** Design and location of thruster
    - **(A)** Thrusters are to be designed to minimize potential interference with other thrusters, sensors, hull or other surfaces which could be encountered in the service for which the ship is intended.
    - **(B)** Thruster intakes are to be located at sufficient depth to reduce the possibility of ingesting floating debris and vortex formation.
  - **(2)** Performance of thruster
    - **(A)** The response and repeatability of thrusters to changes in propeller pitch, speed or direction of rotation are to be suitable for maintaining the area of operation and the heading deviation specified.
    - **(B)** Vessels with DPS(0) or DPS(1) are to have thrusters in number and of capacity sufficient to maintain position and heading under the specified maximum environmental conditions.
    - **(C)** Vessels with DPS(2) or DPS(3) are to have thrusters in number and of capacity sufficient to maintain position and heading, in the event of any single fault, under the specified maximum environmental conditions. This includes the failure of any one thruster.
  - **(3)** Alarm for thruster
    Each thruster unit is to be provided with a high power alarm. The setting of this alarm is to be adjustable and below the maximum thruster output.
- **3.** **DP control system**
  - **(1)** General

    **Table 9.4.1 Minimum Number of Control System, Position reference System and Environmental Sensor** ***(2025)***

    | Class | Control system |   | Position<br>reference system | Environmental sensor |   |   |
    | --- | --- | --- | --- | --- | --- | --- |
    | Class | Control system |   | Position<br>reference system | Heading reference system | Vertical reference sensor | Means to ascertained the wind and direction |
    | DPS(0) | Joystick system<sup>(1)</sup> | 1 set | 1 set | 1 set | 1 set | each 1 set |
    | DPS(1) | DP control system<sup>(2)</sup><br>Joystick system<sup>(1)</sup>(2) | 1 set<br>1 set | 2 sets<sup>(3)</sup> | 1 set | 1 set | 1 set |
    | DPS(2) | DP control system<sup>(2)</sup><br>Joystick system<sup>(1)</sup>(2) | 2 sets<br>1 set | 3 sets<sup>(3)</sup>(4) | 3 sets<sup>(3)</sup> | 3 sets<sup>(3)</sup> | each 3 sets<sup>(3)</sup> |
    | DPS(3) | DP control system<sup>(2)</sup><br>Joystick system<sup>(1)</sup>(2)<br>Backup DP system<sup>(2)</sup> | 2 sets<br>1 set<br>1 set | 3 sets<sup>(3)</sup>(4) | 3 sets<sup>(3)</sup> | 3 sets<sup>(3)</sup> | each 3 sets<sup>(3)</sup> |
    | (NOTES)<br>(1) To be provided to maintain the desired heading of the ship.<br>(2) To be arranged to operate independently so that a failure in one control system will not render the other control system inoperative.<br>(3) To be arranged to operate independently so that a failure in on position reference system(or environmental sensor) will not render the other position reference system(or environmental sensor) inoperative.<br>(4) To be provided with at least two different measurement techniques. |   |   |   |   |   |   |
    - **(A)** In general the DP control system is to be arranged in a DP control station where the operator has a good view of the vessel's exterior limits and the surrounding area.
    - **(B)** The DP control station is to display information from the power system, thruster system and DP control system to ensure that these systems are functioning correctly. Information necessary to operate the DP system safely is to be visible at all times.
    - **(C)** The selection between operational mode is to be provided and easily operated. The active mode is always to be clearly displayed.
    - **(D)** For class notation DPS(2) and DPS(3), means for preventing inadvertent operation which can lead to a loss of position or heading are to be provided.
    - **(E)** Alarms and warnings for failures in all systems interfaced to and/or controlled by the DP control system shall be audible and visual. A record of their occurrence and of status changes shall be provided together with any necessary explanations.
    - **(F)** The DP control system shall prevent failures being transferred from one system to another. The redundant components shall be so arranged that any failed component or components may be easily isolated so that the other component(s) can take over smoothly with no loss of position and/or heading.
    - **(G)** Minimum number of control system, position reference system and environmental sensor for DP systems is to be in accordance with the **Table 9.4.1**:
  - **(2)** Control system
    The control system for dynamic positioning operation is to be stable throughout its operational range and is to meet the specified performance and accuracy criteria.
  - **(3)** Computer systems
    - **(A)** For DPS(2), the DP control system shall consist of at least two computer systems so that, in case of any single failure, automatic position keeping ability will be maintained. Common facilities such as self-checking routines, alignment facilities, data transfer arrangements and plant interfaces shall not be capable of causing failure of more than one computer system. An alarm shall be initiated if any computer fails or is not ready to take control.
    - **(B)** For DPS(3), the main DP control system shall consist of at least two computer systems arranged so that, in case of any single failure, automatic position keeping ability will be maintained. Common facilities such as self-checking routines, alignment facilities, data transfer arrangements and plant interfaces shall not be capable of causing failure of more than one computer system. The two or more computer systems mentioned above do not include the backup computer system; thus, in addition, one separate backup DP control system shall be arranged, see paragraph (D). An alarm shall be initiated if any computer fails or is not ready to take control.
    - **(C)** For DPS(2) and DPS(3), the DP control system shall include a software function, normally known as "consequence analysis", which continuously verifies that the vessel will remain in position even if the worst-case failure occurs. This analysis shall verify that the thrusters, propellers and rudders (if included under DP control) that remain in operation after the worst-case failure can generate the same resultant thruster force and moment as required before the failure. The consequence analysis shall provide an alarm if the occurrence of a worst-case failure were to lead to a loss of position and/or heading due to insufficient thrust for the prevailing environmental conditions (e.g. wind, waves, current, etc.). For operations which will take a long time to safely terminate, the consequence analysis shall include a function which simulates the remaining thrust and power after the worst-case failure, based on input of the environmental conditions.
    - **(D)** For DPS(3), the backup DP control system shall be in a room separated by an A-60 class division from the main DP control station. During DP operation, this backup control system shall be continuously updated by input from at least one of the required sets of sensors, position reference system, thruster feedback, etc. and be ready to take over control. The switchover of control to the backup system shall be manual, situated on the backup computer, and shall not be affected by a failure of the main DP control system. Main and backup DP control systems shall be so arranged that at least one system will be able to perform automatic position keeping after any single failure.
    - **(E)** Each DP computer system shall be isolated from other on-board computer systems and communications systems to ensure the integrity of the DP system and command interfaces. This isolation may be effected via hardware and/or software systems and physical separation of cabling and communication lines. Robustness of the isolation shall be verified by analysis and proven by testing.
  - **(4)** Measuring system
    The deviation from the desired heading is to be adjustable, but is not to exceed the specified limits. Arrangements are to be provided to fix and identify the set point for the desired heading.
    Suitable processing and comparative techniques are to be provided to validate the. control system inputs from position reference systems and other environmental sensors, to ensure the optimum performance of the DP system.
    - **(A)** Measuring systems are to be provided to ensure the specified area of operation and heading deviation can be effectively maintained.
    - **(B)** Set point for the desired heading
    - **(C)** Validation for measuring system
  - **(5)** Indicators
    Indications of the following are to be provided at each station from which it is possible to control the DP system.
    - **(A)** The heading and location of the vessel relative to the desired reference point or course
    - **(B)** Vectorial thrust output of thrusters, individual and total
    - **(C)** Operational status of position reference systems and environmental sensors
    - **(D)** Environmental conditions, e.g. wind strength and direction
    - **(E)** Available status of standby thruster units
  - **(6)** Alarms
    Alarms are to be provided for the following fault conditions:
    - **(A)** Control computer system fault
    - **(B)** Automatic changeover to a standby control computer system
    - **(C)** Abnormal signal errors revealed by the validity checks required by (3) (C)
    - **(D)** When the ship deviates from its predetermined area of operation
    - **(E)** When the ship deviates from its predetermined heading limits
    - **(F)** Taut wire excursion limit
    - **(G)** Fault of position reference system
    - **(H)** Fault of environmental sensor
    - **(I)** Automatic changeover to a standby position reference system or environmental sensor
- **4.** **Auxiliary system (applies to DPS(2) and DPS(3))**
  - **(1)** General
    - **(A)** For class notations DPS(2) and DPS(3), the auxiliary systems that are part of the DP system are to be arranged in accordance with the redundancy requirements.
    - **(B)** A single failure effect analysis for the following auxiliary systems is to be included in FMEA of the DP system.
      - **(a)** Fuel oil system
      - **(b)** Lubricating oil system
      - **(c)** Cooling water system
      - **(d)** Compressed air system
      - **(e)** Hydraulic system
      - **(f)** Pneumatic system
      - **(g)** Ventilation/HVAC system
  - **(2)** Fuel oil system
    - **(A)** The engine fuel supply systems, including service tanks, supply and return lines, filters, heating system(if applicable), pumps, quick closing valves and their controls, are to be arranged in accordance with the redundancy concept.
    - **(B)** Actuators for quick closing valves are to be installed on a per engine basis and hence any remote control system is to fail safe with respect to station keeping.
    - **(C)** For class notation DPS(3), a minimum of one service tank is to be provided for each redundant group. The service tanks are to be in separate compartments with A-60 partitions following redundancy concept.
  - **(3)** Lubricating oil system
    Lubricating oil system for engines are to be associated with one engine only.
  - **(4)** Cooling water system
    - **(A)** The cooling water systems are to be arranged in accordance with the redundancy concept.
    - **(B)** For twin screw vessels where cooling pumps are engine driven, a duplicate spare pump carried onboard, in lieu of the standby pump, is acceptable, as long as loss of pump would maintain DP function even during the worst case failure.
  - **(5)** Compressed air system
    Compressed air systems for DP related functions are to be arranged in accordance with the redundancy concept. Compressed air for starting engines is to be independent to the maximum extent feasible. Control air and starting air may be taken from the same source provided any pressure drops associated with starting air do not affect the control function. Loss of air supply to the thrusters is to be alarmed and is to have no effect on thruster operation.
  - **(6)** Pneumatic system
    Pneumatic systems are to be designed according to required redundancy in view of the risk of leakage.
  - **(7)** Ventilation/HVAC system
    Ventilation and HVAC systems for spaces containing equipment essential to DP are to be arranged to comply with redundancy so that acceptable temperature can be maintained after any single fault in active components and ventilation damper actuation energy source. This requirement also applies to switchboard rooms and instrument rooms containing components that are parts of the DP system.
  - **(8)** Power supply to auxiliary system
    Power for auxiliary systems associated with DP systems is to be taken from within the redundancy group. Auxiliaries for thruster systems such as cooling water pumps and fans are to be powered from the same redundancy group as that providing the drives.

#### 203. Additional requirements for DP systems

- **1.** **DPS(1)**
  - **(1)** In the event of a failure of a position reference system, the control systems are to continue operating on signals from the remaining position reference system without manual intervention.
  - **(2)** The area of operation is to be adjustable, but is not to exceed the specific limits which are to be based on a percentage of water depth, or if applicable a defined absolute surface movement. Arrangements are to be provided to fix and identify the set point for the area of operation.
  - **(3)** A manually initiated emergency alarm, clearly distinguishable from all other alarms associated with the DP system is to be provided at the DP control station to warn all relevant personnel in the event of a total. loss of DP capability. In this respect consideration is to be given to additional alarms being provided at locations such as the master's accommodation and operational control stations.
  - **(4)** For electrically driven thruster units, the following requirements are to be complied with: *(2019)*
    - **(A)** Indication of absorbed electrical power and available on-line generating capacity is to be provided at the main DP control station.
    - **(B)** Means are to be provided to prevent starting of thruster motors until sufficient electrical generating capacity is available.
- **2.** **DPS(2)**
  - **(1)** The requirements of **Par 1** above are to be complied with.
  - **(2)** In the event of a failure of the working system the standby control system is to be arranged to changeover automatically without manual intervention and without any adverse effect on the ship's station keeping performance.
  - **(3)** The power system is to be divisible into two or more systems such that in the event of failure of one system at least one other system will provide enough power for essential services of the DP operation. The power system may be run as one system during operation, but is to be arranged by bus-tie breakers to separate automatically upon failures which could be transferred from one system to another, including overloading and short-circuits. **【See Guidance】**
  - **(4)** The power available for position keeping shall be sufficient to maintain the vessel in position after worst-case failure according to **101. 3**.
  - **(5)** At least one automatic power management system (PMS) shall be provided and shall have redundancy according to the equipment class and a blackout prevention function.
  - **(6)** For electrically driven thruster units, the following requirements are to be complied with: *(2019)*
    - **(A)** With one generating set out of action, the capacity of the remaining generating sets is to be not less than the maximum DP load with the most effective thruster inoperative together with all electrical auxiliary services necessary for maintaining the ship in normal operational and habitable conditions.
    - **(B)** Where generating sets are arranged to operate in parallel, the supplies to, essential services are to be protected by the tripping of non-essential loads as required by **Pt 6, Ch 1, 205. 10** and additionally, on loss of a running generating set, a reduction in thrust demand may be accepted provided the, arrangements are such that a sufficient level of DP capability is retained to permit the maneuverability of the ship.
    - **(C)** In relation to (A) and (B), in order not to loss of position, provision is to be made for automatic starting synchronization and load sharing of a non-running generator before the load reaches the alarm level required by **202. 1** (5). *(2024)*
  - **(7)** Control, alarm and safety systems are to incorporate a computer based consequence analysis which may be continuous or at predetermined intervals and is to analyse the consequence of predetermined failures to verify that position and heading deviation remain within acceptable limits. In the event of a possible hazardous condition that is not possible to keep ship's position and heading in current climatic condition because of expected worst case failure being indicated from the consequence analysis an alarm is to be initiated.
  - **(8)** Power, control and thruster systems and other systems necessary for, or which could affect, the correct functioning of the DP system are to be provided and configured such that a fault in any active component or system will not result in a loss position. This is to be verified by means of a FMEA according to (KS A) IEC 60812 (Failure Mode and Effects Analysis) or equivalent. Active components may include, but are not restricted to, the following
    System which are not part of the DP System but which, in the event of a fault, could affect the correct functioning of the DP System (for example, fire suppression systems, engine ventilation systems, etc.) are to be included in the FMEA.
    - **(A)** Prime movers (e.g. auxiliary engines)
    - **(B)** Generators and their excitation equipment
    - **(C)** Gearing
    - **(D)** Pumps
    - **(E)** Fans
    - **(F)** Switchgear and control gear, including their assemblies **【See Guidance】**
    - **(G)** Thrusters
    - **(H)** Valves (where power actuated)
- **3.** **DPS(3)**
  - **(1)** The requirements of **Par 2** above are to be complied with.
  - **(2)** The power system arrangement is to comply with the following requirements :
    - **(A)** For DPS(3), the power system shall be divisible into two or more systems so that, in the event of failure of one system, at least one other system will remain in operation and provide sufficient power for station keeping. The divided power system is to be located in different spaces separated by A-60 class divisions.
    - **(B)** Where the power systems are located below the operational waterline, each power system is to be separated by independent watertight compartment.
    - **(C)** Bus-tie breakers are to be open during DPS operations unless it can be accepted according to **203. 2** (3).
  - **(3)** The electrical power generating sets are to be arranged so that they are located in at least two separate machinery compartments.
  - **(4)** The switchboard supplying the DP system is to be split into at least two equal sections each fitted in a separate compartment and capable of being connected by bus section switches.
  - **(5)** The control and indication unit of one of the position reference systems required by the **Table 9.4.1** is to be located at the emergency control station. A repeater control and indication unit from this system is to be located at the main control station.
  - **(6)** An independent heading reference system among those required by **Table 9.4.1** is to be located at the emergency control station to provide heading reference to the emergency automatic control system.
  - **(7)** Signals from the environmental sensors required by **Table 9.4.1** are to supply the backup DP control system.
  - **(8)** The backup DP control system is to be supplied from its own independent uninterruptible power supplies.
  - **(9)** Cables for redundant equipment or systems are not to be routed together through the same compartments. Where this is unavoidable such cables could run together in cable ducts of A-60 class, the termination of the ducts included, which are effectively protected from all fire hazards, except that represented by the cables themselves. Cable connection boxes are not allowed in such ducts.


### Section 3 Testing and Inspection

#### 301. Hydraulic Test

Thruster housing is to be tested at a hydraulic pressure of not less than 1.5 times the maximum service immersion head of water or 1.5 bar, whichever is greater.

#### 302. On-board tests

After installation on board, the DP system is to be tested under the condition as close to the actual operation as practicable and confirmed that each equipment functions appropriately. However, the tests may be carried out at the sea trial, when their testing items are considered impracticable to be conducted at occasions other than the sea trials.

#### 303. Sea trials

In the sea trials, performance tests of the DP system are to be carried out in accordance with the sea trial schedule including the followings approved by the Society.
- location of area of operation
- heading of the ship.

#### 304. Maintaining records and data regarding the performance capability of the DP system

Records and data regarding the performance capability of the DP system are to be maintained on board the ship and are to be made available at the time of the periodical survey.

#### 305. Survey Assigned to Maintain Classification

Periodical survey interval and survey items of DP systems are to be applied as follows.

- **1.** **Annual survey**
  - **(1)** System maintenance documentation, including information regarding hardware and software changes, is to be reviewed.
  - **(2)** The electrical installations comprising the DP systems, such as controllers and for DP control station and independent joystick, references systems, sensors and mode change system, are to be visually inspected.
  - **(3)** The technical condition of the DP systems is to be verified during the survey.
  - **(4)** If the survey is carried out when the vessel is undergoing regular operations, then tests that possibly can introduce unacceptable risks are not to be performed.
  - **(5)** Capacity of UPS and other battery systems serving the DP control system, including its peripherals, are to be verified. If the survey is carried out during regular operations, then the capacity of the batteries need not be proven by testing. Additionally, the alarm for loss of charging power is to be verified.
  - **(6)** For DPS(3), normal working condition of the backup DP control system is to be verified. If the survey is carried out during regular operations, then control need not be transferred to the backup DP control system.
  - **(7)** Emergency stop of thrusters from the DP control station is to be tested. If the survey is carried out when the vessel is undergoing regular operations, then testing is not to be performed if there is any possibility of introducing unacceptable risks.
- **2.** **Special survey**
  - **(1)** With the vessel in DP mode, a sea trial is to be performed.
  - **(2)** The complete system is to be tested in all operational modes. The testing is to include simulation of different failure conditions to verify switching of modes, back-up systems and the alarm system.
  - **(3)** The different modes of thruster control from the DP control station are to be tested.
    - **(A)** Manual control
    - **(B)** Joystick control(independent joystick, if installed)
    - **(C)** DP control
    - **(D)** Transfer of control
  - **(4)** Manual override i.e. by thruster lever control and independent joystick control is to be demonstrated during normal operation and during failure conditions.
  - **(5)** Emergency stop of DP thrusters from DP control station is to be tested.
  - **(6)** All sensors, peripheral equipment and reference systems are to be tested.
    - **(A)** Verify correct operation and adequate accuracy
    - **(B)** Failure of sensors and reference systems is to be simulated to check the alarm system and the switching logic
    - **(C)** Switch-over between reference systems as input to controller is to be carried out to assure that warnings, alarms and information to operator are satisfactory.
  - **(7)** Alarm for loss of position and heading out of limit is to be demonstrated.
  - **(8)** The electrical installations comprising the DP systems, such as controllers and DP control stations and independent joystick, references systems, sensors and mode change system, are to be visually inspected.
  - **(9)** Single failures in thruster control systems including signal wire breaks of thruster command and feedback signals are to be tested in order to verify safe response on the thrust output. Equivalent testing may also be required for rudders controlled by the DP control system.
  - **(10)** Overload prevention is to be tested.
  - **(11)** Capacity of UPS and other battery systems serving the DP control system, including its peripherals, are to be verified by testing. Alarm for loss of charging power is also to be verified.
  - **(12)** For DPS(2) & DPS(3), the required redundancy with respect to defined single failures modes is to be verified by redundancy testing.
  - **(13)** For DPS(2) & DPS(3), the FMEA report and FMEA test program are to be verified to ensure that they have been updated when alterations have been done.
  - **(14)** For DPS(2) & DPS(3), correct functioning of the Consequence Analysis facility is to be verified as far as possible.
  - **(15)** For DPS(3), testing is also to be performed on the backup DP control system. Switchover to back-up is to be tested, and monitoring of backup control system status on the main control system is to be verified. ![](images/image3.png)
