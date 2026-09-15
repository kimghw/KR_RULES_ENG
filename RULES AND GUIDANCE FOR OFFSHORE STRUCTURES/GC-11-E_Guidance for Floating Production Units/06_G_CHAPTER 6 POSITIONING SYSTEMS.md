# Guidance for Floating Production Units

> RULES AND GUIDANCE FOR OFFSHORE STRUCTURES / GC-11-E / 2025 / EN / Guidance

## CHAPTER 6 POSITIONING SYSTEMS

### Section 1 General

#### 101. General

- **1.** Units are to be provided with positioning systems complying with the requirements given in this Chapter.

#### 102. Mooring systems

- **1.** Mooring systems are to be sufficiently capable of positioning Units at a specific location against all of the design conditions for positioning as well as all of the safety conditions for systems embedded on the seabed and the ships laden with offloaded crude oil from such Units.
- **2.** In the case of mooring systems of Units operated in sea areas where low temperature, freezing, ice formation, etc. are predicted, the effects of such things are to be taken into consideration or appropriate countermeasures are to be provided.

#### 103. Conditions to be considered for mooring system analysis

- **1.** The various conditions of a Floating Installation which are important for the designer to consider are as follows.
  - **(1)** Intact Design
    A condition with all components of the system intact and exposed to an environment as described by the design environmental condition (DEC).
  - **(2)** Damaged Case with One Broken Mooring Line
    A condition with any one mooring line broken at the design environmental condition (DEC) that would cause maximum mooring line load for the system. The mooring line subjected to the maximum load in intact extreme conditions when broken might not lead to the worst broken mooring line case. The designer should determine the worst case by analyzing several cases of broken mooring line, including lead line broken and adjacent line broken cases. For a disconnectable mooring system with quick release system, the mooring analysis for a broken line case may not be required. For unusual (non-symmetric) mooring pattern, mooring analysis for the broken line case for the disconnectable environmental condition may be required. For a system utilizing the SALM concept, the case with one broken mooring line is not relevant. A case considering loss of buoyancy due to damage of a compartment of the SALM structure should be analyzed for position mooring capability. The loss of thruster power or mechanical failure on thruster-assisted position mooring systems will be considered on a case-by-case basis.
  - **(3)** Transient Condition with One Broken Mooring Line
    A condition with one mooring line broken (usually the lead line) in which the moored installation exhibits transient motions (overshooting) before it settles at a new equilibrium position. The transient condition can be an important consideration when proper clearance is to be maintained between the moored installation and nearby structures. An analysis for this condition under the design environmental condition (DEC) is required. The effect of increased line tensions due to overshoot upon failure of one mooring line (or thruster or propeller if mooring is power-assisted) should also be considered.
- **2.** The proper clearances between Units and any near-by structures and ships are to also be verified.
- **3.** In the case of SALM, cases considering a loss of buoyancy due to damage of a compartment of the SALM structure should be analyzed for position mooring capability instead of cases with one broken mooring line.
- **4.** Mooring system analysis in combination with the assistance of propulsion systems, thrusters, etc. is to be as deemed appropriate by the Society.


### Section 2 Mooring Analysis

#### 201. General

- **1.** Mooring analysis is to be conducted based on the environmental conditions as specified in **Ch 3, Sec 3.** Such analysis is to include the evaluations of the mean environmental forces, the extreme response of the Units, and the corresponding mooring line tension.
- **2.** Mooring system analysis as deemed appropriate by the Society is to be carried out for the all prospective mooring conditions. The effects due to the draught changes of the Units are to be taken into consideration. In the case of Units mooring to individual periphery facilities, such as CALM, separate from the Units, mooring analysis for the total system, including any periphery facilities, is to be carried out.
- **3.** In case of mooring systems using mooring lines, analysis is to be carried out under the awareness that there is no harmful excessive bend of any lines in way of the contact points between mooring lines and mooring equipment (fairleaders, etc.) fitted on board Units.
- **4.** The mooring systems of Units and the seabed mooring points (anchors, sinkers, piles, etc.) of any periphery facilities for positioning are not to be slid, uplifted, overturned, etc. against any envisioned force from the mooring lines. In cases where scouring effects are not considered to be negligible, appropriate consideration is to be taken such as the modification of burial depth, protection against the flow around seabed mooring points, etc.
- **5.** Mooring analysis is to be made under the awareness that the equipment for mooring systems is subjected to steady forces of wind, current and mean wave drift force as well as wind and wave induced dynamic forces. Maximum line tension is to be calculated considering that wind, wave, and current come from unrestricted directions. However, in cases where the data for the specific positioning area of a Units prove a restricted direction of wind, wave and current in that area, calculations under such specific directions may be accepted in cases where deemed appropriate by the Society.
- **6.** The maximum offset of a Units and maximum tension of a mooring line is to be calculated. Depending on the analysis objectives, a quasi-static analytical method, or dynamic analytical method as deemed appropriate by the Society may be used for calculations.
- **7.** In the case of deep water operations with large numbers of production risers, mooring system analysis is to take into account riser loads, stiffness, damping, etc. in case where the interaction between Units/mooring systems and riser systems are significant.

#### 202. Mean environmental forces, etc.

- **1.** The calculation of steady forces due to wind and current are to be in accordance with **Ch 3, Sec 3.**
- **2.** Mean and oscillatory low frequency drift forces may be determined by model tests or using hydrodynamic computer programs verified against model test results or other data. Mean drift forces to be as deemed appropriate by the Society.
- **3.** Load information is to be prepared based on appropriate analysis, model tests, etc., and such information is to be provided on board.

#### 203. Maximum offset and yaw angle of the installation

- **1.** Maximum offset may be calculated as the sum of the offset due to steady components such as wind, current, and wave (steady drift), and dynamic motion offset due to the dynamic components of forces induced by waves (high and low frequency).
- **2.** The following formula is to be adopted as the standard for calculating maximum offset. In the following formula, mean offset and significant single amplitude or maximum amplitude of the maximum offset obtained from model tests or analysis methods deemed appropriate by the Society are used.
  $S _{\max=} S _{mean} +S _{lf(\max)} +S _{wf(sig)}$
  or
  $S _{\max=} S _{mean} +S _{lf(sig)} +S _{wf(\max)}$
  whichever is greater.
  where
  $S _{mean}$ : Mean offset of the Units due to wind, current and mean drift
  $S_{ lf(sig)}$ : Significant single amplitude low frequency motion
  $S _{wf(sig)}$ : Significant single amplitude wave frequency motion
- **3.** The maximum values of low frequency motion $S _{lf(\max)}$ and wave frequency motion $S _{wf(\max)}$ may be calculated by multiplying their corresponding significant single amplitude values by the factor $C$,
  which is to be calculated as follows:
  $C= \frac{1}{2} \sqrt {2InN}$
  $N= \frac{T}{Ta}$
  $T$ : Hypothetical storm duration (seconds), minimum 10,800 (i.e. 3 hours). In the case of areas with longer storm durations (monsoon areas), $T$ needs to be a higher value.
  $T _{a}$ : Average response zero up-crossing period (seconds)
- **4.** In the case of low frequency components, $T _{a}$ may be taken as the natural period $T _{n}$ of a Units with a mooring system. $T _{n}$ can be calculated as follows using the mass of the Units $m$ (including added mass, etc.) and the stiffness of the mooring system $k$ for horizontal motion (port-starboard, fwd-aft, yaw motion) at the Units s mean position and equilibrium heading as follows:
  $Tn=2 \pi \sqrt { \frac{m}{k} }$
  In such cases, information about the stiffness of mooring systems, damping forces, and other parameters which may affect the maximum values of low frequency motion are to be submitted to the Society for reference.
- **5.** In order to assess the motion of Units in waves in relatively shallow water, shallow water effects are to be taken into account. In cases where the changes in tidal levels in shallow waters are relatively large, the tidal difference affecting Units motion and the tension acting on mooring lines is to be considered.
- **6.** In the case of single point mooring systems, the maximum offset for motion in waves is to be calculated using a non-linear time history domain method or model tests. In such cases, wave irregularities and wind variances are to be considered as well.

#### 204. Calculation of mooring line tensions, etc.

- **1.** In order to calculate the maximum tension acting on the mooring lines, the severest combination of wind, waves and current is to be considered together with a sufficient number of angles of incidence. Although this severest condition generally corresponds to cases where all of the wind, wave and current directions are consistent, in the case of specific sea areas, the combination of wind, waves and current in different directions which are likely to create a higher tension are to be taken into account as needed.
- **2.** In calculating the tension acting on mooring lines, at least Sub-paragraph (1) to (3) mentioned below are to be considered. Sub-paragraph (4) may be assessed as necessary. This analytical procedure can be called a quasi-static analytical procedure and is to be adopted as the standard for calculating the tensions acting on mooring lines. The maximum tension of mooring lines calculated by this quasi-static analytical procedure has to have, in principle, a suitable safety factor specified in **Table 6.1** corresponding to specific breaking tension.
  - **(1)** Static tension of mooring lines due to net weight and buoyancy.
  - **(2)** Steady tension of mooring lines due to a steady horizontal offset of Units induced by wind, waves and current.
  - **(3)** Quasi-static varying tension of mooring lines due to Units motion induced by waves.
  - **(4)** Tension of mooring lines in consideration of their elastic elongation in cases where they are used in a moderately taut condition (generally in shallow waters), or in cases where mooring lines with low rigidity such as fibre ropes are used.

    | Condition | Safety Factor |   |
    | --- | --- | --- |
    | Condition | Chains or wire ropes | Synthenic fibre ropes |
    | Intact |   |   |
    | Dynamic analysis | 1.67 | 2.50 |
    | Quasi-static analysis | 2.00 | 3.00 |
    | One broken mooring line (at new equilibrium position) |   |   |
    | Dynamic analysis | 1.25 | 1.88 |
    | Quasi-static analysis | 1.43 | 2.15 |
    | One broken mooring line (transient condition) |   |   |
    | Dynamic analysis | 1.05 | 1.58 |
    | Quasi-static analysis | 1.58 | 1.77 |
- **3.** The maximum tension in a mooring line $T_{ \max}$ is to be determined as follows:
  $T _{\max}= T _{mean} + T _{ lf(\max)}+T _{ wf(sig)}$
  or
  $T _{\max}= T _{mean} + T _{ lf(sig)}+T _{ wf(\max)}$
  whichever is greater
  where
  $T_{ mean}$ : Mean mooring line tension due to wind, current and mean steady drift
  $T_{ lf(sig)}$ : Significant single amplitude low frequency tension
  $T_{ wf(sig)}$ : Significant single amplitude wave frequency tension
  The maximum values of low frequency tension $T _{lf(\max)}$ and wave frequency tension $T_{ wf(\max)}$ are to be calculated by the same procedure as that used for obtaining the motions at low frequency and wave frequency described in **203. 2** above.
- **4.** Mooring systems are to be designed so that the failure of any one mooring line does not cause the progressive failure of the remaining mooring lines. The tension acting on the remaining mooring lines is to be calculated using the quasi-static analytical procedure. The safety factors for the tension of such mooring lines are, in principle, not to be less than those specified in **Table 6.1** corresponding to their respective specific breaking tension. The period of recurrence of environmental loads such as wind and wave loads, however, may be taken as one year.
- **5.** In the analysis of the one broken mooring line condition given in **Par 4** above, in the case of a Units which is moored in the proximity of other Units, the safety factors for any mooring lines arranged on the opposite side of the other Units are to be taken as 1.5 times of those indicated in **Table 6.1.**
- **6.** In cases where the following Sub-paragraph (1) and (2) are taken into account in addition to **Par 2** above, the safety factors required in cases where quasi-static analytical procedures are adopted may be modified to values deemed appropriate by the Society.
  - **(1)** Dynamic tension in mooring lines due to damping forces and inertia forces acting on each mooring line in cases where they are generally used in deep water.
  - **(2)** Quasi-static low-frequency varying tension of mooring lines due to the low-frequency motion of Units in irregular waves in cases where they are used in a sufficiently slack condition. (in cases where the natural period of motion of a Units in a horizontal plane is sufficiently longer than the period of ordinary waves)
- **7.** In the case of Taut Mooring systems, the following are to be complied with in addition to **Par 1** to **Par 5** above:
  - **(1)** Such systems are to be designed so that no slack is caused in any mooring line due to changes in line tension.
  - **(2)** Changes in the tension of mooring lines due to tidal difference including astronomic tides and meteorological tides are to be considered.
  - **(3)** The effects of any changes in the weight and displacements of heavy items carried on board upon the tension of mooring lines are to be sufficiently taken into account.
  - **(4)** In cases where the effects of the non-linear behavior of mooring lines on their tension are not negligible, tension due to non-linear behavior is to be considered.

#### 205. Fatigue analysis

- **1.** The fatigue life of mooring lines is to be assessed in consideration of the changing tension range, $T$ and the number of cycles, $n$. The fatigue life of mooring lines is to be evaluated by estimating the fatigue damage ratio, $Di$ in accordance with Miner's law using a curve relating the changing tension range to the number of cycles to failure.
  $D _{i} = \frac{n _{i}}{N _{i}}$
  $n _{i}$ : Number of cycles within the tension range interval, $i$, for a given sea state.
  $N _{i}$ : Number of cycles to failure at changing tension range, $Ti$.
  The cumulative fatigue damage, $D$ for all expected number of sea states $NN$ (identified in a wave scatter diagram) is to be calculated as follows:
  $D= \sum _{i=1} ^{NN}Di$
  The value of $D$ divided by the usage factor (ɳ) specified in **Table 6.2** is not to be greater than 1. In such cases, the usage factors for the underwater parts of the mooring lines are, in principle, to be taken to be that of an inaccessible and critical area.
- **2.** The fatigue life of each mooring line component is to be considered. $T-N$ curves for various line components are to be based on fatigue test data and regression analysis.
- **3.** Special consideration is to be given to the fatigue strength of the connections between the mooring lines and hull structures of Units, the connections between the mooring lines and seabed mooring points, and the connections between the mooring lines and other mooring lines.

  | Criticality of the structural members | Accessibility | Usage Factor, ɳ |
  | --- | --- | --- |
  | Normal | High | 1.0 |
  | Normal | Low | 0.5 |
  | High | High | 0.33 |
  | High | Low | 0.1^*1 |
  | (NOTES)<br>1. For the structural members whose criticality is high and accessibility is low, special design<br>consideration is to be taken into account in order to provided appropriate measures for inspection and<br>consideration monitoring in principle. |   |   |


### Section 3 Design of Mooring Lines, etc.

#### 301. Components of mooring lines and seabed mooring points

- **1.** Each component of mooring systems is to be designed using design methods by which the severest loading condition can be verified. The strength of connecting shackles, links, etc. used at the connecting points between the mooring lines and hull structures of Units and between mooring lines and seabed mooring points are, in principle, to have safety factors against the breaking loads of such mooring lines or the ultimate strength of structures not less than those indicated in the **Table 6.3.**
  **Table 6.3 Safety Factor**

  **Safety factor**

  | Intact condition (unmoored Units in storm conditions) | 2.50 |
  | --- | --- |
  | Intact condition (moored Units under operating conditions) | 3.00^*1 |
  | (NOTES)<br>1. In cases where a safety factor of 2.0 is ensured, even in the any one broken mooring line condition, a safety factor of 2.5 may be accepted. |   |
- **2.** In the case of catenary mooring systems, mooring lines are to be sufficiently long so that no up-lifting forces act on the parts of the mooring line around the mooring point on the seabed under design conditions. In the case of soft clay conditions (like in the Gulf of Mexico), a small angle for the one broken mooring line condition may be considered in cases where deemed acceptable by the Society.
- **3.** Information verifying that the holding power of seabed mooring points is sufficient against the expected tension from the mooring lines in accordance with **204.** is to be submitted to the Society for reference.
- **4.** In the case of seabed mooring points which rely on friction with the seabed surface, if the submerged unit weight of mooring lines is constant, the maximum load at the seabed mooring point $F_{ anchor}$ can be calculated as follow:
  $F _{anchor} =P _{"line" }-W _{ "_"}WD-F _{ friction}$
  $F _{friction} =f _{sl} L _{bed}W _{ "_"}$
  $P_{ "line"}$: Maximum mooring line tension
  WD : Water depth
  $f_{ sl}$ : Friction coefficient of mooring line on seabed at sliding which is to be determined in consideration of soil conditions, the type of mooring line, etc. In the case of soft mud, sand, and clay, the values of $f_{ sl}$, and the coefficient of friction at the start $f_{ st}$, indicated in the **Table 6.4** may be used.
  $L_{ bed}$ : Length of mooring line on seabed at design storm conditions, not to exceed 20% of the total length of a mooring line.
  $W_{ "_"}$ : Submerged unit weight of mooring line
  In cases where submerged mooring lines are not a single line, or those cases where using intermediate sinkers/buoys, the above equation is to be applied in consideration of such effects.
- **5.** The safety factors for the horizontal holding power capacity of the seabed mooring points of catenary mooring systems and taut mooring systems are, in principle, to be in accordance with **Table 6.5.** However, the above may not be complied with in cases where required ultimate holding capacity is to be determined based on mooring loads derived from dynamic analysis taking into account mooring line dynamics.
- **6.** The safety factors for the vertical holding power capacity of the seabed mooring points of taut mooring systems are, in principle, to be in accordance with **Table 6.6.**
  **Table 6.4 Coefficient of Friction** $f$

  |   | Starting ($f_{ st}$) | Sliding ($f_{ sl}$) |
  | --- | --- | --- |
  | Chain | 1.00 | 0.70 |
  | Wire rope | 0.60 | 0.25 |

  **Table 6.5 Safety Factor for the Horizontal Holding Capacity of the Seabed Mooring Points of**
  **Catenary Mooring Systems and Taut Mooring Systems**

  **Safety factor**

  | Intact | 1.50 |
  | --- | --- |
  | One broken mooring line extreme | 1.00 |

  **Table 6.6 Safety Factor for the Vertical Holding Capacity of the Seabed Mooring Points of Taut Mooring Systems**

  **Safety factor**

  | Intact | 1.20 |
  | --- | --- |
  | One broken mooring line extreme | 1.00 |


### Section 4 Mooring Equipment

#### 401. General

- **1.** The equipment of positioning systems is to have sufficient redundancy. In cases where any single unit of equipment of positioning systems is fitted on board Units, special consideration is to be given to the reliability of such equipment and its components. In cases where the failure of any single unit of equipment may lead to loss of positioning capability, an additional set of such equipment will be required as deemed necessary by the Society.
- **2.** Means are to be provided whereby the normal operations of positioning systems can be sustained or restored even though one unit of equipment becomes inoperative. In the case of driving units, special consideration is to be given for preventing loss of function.
- **3.** The prime movers used for positioning systems are to be designed to operate under the static conditions given in **Ch 9, Sec 1, 102.** as well as under the dynamic conditions given below. Deviation from given values may be permitted, taking into consideration the type, size and service conditions, etc. of the Units in cases where deemed appropriate by the Society.
  - **(1)** In the case of ship type and barge-type Units:
    Rolling up to 22.5° and simultaneously pitching up to 7.5°
  - **(2)** In the case of column-stabilized Units:
    Dynamic inclination up to 22.5° in any direction

#### 402. Chains, wire ropes, etc.

- **1.** Chains, wire ropes or fibre ropes used for mooring systems are to comply with the requirements given in **Pt 4, Ch 8, Sec 4 and Sec 5** of **Rules for the Classification of Steel Ships** or any standards deemed appropriate by the Society. In cases where the Grade R4 chains specified in **Pt 4, Ch 8** of **Rules for the Classification of Steel Ships** or stronger chains are used, special care is to be taken because repairs by welding for any defects, loose studs and corrosion by welding is, in principle, prohibited for such chains.
- **2.** Intermediate sinkers, intermediate buoys and anchors, sinkers, piles, etc. for seabed mooring points are to be as deemed appropriate by the Society.

#### 403. Chain stoppers or windlasses, winches, etc.

- **1.** Individual equipment of mooring systems is, in principle, to be approved by the Society.
- **2.** Chain stoppers used for mooring systems are to have sufficient strength against the breaking strength of the mooring line as deemed appropriate by the Society. The prototypes of chain stoppers are to be verified to have sufficient strength against the breaking strength of the mooring line. It is to be verified that the stress calculated by structural analysis under the awareness that the mooring line is subjected to design maximum loads does not exceed the specified proof stress of the chain stoppers.
- **3.** Windlasses used for the catenary mooring systems of Units are to comply with the requirements specified in following Sub-paragraph (1) to (3):
  - **(1)** Each windlass is to be provided with two independent power-operated brakes. Each brake is to be capable of holding against a static load of at least 50% of braking strength of mooring lines. In cases where deemed appropriate by the Society, one of the brakes may be replaced by a manually operated brake.
  - **(2)** Windlasses are to have sufficient dynamic braking capacity to control the normal combination of loads from anchors, mooring lines and anchor handling vessels during the deployment of anchors at the maximum design pay-out speed of the windlass.
  - **(3)** In cases where a power source for a windlass is lost, power-operated braking systems are to be automatically applied and be capable of holding against 50% of the total static braking capacity of the windlass.
- **4.** The means specified in Sub-paragraph (1) to (4) below are to be provided for controlling catenary mooring systems:
  - **(1)** Each windlass is to be capable of being controlled from a position which provides a good view of the operation.
  - **(2)** Means are to be provided at the windlass control position to monitor mooring line tension and windlass power load as well as to indicate the amount of mooring line paid out.
  - **(3)** Indicators for mooring line tension, wind velocity and wind direction at the control station of each windlass are to be provided at the manned control position.
  - **(4)** Means of communication are to be provided between essential places for mooring operations (for example, operating position, wheel house, control room, etc.)
- **5.** Means are to be so provided that mooring lines can be released from the Units after any loss of the main power supply.
- **6.** In the case of laying taut mooring lines, the initial tension in all mooring lines is to be coordinated to achieve approximate uniformity. Power equipment capable of adjusting the tension of mooring lines is to be provided as necessary.
- **7.** A tension monitoring system is to be provided for each taut mooring line.

#### 404. Fairleaders

- **1.** In cases where chains are used for mooring lines, the standard length of the part where the chain and fairleader make contact is to be not less than 7 times the chain diameter.
- **2.** In cases where wire ropes or fibre ropes are used for mooring lines, the standard length of the part where the wire rope and fairleader make contact is to be not less than 14 times the wire rope nominal diameter.
- **3.** In the case of arrangements that do not comply with the standards given in **Par 1** or **Par 2** above, detailed analysis in which the effects of bending loads acting on mooring lines is taken into account is to be carried out. Otherwise, mooring analysis is to be carried out modifying the values of the safety factors given in **Table 6.1** upto those values deemed appropriate by the Society.


### Section 5 Single Point Mooring Systems

#### 501. Design loads for structures

- **1.** The design of the structure and equipment of single point mooring systems is to consider the severest combination of various loads including at least the following. A detailed report about such designs is to be submitted to the Society for reference.
  - **(1)** Dead loads
  - **(2)** Dynamic loads due to motion (including rotating motion around turn tables)
  - **(3)** Mooring loads
  - **(4)** Fatigue loads
- **2.** In order to consider the design loads acting on turret systems, the loads from mooring lines or risers due to gravity, buoyancy, inertia, and hydraulic forces, etc. are to be taken into account.

#### 502. Structural components

- **1.** Structural components are, in principle, to be in compliance with the codes or standards deemed appropriate by the Society and structural strength is to be evaluated by suitable methods such as FEM, etc.
- **2.** When performing the analysis mentioned in **Par 1** above, the allowable stress for von Mises stress is to be 60% of the specified yield strength (not to exceed 72% of the specified tensile strength) of the material used for the part in concern. In the case of transient conditions in the one broken mooring line condition, however, the value of allowable stress may be increased up to but not exceeding 80% of specified yield strength.
- **3.** Structural components are to have sufficient strength against buckling in consideration of their shape, size, surrounding conditions, etc.
- **4.** A fatigue life evaluation is to be carried out for those parts among essential components designated by the Society, such as turret systems, yokes, etc. In such cases, a usage factor of 0.33(0.1 for inaccessible areas) is to be used for such evaluations.
- **5.** The structures of the periphery facilities for positioning, the connections between such periphery facilities for positioning and mooring systems and the connections between such periphery facilities for positioning and seabed mooring points are to be as deemed appropriate by the Society.
- **6.** The parts of the hull structures of Units which transmit and dissipate the loads from turrets and yokes (turret bearing parts, etc.) are to be capable of withstanding such loads and are to be suitably reinforced.

#### 503. Mechanical components

- **1.** The mechanical components of single point mooring systems(turret bearings, driving mechanisms, various connecting attachments, etc.) are to be in accordance with standards/codes deemed appropriate by the Society in addition to relevant requirements given in **Guidance for single point mooring**.
- **2.** The bearings which carry the loads from rotation structures and mooring lines(turret bearings, etc.) are to be designed with a safety factor of not less than 2.0 against the destructive yielding of the bearing surface.
- **3.** Notwithstanding **Par 2** above, bearings which do not carry loads are to be as deemed appropriate by the Society.

#### 504. Turret mooring

- **1.** A turret mooring system is one type of station keeping system for a floating installation and can either be installed internally or externally.
- **2.** Both internal and external turret mooring systems will allow the installation to weathervane around the turret.
- **3.** The mooring lines are fixed to the sea bottom by anchors or piles.
- **4.** For an internal turret system, the turret is supported in the installation by a system of bearings.
- **5.** The loads acting on the turret will pass through the bearing system into the installation.
- **6.** Typically, a roller bearing is located near the installation deck level, and radial sliding bearing is located near the keel of the installation. For an external turret mooring system, the installation is extended to attach the turret mooring system at the end of the installation.
- **7.** The loads acting on an internal turret system include those basic loads induced by the mooring lines, risers, gravity, buoyancy, inertia and hydrostatic pressure.
- **8.** Other loads, such as wave slamming and loads resulting from misalignment and tolerance, that may have effect on the turret should also be considered in the design. In establishing the controlling turret design loads, various combinations of installation loading conditions ranging from the full to minimum storage load conditions, wave directions, and both collinear and non-collinear environments are to be considered. The mooring loads and loads applied to the external turret structure are transferred through its bearing system into the installation. The load range and combinations to be considered and analysis methods are similar to those stated for an internal turret mooring system, with additional consideration of environmentally-induced loads on the turret structure.
- **9.** A structural analysis using finite element method is required to verify the sufficient strength of the turret structure.
- **10.** The allowable von Mises stress of the turret structure is to be 0.7 of the yield strength for the operational intact mooring design conditions.
- **11.** The von Mises stress allowed for the design storm intact mooring design conditions and for the design storm one-line broken mooring condition are 90% and 100% of the yield strength, respectively, to verify the turret structure mooring attachment locations and supporting structure.
- **12.** A fatigue evaluation of the turret system using a spectral method or other proven approaches is needed to determine the fatigue lives for the turret components.


### Section 6 Anchor Holding Power

#### 601. Generals

Different types of foundation systems used for floating installations are drag anchors, pile anchors, vertically loaded anchors (VLAs) and suction piles. Gravity boxes, grouted piles, templates, etc., may also be used and are considered to be within the scope of classification.

#### 602. Drag anchor

- **1.** For a mooring system with drag anchors, the mooring line length should be sufficiently long such that there is no angle between the mooring line and the seabed at any design condition.
- **2.** For soft clay (in Gulf of Mexico) condition, a small angle for the damaged case with one broken line are to be as deemed appropriate by the Society.
- **3.** Drag anchor holding power depends on the anchor type, as well as the condition of the anchor deployed in regard to penetration of the flukes, opening of the flukes, depth of burial, stability of the anchor during dragging, soil behavior of the flukes, etc.
- **4.** The designer should submit to the Society the performance data for the specific anchor type and the site-specific soil conditions for the estimation of the ultimate holding capacity (UHC) of an anchor design. Because of uncertainties and the wide variation of anchor characteristics, exact holding power is to be determined after the anchor is deployed and test loaded.
- **5.** The maximum load at anchor, $F_{anchor }$ is to be calculated, in consistent units, as follows **301. 4**

#### 603. Conventional pile

- **1.** Conventional pile anchors are capable of withstanding uplift and lateral forces at the same time.
- **2.** Analysis of the pile as a beam column on an elastic foundation is to be submitted to the Society for review.
- **3.** The analyses for different kinds of soil using representative soil resistance and deflection (p-y) curves are described in the API RP 2A and API RP 2T, as applicable. The fatigue analysis of the pile should be submitted for review.

#### 604. Vertically loaded drag anchors (VLA)

- **1.** VLAs can be used in a taut leg mooring system with approximately a 35° to 45° angle between the seabed and the mooring lines.
- **2.** These anchors are designed to withstand both the vertical and horizontal loads imposed by the mooring line.
- **3.** The structural and geotechnical holding capacity design of the VLA are to be submitted for review. This is to include the ultimate holding capacity and the anchor's burial depth beneath the seabed. Additionally, the fatigue analysis of the anchor and the connectors joining the VLA to the mooring line should be submitted for review.
- **4.** The safety factors of VLA anchors' holding capacity are specified in **Table 6-7.**
  **Table 6.7 Factor of Safety for Anchor Holding Capacities^1)**

  |   | Factor of Safety |   |
  | --- | --- | --- |
  | Drag Anchors |   |   |
  | Intact Design | (DEC) | 1.50 |
  | Broken Line Extreme | (DEC) | 1.00 |
  | Vertically Loaded Anchors(VLAs) |   |   |
  | Intact Design | (DEC) | 2.00 |
  | Broken Line Extreme | (DEC) | 1.50 |
  | One broken Line(Transient) |   |   |
  | Dynamic Analysis | (DEC) | 1.05 |
  | Quasi-Static | (DEC) | 1.18 |
  | Pile Anchors |   |   |
  | Refer to API RP 2A, API 2T as applicable |   |   |
  | Suction Piles |   |   |
  | Intact Design | (DEC) | 1.5 to 2.0 |
  | Broken Line Extreme | (DEC) | 1.2 to 1.5 |
  | (NOTES)<br>1) The safety factor to be used in the design should be based on the extent of the geotechnical investigation, confidence in the prediction of soil-pile behavior, experience in the design and behavior of suction piles in the area of interest, and the inclination of the mooring load. |   |   |

#### 605. Suction piles

- **1.** Suction pile anchors are caisson foundations that are penetrated to the target depth by pumping out the water inside of the pile to create underpressure within the pile.
- **2.** They may typically consist of a stiffened cylindrical shell with a cover plate at the top and an openbottom and generally have larger diameters and are shorter in length than conventional piles.
- **3.** These piles can be designed to have a permanent top or a retrievable top depending on the required vertical holding capacity.
- **4.** The pad eye for the mooring line connection can be at the top or at an intermediate level depending on the application of the suction pile. Suction pile anchors are capable of withstanding uplift and lateral forces.
- **5.** Due to the geometry of the suction piles, the failure modes of the soils maybe different than what are applicable for long slender conventional piles.
- **6.** The safety factors for the suction piles' holding capacity are specified in **Table 6.7.** Geotechnical holding capacity and structural analyses for the suction piles are to be submitted to verify the adequacy of the suction piles to withstand the in-service and installation loads.
- **7.** Additionally, fatigue analysis of the suction piles are to be submitted to verify the adequacy of the fatigue life of the critical locations. Installation analyses are to be submitted to verify that the suction piles can be penetrated to the design penetration and that the suction piles can be retrieved, if necessary.
- **8.** It is suggested that a ratio of at least 1.5 between the force that would cause uplift of the soil-plug inside of the pile and the effective pile installation force be considered in the penetration analysis.
