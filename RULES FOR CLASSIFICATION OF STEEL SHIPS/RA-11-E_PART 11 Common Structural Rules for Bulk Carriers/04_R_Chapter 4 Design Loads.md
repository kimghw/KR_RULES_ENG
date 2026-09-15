# PART 11 Common Structural Rules for Bulk Carriers

> RULES FOR CLASSIFICATION OF STEEL SHIPS / RA-11-E / 2025 / EN / Rules

## Chapter 4 Design Loads

### Section 1 - GENERAL

#### 1. General

- **1.1**
  - **1.1.1** The equivalent design wave (EDW) method is used to set the design loads which include lateral loads normal to plating and hull girder loads in still water and in waves.
  - **1.1.2** External hydrostatic pressure and internal static pressure due to cargo and ballast are considered as lateral loads in still water. External hydrodynamic pressure and internal inertial pressure due to cargo and ballast are considered as lateral loads in waves.
  - **1.1.3** Still water vertical shear force and bending moment, wave-induced vertical shear force and bending moment and wave-induced horizontal bending moment are considered as the hull girder loads.
  - **1.1.4** The stresses due to the lateral loads in waves and the hull girder loads in waves are to be combined using load combination factors determined for each equivalent design wave.


### Section 2 - SHIP MOTIONS AND ACCELERATIONS

Symbols
For symbols not defined in this Section, refer to Ch 1, Sec 4.
$a _{0}$ : Acceleration parameter, taken equal to:
![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image79.png)
*T_R* : Roll period, in s, defined in [2.1.1]
*q* : Single roll amplitude, in deg, defined in [2.1.1]
*T* : Pitch period, in s, defined in [2.2.1]
*F* : Single pitch amplitude, in deg, defined in [2.2.1]
*f_p* : Coefficient corresponding to the probability level, taken equal to:
*f_p* = 1.0 for strength assessments corresponding to the probability level of $10 ^{-8}$
*f_p* = 0.5 for strength assessments corresponding to the probability level of $10 ^{-4}$

#### 1. General

- **1.1**
  - **1.1.1** Ship motions and accelerations are assumed to be periodic. The motion amplitudes, defined by the formulae in this Section, are half of the crest to trough amplitudes.
  - **1.1.2** As an alternative to the formulae in this Section, the Society may accept the values of ship motions and accelerations derived from direct calculations or obtained from model tests, when justified on the basis of the ship’s characteristics and intended service. In general, the values of ship motions and accelerations to be determined are those which can be reached with a probability level of $10 ^{-8}$ or $10 ^{-4}$. In any case, the model tests or the calculations, including the assumed sea scatter diagrams and spectra, are to be submitted to the Society for approval.

#### 2. Ship absolute motions and accelerations

- **2.1** Roll
  - **2.1.1** The roll period *T_R*, in s, and the single roll amplitude *q*, in deg, are given by:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image80.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image81.png)
    where:
    *k_b* : Coefficient taken equal to:
    *k_b* =1.2 for ships without bilge keel
    *k_b* =1.0 for ships with bilge keel
    *k_r* : Roll radius of gyration, in m, in the considered loading condition. When *k_r* is not known, the values indicated in Table 1 may be assumed.
    *GM* : Metacentric height, in m, in the considered loading condition. When *GM* is not known, the values indicated in Table 1 may be assumed.

    | Loading condition |   | *k_r* | *GM* |
    | --- | --- | --- | --- |
    | Full load condition | Alternate or homogeneous loading | 0.35 *B* | 0.12 *B* |
    | Full load condition | Steel coil loading | 0.42 *B* | 0.24 *B* |
    | Normal ballast condition |   | 0.45 *B* | 0.33 *B* |
    | Heavy ballast condition |   | 0.40 *B* | 0.25 *B* |
- **2.2** Pitch
  - **2.2.1** The pitch period *T_P*, in s, and the single pitch amplitude *φ*, in deg, are given by:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image82.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image83.png)
    where:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image84.png)
- **2.3** Heave
  - **2.3.1** The vertical acceleration due to heave, in $\mathrm{m}/s ^{2}$, is given by:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image85.png)
- **2.4** Sway
  - **2.4.1** The transverse acceleration due to sway, in $\mathrm{m}/s ^{2}$, is given by:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image86.png)
- **2.5** Surge
  - **2.5.1** The longitudinal acceleration due to surge, in $\mathrm{m}/s ^{2}$, is given by:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image87.png)

#### 3. Ship relative accelerations

- **3.1** General
  - **3.1.1** At any point, the accelerations in X, Y and Z directions are the acceleration components which result from the ship absolute motions and accelerations defined in [2.1] to [2.5].
- **3.2** Accelerations
  - **3.2.1** The reference values of the longitudinal, transverse and vertical accelerations at any point are obtained from the following formulae:
    • In longitudinal direction:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image88.png)
    • In transverse direction:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image89.png)
    • In vertical direction:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image90.png)
    where:
    *C_XG*, *C_XS*, *C_XP*, *C_YG*, *C_YS*, *C_YR*, *C_ZH*, *C_ZR* and *C_ZP* : Load combination factors defined in Ch 4, Sec 4, [2.2]
    *a_pitchx* : Longitudinal acceleration due to pitch, in $\mathrm{m}/s ^{2}$
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image91.png)
    *a_rolly* : Transverse acceleration due to roll, in $\mathrm{m}/s ^{2}$
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image92.png)
    *a_rollz* : Vertical acceleration due to roll, in $\mathrm{m}/s ^{2}$
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image93.png)
    *a_pitchz* : Vertical acceleration due to pitch, in $\mathrm{m}/s ^{2}$
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image94.png)
    where ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image95.png) is to be taken not less than 0.2 *L*
    *R* = ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image96.png)
    *x, y, z* : X, Y and Z co-ordinates, in m, of any point considered with respect to the reference co-ordinate system defined in Ch 1, Sec 4


### Section 3 - HULL GIRDER LOADS

Symbols
For symbols not defined in this Section, refer to Ch 1, Sec 4.
*x* : X co-ordinate, in m, of the calculation point with respect to the reference co-ordinate system
*f_p* : Coefficient corresponding to the probability, defined in Ch 4, Sec 2.

#### 1. General

- **1.1** Sign conventions of bending moments and shear forces
  - **1.1.1** Absolute values are to be taken for bending moments and shear forces introduced in this Section. The sign of bending moments and shear forces is to be considered according to Sec 4, Table 3. The sign conventions of vertical bending moments, horizontal bending moments and shear forces at any ship transverse section are as shown in Fig 1, namely:
    • the vertical bending moments *M_SW* and *M_WV* are positive when they induce tensile stresses in the strength deck (hogging bending moment) and are negative in the opposite case (sagging bending moment)
    • the horizontal bending moment *M_WH* is positive when it induces tensile stresses in the starboard and is negative in the opposite case.
    • the vertical shear forces *Q_SW*, *Q_WV* are positive in the case of downward resulting forces preceding and upward resulting forces following the ship transverse section under consideration, and is negative in the opposite case.
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image97.png)
    Fig 1: Sign conventions for shear forces *Q_SW*, *Q_WV* and bending moments *M_SW*, *M_WV* and *M_WH*

#### 2. Still water loads

- **2.1** General
  - **2.1.1** In general the vertical still water bending moment and the shear force of the individual loading condition is to be applied. The shipbuilder has to submit for each of the loading condition defined in Ch 4, Sec 7 a longitudinal strength calculation.
    The values of still water vertical bending moment and shear force are to be treated as the upper limits with respect to hull girder strength.
    In general, the design cargo and ballast loading conditions, based on amount of bunker, fresh water and stores at departure and arrival, are to be considered for the *M_SW* and *Q_SW* calculations. Where the amount and disposition of consumables at any intermediate stage of the voyage are considered more severe, calculations for such intermediate conditions are to be submitted in addition to those for departure and arrival conditions. Also, where any ballasting and/or deballasting is intended during voyage, calculations of the intermediate condition just before and just after ballasting and/or deballasting any ballast tank are to be submitted and where approved included in the loading manual for guidance.
  - **2.1.2** Partially filled ballast tanks in ballast loading conditions
    Ballast loading conditions involving partially filled peak and/or other ballast tanks at departure, arrival or during intermediate conditions are not permitted to be used as design conditions unless:
    • design stress limits are satisfied for all filling levels between empty and full, and
    • for BC-A and BC-B ships, longitudinal strength of hull girder in flooded condition according to Ch 5, Sec 1, [2.1.3] is complied with for all filling levels between empty and full.
    To demonstrate compliance with all filling levels between empty and full, it will be acceptable if, in each condition at departure, arrival, and where required by [2.1.1], any intermediate condition, the tanks intended to be partially filled are assumed to be:
    • empty
    • full
    • partially filled at intended level
    Where multiple tanks are intended to be partially filled, all combinations of empty, full or partially filled at intended level for those tanks are to be investigated.
  - **2.1.3** Partially filled ballast tanks in cargo loading conditions
    In cargo loading conditions, the requirement in [2.1.2] applies to the peak tanks only.
  - **2.1.4** Sequential ballast water exchange
    Requirements of [2.1.2] and [2.1.3] are not applicable to ballast water exchange using the sequential method.
- **2.2** Still water bending moment
  - **2.2.1** The design still water bending moments *M_SW*_,*_H* and *M_SW*_,*_S* at any hull transverse section are the maximum still water bending moments calculated, in hogging and sagging conditions, respectively, at that hull transverse section for the loading conditions, as defined in [2.1.1]. Greater values may be considered if defined by the Designer.
  - **2.2.2** If the design still water bending moments are not defined, at a preliminary design stage, at any hull transverse section, the longitudinal distributions shown in Fig 2 may be considered.
    In Fig 2, *M_SW* is the design still water bending moment amidships, in hogging or sagging conditions, whose values are to be taken not less than those obtained, in kN.m, from the following formulae:
    • hogging conditions:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image98.png)
    • sagging conditions:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image99.png)
    where *M_WV*_,*_H* and *M_WV*_,*_S* are the vertical wave bending moments, in kN.m, defined in [3.1].
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image100.png)
    Fig 2: Preliminary still water bending moment distribution
- **2.3** Still water shear force
  - **2.3.1** The design still water shear force *Q_SW* at any hull transverse section is the maximum positive or negative shear force calculated, at that hull transverse section, for the loading conditions, as defined in [2.1.1]. Greater values may be considered if defined by the Designer.
- **2.4** Still water bending moment and still water shear force in flooded condition
  - **2.4.1** The still water bending moments *M_SW*_,*_F*, in hogging and sagging conditions, and the still water shear force *Q_SW*_,*_F*, in flooded condition are to be determined for the flooding scenario considering each cargo hold individually flooded up to the equilibrium waterline.
    This means that double side spaces may not be considered flooded, and the cargo holds may not be considered completely flooded, but only up to the equilibrium waterline.
  - **2.4.2** To calculate the weight of ingressed water, the following assumptions are to be made:
    For packed cargo conditions (such as steel mill products), the actual density of the cargo should be used with a permeability of zero.
    - **a)** The permeability of empty cargo spaces and volume left in loaded cargo spaces above any cargo is to be taken as 0.95.
    - **b)** Appropriate permeabilities and bulk densities are to be used for any cargo carried. For iron ore, a minimum permeability of 0.3 with a corresponding bulk density of 3.0 $\mathrm{t}/m ^{3}$ is to be used. For cement, a minimum permeability of 0.3 with a corresponding bulk density of 1.3 $\mathrm{t}/m ^{3}$ is to be used. In this respect, “permeability” for solid bulk cargo means the ratio of the floodable volume between the particles, granules or any larger pieces of the cargo, to the gross volume of the bulk cargo.
  - **2.4.3** To quantify the effects of ingressed water on the hull girder still water bending moments and still water shear forces, specific calculations are to be carried out. The loading conditions on which the design of the ship has been based are to be considered and, for each of them, the cargo holds are to be considered as being individually flooded up to the equilibrium waterline. The still water bending moments and still water shear forces are therefore to be calculated for any combination of considered loading conditions and flooded cargo holds.

#### 3. Wave loads

- **3.1** Vertical wave bending moments
  - **3.1.1** Intact condition
    The vertical wave bending moments in intact condition at any hull transverse section are obtained, in kN.m, from the following formulae:
    • hogging conditions:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image101.png)
    • sagging conditions:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image102.png)
    where:
    *F_M* : Distribution factor defined in Table 1 (see also Fig 3).

    | Hull transverse section location | Distribution factor *F_M* |
    | --- | --- |
    | 0 ≤ $x$ < 0.4 *L* | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image103.png) |
    | 0.4 *L* ≤ $x$ ≤ 0.65 *L* | 1.0 |
    | 0.65 *L* ≤ $x$ < *L* | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image104.png) |

    ![Fig 3: Distribution factor F_M](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image105.png)
    Fig 3: Distribution factor *F_M*
  - **3.1.2** Flooded condition
    The vertical wave bending moments in flooded condition at any hull transverse section are obtained, in kN.m, from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image106.png)
    where *M_WV* is defined in [3.1.1].
  - **3.1.3** Harbour condition
    The vertical wave bending moments in harbour condition at any hull transverse section are obtained, in kN.m, from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image107.png)
    where *M_WV* is defined in [3.1.1].
- **3.2** Vertical wave shear force
  - **3.2.1** Intact condition
    The vertical wave shear force in intact condition at any hull transverse section is obtained, in kN, from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image108.png)
    where:
    *F_Q* : Distribution factor defined in Table 2 for positive and negative shear forces (see also Fig 4).
    Table 2: Distribution factor *F_Q*

    | Hull transverse section location | Distribution factor *F_Q* |   |
    | --- | --- | --- |
    | Hull transverse section location | Positive wave shear force | Negative wave shear force |
    | 0 ≤ $x$ < 0.2 *L* | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image109.png) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image110.png) |
    | 0.2 *L* ≤ $x$ ≤ 0.3 *L* | 0.92 *A* | 0.92 |
    | 0.3 *L* < $x$ < 0.4 *L* | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image111.png) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image112.png) |
    | 0.4 *L* ≤ $x$ ≤ 0.6 *L* | 0.7 | 0.7 |
    | 0.6 *L* < $x$ < 0.7 *L* | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image113.png) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image114.png) |
    | 0.7 *L* ≤ $x$ ≤ 0.85 *L* | 1 | A |
    | 0.85 *L* < $x$ ≤ *L* | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image115.png) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image116.png) |
    | Note : ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image117.png) |   |   |

    ![Fig 4: Distribution factor F_Q](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image118.png)
    Fig 4: Distribution factor *F_Q*
  - **3.2.2** Flooded condition
    The vertical wave shear force in flooded condition at any hull transverse section are obtained, in kN, from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image119.png)
    where *Q_WV* is defined in [3.2.1].
  - **3.2.3** Harbour condition
    The vertical wave shear force in harbour condition at any hull transverse section are obtained, in kN, from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image120.png)
    where *Q_WV* is defined in [3.2.1].
- **3.3** Horizontal wave bending moment
  - **3.3.1** The horizontal wave bending moment at any hull transverse section, in kN.m, is given by:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image121.png)
    where *F_M* is the distribution factor defined in [3.1.1].
- **3.4** Wave torsional moment
  - **3.4.1** The wave torsional moment at any hull transverse section, in kN.m, is given by:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image122.png)
    where:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image123.png)
    *F_T*_1*_,* *F_T*_2 : Distribution factors, defined as follows:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image124.png)


### Section 4 - LOAD CASES

Symbols
For symbols not defined in this Section, refer to Ch 1, Sec 4.
*a_surge*, *a_pitchx*, *a_sway*, *a_rolly*, *a_heave*, *a_rollz*, *a_pitchz* : Components of accelerations, defined in Ch 4, Sec 2.

#### 1. General

- **1.1** Application
  - **1.1.1** The load cases described in this section are those to be used for:
    • the local strength analysis of plating and ordinary stiffeners and primary supporting members according to the applicable requirements of Ch 6, Sec 1, Ch 6, Sec 2 and Ch 6, Sec 4 respectively,
    • the direct strength analysis of structural members, according to the applicable requirements of Ch 7,
    • the fatigue check of structural details, according to the applicable requirements of Ch 8.
  - **1.1.2** For the local strength analysis and for the direct strength analysis, the load cases are the mutually exclusive load cases H1, H2, F1, F2, R1, R2, P1 and P2 described in [2].
- **1.2** Equivalent design wave
  - **1.2.1** Regular waves that generate response values equivalent to the long-term response values of the load components considered being predominant to the structural members are set as Equivalent Design Waves (EDWs). They consist of:
    • regular waves when the vertical wave bending moment becomes maximum in head sea (EDW “H”)
    • regular waves when the vertical wave bending moment becomes maximum in following sea (EDW “F”)
    • regular waves when the roll motion becomes maximum (EDW “R”)
    • regular waves when the hydrodynamic pressure at the waterline becomes maximum (EDW “P”)
    The definitions of wave crest and wave trough in the EDW “H” and EDW “F” are given in Fig 1. The definitions of weather side down and weather side up for the EDW “R” and EDW “P” are given in Fig 2.
    ![Fig 1: Definition of wave crest and wave trough for EDWs “H” and “F”](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image125.png)
    Fig 1: Definition of wave crest and wave trough for EDWs “H” and “F”
    ![Fig 2: Definitions of ship motion](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image126.png)
    Fig 2: Definitions of ship motion

#### 2. Load cases

- **2.1** General
  - **2.1.1** The load cases corresponding to the Equivalent Design Waves (EDWs) are defined in Table 1. The corresponding hull girder loads and motions of the ship are indicated in Table 2. If the ship structure or the ship loading condition is not symmetrical with respect to the centreline plane of ship, the load cases (R1, R2, P1 and P2) corresponding to the beam conditions in which the encounter wave comes from the starboard (in this case the starboard is the weather side), should be also included in the structural strength assessment.

    | Load case | H1 | H2 | F1 | F2 | R1 | R2 | P1 | P2 |
    | --- | --- | --- | --- | --- | --- | --- | --- | --- |
    | EDW | “H” |   | “F” |   | “R” |   | “P” |   |
    | Heading | Head |   | Follow |   | Beam<br>(Port: weather side) |   | Beam<br>(Port: weather side) |   |
    | Effect | Max. Bending Moment |   | Max. Bending Moment |   | Max. Roll |   | Max. Ext. Pressure |   |
    | Effect | Sagging | Hogging | Sagging | Hogging | (+) | (-) | (+) | (-) |

    | Load case | H1 | H2 | F1 | F2 | R1 | R2 | P1 | P2 |
    | --- | --- | --- | --- | --- | --- | --- | --- | --- |
    | Vert. BM<br>& SF | Yes |   | Yes |   | - |   | Yes |   |
    | Hor. BM | - |   | - |   | Yes |   | - |   |
    | Heave | Down | Up | - | - | Down | Up | Down | Up |
    | Pitch | Bow down | Bow up | - | - | - | - | - | - |
    | Roll | - | - | - | - | Stbd up | Stbd down | Stbd up | Stbd down |
    | Surge | Stern | Bow | - | - | - | - | - | - |
    | Sway | - | - | - | - | - | - | Port | Stbd |
- **2.2** Load combination factors
  - **2.2.1** The hull girder loads and the acceleration components to be considered in each load case H1, H2, F1, F2, R1, R2, P1 and P2 are to be obtained by multiplying the reference value of each component by the relevant load combination factor LCF defined in Table 3.
  - **2.2.2** The still water vertical bending moment is to be added to the hull girder loads in waves, calculated with load combination factors.
  - **2.2.3** The internal loads are the sum of static pressures or forces induced by the weights carried, including those carried on decks, and of inertial pressures or forces induced by the accelerations on these weights and calculated with load combination factors.

    |   | LCF | H1 | H2 | F1 | F2 | R1 | R2 | P1 | P2 |
    | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
    | *M_WV* | *C_WV* | -1 | 1 | -1 | 1 | 0 | 0 | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image127.png) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image128.png) |
    | *Q_WV* | *C_QW*<sup>(1)</sup> | -1 | 1 | -1 | 1 | 0 | 0 | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image129.png) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image130.png) |
    | *M_WH* | *C_WH* | 0 | 0 | 0 | 0 | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image131.png) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image132.png) | 0 | 0 |
    | *a_surge* | *C_XS* | -0.8 | 0.8 | 0 | 0 | 0 | 0 | 0 | 0 |
    | *a_pitchx* | *C_XP* | 1 | -1 | 0 | 0 | 0 | 0 | 0 | 0 |
    | *gsinF* | *C_XG* | 1 | -1 | 0 | 0 | 0 | 0 | 0 | 0 |
    | *a_sway* | *C_YS* | 0 | 0 | 0 | 0 | 0 | 0 | 1 | -1 |
    | *a_rolly* | *C_YR* | 0 | 0 | 0 | 0 | 1 | -1 | 0.3 | -0.3 |
    | *gsinq* | *C_YG* | 0 | 0 | 0 | 0 | 1 | -1 | 0.3 | -0.3 |
    | *a_heave* | *C_ZH* | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image133.png) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image134.png) | 0 | 0 | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image135.png) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image136.png) | 1 | -1 |
    | *a_rollz* | *C_ZR* | 0 | 0 | 0 | 0 | 1 | -1 | 0.3 | -0.3 |
    | *a_pitchz* | *C_ZP* | 1 | -1 | 0 | 0 | 0 | 0 | 0 | 0 |
    | (1) The LCF for *C_QW* is only used for the aft part of midship section. The inverse value of it should be used for the forward part of the midship section. |   |   |   |   |   |   |   |   |   |


### Section 5 - EXTERNAL PRESSURES

Symbols
For symbols not defined in this Section, refer to Ch 1, Sec 4.
$L _{2}$ : Rule length L, but to be taken not greater than 300 m
*C* : Wave coefficient, as defined in Ch 1, Sec 4, [2.3.1]
$\lambda$ : Wave length, in m, corresponding to the load case, defined in [1.3.1], [1.4.1], and [1.5.1]
$f _{p}$ : Coefficient corresponding to the probability, defined in Ch 4, Sec 2
$T _{LC i}$ : Draught in the considered cross section, in m, in the considered loading condition
$B _{i}$ : Moulded breadth at the waterline, in m, in the considered cross section
*x, y, z* : X, Y and Z co-ordinates, in m, of the load point with respect to the reference co-ordinate system defined in Ch 1, Sec 4.

#### 1. External sea pressures on side shell and bottom

- **1.1** General
  - **1.1.1** The total pressure *p* at any point of the hull, in $\mathrm{kN}/m ^{ 2}$, to be obtained from the following formula is not to be negative:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image137.png)
    Where:
    *p_S* : Hydrostatic pressure defined in [1.2]
    *p_W* : Wave pressure equal to the hydrodynamic pressure defined in [1.3], [1.4] or [1.5], as the casemay be, and corrected according to [1.6]
- **1.2** Hydrostatic pressure
  - **1.2.1** The hydrostatic pressure *p_S* at any point of the hull, in $\mathrm{kN}/m ^{ 2}$, corresponding to the draught in still water is obtained, for each loading condition, from the formulae in Table 1 (see also Fig 1).

    | Location | Hydrostatic pressure, *p_S*, in $\mathrm{kN}/m ^{ 2}$ |
    | --- | --- |
    | Points at and below the waterline (![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image138.png)) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image139.png) |
    | Points above the waterline (![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image140.png)) | 0 |

    ![Fig 1: Hydrostatic pressure p_S](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image141.png)
    Fig 1: Hydrostatic pressure *p_S*
- **1.3** Hydrodynamic pressures for load cases H1, H2, F1 and F2
  - **1.3.1** The hydrodynamic pressures *p_H* and *p_F*, for load cases H1, H2, F1 and F2, at any point of the hull below the waterline are to be obtained, in $\mathrm{kN}/m ^{ 2}$, from Table 2.
    The distribution of pressure *p_F*_2 is schematically given in Fig 2.

    | Load case | Hydrodynamic pressure, in $\mathrm{kN}/m ^{ 2}$ |
    | --- | --- |
    | H1 | *p_H*_1 = -*k*_l *k_p* *p_HF* |
    | H2 | *p_H*_2 = *k*_l *k_p* *p_HF* |
    | F1 | *p_F*_1 = -*p_HF* |
    | F2 | *p_F*_2 = *p_HF* |

    where:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image142.png); with ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image143.png)and *z* is to be taken not greater than $T _{LC i}$
    *f_nl* : Coefficient considering nonlinear effect, taken equal to:
    *f_nl* = 0.9 for the probability level of $10 ^{-8}$
    *f_nl* = 1.0 for the probability level of $10 ^{-4}$
    *k*_l : Amplitude coefficient in the longitudinal direction of the ship, taken equal to:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image144.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image145.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image146.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image147.png)
    *k_p* : Phase coefficient in the longitudinal direction of the ship, taken equal to:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image148.png), for local strength analysis in conditions other than full load condition, for direct strength analysis and for fatigue strength assessments
    *k_p* = -1.0, for local strength analysis in full load condition
    $\lambda$ : Wave length, in m, taken equal to:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image149.png) for load cases H1 and H2
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image150.png) for load cases F1 and F2
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image151.png)
    Fig 2: Distribution of hydrodynamic pressure *p_F2* at midship
- **1.4** Hydrodynamic pressures for load cases R1 and R2
  - **1.4.1** The hydrodynamic pressures *p_R*, for load cases R1 and R2, at any point of the hull below the waterline are to be obtained, in $\mathrm{kN}/m ^{ 2}$, from the following formulae. The distribution of pressure *p_R1* is schematically given in Fig 3.
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image152.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image153.png)
    where:
    *f_nl* : Coefficient considering nonlinear effect, taken equal to:
    *f_nl* = 0.8 for the probability level of $10 ^{-8}$
    *f_nl* = 1.0 for the probability level of $10 ^{-4}$
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image154.png)
    *y* : Y co-ordinate of the load point, in m, taken positive on the portside.
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image155.png)
    Fig 3: Distribution of hydrodynamic pressure *p_R*_1 at midship
- **1.5** Hydrodynamic pressures for load cases P1 and P2
  - **1.5.1** The hydrodynamic pressures *p_P*, for the load cases P1 and P2, at any point of the hull below the waterline are to be obtained, in $\mathrm{kN}/m ^{ 2}$, from Table 3. The distribution of pressure *p_P1* is schematically given in Fig 4.

    | Load case | Hydrodynamic pressure, in $\mathrm{kN}/m ^{ 2}$ |   |
    | --- | --- | --- |
    | Load case | weather side | lee side |
    | P1 | *p_P*_1 = *p_P* | *p_P*_1 = *p_P*/3 |
    | P2 | *p_P*_2 = -*p_P* | *p_P2* = - *p_P*/3 |

    where:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image156.png)
    *f_nl* : Coefficient considering nonlinear effect, taken equal to:
    *f_nl* = 0.65 for the probability level of ${10} ^{-8}$
    *f_nl* = 1.0 for the probability level of ${10} ^{-4}$
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image157.png)
    *y* : Y co-ordinate of the load point, in m, as defined in [1.4.1]
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image158.png)
    Fig 4: Distribution of hydrodynamic pressure *p_P*_1 at midship
- **1.6** Correction to hydrodynamic pressures
  - **1.6.1** For the positive hydrodynamic pressure at the waterline (in load cases H1, H2, F2, R1, R2 and P1), the hydrodynamic pressure P_W,*_C* at the side above waterline is given (see Fig 5), in $\mathrm{kN}/m ^{ 2}$, by:
    • ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image159.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image160.png)
    • ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image161.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image162.png)
    where:
    *p_W,WL* : positive hydrodynamic pressure at the waterline for the considered load case
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image163.png)
  - **1.6.2** For the negative hydrodynamic pressure at the waterline (in load cases H1, H2, F1, R1, R2, and P2), the hydrodynamic pressure P_W,*_C*, under the waterline is given (see Fig 5), in $\mathrm{kN}/m ^{ 2}$, by:
    *p_W*_,*_C* = *p_W*, without being taken less than *rg*(*z-T_LCi*)
    where
    *p_W* : Negative hydrodynamic pressure under the waterline for the considered load case
    ![Fig 5: Correction to hydrodynamic pressure](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image164.png)
    Fig 5: Correction to hydrodynamic pressure

#### 2. External pressures on exposed decks

- **2.1** General
  - **2.1.1** The external pressures on exposed decks are to be applied for the local scantling check of the structures on exposed deck but not applied for fatigue strength assessment.
    If a breakwater is fitted on the exposed deck, no reduction in the external pressures defined in [2.2] and [2.3] is allowed for the area of the exposed deck located aft of the breakwater.
- **2.2** Load cases H1, H2, F1 and F2
  - **2.2.1** The external pressure *p_D*, for load cases H1, H2, F1 and F2, at any point of an exposed deck is to be obtained, in $\mathrm{kN}/m ^{ 2}$, from the following formula:
    $p _{D} = \varphi p _{W}$
    where:
    *p_W* : Pressure obtained from the formulae in Table 4
    $\varphi$ : Coefficient defined in Table 5.

    | Location | Pressure $p _{W}$, in $\mathrm{kN}/m ^{ 2}$ |   |
    | --- | --- | --- |
    | Location | $L _{LL}$ ≥ 100 m | $L _{LL}$ < 100 m |
    | 0 ≤ $x _{LL} /L _{LL}$ ≤0.75 | 34.3 | 14.9 + 0.195 $L _{LL}$ |
    | 0.75 < $x _{LL} /L _{LL}$ <1 | $34.3+ \left( 14.8+a \left( L _{LL} -100 \right) \right) \left( 4 \frac{x _{LL}}{L _{LL}} -3 \right)$ | $12.2+ \frac{L _{LL}}{9} \left( 5 \frac{x _{LL}}{L _{LL}} -2 \right) +3.6 \frac{x _{LL}}{L _{LL}}$ |
    | where:<br>$a$ : Coefficient taken equal to:<br>$a$ = 0.0726 for Type B freeboard ships<br>$a$ = 0.356 for Type B-60 or Type B-100 freeboard ships.<br>$x _{LL}$ : X coordinate of the load point measured from the aft end of the freeboard length $L _{LL}$. |   |   |

    | Exposed deck location | $\varphi$ |
    | --- | --- |
    | Freeboard deck | 1.00 |
    | Superstructure deck, including forecastle deck | 0.75 |
    | 1st tier of deckhouse | 0.56 |
    | 2nd tier of deckhouse | 0.42 |
    | 3rd tier of deckhouse | 0.32 |
    | 4th tier of deckhouse | 0.25 |
    | 5th tier of deckhouse | 0.20 |
    | 6th tier of deckhouse | 0.15 |
    | 7th tier of deckhouse and above | 0.10 |
- **2.3** Load cases R1, R2, P1 and P2
  - **2.3.1** The external pressure *p_D*, for load cases R1, R2, P1 and P2, at any point of an exposed deck is to be obtained, in $\mathrm{kN}/m ^{ 2}$, from the following formula:
    $p _{D} = 0.4 \varphi p _{W}$
    where:
    *p_W* : Hydrodynamic pressure at side of the exposed deck for the load cases P1, P2, R1 and R2, in $\mathrm{kN}/m ^{ 2}$, can be determined by [1.6] at the *z* co-ordinate. *p_W* is to be taken greater one of the hydrodynamic pressures *p_W,C* at both sides of the exposed deck (portside and starboard), and is not to be taken less than zero.
    $\varphi$ : Coefficient defined in Table 5.
- **2.4** Load carried on exposed deck
  - **2.4.1** Pressure due to distributed load
    If a distributed load is carried on an exposed deck, the static pressure *p_S* corresponding to this load is to be defined by the Designer and, in general, is not to be taken less than 10 $\mathrm{kN}/m ^{ 2}$.
    The total pressure *p* due to this load is to be considered not simultaneously to the pressures defined in [2.2] and [2.3]. It is to be taken equal, in $\mathrm{kN}/m ^{ 2}$, to the greater value obtained from the following formulae:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image165.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image166.png)
    where:
    *p_S* : Static pressure due to the distributed load carried, if any
    *p_W* : Dynamic pressure due to the distributed load carried, in $\mathrm{kN}/m ^{ 2}$, taken equal to:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image167.png)
    *a_Z* : Vertical acceleration at the centre of gravity of the distributed load carried for the load case considered, in $\mathrm{m}/s ^{2}$, obtained by the formulae defined in Ch 4, Sec 2, [3.2]
    *p_D* : Pressure for the exposed deck, for the load case considered, as defined in [2.2.1] and [2.3.1].
  - **2.4.2** Concentrated forces due to unit load
    If a unit load is carried on an exposed deck, the static and dynamic forces due to the unit load carried are considered.
    The total force *F* due to this load is to be considered not simultaneously to the pressures defined in [2.2] and [2.3]. It is to be taken, in kN, equal to value obtained from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image168.png)
    where:
    *F_S* : Static force due to the unit load carried, in kN, taken equal to:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image169.png)
    *F_W* : Dynamic force due to unit load carried, in kN, taken equal to:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image170.png)
    *m_U* : Mass of the unit load carried, in t
    *a_Z* : Vertical acceleration at the centre of gravity of the unit load carried for the load case considered, in $\mathrm{m}/s ^{2}$, obtained by the formulae defined in Ch 4, Sec 2, [3.2].

#### 3. External pressures on superstructure and deckhouses

- **3.1** Exposed decks
  - **3.1.1** External pressures on exposed decks of superstructures and deckhouses are to be obtained according to [2].
- **3.2** Exposed wheel house tops
  - **3.2.1** The lateral pressure for exposed wheel house tops, in $\mathrm{kN}/m ^{ 2}$, is not to be taken less than:
    *p* = 12.5
- **3.3** Sides of superstructures
  - **3.3.1** The lateral pressure for sides of superstructures, in $\mathrm{kN}/m ^{ 2}$, is to be obtained from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image171.png)
    $f _{p}$ : Probability factor, taken equal to:
    $f _{P} = 1.0$ for plate panels
    $f _{P} = 0.75$ for ordinary stiffeners and primary supporting members
    $c _{F}$ : Distribution factor according to Table 6.
    Table 6: Distribution factor *c_F*

    | Location | $c _{F}$ |
    | --- | --- |
    | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image172.png) | $1.0+ \frac{5}{C _{B}} \left( 0.2- \frac{x}{L} \right)$, without taking $\frac{x}{L}$ less than 0.1 |
    | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image173.png) | 1.0 |
- **3.4** End bulkheads of superstructure and deckhouse walls
  - **3.4.1** The lateral pressure, in $\mathrm{kN}/m ^{ 2}$, for determining the scantlings is to be obtained from the greater of the following formulae:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image174.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image175.png)
    where:
    *n* : Coefficient defined in Table 7, depending on the tier level. The lowest tier is normally that tier which is directly situated above the uppermost continuous deck to which the depth D is to be measured. However, where the actual distance (*D–T*) exceeds the minimum non-corrected tabular freeboard according to ILLC as amended by at least one standard superstructure height as defined in Ch1, Sec4, [3.18.1], this tier may be defined as the 2^nd tier and the tier above as the 3^rd tier
    *c* : Coefficient taken equal to:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image176.png)
    For exposed parts of machinery casings, *c* is not to be taken less than 1.0
    $b _{1}$ : Breadth of deckhouse at the position considered
    $B _{1}$ : Actual maximum breadth of ship on the exposed weather deck at the position considered.
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image177.png)is not to be taken less than 0.25
    $b$ : Coefficient defined in Table 8
    $x$ : X co-ordinate, in m, of the calculation point for the bulkhead considered. When determining sides of a deckhouse, the deckhouse is to be subdivided into parts of approximately equal length, not exceeding 0.15 *L* each, and $x$ is to be taken as the X co-ordinate of the centre of each part considered.
    $z$ : *Z* co-ordinate, in m, of the midpoint of stiffener span, or to the middle of the plate field
    $\ell$ : Span, in m, to be taken as the superstructure height or deckhouse height respectively, and not less than 2.0 m
    *p_A*_min : Minimum lateral pressure, in $\mathrm{kN}/m ^{ 2}$, defined in Table 9.

    | Type of bulkhead | Location | *n* |
    | --- | --- | --- |
    | Unprotected front | Lowest tier | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image178.png) |
    | Unprotected front | Second tier | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image179.png) |
    | Unprotected front | Third tier and above | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image180.png) |
    | Protected<br>front | All tiers | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image181.png) |
    | Sides | All tiers | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image182.png) |
    | Aft end | Abaft amidships | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image183.png) |
    | Aft end | Forward of amidships | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image184.png) |

    | Location of bulkhead | *b* |
    | --- | --- |
    | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image185.png) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image186.png) |
    | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image187.png) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image188.png) |
    | Where:<br>$C_{ B}$ : Block coefficient with 0.6 ≤ $C_{ B}$ ≤ 0.8. When determining scantlings of aft ends forward of amidships,$C_{ B}$ need not be taken lessthan 0.8. |   |

    | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image189.png) | $P _{A \mathrm{\min}}$ ($\mathrm{kN}/m ^{ 2}$) |   |
    | --- | --- | --- |
    |   | Lowest tier of unprotected fronts | Elsewhere<sup>(1)</sup> |
    | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image190.png) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image191.png) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image192.png) |
    | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image193.png) | 50 | 25 |
    | (1) For the 4^th tier and above, $P _{A \mathrm{\min}}$ is to be taken equal to 12.5 $\mathrm{kN}/m ^{ 2}$. |   |   |

#### 4. Pressure in bow area

- **4.1**
  - **4.1.1** The bow pressure, in $\mathrm{kN}/m ^{ 2}$, to be considered for the reinforcement of the bow flare area is to be obtained from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image194.png)
    where:
    *p_S*, *p_W* : Hydrostatic pressure and maximum hydrodynamic pressures among load cases H, F, R and P at considered point of the hull in normal ballast condition. Minimum ballast draught in ballast condition ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image195.png) defined in Ch 1, Sec 4, [2.1.1] is to be considered as $T _{LCi}$ for the calculation of hydrostatic pressure and hydrodynamic pressures.
    *K* : Coefficient taken equal to:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image196.png) to be taken not less than 1.0
    *c_FL* : Coefficient taken equal to:
    *c_FL* = 0.8 in general
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image197.png) where the flare angle *a* is greater than 40°
    Where, the flare angle α at the load calculation point is to be measured in plane of the frame between a vertical line and the tangent to the side shell plating. (see Fig 6)
    ![Fig 6 : The definition of the flare angle](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image198.png)
    Fig 6 : The definition of the flare angle
- **4.2** Design bottom slamming pressure
  - **4.2.1** The bottom slamming pressure, in $\mathrm{kN}/m ^{ 2}$, to be considered for the reinforcement of the flat bottom forward is to be obtained from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image199.png) for *L* ≤ 150 m
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image200.png) for *L* > 150 m
    where:
    *c*_1 : Coefficient taken equal to:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image201.png), to be taken not greater than 1.0
    $T _{BFP}$ : Smallest design ballast draught, in m, defined at forward perpendicular for normal ballast conditions. Where the sequential method for ballast water exchange is intended to be ap plied, *T_BFP* is to be considered for the sequence of exchange.
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image202.png) : Distribution factor taken equal to(see Fig 7):
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image203.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image204.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image205.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image206.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image207.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image208.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image209.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image210.png)
    *c*_2 : Coefficient taken equal to:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image211.png), to be taken not greater than 0.35.
    ![Fig 7: Distribution Factor #imgID-214](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image212.png)
    Fig 7: Distribution Factor #imgID-214
  - **4.2.2** It is the Master’s responsibility to observe, among others, the weather conditions and the draught at forward perpendicular during water ballast exchange operations, in particular when the forward draught during these operations is less than *T_BFP*.
    The above requirement and the draught *T_BFP* is to be clearly indicated in the operating manuals.

#### 5. External pressures on hatch covers

- **5.1** General
  - **5.1.1** If a specific load is carried on a hatch cover, the pressure is to be obtained according to [2.4].
- **5.2** Wave pressure
  - **5.2.1** The pressure at any point of the hatch cover is to be obtained according to [2.2.1], considering $\varphi$ equal to 1.0.
    However, when the hatchway is located at least one superstructure standard height, as defined in Ch 1, Sec 4, [3.18], higher than the freeboard deck, the pressure *p_W* may be taken equal to 34.3 $\mathrm{kN}/m ^{ 2}$.


### Section 6 - INTERNAL PRESSURES AND FORCES

Symbols
For symbols not defined in this Section, refer to Ch 1, Sec 4.
$\rho _{C}$ : Density of the dry bulk cargo, in $\mathrm{t}/m ^{3}$, taken equal to:
• the value given in Table 1 for ships having a length *L* of 150 m and above
• the maximum density from the loading manual for ships having a length *L* less than 150 m

| Type of loading | Density |   |
| --- | --- | --- |
| Type of loading | BC-A, BC-B | BC-C |
| Cargo hold loaded up to the upper deck | max(*M_H/V_H*, 1.0) | 1.0 |
| Cargo hold not loaded up to the upper deck | 3.0<sup>(1)</sup> | - |
| (1) Except otherwise specified by the designer. |   |   |

$\rho _{L}$ : Density of internal liquid, in $\mathrm{t}/m ^{3}$, taken equal to 1.025 when internal liquid is ballast water
*M_H* : The actual cargo mass in a cargo hold corresponding to a homogeneously loaded condition at maximum draught, in t
*V_H* : Volume, in $\mathrm{m} ^{3}$, of cargo hold excluding the volume enclosed by hatch coaming
*K_C* : Coefficient taken equal to:
![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image213.png) for inner bottom, hopper tank, transverse and longitudinal bulkheads, lower stool, vertical upper stool, inner side and side shell:
![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image214.png) for top side tank, upper deck and sloped upper stool:
*a* : Angle, in deg, between panel considered and the horizontal plane
$\psi$ : Assumed angle of repose, in deg, of bulk cargo (considered drained and removed); in the absence of more precise evaluation, the following values may be taken:
$\psi$ = 30° in general
$\psi$ = 35° for iron ore
$\psi$ = 25° for cement
*h_C* : Vertical distance, in m, from the inner bottom to the upper surface of bulk cargo, as defined in [1.1.1] or [1.1.2]
*h_DB* : Height, in m, of the double bottom in the centreline
*h_LS* : Mean height, in m, of the lower stool, measured from the inner bottom
*z_TOP* : *Z* co-ordinate, in m, of the top of the tank, in upright condition
*z_BO* : *Z* co-ordinate, in m, of the top of the overflow pipe
*a_X* : Longitudinal acceleration at the centre of gravity of the hold or tank considered, in $\mathrm{m}/s ^{2}$, obtained by the formulae defined in Ch 4, Sec 2, [3.2]
*a_Y* : Transverse acceleration at the centre of gravity of the hold or tank considered, in $\mathrm{m}/s ^{2}$, obtained by the formulae defined in Ch 4, Sec 2, [3.2]
*a*_Z : Vertical acceleration at the centre of gravity of the hold or tank considered, in $\mathrm{m}/s ^{2}$, obtained by the formulae defined in Ch 4, Sec 2, [3.2]
*B_H* : Mean breadth of the cargo hold, in m
*b_IB* : Breadth of inner bottom, in m, as defined on Fig 2
*D*_1 : Distance, in m, from the base line to the freeboard deck at side amidships
*s_C* : Spacing of corrugations, in m; see Ch 3, Sec 6, Fig 28
*x*, *y*, *z* : *X*, *Y* and *Z* co-ordinates, in m, of the load point with respect to the reference co-ordinate system defined in Ch 1, Sec 4. *y* is to be taken positive on the weather side
*x_G*, *y_G*, *z_G*: *X*, *Y* and *Z* co-ordinates, in m, of the centre of gravity of the hold or tank considered with respect to the reference co-ordinate system defined in Ch 1, Sec 4
*d_AP* : Distance from the top of air pipe to the top of compartment, in m, taken equal to:
*d_AP* *= z_BO* - *z_TOP*

#### 1. Lateral pressure due to dry bulk cargo

- **1.1** Dry bulk cargo upper surface
  - **1.1.1** When the dry bulk cargo density is such that the cargo hold is loaded to the top of hatch coaming, the upper surface of the dry bulk cargo is an equivalent horizontal surface to be determined in considering the same loaded cargo volume in the considered hold bounded by the side shell or inner hull, as the case may be.
    For holds of cylindrical shape, the equivalent horizontal surface of the dry bulk cargo may be taken at a distance *h_C*, in m, above the inner bottom obtained from the following formula (see Fig 1):
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image215.png)
    where:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image216.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image217.png)
    *h_HPU* : Vertical distance, in m, between inner bottom and lower intersection of top side tank and side shell or inner side, as the case may be, as defined in Fig 1
    *S*_0 : Shaded area, in $\mathrm{m}^{ 2}$, above the lower intersection of top side tank and side shell or inner side, as the case may be, and up to the upper deck level, as defined in Fig 1
    *V*_HC : Volume, in $\mathrm{m} ^{3}$, enclosed by the hatch coaming.
    ![Fig 1: Definitions of h_C ,h_0, h_HPU and S_0](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image218.png)
    Fig 1: Definitions of *h_C* ,*h*_0, *h_HPU* and *S*_0
  - **1.1.2** When the dry bulk cargo density is such that the cargo hold is not loaded up to the upper deck, the upper surface of the dry bulk cargo is considered as having a plane surface of width *B_H*/2 in the centreline and inclined parts with an angle equal to half the angle of repose ($\psi /2$) at sides, and is to be determined in considering the same loaded cargo volume in the considered hold, taken equal to $M / \rho _{C}$.
    For holds of cylindrical shape, the upper surface of the dry bulk cargo may be taken at a distance *h_C*, in m, above the inner bottom obtained from the following formula (see Fig 2):
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image219.png)
    where:
    *h_HPL* : Vertical distance, in m, between inner bottom and upper intersection of hopper tank and inner side, as defined in Fig 2. *h_HPL* is to be taken equal to 0 if there is no hopper tank.
    *h*_1 : Vertical distance, in m, obtained from the following formula, see Fig 2.
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image220.png)
    *M* : Mass, in t, of the bulk cargo to be considered, as defined in Ch 4 Sec 7
    *V_TS* : Total volume, in $\mathrm{m} ^{3}$, of transverse stools at bottom of transverse bulk heads within the concerned cargo hold length l*_H*. This volume excludes the part of hopper tank passing through the transverse bulkhead.
    *h*_2 : Bulk cargo upper surface, in m, depending on *y*, given by:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image221.png), if ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image222.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image223.png), if ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image224.png)
    ![Fig 2: Definitions of h_C, h_1, h_2 and h_HPL](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image225.png)
    Fig 2: Definitions of *h_C*, *h*_1, *h*_2 and *h_HPL*
    For holds of non-cylindrical shape, and in case of prescriptive rule requirements, the upper surface of the bulk cargo may be taken at the upper deck level with a density of dry bulk cargo equal to *M/V_H*.
- **1.2** Dry bulk cargo pressure in still water
  - **1.2.1** The dry bulk cargo pressure in still water *p_CS*, in $\mathrm{kN}/m ^{ 2}$, is given by:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image226.png)
- **1.3** Inertial pressure due to dry bulk cargo
  - **1.3.1** The inertial pressure induced by dry bulk cargo *p_CW*, in $\mathrm{kN}/m ^{ 2}$, for each load case is given by the following formulae.
    • for load case H: ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image227.png)
    • for load case F: ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image228.png)
    • for load cases R and P: ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image229.png)
    (*x*-*x_G*) is to be taken as 0.25 l*_H* in the load case H1 or -0.25 l*_H* in the load case H2 for local strength by Ch 6 and fatigue check for longitudinal stiffeners by Ch 8.
    The total pressure (*p_CS* + *p_CW*) is not to be negative.
- **1.4** Shear load due to dry bulk cargo
  - **1.4.1** In order to evaluate the total force in the vertical direction, shear load due to dry bulk cargo acting along sloping plates in way of bilge hopper tank and lower stool is to be considered.
    The shear load due to dry bulk cargo acting along the sloping members in still water *p_CS-S* (positive down to inner bottom plating), in $\mathrm{kN}/m ^{ 2}$, is given by:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image230.png)
    The shear load due to dry bulk cargo acting along the sloping members in waves *p_CW-S* (positive down to inner bottom plating), in $\mathrm{kN}/m ^{ 2}$, is given by:
    • for load cases H, R and P: ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image231.png)
    • for load case F: ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image232.png)
  - **1.4.2** In order to evaluate the total force in the longitudinal and transverse directions, shear load due to dry bulk cargo in way of inner bottom plating is to be considered.
    The shear load due to dry bulk cargo in the longitudinal direction in waves *p_CW-S* (positive forward), in $\mathrm{kN}/m ^{ 2}$, is given by:
    • for load case H: *p_CW-S* = 0.75*r_C* *a*_X *h_C*
    • for load cases F, R and P: *p_CW-S* = 0
    The shear load due to dry bulk cargo in the transverse direction in waves *p_CW-S* (positive weather side), in $\mathrm{kN}/m ^{ 2}$, is given by:
    • for load cases R and P: *p_CW-S* = 0.75*r_C* *a*_Y *h_C*
    • for load cases H and F: *p_CW-S* = 0

#### 2. Lateral pressure due to liquid

- **2.1** Pressure due to liquid in still water
  - **2.1.1** The liquid pressure in still water *p_BS*, in $\mathrm{kN}/m ^{ 2}$, is given by the greater of the following values:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image233.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image234.png)
    where:
    *P_PV* : Setting pressure, in bar, of safety valves to be considered if any
    For local strength assessments, the static pressure *p_BS* is to be taken not less than 25 $\mathrm{kN}/m ^{ 2}$.
  - **2.1.2** When checking ballast water exchange operations by means of the flow through method, the static pressure *p_B* for local strength assessments and direct strength analysis by Ch 7 is to be not less than:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image235.png)
    Additional calculation may be required where piping or pumping arrangements may lead to a higher pressure.
  - **2.1.3** For fatigue strength assessment, the liquid pressure in still water *p_BS*, in $\mathrm{kN}/m ^{ 2}$, is given by the following formula.
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image236.png)
    If the *p_BS* is negative, *p_BS* is to be taken equal to 0.
    Where the considered load point is located in the fuel oil, other oils or fresh water tanks, liquids are assumed to be fulfilled up to the half height of the tanks and z*_TOP* is taken to the Z coordinate of the liquid surface at the upright condition.
- **2.2** Inertial pressure due to liquid
  - **2.2.1** The inertial pressure due to liquid *p_BW*, in $\mathrm{kN}/m ^{ 2}$, for each load case is given as follows. When checking ballast water exchange operations by means of the flow through method, the inertial pressure due to ballast water is not to be considered for local strength assessments and direct strength analysis.
    • for load case H: *p_BW* = *r_L*[*a_Z*(*z_TOP*–*z*)+*a_X*(*x*–*x_B*)]
    (*x*–*x_B*) is to be taken as 0.75 l*_H* in the load case H1 or -0.75 l*_H* in the load case H2 for local strength by Ch 6 and fatigue check for longitudinal stiffeners by Ch 8
    • for load case F: *p_BW* = 0
    • for load cases R and P: *p_BW* = *r_L*[*a_Z*(*z_B*–*z*)+*a_Y*(*y*–*y_B*)]
    where:
    *x_B* : X co-ordinate, in m, of the aft end of the tank when the bow side is downward, or of the fore end of the tank when the bow side is upward, as defined in Fig 3
    *y_B* : Y co-ordinate, in m, of the tank top located at the most lee side when the weather side is downward, or of the most weather side when the weather side is upward, as defined in Fig 3
    *z_B* : Z co-ordinate of the following point:
    • for completely filled spaces: the tank top
    • for ballast hold: the top of the hatch coaming
    The reference point *B* is defined as the upper most point after rotation by the angle $\varphi$ between the vertical axis and the global acceleration vector $\vec{A} _{G}$ shown in Fig 3. $\varphi$ is obtained from the following formulae:
    • load cases H1 and H2:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image237.png)
    • load cases R1(P1) and R2(P2):
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image238.png)
    where:
    *q* : Single roll amplitude, in deg, defined in Ch 4, Sec 2, [2.1.1]
    *F* : Single pitch amplitude, in deg, defined in Ch 4, Sec 2, [2.2.1]
    The total pressure (*p_BS*+*p_BW*) is not to be negative.
    ![Fig 3: Definition of x_B and y_B](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image239.png)
    Fig 3: Definition of *x_B* and *y_B*

#### 3. Lateral pressures and forces in flooded condition

- **3.1** Application
  - **3.1.1** The lateral pressures to be considered in flooded condition are indicated in:
    • [3.2] in general cases
    • [3.3] for the particular case of transverse corrugated bulkheads
    • [3.4] for the particular case of double bottom
- **3.2** General
  - **3.2.1** The pressure *p_F* to be considered as acting on plating (excluding bottom and side shell plating) which constitute boundaries of compartments not intended to carry liquids is to be obtained, in $\mathrm{kN}/m ^{ 2}$, from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image240.png), without being less than *gd*_0
    where:
    *z_F* : *Z* co-ordinate, in m, of the freeboard deck at side in way of the transverse section considered. Where the results of damage stability calculations are available, the deepest equilibrium waterline may be considered in lieu of the freeboard deck; in this case, the Society may require transient conditions to be taken into account
    *d*_0 : Distance, in m, to be taken equal to:
    *d*_0 = 0.02 *L* for 90 m ≤ *L* < 120 m
    *d*_0 = 2.4 for *L* ≥ 120 m
- **3.3** Transverse vertically corrugated watertight bulkheads
  - **3.3.1** Application
    Each cargo hold is to be considered individually flooded.
  - **3.3.2** General
    The loads to be considered as acting on each bulkhead are those given by the combination of those induced by cargo loads with those induced by the flooding of one hold adjacent to the bulkhead under examination. In any case, the pressure due to the flooding water alone is to be considered.
    The most severe combinations of cargo induced loads and flooding loads are to be used for the check of the scantlings of each bulkhead, depending on the loading conditions included in the loading manual:
    • homogeneous loading conditions
    • non-homogeneous loading conditions,
    considering the individual flooding of both loaded and empty holds.
    For the purpose of this item, homogeneous loading condition means a loading condition in which the ratio between the highest and the lowest filling ratio, evaluated for each hold, does not exceed 1.20, to be corrected for different cargo densities.
    Non-homogeneous part loading conditions associated with multiport loading and unloading operations for homogeneous loading conditions need not be considered according to these requirements.
    The specified design load limits for the cargo holds are to be represented by loading conditions defined by the Designer in the loading manual.
    For the purpose of this item, holds carrying packed cargoes are to be considered as empty.
    Unless the ship is intended to carry, in non-homogeneous conditions, only iron ore or cargo having bulk density equal to or greater than 1.78 $\mathrm{t}/m ^{3}$, the maximum mass of cargo which may be carried in the hold is also to be considered to fill that hold up to the upper deck level at centreline.
  - **3.3.3** Flooding level
    The flooding level *z_F* is the distance, in m, measured vertically from the base line with the ship in the upright position, and equal to:
    • in general:
    • *D1* for the foremost transverse corrugated bulkhead
    • 0.9 *D1* for other bulkheads;
    where the ship is to carry cargoes having bulk density less than 1.78 $\mathrm{t}/m ^{3}$ in non-homogeneous loading conditions, the following values may be assumed:
    • 0.95 *D1* for the foremost transverse corrugated bulkhead
    • 0.85 *D1* for other bulkheads
    • for ships less than 50000 *t* deadweight with type B freeboard:
    • 0.95 *D1* for the foremost transverse corrugated bulkhead
    • 0.85 *D1* for other bulkheads;
    where the ship is to carry cargoes having bulk density less than 1.78 $\mathrm{t}/m ^{3}$ in non-homogeneous loading conditions, the following values may be assumed:
    • 0.9 *D1* for the foremost transverse corrugated bulkhead
    • 0.8 *D1* for other bulkheads.
  - **3.3.4** Pressures and forces on a corrugation in non-flooded bulk cargo loaded holds
    At each point of the bulkhead, the pressure is to be obtained, in $\mathrm{kN}/m ^{ 2}$, from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image241.png)
    The force acting on a corrugation is to be obtained, in kN, from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image242.png)
  - **3.3.5** Pressures and forces on a corrugation in flooded bulk cargo loaded holds
    Two cases are to be considered, depending on the values of *z_F* and *h_C* (see [3.3.3] and [1.1]):
    • First case, when *z_F* *≥* *h_C* + *h_DB*
    At each point of the bulkhead located at a distance between *z_F* and *h_C* + *h_DB* from the base line, the pressure, in $\mathrm{kN}/m ^{ 2}$, is to be obtained from the following formula:
    *p_B*_,*_F* = *rg*(*z_F*–*z*)
    At each point of the bulkhead located at a distance lower than hC+hDB from the base line, the pressure, in $\mathrm{kN}/m ^{ 2}$, is to be obtained from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image243.png)
    where perm is the permeability of cargo, to be taken as 0.3 for iron ore, coal cargoes and cement.
    The force acting on a corrugation is to be obtained, in kN, from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image244.png)
    where (*p_B*_,*_F*)*_LE* is the pressure *p_B*_,*_F*, in $\mathrm{kN}/m ^{ 2}$, calculated at the lower edge of the corrugation.
    • Second case, when *z_F* < *h_C* + *h_DB*
    At each point of the bulkhead located at a distance between *z_F* and *h_C* + *h_DB* from the base line, the pressure is to be obtained, in $\mathrm{kN}/m ^{ 2}$, from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image245.png)
    At each point of the bulkhead located at a distance lower than *z_F* from the base line, the pressure is to be obtained, in $\mathrm{kN}/m ^{ 2}$, from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image246.png)
    where perm is the permeability of cargo, to be taken as 0.3 for iron ore, coal cargoes and cement.
    The force acting on a corrugation is to be obtained, in kN, from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image247.png)
    where (*p_B,F*)*_LE* is the pressure *p_B,F*, in $\mathrm{kN}/m ^{ 2}$, calculated at the lower edge of the corrugation.
  - **3.3.6** Pressures and forces on a corrugation in flooded empty holds
    At each point of the bulkhead, the still water pressure induced by the flooding to be considered is to be obtained, in $\mathrm{kN}/m ^{ 2}$, from the following formula:
    *p_F* = *rg*(*z_F*–*z*)
    The force acting on a corrugation is to be obtained, in kN, from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image248.png)
  - **3.3.7** Resultant pressures and forces
    Resultant pressures and forces to be calculated for homogeneous and non-homogeneous loading conditions are to be obtained according to the following formulae:
    • Homogeneous loading conditions
    At each point of the bulkhead structures, the resultant pressure to be considered for the scantlings of the bulkhead is to be obtained, in $\mathrm{kN}/m ^{ 2}$, from the following formula:
    *p* = *p_B,F*–0.8*p_B*
    The resultant force acting on a corrugation is to be obtained, in kN, from the following formula:
    *F = F_B,F*–0.8*F_B*
    where:
    *p_B* : Pressure in the non-flooded holds, in $\mathrm{kN}/m ^{ 2}$, to be obtained as specified in [3.3.4]
    *p_B*_,*_F* : Pressure in the flooded holds, in $\mathrm{kN}/m ^{ 2}$, to be obtained as specified in [3.3.5]
    *F_B*_,*_F* : Force acting on a corrugation in the flooded holds, in kN, to be obtained as specified in [3.3.5].
    *F_B* : Force acting on a corrugation in non-flooded holds, in kN, to be obtained as specified in [3.3.4].
    • Non-homogeneous loading conditions
    At each point of the bulkhead structures, the resultant pressure to be considered for the scantlings of the bulkhead is to be obtained, in $\mathrm{kN}/m ^{ 2}$, by the following formula:
    *p* = *p_B*_,*_F*
    The resultant force acting on a corrugation is to be obtained, in kN, by the following formula:
    *F* = *F_B*_,*_F*
    where:
    *p_B*_,*_F* : Pressure in the flooded holds $\mathrm{kN}/m ^{ 2}$, to be obtained as specified in [3.3.5]
    *F_B*_,*_F* : Force acting on a corrugation in the flooded holds $\mathrm{kN}/m ^{ 2}$, to be obtained as specified in [3.3.5].
- **3.4** Double bottom
  - **3.4.1** Application
    Each cargo hold is to be considered individually flooded.
  - **3.4.2** General
    The loads to be considered as acting on the double bottom are those given by the external sea pressures and the combination of the cargo loads with those induced by the flooding of the hold which the double bottom belongs to.
    The most severe combinations of cargo induced loads and flooding loads are to be used, depending on the loading conditions included in the loading manual:
    • homogeneous loading conditions
    • non-homogeneous loading conditions
    • packed cargo conditions (such as in the case of steel mill products).
    For each loading condition, the maximum dry bulk cargo density to be carried is to be considered in calculating the allowable hold loading.
  - **3.4.3** Flooding level
    The flooding level *z_F* is the distance, in m, measured vertically from the base line with the ship in the upright position, and equal to:
    • for ships less than 50000 t deadweight with type B freeboard:
    • 0.95 ${D} _{1}$ for the foremost hold
    • 0.85 ${D} _{1}$ for other holds;
    • for other ships:
    • ${D} _{1}$ for the foremost hold
    • 0.9 ${D} _{1}$for other holds;

#### 4. Testing lateral pressure

- **4.1** Still water pressures
  - **4.1.1** The total pressure to be considered as acting on plates and stiffeners subject to tank testing is obtained, in $\mathrm{kN}/m ^{ 2}$, from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image249.png)
    where:
    *z_ST* : Testing load height, in m, as defined in Table 2.
    Table 2: Testing load height

    | Compartment or structure to be tested | Testing load height, in m |
    | --- | --- |
    | Double bottom tanks | The greater of the following:<br>*z_ST* *= z_TOP* *+ d_AP*<br>*z_ST* *= z_ml* |
    | Hopper side tanks, topside tanks, double side tanks, fore and after peaks used as tank, cofferdams | The greater of the following:<br>*z_ST* *= z_TOP* *+ d_AP*<br>*z_ST* = *z_TOP* + 2.4 |
    | Tank bulkheads, deep tanks, fuel oil bunkers | The greater of the following:<br>*z_ST* = *z_TOP* + *d_AP*<br>*z_ST* = *z_TOP* + 2.4<br>*z_ST* = *z_TOP* + 10 *p_PV* |
    | Ballast hold | The greater of the following:<br>*z_ST* = *z_TOP* + *d_AP*<br>*z_ST* = *z_h* + 0.9 |
    | Fore and aft peak not used as tank | The greater of the following:<br>*z_ST* = *z_F*<br>*z_ST* = *z_ml* |
    | Watertight doors below freeboard deck | *z_ST* = *z_fd* |
    | Chain locker (if aft of collision bulkhead) | *z_ST* = *z_TOP* |
    | Independent tanks | The greater of the following:<br>*z_ST* = *z_TOP* + *d_AP*<br>*z_ST* = *z_TOP* + 0.9 |
    | Ballast ducts | Testing load height corresponding to ballast pump maximum pressure |
    | where:<br>*z_ml* : Z co-ordinate, in m, of the bulkhead deck at side.<br>*z_h* : Z co-ordinate, in m, of the top of hatch coaming.<br>*z_F* : As defined in [3.2.1].<br>*z_fd* : Z co-ordinate, in m, of the freeboard deck.<br>*p_PV* : Setting pressure, in bar, of safety valves. |   |


### Section 7 - LOADING CONDITIONS

Symbols
*M_H* : The actual cargo mass in a cargo hold corresponding to a homogeneously loaded condition at maximum draught, in t
*M_Full* : The cargo mass in a cargo hold corresponding to cargo with virtual density (homogenous mass / hold cubic capacity, minimum 1.0 $\mathrm{t}/m ^{3}$) filled to the top of the hatch coaming, in t.
![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image250.png)
*M_Full* is in no case to be less than *M_H*
*M_HD* : The maximum cargo mass allowed to be carried in a cargo hold according to design loading condition(s) with specified holds empty at maximum draught, in t
*V_Full* : Volume, in $\mathrm{m} ^{3}$, of the cargo hold including the volume enclosed by the hatch coaming
*V_H* : Volume, in $\mathrm{m} ^{3}$, defined in Ch4, Sec6
*T_HB* : Deepest ballast draught, in m.

#### 1. Application

- **1.1** Ships having a length *L* less than 150 m
  - **1.1.1** The severest loading conditions from the loading manual, midship section drawing or otherwise specified by the Designer are to be considered for the longitudinal strength according to Ch 5, Sec 1 and for the local strength check of plating, ordinary stiffeners and primary supporting members according to Ch 6.
- **1.2** Ships having a length *L* of 150 m and above
  - **1.2.1** The requirements in [2] to [4] are applicable to ships having a length *L* of 150 m and above.
  - **1.2.2** These requirements are not intended to prevent any other loading conditions to be included in the loading manual for which calculations are to be submitted. It is not intended to replace in any way the required loading manual/instrument.
  - **1.2.3** The maximum loading condition draught is to be taken as the moulded summer load line draught.
  - **1.2.4** The loading conditions listed in [2] are to be applied for the check of longitudinal strength as required by Ch 5, Sec 1, the check of local strength by Ch 6, the direct strength analysis by Ch 7, for capacity and disposition of ballast tanks and stability purposes. The loading conditions listed in [3] are to be applied for the check of local strength. The loading conditions listed in [4] are to be applied for direct strength analysis.
  - **1.2.5** In operation, a bulk carrier may be loaded differently from the design loading conditions specified in the loading manual, provided longitudinal and local strength as defined in the loading manual and onboard loading instrument and applicable stability requirements are not exceeded.

#### 2. General

- **2.1** Design loading conditions - General
  - **2.1.1** For the determination of the maximum cargo mass in cargo holds, the condition corresponding to the ship being loaded at maximum draught with 50% of consumables is to be considered.
  - **2.1.2** BC-C
    Homogeneous cargo loaded condition where the cargo density corresponds to all cargo holds, including hatchways, being 100 % full at maximum draught with all ballast tanks empty.
  - **2.1.3** BC-B
    As required for BC-C, plus:
    Homogeneous cargo loaded condition with cargo density 3.0 $\mathrm{t}/m ^{3}$, and the same filling ratio (cargo mass/hold cubic capacity) in all cargo holds at maximum draught with all ballast tanks empty.
    In cases where the cargo density applied for this design loading condition is less than 3.0 $\mathrm{t}/m ^{3}$, the maximum density of the cargo that the ship is allowed to carry is to be indicated with the additional service feature **{**maximum cargo density x.y $\mathrm{t}/m ^{3}$.}
  - **2.1.4** BC-A
    As required for **BC-B**, plus:
    At least one cargo loaded condition with specified holds empty, with cargo density 3.0 $\mathrm{t}/m ^{3}$, and the same filling ratio (cargo mass/hold cubic capacity) in all loaded cargo holds at maximum draught with all ballast tanks empty.
    The combination of specified empty holds is to be indicated with the additional service feature **{**holds a, b,... may be empty**.**}
    In such cases where the design cargo density applied is less than 3.0 $\mathrm{t}/m ^{3}$, the maximum density of the cargo that the ship is allowed to carry is to be indicated within the additional service feature **{**holds a, b,... maybe empty with maximum cargo density x.y $\mathrm{t}/m ^{3}$**.**}
- **2.2** Applicable ballast conditions
  - **2.2.1** Ballast tank capacity and disposition
    All bulk carriers are to have ballast tanks of sufficient capacity and so disposed to at least fulfill the following requirements.
    Normal ballast condition
    Normal ballast condition is a ballast (no cargo) condition where:
    • the ballast tanks may be full, partially full or empty. Where ballast tanks are partially full, the conditions in Ch 4, Sec 3 are to be complied with
    • any cargo hold or holds adapted for the carriage of water ballast at sea are to be empty
    • the propeller is to be fully immersed, and
    • the trim is to be by the stern and is not to exceed 0.015 $L _{BP}$.
    In the assessment of the propeller immersion and trim, the draughts at the forward and after perpendiculars may be used.
    Heavy ballast condition
    Heavy ballast condition is a ballast (no cargo) condition where:
    • the ballast tanks may be full, partially full or empty. Where ballast tanks are partially full, the conditions in Ch 4, Sec 3 are to be complied with
    • at least one cargo hold adapted for carriage of water ballast at sea is to be full
    • the propeller immersion *I/D* is to be at least 60 %, where:
    *I* = Distance from propeller centerline to the waterline
    *D* = Propeller diameter
    • the trim is to be by the stern and is not to exceed 0.015 $L _{BP}$
    • the moulded forward draught in the heavy ballast condition is not to be less than the smaller of 0.03 $L _{BP}$ or 8 m.
  - **2.2.2** Strength requirements
    All bulk carriers are to meet the following strength requirements:
    Normal ballast condition:
    • the structures of bottom forward are to be strengthened in accordance with the Rules against slamming for the condition of [2.2.1] for normal ballast condition at the lightest forward draught,
    • the longitudinal strength requirements according to Ch 4, Sec 3 are to be met for the condition of [2.2.1] for normal ballast condition, and
    • in addition, the longitudinal strength requirements according to Ch 4, Sec 3 are to be met with all ballast tanks 100 % full.
    Heavy ballast condition:
    • the longitudinal strength requirements according to Ch 4, Sec 3 are to be met for the condition of [2.2.1] for heavy ballast condition
    • in addition, the longitudinal strength requirements according to Ch 4, Sec 3 are to be met with all ballast tanks 100 % full and one cargo hold adapted and designated for the carriage of water ballast at sea, where provided, 100 % full, and
    • where more than one hold is adapted and designated for the carriage of water ballast at sea, it will not be required that two or more holds be assumed 100 % full simultaneously in the longitudinal strength assessment, unless such conditions are expected in the heavy ballast condition. Unless each hold is individually investigated, the designated heavy ballast hold and any/all restrictions for the use of other ballast hold(s) are to be indicated in the loading manual.
  - **2.3.1** Unless otherwise specified, each of the design loading conditions defined in [2.1] and [2.2] is to be investigated for the arrival and departure conditions as defined as follows:
    • Departure condition : with bunker tanks not less than 95 % full and other consumables 100 %
    • Arrival condition : with 10 % of consumables

#### 3. Design loading conditions for local strength

- **3.1** Definitions
  - **3.1.1** The maximum allowable or minimum required cargo mass in a cargo hold, or in two adjacently loaded holds, is related to the net load on the double bottom. The net load on the double bottom is a function of draft, cargo mass in the cargo hold, as well as the mass of fuel oil and ballast water contained in double bottom tanks.
- **3.2** Applicable general conditions
  - **3.2.1** Any cargo hold is to be capable of carrying *M_Full* with fuel oil tanks in double bottom in way of the cargo hold, if any, being 100 % full and ballast water tanks in the double bottom in way of the cargo hold being empty, at maximum draught.
  - **3.2.2** Any cargo hold is to be capable of carrying minimum 50 % of *M_H*, with all double bottom tanks in way of the cargo hold being empty, at maximum draught.
  - **3.2.3** Any cargo hold is to be capable of being empty, with all double bottom tanks in way of the cargo hold being empty, at the deepest ballast draught.
- **3.3** Additional conditions applicable except when additional service feature {no MP} is assigned
  - **3.3.1** Any cargo hold is to be capable of carrying *M_Full* with fuel oil tanks in double bottom in way of the cargo hold, if any, being 100 % full and ballast water tanks in the double bottom in way of the cargo hold being empty, at 67 % of maximum draught.
  - **3.3.2** Any cargo hold is to be capable of being empty with all double bottom tanks in way of the cargo hold being empty, at 83 % of maximum draught.
  - **3.3.3** Any two adjacent cargo holds are to be capable of carrying *M_Full* with fuel oil tanks in double bottom in way of the cargo hold, if any, being 100 % full and ballast water tanks in the double bottom in way of the cargo hold being empty, at 67 % of the maximum draught. This requirement to the mass of cargo and fuel oil in double bottom tanks in way of the cargo hold applies also to the condition where the adjacent hold is filled with ballast, if applicable.
  - **3.3.4** Any two adjacent cargo holds are to be capable of being empty, with all double bottom tanks in way of the cargo hold being empty, at 75 % of maximum draught.
- **3.4** Additional conditions applicable for BC-A only
  - **3.4.1** Cargo holds, which are intended to be empty at maximum draught, are to be capable of being empty with all double bottom tanks in way of the cargo hold also being empty.
  - **3.4.2** Cargo holds, which are intended to be loaded with high density cargo, are to be capable of carrying *M_HD* plus 10 % of *M_H*, with fuel oil tanks in the double bottom in way of the cargo hold, if any, being 100 % full and ballast water tanks in the double bottom being empty in way of the cargo hold, at maximum draught.
    In operation the maximum allowable cargo mass shall be limited to *M_HD*.
  - **3.4.3** Any two adjacent cargo holds which according to a design loading condition may be loaded with the next holds being empty, are to be capable of carrying 10% of *M_H* in each hold in addition to the maximum cargo load according to that design loading condition, with fuel oil tanks in the double bottom in way of the cargo hold, if any, being 100 % full and ballast water tanks in the double bottom in way of the cargo hold being empty, at maximum draught.
    In operation the maximum allowable mass shall be limited to the maximum cargo load according to the design loading conditions.
- **3.5** Additional conditions applicable for ballast hold(s) only
  - **3.5.1** Cargo holds, which are designed as ballast water holds, are to be capable of being 100 % full of ballast water including hatchways, with all double bottom tanks in way of the cargo hold being 100 % full, at any heavy ballast draught. For ballast holds adjacent to topside wing, hopper and double bottom tanks, it shall be strengthwise acceptable that the ballast holds are filled when the topside wing, hopper and double bottom tanks are empty.
- **3.6** Additional conditions applicable during loading and unloading in harbour only
  - **3.6.1** Any single cargo hold is to be capable of holding the maximum allowable seagoing mass at 67 % of maximum draught, in harbour condition.
  - **3.6.2** Any two adjacent cargo holds are to be capable of carrying *M_Full*, with fuel oil tanks in the double bottom in way of the cargo hold, if any, being 100 % full and ballast water tanks in the double bottom in way of the cargo hold being empty, at 67 % of maximum draught, in harbour condition.
  - **3.6.3** At reduced draught during loading and unloading in harbour, the maximum allowable mass in a cargo hold may be increased by 15 % of the maximum mass allowed at the maximum draught in sea-going condition, but shall not exceed the mass allowed at maximum draught in the sea-going condition. The minimum required mass may be reduced by the same amount.
- **3.7** Hold mass curves
  - **3.7.1** Based on the design loading criteria for local strength, as given in [3.2] to [3.6] except [3.5.1], hold mass curves are to be included in the loading manual and the loading instrument, showing maximum allowable and minimum required mass as a function of draught in sea-going condition as well as during loading and unloading in harbour. Hold mass curves are to be calculated according to Ch 4, App 1.
  - **3.7.2** At other draughts than those specified in the design loading conditions, the maximum allowable and minimum required mass is to be adjusted for the change in buoyancy acting on the bottom. Change in buoyancy is to be calculated using water plane area at each draught.
    Hold mass curves for each single hold, as well as for any two adjacent holds, are to be included in the loading manual and the loading instrument.

#### 4. Design loading conditions for direct strength analysis

- **4.1** Loading patterns
  - **4.1.1** The loading patterns applicable to types of bulk carriers with various service feature notations are summarized in Table 1, which are to be considered in direct strength analysis in accordance with [2] and [3].
    Table 1: Applicable loading patterns according to additional service features

    | No. | Loading pattern | Ref. | BC- |   |   | BC-,(no MP) |   |   |
    | --- | --- | --- | --- | --- | --- | --- | --- | --- |
    | No. | Loading pattern | Ref. | A | B | C | A | B | C |
    | 1 | Full load in homogeneous condition | 3.2.1 | x | x | x | x | x | x |
    | 2 | Slack load | 3.2.2 | x | x | x | x | x | x |
    | 3 | Deepest ballast | 3.2.3 | x | x | x | x | x | x |
    |   |   |   |   |   |   |   |   |   |
    | 4 | Multiport -1 | 3.3.1 | x | x | x |   |   |   |
    | 5 | Multiport -2 | 3.3.2 | x | x | x |   |   |   |
    | 6 | Multiport -3 | 3.3.3 | x | x | x |   |   |   |
    | 7 | Multiport -4 | 3.3.4 | x | x | x |   |   |   |
    |   |   |   |   |   |   |   |   |   |
    | 8 | Alternate load | 3.4.1 ＆ .2 | x |   |   | x |   |   |
    | 9 | Alternate block load | 3.4.3 | x |   |   | x |   |   |
    |   |   |   |   |   |   |   |   |   |
    | 10 | Heavy ballast | 3.5.1 | x | x | x | x | x | x |
    |   |   |   |   |   |   |   |   |   |
    | 11 | Harbour condition -1 | 3.6.1 |   |   |   | x | x | x |
    | 12 | Harbour condition -2 | 3.6.2 |   |   |   | x | x | x |
  - **4.1.2** Other loading conditions from the loading manual, which are not covered in Table 1, if any, are also to be considered.
- **4.2** Still water bending moment and shear force
  - **4.2.1** Load cases defined in Sec 4 are to be considered for each loading pattern given in Table 1. The still water vertical bending moment provided in Table 2 and the still water vertical shear force provided in Table 3 are to be used for each combination of loading pattern and load case.
  - **4.2.2** If one loading condition in the loading manual has a still water vertical bending moment more severe than the value in Table 2 for the corresponding loading pattern, the value in Table 2 for this loading pattern is to be replaced with the value from the loading manual.
- **4.3** Application
  - **4.3.1** The minimum required loading conditions for direct strength analysis, including vertical shear force analysis, are defined in Ch 4, App 2.
  - **4.3.2** The standard loading conditions for fatigue assessment are defined in Ch 4, App 3.

    |   |   | Loading pattern |   |   |   |   |
    | --- | --- | --- | --- | --- | --- | --- |
    |   |   | Full load in homogeneous condition | Slack load | Multiport | Heavy ballast<br>(Ballast hold) | Harbour condition |
    |   |   | Full load in homogeneous condition | Alternate load | Alternate block load | Heavy ballast<br>(Ballast hold) | Harbour condition |
    |   |   | Full load in homogeneous condition | Normal ballast | Deepest ballast | Heavy ballast<br>(Ballast hold) | Harbour condition |
    | load case | H1 | 0.5 $M _{SW,S}$ | 0 | $M _{SW,S}$ | $M _{SW,S}$ | --- |
    | load case | H2 | 0.5 $M _{SW,H}$ | $M _{SW,H}$ | $M _{SW,H}$ | 0 | --- |
    | load case | F1 | 0.5 $M _{SW,S}$ | 0 | $M _{SW,S}$ | $M _{SW,S}$ | --- |
    | load case | F2 | 0.5 $M _{SW,H}$ | $M _{SW,H}$ | $M _{SW,H}$ | 0 | --- |
    | load case | R1 | 0.5 $M _{SW,S}$ | 0 | $M _{SW,S}$ | $M _{SW,S}$ | --- |
    | load case | R1 | 0.5 $M _{SW,H}$ | $M _{SW,H}$ | $M _{SW,H}$ | 0 | --- |
    | load case | R2 | 0.5 $M _{SW,S}$ | 0 | $M _{SW,S}$ | $M _{SW,S}$ | --- |
    | load case | R2 | 0.5 $M _{SW,H}$ | $M _{SW,H}$ | $M _{SW,H}$ | 0 | --- |
    | load case | P1 | 0.5 $M _{SW,S}$ | 0 | $M _{SW,S}$ | $M _{SW,S}$ | --- |
    | load case | P2 | 0.5 $M _{SW,H}$ | $M _{SW,H}$ | $M _{SW,H}$ | 0 | --- |
    | load case | Static | --- |   |   |   | $M _{SW,P,S}$ |
    | load case | Static | --- |   |   |   | $M _{SW,P,H}$ |

    where:
    $M _{SW,H}$ : Allowable still water vertical bending moment in hogging condition for seagoing condition
    $M _{SW,S}$ : Allowable still water vertical bending moment in sagging condition for seagoing condition
    $M _{SW,P,H}$ : Allowable still water vertical bending moment in hogging condition for harbour condition
    $M _{SW,P,S}$ : Allowable still water vertical bending moment in sagging condition for harbour condition
    Table 3: Vertical still water shear force

    |   |   | Loading pattern |   |   |   |   |
    | --- | --- | --- | --- | --- | --- | --- |
    |   |   | Full load in homogeneous condition | Alternate load<br>(BC-A) | Multiport<br>(BC-B and<br>BC-C) | Heavy ballast<br>(Ballast hold) | Heavy ballast<br>(Except for<br>ballast hold) |
    | Load case | H1 | --- | $Q _{SW}$ | $Q _{SW}$ | $Q _{SW}$ | --- |
    | Load case | H2 | --- | $Q _{SW}$ | $Q _{SW}$ | $Q _{SW}$ | --- |
    | Load case | F1 | --- | $Q _{SW}$ | $Q _{SW}$ | $Q _{SW}$ | --- |
    | Load case | F2 | --- | $Q _{SW}$ | $Q _{SW}$ | $Q _{SW}$ | --- |

    where:
    $Q _{SW}$ : Allowable still water shear force at the position of the considered transverse bulkhead


### Section 8 - LOADING MANUAL AND LOADING INSTRUMENT

#### 1. General

- **1.1** All ships
  - **1.1.1** An approved loading manual is to be supplied on board for all ships.
    In addition, an approved loading instrument is to be supplied for all ships.
    The loading instrument is ship specific onboard equipment and the results of the calculations are only applicable to the ship for which it has been approved.
    An approved loading instrument may not replace an approved loading manual.
- **1.2** Ships equal to or greater than 150 m in length *L*
  - **1.2.1** BC-A, BC-B, and BC-C ships are to be provided with an approved loading manual and an approved computer-based loading instrument, in accordance with the applicable requirements of this Section.
    A guidance for loading and unloading sequences is given in [5].

#### 2. Loading manual

- **2.1** Definitions
  - **2.1.1** All ships
    A loading manual is a document which describes:
    • the loading conditions on which the design of the ship has been based, including permissible limits of still water bending moment and shear force. The conditions specified in the ballast water exchanging procedure and dry docking procedure are to be included in the loading manual.
    • the results of the calculations of still water bending moments and shear forces
    • the allowable local loading for the structure (hatch covers, decks, double bottom, etc.).
  - **2.1.2** Ships equal to or greater than 150 m in length *L*
    In addition to [2.1.1], for BC-A, BC- and BC-C ships, the loading manual is also to describe:
    • envelope results and permissible limits of still water bending moments and shear forces in the hold flooded condition according to Ch 5, Sec 1
    • the cargo hold(s) or combination of cargo holds that might be empty at full draught. If no cargo hold is allowed to be empty at full draught, this is to be clearly stated in the loading manual
    • maximum allowable and minimum required mass of cargo and double bottom contents of each hold as a function of the draught at mid-hold position
    • maximum allowable and minimum required mass of cargo and double bottom contents of any two adjacent holds as a function of the mean draught in way of these holds. This mean draught may be calculated by averaging the draught of the two mid-hold positions
    • maximum allowable tank top loading together with specification of the nature of the cargo for cargoes other than bulk cargoes
    • maximum allowable load on deck and hatch covers. If the ship is not approved to carry load on deck or hatch covers, this is to be clearly stated in the loading manual
    • maximum rate of ballast change together with the advice that a load plan is to be agreed with the terminal on the basis of the achievable rates of change of ballast.
- **2.2** Conditions of approval
  - **2.2.1** All ships
    The approved loading manual is to be based on the final data of the ship. The manual is to include the design (cargo and ballast) loading conditions, subdivided into departure and arrival conditions as appropriate, upon which the approval of the hull scantlings is based.
    In the case of modifications resulting in changes to the main data of the ship, a new approved loading manual is to be issued.
  - **2.2.2** Ships equal to or greater than 150 m in length *L*
    In addition to [2.2.1], for BC-A, BC-B and BC-C ships, the following loading conditions, subdivided into departure and arrival conditions as appropriate, are also to be included in the loading manual:
    • homogeneous light and heavy cargo loading conditions at maximum draught
    • alternate light and heavy cargo loading conditions at maximum draught, where applicable
    • ballast conditions. For ships having ballast holds adjacent to topside wing, hopper and double bottom tanks, it shall be strengthwise acceptable that the ballast holds are filled when the topside wing, hopper and double bottom tanks are empty
    • short voyage conditions where the ship is to be loaded to maximum draught but with limited amount of bunkers
    • multiple port loading / unloading conditions
    • deck cargo conditions, where applicable
    • typical loading sequences where the ship is loaded from commencement of cargo loading to reaching full deadweight capacity, for homogeneous conditions, relevant part load conditions and alternate conditions where applicable. Typical unloading sequences for these conditions are also to be included. The typical loading / unloading sequences are also to be developed to not exceed applicable strength limitations. The typical loading sequences are also to be developed paying due attention to loading rate and the deballasting capability. Table 1 contains, as guidance only, an example of a Loading Sequence Summary Form
    • typical sequences for change of ballast at sea, where applicable.
- **2.3** Language
  - **2.3.1** The loading manual is to be prepared in a language understood by the users. If this language is not English, a translation into English is to be included.

#### 3. Loading instrument

- **3.1** Definitions
  - **3.1.1** All ships
    A loading instrument is an instrument which is either analog or digital and by means of which it can be easily and quickly ascertained that, at specified read-out points, the still water bending moments, shear forces, in any load or ballast condition, do not exceed the specified permissible values.
  - **3.1.2** Ships equal to or greater than 150 m in length *L*
    For BC-A, BC-B and BC-C ships, the loading instrument is an approved digital system as defined in [3.1.1]. In addition to [3.1.1], it is also to ascertain as applicable that:
    • the mass of cargo and double bottom contents in way of each hold as a function of the draught at mid-hold position
    • the mass of cargo and double bottom contents of any two adjacent holds as a function of the mean draught in way of these holds
    • the still water bending moment and shear forces in the hold flooded conditions do not exceed the specified permissible values.
- **3.2** Conditions of approval
  - **3.2.1** All ships
    The loading instrument is subject to approval, which is to include:
    • verification of type approval, if any
    • verification that the final data of the ship have been used
    • acceptance of number and position of all read-out points
    • acceptance of relevant limits for read-out points
    • checking of proper installation and operation of the instrument on board, under agreed test conditions, and that a copy of the operation manual is available.
  - **3.2.2** Ships equal to or greater than 150 m in length *L*
    In addition, for BC-A, BC-B and BC-C ships, the approval is also to include, asapplicable:
    • acceptance of hull girder bending moment limits for all read-out points
    • acceptance of hull girder shear force limits for all read-out points
    • acceptance of limits for the mass of cargo and double bottom contents of each hold as a function of draught
    • acceptance of limits for the mass of cargo and double bottom contents in any two adjacent holds as a function of draught.
  - **3.2.3** In the case of modifications implying changes in the main data of the ship, the loading instrument is to be modified accordingly and approved.
  - **3.2.4** An operational manual is always to be provided for the loading instrument.
    The operation manual and the instrument output are to be prepared in a language understood by the users. If this language is not English, a translation into English is to be included.
  - **3.2.5** The operation of the loading instrument is to be verified upon installation under the agreed test conditions. It is to be checked that the agreed test conditions and the operation manual for the instrument are available on board.

#### 4. Annual and class renewal survey

- **4.1** General
  - **4.1.1** At each annual and class renewal survey, it is to be checked that the approved loading manual is available on board.
  - **4.1.2** The loading instrument is to be checked for accuracy at regular intervals by the ship's Master by applying test loading conditions.
  - **4.1.3** At each class renewal survey this checking is to be done in the presence of the Surveyor.

#### 5. Guidance for loading/unloading sequences

- **5.1** General
  - **5.1.1** The typical loading/unloading sequences shall be developed paying due attention to the loading/unloading rate, the ballasting/deballasting capacity and the applicable strength limitations.
  - **5.1.2** The shipbuilder will be required to prepare and submit for approval typical loading and unloading sequences.
  - **5.1.3** The typical loading sequences as relevant should include:
    • alternate light and heavy cargo load condition
    • homogeneous light and heavy cargo load condition
    • short voyage condition where the ship is loaded to maximum draught but with limited bunkers
    • multiple port loading/unloading condition
    • deck cargo condition
    • block loading.
  - **5.1.4** The loading/unloading sequences may be port specific or typical.
  - **5.1.5** The sequence is to be built up step by step from commencement of cargo loading to reaching full deadweight capacity. Each time the loading equipment changes position to a new hold defines a step. Each step is to be documented and submitted to the Society. In addition to longitudinal strength, the local strength of each hold is to be considered.
  - **5.1.6** For each loading condition a summary of all steps is to be included. This summary is to highlight the essential information for each step such as:
    • how much cargo is filled in each hold during the different steps,
    • how much ballast is discharged from each ballast tank during the different steps,
    • the maximum still water bending moment and shear at the end of each step,
    • the ship’s trim and draught at the end of each step.
    Table 1: Guidance on Typical loading Sequence Summary Form
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image251.png)


### Appendix 1 - HOLD MASS CURVES

Symbols
$h$ : Vertical distance from the top of inner bottom plating to the lowest point of the upper deck plating at the ship’s centreline, in m.
$h _{a}$ : Vertical distance from the top of inner bottom plating to the lowest point of the upper deck plating at the ship’s centreline of the aft cargo hold in a block loading, in m.
$h _{f}$ : Vertical distance from the top of inner bottom plating to the lowest point of the upper deck plating at the ship’s centreline of the fore cargo hold in a block loading, in m.
$M _{H}$ : As defined in Ch 4, Sec 7
$M _{Full}$ : As defined in Ch 4, Sec 7
$M _{HD}$ : As defined in Ch 4, Sec 7
$M _{D}$ : The maximum cargo mass given for each cargo hold, in t
$M _{BLK}$ : The maximum cargo mass in a cargo hold according to the block loading condition in the loading manual, in t
$T _{HB}$ : As defined in Ch 4, Sec 7
$T _{i}$ : Draught in loading condition No. *i*, at mid-hold position of cargo hold length $\ell _{H}$, in m
$V _{H}$ : As defined in Ch 4, Sec 6
$V _{f}$and$V _{a}$: Volume of the forward and after cargo hold excluding volume of the hatchway part, in $\mathrm{m} ^{3}$
$T _{\min}$ : 0.75 $T _{S}$ or draught in ballast conditions with the two adjacent cargo holds empty, which ever is greater, in m.
$\Sigma$ : The sum of masses of two adjacent cargo holds

#### 1. General

- **1.1** Application
  - **1.1.1** The requirements of this Appendix apply to ships of 150 m in length *L* and above.
  - **1.1.2** This Appendix describes the procedure to be used for determination of:
    • the maximum and minimum mass of cargo in each cargo hold as a function of the draught at mid-hold position of cargo hold
    • the maximum and minimum mass of cargo in any two adjacent holds as a function of the mean draught in way of these holds.
  - **1.1.3** Results of these calculations are to be included in the reviewed loading manual which has also to indicate the maximum permissible mass of cargo at scantling draught in each hold or in any two adjacent holds, as obtained from the design review.
  - **1.1.4** The following notice on referring to the maximum permissible and the minimum required mass of cargo is to be described in loading manual.
    Where ship engages in a service to carry such hot coils or heavy cargoes that have some adverse effect on the local strength of the double bottom and that the loading is not described as cargo in loading manual, the maximum permissible and the minimum required mass of cargo are to be considered specially.

#### 2. Maximum and minimum masses of cargo in each hold

- **2.1** Maximum permissible mass and minimum required masses of single cargo hold in seagoing condition
  - **2.1.1** General
    The cargo mass curves of single cargo hold in seagoing condition are defined in [2.1.2] to [2.1.5]. However if the ship structure is checked for more severe loading conditions than the ones considered in Ch 4, Sec 7, [3.7.1], the minimum required cargo mass and the maximum allowable cargo mass can be based on those corresponding loading conditions.
  - **2.1.2** BC-A ship not having {No MP} assigned
    • For loaded holds
    The maximum permissible mass ($W _{\max} (T _{i} )$) at various draughts ($T _{i}$) is obtained, in t, by the following formulae:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image252.png)
    However, $W _{\max} (T _{i} )$ is no case to be greater than ${M} _{HD}$.
    The minimum required cargo mass ($W _{\min} (T _{i} )$) at various draughts ($T _{i}$) is obtained, in t, by the following formulae:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image253.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image254.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image255.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image256.png)
    • For empty holds which can be empty at the maximum draught
    The maximum permissible mass ($W _{\min} (T _{i} )$) at various draughts ($T _{i}$) is obtained, in t, by the following formulae:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image257.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image258.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image259.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image260.png)
    The minimum required mass ($W _{\min} (T _{i} )$) is obtained, in t, by the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image261.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image262.png)
    Examples for mass curve of loaded cargo hold and cargo hold which can be empty at the maximum draught for BC-A ships not having {No MP} assigned are shown in Fig 1.
    ![Fig 1: Example of mass curve for BC-A ships not having {No MP} assigned](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image263.png)
    Fig 1: Example of mass curve for BC-A ships not having {No MP} assigned
  - **2.1.3** BC-A ship having {No MP} assigned
    • For loaded holds
    The maximum permissible mass ($W _{\max} (T _{i} )$) at various draughts ($T _{i}$) is the same specified in [2.1.2].
    The minimum required mass ($W _{\min} (T _{i} )$) is obtained, in t, by the following formulae:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image264.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image265.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image266.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image267.png) or
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image268.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image269.png)
    • For empty hold which can be empty at the maximum draught
    The maximum permissible mass ($W _{\max} (T _{i} )$) at various draughts ($T _{i}$) is obtained, in t, by the following formulae:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image270.png)
    The minimum required cargo mass ($W _{\min} (T _{i} )$) at various draughts ($T _{i}$) is obtained, in t, by the following formulae:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image271.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image272.png)
    Examples for mass curve of cargo hold for BC-A ships, having {No MP} assigned are shown in Fig 2.
    ![Fig 2: Example of mass curve for BC-A ships having {No MP} assigned](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image273.png)
    Fig 2: Example of mass curve for BC-A ships having {No MP} assigned
  - **2.1.4** BC-B and BC-C ships not having {No MP} assigned
    The maximum permissible mass ($W _{\max} (T _{i} )$) at various draughts ($T _{i}$) is obtained, in t, by the following formulae:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image274.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image275.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image276.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image277.png)
    The minimum required cargo mass ($W _{\min} (T _{i} )$) at various draughts ($T _{i}$) is obtained, in t, by the following formulae:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image278.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image279.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image280.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image281.png)
    Example for mass curve of cargo hold for BC-B and BC-C ships is shown in Fig 3.
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image282.png)
    Fig 3: Example of mass curve for BC-B and BC-C ships not having {No MP} assigned
  - **2.1.5** BC-B and BC-C ships having {No MP} assigned
    The maximum permissible mass ($W _{\max} (T _{i} )$) at various draughts $T _{i}$ is obtained, in t, by the following formulae:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image283.png)
    The minimum required cargo mass ($W _{\min} (T _{i} )$) at various draughts ($T _{i}$) is obtained, in t, by the following formulae:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image284.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image285.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image286.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image287.png) or
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image288.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image289.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image290.png)
    Example for mass curve of cargo hold for BC-B or BC-C ships with {No MP} is shown in Fig 4.
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image291.png)
    Fig 4: Example of mass curve for BC-B and BC-C ships having {No MP} assigned
- **2.2** Maximum permissible mass and minimum required masses of single cargo hold in harbour condition
  - **2.2.1** General
    The cargo mass curves of single cargo hold in harbour condition are defined in [2.2.2]. However if the ship structure is checked for more severe loading conditions than ones considered in Ch 4, Sec 7, [3.7.1], the minimum required cargo mass and the maximum allowable cargo mass can be based on those corresponding loading conditions.
  - **2.2.2** All ships
    The maximum permissible cargo mass and the minimum required cargo mass corresponding to draught for loading/unloading conditions in harbour may be increased or decreased by 15 % of the maximum permissible mass at the maximum draught for the cargo hold in seagoing condition. However, maximum permissible mass is in no case to be greater than the maximum permissible cargo mass at designed maximum load draught for each cargo hold.
  - **2.2.3** BC-A ship not having {No MP} assigned
    The maximum permissible mass ($W _{\max} (T _{i} )$) at various draughts $T _{i}$ in harbour condition is also to be checked by the following formulae in addition to the requirements in [2.1.2]:
    For loaded hold
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image292.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image293.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image294.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image295.png)
  - **2.2.4** BC-A ship having {No MP} assigned
    The maximum permissible mass ($W _{\max} (T _{i} )$) at various draughts $T _{i}$ in harbour condition is also to be checked by the following formulae in addition to the requirements in [2.1.3]:
    For empty hold which can be empty at the maximum draught
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image296.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image297.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image298.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image299.png)
  - **2.2.5** BC-B and BC-C ships having {No MP} assigned
    The maximum permissible mass $W _{\max} (T _{i} )$ at various draughts $T _{i}$ in harbour condition is also to be checked by the following formulae in addition to the requirements in [2.2.2]:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image300.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image301.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image302.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image303.png)

#### 3. Maximum and minimum masses of cargo of two adjacent holds

- **3.1** Maximum permissible mass and minimum required masses of two adjacent holds in seagoing condition
  - **3.1.1** General
    The cargo mass curves of two adjacent cargo holds in seagoing condition are defined in [3.1.2] and [3.1.3]. However if the ship structure is checked for more severe loading conditions than ones considered in Ch 4, Sec 7, [3.7.1], the minimum required cargo mass and the maximum allowable cargo mass can be based on those corresponding loading conditions.
  - **3.1.2** BC-A ships with “Block loading” and not having {No MP} assigned
    The maximum permissible mass ($W _{\max} (T _{i} )$) at various draughts ($T _{i}$) is obtained, in t, by the greater of the following formulae:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image304.png) or
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image305.png)
    However, $W _{\max} (T _{i} )$ is no case to be greater than $\Sigma M _{BLK}$.
    The minimum required cargo mass ($W _{\min} (T _{i} )$) at various draughts ($T _{i}$) is obtained, in t, by the following formulae:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image306.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image307.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image308.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image309.png)
  - **3.1.2** bis BC-A ships with “Block loading” and having {No MP} assigned
    The maximum permissible mass $W _{\max} (T _{i} )$ at various draughts $T _{i}$ is obtained, in t, by the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image310.png)
    However, $W _{\max} (T _{i} )$ is no case to be greater than $M _{BLK}$.
    The minimum required cargo mass $W _{\min} (T _{i} )$ at various draughts $T _{i}$ is obtained, in t, by the following formulae:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image311.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image312.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image313.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image314.png)
    Examples for mass curve of cargo hold for BC-A with block loading ships are shown in Fig 5.
    ![Fig 5: Example of mass curve for BC-A ships with “Block loading”](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image315.png)
    Fig 5: Example of mass curve for BC-A ships with “Block loading”
  - **3.1.3** (void)
  - **3.1.4** BC-A ships without “Block loading” and BC-B, BC-C ships, not having {No MP} assigned
    The maximum permissible mass $W _{\max} (T _{i} )$ at various draughts $T _{i}$ is obtained, in t, by the following formulae:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image316.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image317.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image318.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image319.png)
    The minimum required cargo mass $W _{\min} (T _{i} )$ at various draughts $T _{i}$ is obtained, in t, by the following formulae:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image320.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image321.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image322.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image323.png)
  - **3.1.5** BC-A ships without “Block loading” and BC-B, BC-C ships, having {No MP} assigned
    The maximum permissible mass $W _{\max} (T _{i} )$ at various draughts $T _{i}$ is obtained, in t, by the following formulae:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image324.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image325.png)
    The minimum required cargo mass $W _{\min} (T _{i} )$ at various draughts $T _{i}$ is obtained, in t, by the following formulae:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image326.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image327.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image328.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image329.png)
    Examples for mass curve of cargo hold for BC-A without block loading and BC-B or BC-C are shown
    in Fig 6.
    ![Fig 6: Example of mass curve for BC A-ship without block loading and BC-B or BC-C ships](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image330.png)
    Fig 6: Example of mass curve for BC A-ship without block loading and BC-B or BC-C ships
- **3.2** Maximum permissible mass and minimum required masses of two adjacent cargo holds in harbour condition
  - **3.2.1** General
    The cargo mass curves of two adjacent cargo holds in harbour condition are defined in [3.2.2]. However if the ship structure is checked for more severe loading conditions than ones considered in Ch 4, Sec 7, [3.7.1], the minimum required cargo mass and the maximum allowable cargo mass can be based on those corresponding loading conditions.
  - **3.2.2** All ships
    The maximum permissible cargo mass and minimum required cargo mass corresponding to draught for loading/unloading conditions in harbour may be increased or decreased by 15 % of the maximum permissible mass at the maximum draught for the cargo hold in seagoing condition. However, maximum permissible mass is in no case to be greater than the maximum permissible cargo mass at designed maximum load draught for each cargo hold.
  - **3.2.3** BC-A ships with “Block loading” and having {No MP} assigned
    The maximum permissible mass ($W _{\max} (T _{i} )$) at various draughts $T _{i}$ in harbour condition is also to be checked by the following formulae in addition to the requirements in [3.1.2 bis]:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image331.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image332.png)
  - **3.2.4** BC-A ships without “Block loading” and BC-B, BC-C ships, having {No MP} assigned
    The maximum permissible mass ($W _{\max} (T _{i} )$) at various draughts $T _{i}$ in harbour condition is also to be checked by the following formulae in addition to the requirements in [3.1.5]:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image333.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image334.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image335.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image336.png)
