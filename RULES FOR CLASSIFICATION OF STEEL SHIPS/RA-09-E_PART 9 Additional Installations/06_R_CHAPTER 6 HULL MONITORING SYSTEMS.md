# PART 9 Additional Installations

> RULES FOR CLASSIFICATION OF STEEL SHIPS / RA-09-E / 2025 / EN / Rules

## CHAPTER 6 HULL MONITORING SYSTEMS

### Section 1 General

#### 101. Definition

Hull monitoring system (hereinafter referred to as "systems") are to monitor a behavior of hull girder during navigation, loading and unloading, and to provide real-time information on stress level due to longitudinal bending moment and acceleration level due to ship's motion. The systems will give warning when stress levels and acceleration of ship motions approach levels which require corrective action.

#### 102. General

- **1.** Application:
  The requirements in this Chapter apply for a ship that the class notations assigned to the hull monitoring system to be classed or intended to be classed with the Society.
- **2.** Class notations, HMS: *(2023)*
  Ships equipped with monitoring systems in **Sec. 2 202.** are designated with HMS notation. If sensors and/or functional devices of **Sec. 2 203**. are added to the HMS system, the qualifiers specified in **Table 6.1.1** should be added. (Ex. HMS(G,W, SD,...)
- **3.** Liability:
  This system is intended as an aid to the Master's judgement and not as a substitute for it. Accordingly, any failure of the system does not, in anyway, remove the master from his/her absolute responsibility to take correct action in operation the ship.

#### 103. Information and Plans

The following plans and information are to be submitted or approval:
- arrangement and layout of the system
- block diagram of the electric system
- flowchart of functions of sensors and the system
- list of instruments and equipment (name, kind, type, manufacturer, etc.)
- operating manual including procedures of maintenance, fault detection and management ad setting up and calibration
- in-service test program
- list of software modules and the description of the calculation method
- sensor specifications (accuracy, range, frequency response, etc.)
- description of the method to display the output


### Section 2 System Requirements

#### 201. General

All components are to be replaceable and designed for easy maintenance. Sensors are to be approved by this Society or to be approved by the other recognized organization.

#### 202. Requirements for HMS

- **1.** **Sensors**
  - **(1)** Long based strain gauge
    - 2 at midship (one port, one starboard on deck)
    - 1 at L/4 from the bow(on deck)
    - 1 at L/4 from the stern(on deck)
    - 4 at midship in a ring around the section(two port, two starboard; on deck and upper turn of bilge)
    - 1 at L/4 from the bow(on deck)
    - 1 at L/4 from the stern(on deck)
    - **(A)** Each long strain gauge is instrument for measure the longitudinal bending stress of ship. It is to be able to measure the strain which is characteristic for the structural response considered.
    - **(B)** The type and installation are in general to exclude the effects of local stress concentrations. The length of the long based strain gauge is recommended to be between 1.5 $\mathrm{m}$ and 2.5 $\mathrm{m}$.
    - **(C)** The position of the long based strain gauge is to be planned to measure longitudinal hull girder bending stress. The minimum required number and approximate position of the strain gauges are as follows:
      - **(a)** Tankers, Bulk Carriers and General dry cargo ships:
      - **(b)** Container ship :
    - **(D)** Strain gauges are to have an accuracy better than ±20 $\mathrm{\mu} \epsilon$. The linear range of each strain gauge is to be in excess of the full range of expected still water and dynamic stress variation. For dynamic stress range each strain gauge is to have a frequency response capable of measuring strain in the frequency range 0 to 5 $\mathrm{Hz}$*.*
    - **(E)** When measuring longitudinal bending stresses of ship and corresponding loads the effects of temperature variations due to the daily environmental changes are to be considered. If possible, these effects are to be removed from any display of still water loading.
  - **(2)** Accelerometer
    - **(A)** The vertical acceleration is to be measured on the centerline, at the main deck level within the forward 0.01 $\mathrm{L}$ of the ship.
    - **(B)** Accelerations are to be measured over a range of ±1 g. The measurement uncertainty of the acceleration is to be less than 1 % of the measured value in the frequency range of 0 to 5 $\mathrm{Hz}$*.*
  - **(3)** Pressure Transducer
    - **(A)** If possible, the pressure transducers may be installed to measure the number of slam.
    - **(B)** Pressure gauge where fitted through the hull are to be arranged so that the pressure diaphragm is flush with the outside of the plating. The gauge is to be arranged with a suitable valve to enable the gauge to be removed and refitted with the vessel in the water at an operational draft.
  - **(4)** Clinometer
    In order to measure the motion characteristics, the clinometer may be installed.
  - **(5)** Thermal loads due to cargo temperatures are to be considered separately. Consideration as to whether or not the thermal loads should be included in the still water or water loads are to be determined when taking into account the type of vessel and cargo and the approved ship's scantlings and their conditions of approval. (The data of calculation were to be submitted of the Society.) *(2023)*
- **2.** **Date Processing and Output Display**
  - **(1)** Display and alarm devices
    - the peak value of the longitudinal hull girder bending stress or vertical acceleration
    - the mean value of the longitudinal hull girder bending stress or vertical acceleration
    - the standard deviation of the longitudinal hull girder bending stress or vertical acceleration
    - **(A)** The hull monitoring system is to be able to provide real-time information to the bridge of the measured values while at sea and during loading and unloading operations. The system is to be able to record and display the following sets of data for each strain gauge and accelerometer:
    - **(B)** The system is to include a computer that can process sensor signals and compare these with threshold levels approved by the Society. When values exceed these pre-set threshold values, the system is to give visual and audible alarm on the bridge.
    - **(C)** In order to verify intermediate and final stages of loading and unloading operations, the hull monitoring system is to have a direct link or easy connection to the loading computer.
    - **(D)** Each update of the display is to be based on statistics of the recorded data within 30 minutes interval. The sensor readings are to be displayed in a manner that enables the trends in the data over at least the last 1 hours to be seen.
    - **(E)** The number of acceleration peak exceeding a pre-set acceleration level, which indicates a slam in the bow are to be recorded and displayed. The pre-set acceleration level is to be reported.
    - **(F)** The recordings from strain sensors are to be processed using a type of cycle count method (e. g. "rain flow" method) to produce response histogram. The stress spectra may be used as basis for fatigue life predictions. The size of strain interval is not to exceed 50 $\mathrm{\mu} \varepsilon$. The cycle count method is to be reported and submitted.
  - **(2)** Signal processing
    - **(A)** The sampling rates are to be suitable for the frequency response of the transducer and the use of the signal. In general the sampling rate is not to be less than 3 times the required frequency response. Special attention is to be paid to the sampling rate if it is intended to capture transient components of signals.
    - **(B)** The measured signal induced by wave is to be statistically calculated with the time interval of between 5 minutes and 30 minutes.
- **3.** **Storage device**
  - **(1)** For the purpose of verifying that all sensors are working under sea-going conditions the system is to have a minimum recording capability. This requires that a semi-permanent data storage medium is to be used to record, at least once per month and the following information processed over a period of 5 minutes.
    - maximum peak to peak value of stress/acceleration
    - mean value of stress/acceleration
    - standard deviation of stress/acceleration
    - average zero crossing period of stress/acceleration
    - time reference
  - **(2)** Automatic post-processing of data on-board or ashore is to be available on shore or on the vessel to enable the data to be evaluated. Proposals will be considered for recording to be replaced by sending the data ashore via satellite on a regular basis. Recorded data and evaluated result are to be regularly submitted to the Society every year. *(2023)*
  - **(3)** Where manual input, for example via a computer keyboard, is used, the input procedures are to be included in the operating manual and are to be submitted for review. This data is to be checked regularly against the criteria described in the checking procedure.

#### 203. Additional requirement for HMS (2023)

The equipment that measures the following information should be connected to the monitoring device to output and store the information.

- **1.** **Navigational information**
  The system should be possible to acquire information from GPS (ship position, route and speed), record of speed through specific sea area and gyro-compass information for heading and motions like roll and pitch angle, etc.
- **2.** **Wind speed and direction**
  The system is to indicate the wind speed and direction provided by wind speed indicator and anemoscope.
- **3.** **Ship speed and direction**
  The system is to indicate the real-time information of ship speed and direction provided by GPS and speed and distance indicator onboard.
- **4.** **Sea state**
  The system should be possible to obtain sea state information using x-band navigational radar or sensors.
- **5.** **Engine output**
  As a ship with UMA notation, it should be possible to monitor various information in the machinery space, such as the output/rpm of the propulsion shaft, from the bridge.
- **6.** **Local hull strain**
  The system should be possible to monitor local hull strains.

  | **Item** | **Description** |
  | --- | --- |
  | **G** | Sensor for location tracking (GPS) (203.1) |
  | **W** | Sensor for monitoring wind speed and wind heading (203.2) |
  | **SD** | Sensor for monitoring ship speed and direction (203.3) |
  | **S** | System for acquiring sea state information (203.4) |
  | **U** | As a ship with UMA notation, system for monitoring information in the machinery space, such as the output/rpm of the propulsion shaft (203.5) |
  | **LS** | Sensors for monitoring local hull strain (203.6) |

#### 204. Electrical and mechanical equipment (2023)

- **1.** **Flame proof**
  All electrical and mechanical equipments associated with the hull monitoring system located in hazardous areas is to be in accordance with the requirements in **Pt 7, Ch 1, Ch 5** and **Ch 6.**
- **2.** **Uninterruptible Power Supply (UPS)**
  - **(1)** The monitoring system is to be powered through an Uninterruptible Power Supply (UPS).
  - **(2)** In case of failure of the main input voltage the battery capacity is to be sufficient to maintain normal operation of the monitoring system for at least 10 minutes. Failure of any power supply to the system is to initiate an audible and visual alarm.
  - **(3)** In the case of power failure the system software and recorded date is stored safely. The system is to be able to return automatically to normal operating condition when the power is restored.


### Section 3 Approval for Plans and Documents, Installation and Installation Survey

#### 301. Approval for plans and documents

Instruction manuals are to be described in relevant language and kept on board. The manuals are to contain necessary instructions on:
- instruction of system
- interpretation of measuring results
- systematic maintenance and function testing
- identification of faults and repairs
- procedures of installation
- procedures of initial calibration and checking
- checking procedure
- components list
The plan for systematic maintenance and function testing is to show how components and systems are to be tested and what is to be observed during the tests. The procedure is to describe how to check the normal operation of the signal acquisition and analysis and display. The check list of checking procedure is to be included in instruction manuals.

#### 302. Installation

- **1.** **General:**
  Information on how to initialize the sensors is to be verified by the Society. The system is to be installed with attendance of a surveyor.
- **2.** **Installation of the sensors**
  - **(1)** Sensors are to be protected from mechanical damage, humidity by the sea water, effects of very high and low temperature and damage due to local vibration.
  - **(2)** Sensors mounted on deck of the ship are to be protected from heavy sea condition. For container ship, the system is to be located in the safety area where it is not disturb to remove/install the dropped container securing appliances during loading/unloading operation.
  - **(3)** Deck mounted strain gauge is to be protected from green sea on deck by appropriate siting of by using substantially constructed breakwaters or similar means. Attention is to be paid to the possibility of green water damage to other gauge, junction boxes, cable conduits, etc.
  - **(4)** Motion sensors to measure motions are to be placed in positions where their functioning will not be affected by vibrations. Accelerometers and motion monitoring devices are to be mounted on a hard structural point where local structural vibration will be minimal. If resilient mounts are used, it is to be demonstrated that they have frequency characteristics that do not affect the signal in the frequency range of interest.
  - **(5)** When gauges are welded to the hull welding procedures are to comply with Class Rules of the Society. Consideration is to be given to the damage and repair of coatings.
  - **(6)** Pressure gauges where fitted through the hull are to be constructed in accordance with the Class Rules of the Society.

#### 303. Installation survey

- **1.** **Initial calibration and test**
  - **(1)** Initial calibration
    - **(A)** Each long based strain gauge is to be initially set to a stress calculated in an associated loading condition.
    - **(B)** This calculated stress is to be compatible with the output of the loading instrument and calculations made using the loading manual. The set-up is not to be carried out when dynamic stresses are present and are to be made when temperature effects are minimized and in absence of large gradients due to loading condition. In the case of measuring local stresses the sensor stress is to be set to the stress calculated through the detailed structural analysis.
    - **(C)** Also, the motion measuring device is to be set according to the ship condition.
  - **(2)** Checking of the initialized value
    - **(A)** After installation, the initial set-up of each long strain gauge is to be checked at least one time within 6 months.
    - **(B)** This is to be undertaken by the ships operating personnel taking the relevant values from the Loading Instrument and the Hull Condition Monitor in accordance with the Verification Procedure and submitting them to the Surveyor.
    - **(C)** In the event that differences greater than 10 % of the calculated value occur, the set-up and subsequent checking procedure are to be repeated.
- **3.** **Sensor re-calibration**
  Each strain gauge is to be re-calibrated annually in accordance with the manufacturer's recommendations. The certificates of calibration, signed by an authorized person, are to be kept onboard the ship.
- **4.** **Other survey**
  In the case of set-up sensor on exposed deck, to be carried out hose test according to **Pt 3, Ch 1, Sec 2.**


### Section 4 Periodical Survey

#### 401. General

Periodical survey for the systems is to be carried out at the time of Annual/Intermediate/Special Survey specified in **Pt 1, Ch 2.**

#### 402. Survey items

The general conditions of electrical, mechanical and hazardous area equipment are to be carried out so far as practicable on hull monitoring systems, with special attention being paid to the following;

- **1.** The verification of location of sensors.
- **2.** The operation of the system is to be verified in accordance with the approved verification procedure.
- **3.** Current calibration certificates for the sensors and Operating Manual is to be established on board.
- **4.** The protection of sensors is to be inspected. ![](images/image3.png)
