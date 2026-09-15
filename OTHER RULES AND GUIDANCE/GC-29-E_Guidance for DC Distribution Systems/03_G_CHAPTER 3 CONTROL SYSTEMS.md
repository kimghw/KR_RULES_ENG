# Guidance for DC Distribution Systems

> OTHER RULES AND GUIDANCE / GC-29-E / 2025 / EN / Guidance

## CHAPTER 3 CONTROL SYSTEMS

### Section 1 General

#### 101. General

- **1.** All control systems applicable to DC distribution systems are to comply with the requirements in **Pt 6, Ch 2** of the **Rules for the Classification of Steel Ships**.
- **2.** The control system shall consist of the following control and alarm functions.
  - **(1)** Monitoring of all power sources and inverters and disconnectors for the distribution system
  - **(2)** Alarm functions for all power sources and inverters and disconnectors for the distribution system
  - **(3)** Active control of power sources and distribution system
  - **(4)** Voltage and power control for DC distribution system
  - **(5)** Available power control depending on state of charge (if applicable)
  - **(6)** Charge and discharge control (if applicable)
  - **(7)** Power management system (PMS) functions for a DC distribution system
  - **(8)** Interface with energy storage management systems (if applicable)
  - **(9)** Interface with PMS for combinations of AC and DC distribution systems (if applicable)
  - **(10)** Inverter control for the overall system stability
  - **(11)** Interconnection to alert system or integrated automation system. The alert functions will be classified and presented according to the instructions given in MSC.302 (87).


### Section 2 System Design

#### 201. Power management system(PMS)

- **1.** **General**
  - **(1)** Automatic control systems for power production and distribution may include following functions.
    - **(A)** Automatic starting of a power source
    - **(B)** Automatic connecting onto a dead bus bar
    - **(C)** Automatic paralleling and load sharing
    - **(D)** Automatic shut-down of power source
    - **(E)** Automatic disconnecting of non-essential loads
    - **(F)** Automatic analysis of power reserve
  - **(2)** Commands for automatic starting of power management system may be given, for example, by
    - **(A)** No voltage (blackout),
    - **(B)** Prolonged voltage drop
    - **(C)** Prolonged frequency drop
    - **(D)** Emergency alarms
    - **(E)** Expected stop of running set
    - **(F)** Overload
    - **(G)** Increase of power demand
    - **(H)** Start signal for large electric power consumer(s), for example transverse thruster motor
    - **(I)** Remote manual means in case of failure of the equipment in operation
- **2.** **Start of Power Source**
  - **(1)** If more than one power source is fitted with automatic starting devices, there shall be installed a sequence system, which, in case of failing to start after three start attempts, automatically transfers the start-command to the next power source or a selector switch for manual use.
  - **(2)** Stand-by indication shall be arranged for indication. The automatic starting and running of a power source shall be indicated. Starting failure of a power source shall give an alert.
  - **(3)** Reconnection of DC power sources shall be done automatically according to the sequence set by the power management system.
- **3.** **Load sharing**
  - **(1)** Load sharing of different power sources may be performed by a separate control system or by the power management system. The available power for each power source may be a static or a dynamic value depending on the speed, state of charge or other characteristics of the power source.
  - **(2)** The load sharing shall be based on the ability for the different power sources to handle load variations and transients.
  - **(3)** Available power is a static value based on the rating of the power source.
  - **(4)** Load sharing may be done based on a DC droop function or other control means. Stable load sharing function shall be provided.
  - **(5)** Power sources such as batteries, shall be defined for its maximum available power for discharge and charge.
  - **(6)** Charging functions shall be implemented in the power management system and shall not interfere with the ability to deliver power as defined in the available power signal. ![](images/image3.png)
