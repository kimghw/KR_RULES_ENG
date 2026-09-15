# Guidance for Smart Systems

> OTHER RULES AND GUIDANCE / GC-41-E / 2025 / EN / Guidance

## CHAPTER 3 FUNCTIONAL REQUIREMENTS FOR SMART SYSTEMS

### Section 1 Smart Infrastructure

#### 101. General

- **1.** The purpose of smart infrastructure is to perform smart system functions through hardware and software installed to implement smart system functions.
- **2.** The smart infrastructure includes the necessary components to collect, manage and relay data.
- **3.** The smart infrastructure shall be capable of collecting and storing information received from one or more source systems.
- **4.** The smart infrastructure shall meet the relevant requirements for data quality management in this guidance.
- **5.** Electrical and electronic equipment on the bridge shall be installed so that electromagnetic interference does not affect the proper function of navigational systems and equipment.
- **6.** Screen displays and indications installed on the bridge shall be installed so as not to obstruct the navigator’s view even at night. *(2024)*

#### 102. Configuration and functional requirements of smart systems

The infrastructure for implementing the functions of a smart system may include the following configurations and functions, but is not limited to.

- **1.** Sensor for smart system functions
  - **(1)** Internal and external data are received through sensors installed to implement smart system functions.
  - **(2)** Hardware and software installed to interface with the on-board system shall have the following functions:
    - **(A)** Data interface to support certain number and type of input/output channels;
    - **(B)** Configurable and expandable input/output channels, in terms of number and type of channels;
    - **(C)** Connection to the data network and communication function when smart system function is implemented;
    - **(D)** Time stamping and time synchronization for the data collected; and
    - **(E)** Monitoring and alarming for data transmission
- **2.** Interface to on-board system
  - **(1)** The interface to on-board system is to access and retrieve data from other on-board systems, such as monitoring, control and automation systems for the smart system function.
  - **(2)** Hardware and software installed for interface with the on-board system shall have the following functions:
    - **(A)** Data interface to support certain number and type of input/output channels ;
    - **(B)** Configurable and expandable input/output channels, in terms of number and type of channels;
    - **(C)** Connection to the data network and communication function when smart system function is implemented;
    - **(D)** Time stamping and time synchronization for the data collected;
    - **(E)** Monitoring and alarming for data transmission; and
    - **(F)** Safeguard for potential error propagation to the interfaced on-board systems
- **3.** Data Network and Communication
  - **(1)** Network and communication-related hardware and software installed to transmit data shall have the following functions:
    - **(A)** Prewired or wireless on-board data network to access specific data interface locations, such as navigation bridge and engine control room;
    - **(B)** Use of recognized data communication protocols;
    - **(C)** Communication volume and network load monitoring; and
    - **(D)** Two-way communication between the ship and onshore (if applicable)

#### 103. Data-related requirements for smart systems

- **1.** **Data model**
  - **(1)** The smart infrastructure shall be able to define an information model as an organization of tags in graphs or hierarchies that reflect relationships between the tags.
  - **(2)** For data extraction, a unique tag defined in each component of the smart infrastructure server shall be provided.
  - **(3)** The on-board smart system server shall be able to clearly distinguish between identical tags from connected data source systems.
  - **(4)** Remote data servers shall be able to distinguish identical tags from separate connected ship’s servers.
  - **(5)** Ship’s servers and remote data servers in the smart infrastructure shall be capable of maintaining metadata for each tag.
- **2.** **Data capacity**
  - **(1)** Smart infrastructure shall provide the following data capacity and functions:
    - **(A)** Expandable and scalable data storage capacity;
    - **(B)** Data backup and data recovery capacity;
    - **(C)** Data storage capacity and usage monitoring and alarming; and
    - **(D)** Time synchronization among all connected data sources
  - **(2)** All components in smart infrastructure shall have mechanisms to restrict user access through an administration interface.
- **3.** **Data communication**
  - **(1)** The ship's server shall be able to receive data from many source systems.
  - **(2)** The remote data server shall be able to receive data from many ship's servers.
  - **(3)** The smart infrastructure shall define a delay transfer, measured as the time it takes from when a value changes in a source system to when the change in value is reflected to ship’s servers and remote data servers. local and remote data consumers.
- **4.** **Data change and backup**
  - **(1)** It shall be possible to perform backup of the system configuration and the data storage on the ship’s server and on the remote data server.
  - **(2)** Defined procedure shall be in place for how to restore backups.
  - **(3)** The smart infrastructure shall maintain an audit trail of changes to the system. This includes changes to the system configuration settings, changes made to information models, metadata and manual changes made to the raw values being collected through the infrastructure.
  - **(4)** There shall be a recovery mechanism to automatically reset the links when the data communication link or associated hardware offline.
  - **(5)** There shall be a recovery mechanism for buffered data to avoid data loss in the remote data server.


### Section 2 Structural Health Monitoring (SHM)

#### 201. General

- **1.** The objective of Structural Health Monitoring(hereinafter referred to as “SHM”) function is to assess and predict structural damage and provide decision-making support on safer and more optimal ship operation, inspection and repairs, and asset integrity management.
- **2.** The SHM function uses data acquired from existing sensors installed on-board or from sensors installed separately for SHM functions.
- **3.** The SHM function enables structural integrity analysis and potential structural damage prediction based on the ship's data on the marine environment, ship operation, operating loads and recent structural condition.

#### 202. Interface with on-board systems

- **1.** **Hull monitoring system**
  - **(1)** In case of using the hull monitoring system for the SHM function, the relevant requirements in Pt 9, Ch 6 of Rules for the Classification of Steel Ships are to be satisfied.

#### 203. Functional requirements

The smart system functions for SHM described in this Guidance are as follows, but the SHM function is not limited to the following items and may be adjusted according to agreement between the ship owner and the system developer or shipyard.

- **1.** Data collection and storage
  - **(1)** In order to implement the ship's SHM function, the following data may be considered, but not limited to:
    - **(A)** Marine environment data
    - **(B)** History of cargo and other payload
    - **(C)** Operational data: vessel speed, heading, draft, trim, etc.
  - **(2)** The smart system shall be able to periodically receive and store the data of (1), and the reception period and storage period can be set according to the operating environment.
  - **(3)** The load of the wave can be directly acquired through on-board measurements or obtained from meteorological data obtained through the past ship's route or location history.
- **2.** Data Analysis
  - **(1)** The following data may be considered for the SHM and analysis of ships.
    - **(A)** Data in 1 (1)
    - **(B)** Up-to-date structural health data
    - **(C)** Finite Element(FE) based or other physics-based or data-driven analytics using the vessel-specific operations and up-to-date structural conditions.
- **3.** **D**ecision-making support function
  - **(1)** In order to implement the decision-making support function of the smart system, sensors shall be installed according to the ship’s operating environment.
  - **(2)** The smart system can be utilized for decision-making support depending on the ship's working environment, such as:
    - **(A)** When an alarm is activated for parameters such as hull structural stress, ship motion and acceleration, bow slamming pressure and tank sloshing pressure during navigation, the smart system shall be able to provide support for whether or not to change route and speed by performing calculations, analysis and evaluation of:
      - **(a)** Current sea conditions
      - **(b)** Ship's route and speed
    - **(B)** In case of exceeding the limit in relation to hull structural stress during loading and unloading at the port, whether to continue loading and unloading, adjustment of loading and unloading of cargo tanks, and adjustment of loading and unloading speed
    - **(C)** Decision-making support functions may be added according to the actual ship's working environment and safety requirements.
- **4.** Data communication
  - **(1)** Data provided by the SHM function shall be available from designated locations on-board or ashore.


### Section 3 Machinery Health Monitoring (MHM)

#### 301. General

- **1.** The purpose of Machinery Health Monitoring(hereinafter referred to as “MHM”) function is to provide improved awareness of the health and operating conditions of machinery and systems installed on-board.
- **2.** The MHM function can support ship owners' decision-making for safer and more reliable operation, maintenance planning and integrity management.
- **3.** The MHM function uses data acquired from existing sensors installed on-board or from sensors installed separately for MHM functions.

#### 302. Functional requirements

The smart system functions for MHM described in these guidance are as follows, but the MHM function is not limited to the following items and may be adjusted according to agreement between the ship owner and the system developer or shipyard.

- **1.** Data collection and storage
  - **(1)** In order to implement the ship's MHM function, the following data may be considered, but not limited to:
    - **(A)** Monitoring of engine combustion condition
    - **(B)** Monitoring of engine cylinder related parts
    - **(C)** Monitoring of machinery and system related parameters
    - **(D)** Alarms on abnormalities in monitored parameters
  - **(2)** The smart system shall be able to periodically receive and store the data of (1), and the reception period and storage period can be set according to the operating environment.
  - **(3)** In order to implement the MHM function, data from existing automation system can be utilized.
- **2.** Data Analysis
  - **(1)** The following data may be considered for the MHM and analysis of ships.
    - **(A)** Data in 1 (1)
    - **(B)** Up-to-date machinery health data
    - **(C)** Physics-based or data-driven analytics using the vessel-specific operations and up-to-date machinery conditions.
- **3.** **D**ecision-making support function
  - **(1)** In order to implement the decision-making support function of the smart system, sensors shall be installed according to the ship’s operating environment.
  - **(2)** The smart system may be utilized for decision-making support depending on the ship's working environment, such as:
    - **(A)** Monitoring, anomaly detection, and diagnostics of machinery or systems in normal operational modes
    - **(B)** Diagnosis of single faults that may lead to total system failure
    - **(C)** Decision-making support functions may be added according to the actual ship's working environment and safety requirements.
- **4.** Data communication
  - **(1)** Data provided by the MHM function shall be available from designated locations on-board or ashore.


### Section 4 Energy Efficiency Management (EEM)

#### 401. General

- **1.** Smart system functions for energy efficiency management can help plan to optimize the ship's route and speed by monitoring the ship's operational status, energy efficiency and energy consumption status, weather and marine environment data, etc.
- **2.** For ships equipped with smart system functions such as voyage information, ship operation data and energy consumption monitoring, Smart(EEM) notation can be assigned.
- **3.** The information and data in 2 above can be monitored on-board or on land, and can be used to review ship performance management, navigation plan establishment, ship operation management, and maintenance plan.
- **4.** All data, including energy consumption monitoring, are to be available at designated locations on-board or on land.
- **5.** Enhancements to Energy efficiency management may include functions that support for energy-efficient route planning and trim optimization together with route characteristics and weather and marine information.

#### 402. Functional requirements

- **1.** **Interface with on-board systems**
  - **(1)** Smart system functions for energy efficiency management can generally be implemented through interfaces with the following equipment, but not limited to:
    - **(A)** BMS (Bridge maneuvering systems)
    - **(B)** AMS (Alarm and monitoring systems)
    - **(C)** SPM (Shaft power meter)
    - **(D)** VDR (Voyage data recorder)
    - **(E)** Flowmeter
    - **(F)** Anemometer
- **2.** **Data collection, transmission and storage**
  - **(1)** The following parameters may be considered for smart system functions for energy efficiency management, but not limited to:
    - **(A)** Fuel oil consumption of main energy consuming equipment
    - **(B)** Power, pressure and temperature of main energy consuming equipment
    - **(C)** Shaft power of main engine
    - **(D)** Ship’s position, course and speed
    - **(E)** Wind speed and direction
  - **(2)** The smart system shall be able to periodically receive and store the data in (1), and the reception period and storage period can be set according to the operating environment.
- **3.** **Data analysis**
  - **(1)** Smart systems shall be able to automatically calculate fuel consumption and emission factors such as:
    - **(A)** Fuel oil consumption per day of major energy consuming equipment
    - **(B)** Fuel oil consumption per voyage of major energy consuming equipment
    - **(C)** CO2 emissions
- **4.** **Utilization of data**
  - **(1)** The smart system can be utilized for ship operation by providing the following functions, if applicable.
    - **(A)** Data recording for engine power limit(EPL) or shaft power limit(ShaPoLi)
    - **(B)** Annual efficiency ratio(AER) monitoring to estimate Carbon intensity indicator(CII)
    - **(C)** Data recording for BMS, AMS, SPM and VDR
    - **(D)** Operational report


### Section 5 Intelligent Navigation

#### 501. General

- **1.** The intelligent navigation function supports operators to reduce human error and ensure safe and comfortable navigation by providing navigation related information or automating navigation tasks.
- **2.** The intelligent navigation system can obtain navigation-related information from smart infrastructure and use it to set an economical route.
- **3.** The decision to use an intelligent navigation system is determined by considering visibility and environmental conditions.
- **4.** Even if an intelligent navigation system is used, a navigational watch shall be maintained for the safe operation of the ship.

#### 502. Functional requirements

- **1.** **Interface with on-board systems**
  - **(1)** Smart system functions for intelligent navigation can generally be implemented through interfaces with the following equipment, but not limited to:
    - **(A)** VDR
    - **(B)** Radar
    - **(C)** ECDIS
- **2.** **Marine environment**
  - **(1)** The impact of information collection due to weather changes at sea, such as heavy snowfall/heavy rain and lightning, should be minimized, and the following measures can be considered.
    - **(A)** Periodic maintenance for cameras
    - **(B)** Install a thermal imaging camera or infrared camera
  - **(2)** The following countermeasures can be considered in situations where visibility is restricted, such as fog or night operation. For the use of intelligent navigation functions at night, on-board safety management procedures are followed.
    - **(A)** keep a navigational watch
    - **(B)** Install a thermal imaging camera or infrared camera
  - **(3)** Countermeasures according to (1) and (2) can be considered when the maritime environment changes, but if the maritime environment changes affect the function of the intelligent navigation system, the autonomous navigation function must be limited.
- **3.** **Equipment and systems**
  - **(1)** Sensor status is to be monitored and an alarm is to be issued in case of sensor failure.
  - **(2)** Periodic maintenance is required to minimize the occurrence of camera function failure or image sensor error (data is different).
  - **(3)** In order to recognize objects due to work near the ship's route, information on work near the route is to be checked before using the intelligent navigation system. ![](images/image3.png)
