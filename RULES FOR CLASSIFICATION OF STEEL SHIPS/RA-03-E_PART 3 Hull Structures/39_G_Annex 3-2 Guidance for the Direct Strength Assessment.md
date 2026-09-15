# PART 3 Hull Structures

> RULES FOR CLASSIFICATION OF STEEL SHIPS / RA-03-E / 2025 / EN / Guidance

## Annex 3-2 Guidance for the Direct Strength Assessment

### I. General

#### 1. Application

- **(1)** This Guidance deals with procedure of direct structural analysis that is composed of structural modeling, stress calculating, yielding check and buckling check for the primary supporting members of hull.
- **(2)** This Guidance consists of global structural analysis and hold structural analysis according to size of structural model.

#### 2. Classification note

Upon the request of the applicant (i.e., the Owner or the Builder), the class notation **SeaTrust(DSA1)** or **SeaTrust(DSA2)** shall be assigned to ships which have been built to comply with the following requirements.

- **(1)** The ships, which are contracted for construction on or after 1 April 2006 and are to be complied with Rule **Pt 11** or **Pt 12,** are to meet all the requirements of the corresponding parts.
- **(2)** The container ships, bulk carriers, double hull tankers, Ro-Ro and car carrier, membrane tank LNG carriers and LPG carriers with independent tank type A should meet all requirements in **Ⅲ. Hold Analysis** and **SeaTrust(DSA1)** is assigned to those ships. Where, however, it is deemed to be necessary by the Society, the requirements in **Ⅱ. Direct Global Structural Analysis** should be applied additionally, and **SeaTrust(DSA2)** is assigned in this case. However, in case that **SeaTrust(DSA2)** is assigned to ships , **SeaTrust(DSA1)** is to be performed. *(2017)*
- **(3)** When allowing the classification notation **SeaTrust(DSA1)** or **SeaTrust(DSA2)** for other types of ships not specified in (1) or (2) above, the relevant requirements of this Guidance may be applied as appropriate.


### II. Direct Global Structural Analysis

#### 1.General

- **(1)** Application
  - **(A)** This Guidance provides overall procedures to be used in the global structural analysis with direct transfer of loads from hydrodynamic and stochastic analysis for the purpose of structural safety assurance. This guidance is only applicable to ships intended for unrestricted service and specified in **Ch 3** of the Rules.
  - **(B)** The design of the structure is to be in accordance with **Ch 3** of the Rules regardless of the structural analysis according to this guidance, and the results of the direct global structural analyses cannot be used to reduce the basic scantlings based on the Rules.
  - **(C)** The seakeeping and hydrodynamic load analysis is to be carried out using computer program recognized by the Society based on linear 2D Strip method or linear 3D panel method. The non-linear effects should be considered if these effects are regarded to be important after initial evaluation of the hull shape.
  - **(D)** The structural analysis is to be carried out using computer program which can consider the effects of bending deformation, shear deformation, axial deformation and torsional deformation.
- **(2)** Documentation *(2020)*
  The followings should be presented to the Society for approval of the direct global structural analysis in accordance with this Guidance.
  - **(A)** List of drawings used for the direct global structural analysis(including date and revision number).
  - **(B)** Information about the software used in the hydrodynamics and structural analysis (name, version and reference of the software).
  - **(C)** Description of the idealized part of the structural modeling compared to the drawings.
  - **(D)** Structural modeling information, including steel grades, plate thicknesses, and stiffener dimensions (figure and table).
  - **(E)** Details of boundary conditions applied to structural analysis (figure and table).
  - **(F)** Result of motion analysis and load analysis (transfer function, design wave calculation result, etc.).
  - **(G)** Structural analysis results at design wave condition (figure and table).
    - **(a)** Deformation shape and magnitude of structural analysis model.
    - **(b)** Stress contour and allowable stress ratio of all members.
    - **(c)** Buckling strength of plate member.
  - **(H)** The design amendment and evaluation result when the allowable stress and buckling strength evaluation is not satisfied.
- **(3)** The flow chart of the direct global structural analysis is shown in **Fig 1**
  ![Fig 1 Flow chart of the direct global structural analysis](images/image128.png)
  **Fig 1 Flow chart of the direct global structural analysis**

#### 2. Hydrodynamic m odel

- **(1)** The hydrodynamic model applied in seakeeping and hydrodynamic load analysis is to represent the geometry and hydrodynamic characteristics of wetted surface exactly as far as possible.
- **(2)** 2D strip model
  At least 25 ~ 30 strips should be applied, including at least 10 ~ 14 offsets points on half side. A good representation in areas with large transitions in shape(fore and aft part, bilge) should be ensured using higher density of strips and offsets points. Even areas with constant shape should be divided into several segments to consider the gradient of the hydrodynamic pressure distribution.
- **(3)** 3D Panel model
  The element size should be sufficiently small to avoid numerical errors. At least 30 ~ 40 stations, including 15 ~ 20 panels at each station should be applied. This means 500 ~ 800 elements on half side. A good representation in areas with large transitions in shape(bow and fore part, bilge) should be ensured using higher density of panels. Areas with constant shape should be divided into several panels to consider of hydrodynamic pressure distribution.
- **(4)** Hydrodynamic model should be made to coincide with structural model in geometry, displacement and center of buoyancy.

#### 3. Structural model

- **(1)** Modeling of structure *(2020)*
  - **(A)** The extent of the finite element model is all hull structures, including superstructures, for the full breadth and length of the ship. All main longitudinal and transverse structural elements are to be modelled. These include:
    - **(a)** Inner and outer shell,
    - **(b)** Deck,
    - **(c)** Double bottom floors and girders,
    - **(d)** Transverse and vertical web frames,
    - **(e)** Hatch coamings,
    - **(f)** Stringers,
    - **(g)** Transverse and longitudinal bulkhead structures,
    - **(h)** Other primary supporting members,
    - **(i)** Other structural members which contribute to hull girder strength.
  - **(B)** Four or three node shell elements and two node beam element are to be used for the finite element model.
  - **(C)** All stiffeners are to be modelled with beam elements having axial, torsional, bi-directional shear and bending stiffness. Face plates of primary supporting members and brackets are to be modelled using rod or beam elements.
  - **(D)** The aspect ratio of the shell elements is in general not to exceed 3. The use of triangular shell elements is to be kept to a minimum. Where possible, the aspect ratio of shell elements in areas where there are likely to behigh stresses or a high stress gradient is to be kept close to 1 and the use of triangular elements is to be avoided.
  - **(E)** The scantlings is to be modelled with corrosion addition.
  - **(F)** In general, the shell element mesh is to follow the stiffening system as far as practicable, hence representing the actual plate panels between stiffeners.
  - **(G)** At least 3 elements over the depth of double bottom girders, floors, transverse web frames, vertical web frames and horizontal stringers on transverse bulkheads.
  - **(H)** Model check
    In order to confirm the proper modelling of the hull structure, the model is to be checked according to the following methods, or equivalent ones recognized by the Society.
    - **(a)** The tolerance between the section modulus obtained from F.E model and that of the midship drawings, is to be less than ±1 %.
    - **(b)** The axial bending stresses should be the same value as those obtained from the beam theory as far as possible. The axial bending stresses are $M/Z$ in the beam theory, where $M$ is the sum of the still water bending moment and the wave bending moment and $Z$ is the section modulus of the section of interest.
- **(2)** Boundary conditions *(2021)*
  The boundary conditions for the global structure model should reflect simple supporting. This is obtained through the example shown **Table 2** and **Fig 2.** The fixation points should be located far away from the areas of interest. However, when it is necessary to evaluate the area near the boundary condition, or in the case of wave load conditions in which reaction force occurs largely in the boundary condition, the boundary condition can be replaced by using the inertia relief method. In this case, data on the unbalanced force are to be submitted to the Society and discussed in order to confirm the accuracy of the load transfer.

  | Location | Displacement |   |   |
  | --- | --- | --- | --- |
  | Location | $\delta x$ | $\delta y$ | $\delta z$ |
  | Point A | 1 | 1 | 1 |
  | Point B | 0 | 1 | 1 |
  | Point C | 0 | 1 | 0 |
  | (Notes)<br>1 : constrained<br>0 : Free |   |   |   |

  ![Fig 2 Boundary condition](images/image129.png)
  **Fig 2 Boundary condition**

#### 4. Mass model

- **(1)** The total weight of the ship structures is the sum of all the individual members. The weight of each member is the product of structure volume by structure density, and the structure density may be increased properly to consider omitted minor structures. The additional weight should be distributed properly over ship length because the weight differences occur all over the ship.
- **(2)** The cargo weight model should have the same longitudinal, vertical and transverse mass distribution in accordance with the loading manual. However, the total weight can be modelled as a point mass at the gravity center of weight.
- **(3)** If there is a slight differences between the mass model used in hydrodynamic analysis and that used in structural analysis, severe unbalance forces may be resulted in. Therefore the amount, the gravity center and the distribution of the total weight used in both of the analysis are to be identical, as far as possible.
- **(4)** The hydrodynamic model and the structure model should be in proper balance and give a good representation of the still water vertical bending moment distribution in the ship loading manual. The displacement, longitudinal gravity center (LCG) and the still water vertical bending moment (SWBM) should be checked to meet following tolerances compared with those from loading manual.
  - Displacement : 1 %
  - LCG : 0.1 % of length
  - SWBM : 3 %

#### 5. Load analysis

- **(1)** Loading condition
  The loading conditions are to include both of the ballast condition and the full load condition which are most demanded and also include both of the maximum still water sagging and the hogging condition. In addition, when the Society considers that the distribution of cargo loads may affect the overall behavior of the ship, additional loading conditions are to be considered. *(2020)*
- **(2)** Hydrostatic loads
  Hydrostatic loads may be calculated based on hydrodynamic model and weight or structural model and weight. The buoyancy and the weight should be in proper balance. Especially for the ship with significant trim, the unbalance forces should be minimized as far as possible.
- **(3)** Hydrodynamic loads *(2020)*
  - **(A)** It is recommended to use 5 knots for strength analysis and 2/3 of design speed for fatigue analysis.
  - **(B)** Wave heading angles
    In the strength analysis, the wave heading angle should be considered in all directions from 0° to 360° and applied at intervals of up to 30°. If the structure and loading conditions of the hull are left and right symmetrical and approved by the Society, it may be considered from 0° to 180°. In the fatigue analysis, the wave heading angle should be considered for all directions from 0° to 360°.
  - **(C)** Wave length
    The hydrodynamic load analysis should consider a sufficient number of wave lengths more than 20 including the longest length about 4times of the ship length and the shortest length about 5times of the smallest panels. The range and density of wave lengths should be selected to ensure a good representation of all relevant response transfer functions, including peak values.
  - **(D)** Seakeeping and hydrodynamic load analysis
    The seakeeping and hydrodynamic load analysis is to be carried out using the program recognized by the Society based on the calculation conditions described in (A), (B) and (C) above. The results of the analysis should include the transfer functions of motions in 6 degrees of freedom (for 2D strip, surge motion omitted), sectional forces and moments, acceleration and pressure at the places of interest(for 2D strip, the axial forces due to pressures omitted).
  - **(E)** Short-term analysis
    The short-term analysis is to be carried out based on the transfer functions obtained from the analysis described in (D) above and the wave spectrum which represents the total energy of irregular seaway. The Bretschneider or two parameter Pierson-Moskowitz spectrum is recommended for the North Atlantic, described by the following expression :
    $S _{\eta } ( \omega |H _{s} , T _{z} ) = \frac{H _{s}^{2}}{4 \pi} \left( \frac{2 \pi}{T _{z}} \right) ^{4} \omega ^{-5} \exp \left[ - \frac{1}{\pi} \left( \frac{2 \pi}{T _{z}} \right) ^{4} \omega ^{-4} \right]$
    where,
    $H_s$ : Significant wave height (m)
    $\omega$ : Angular wave frequency (rad/s)
    $T_z$ : Average Zero up-crossing wave period (s)
    The short-term response spectrum of a ship is calculated using the load transfer function as follows.
    $S \left( \omega |H _{s} , T _{z} , \theta \right) = \left| H \left( \omega | \theta \right) \right| ^{2} S _{\eta } \left( \omega | H _{s} , T _{z} \right)$
    The spectral moments of order $n$ of the response process for a given heading may be described as
    $m _{n} = \int _{\omega } ^{} {} \sum _{ \theta _{0} -90 {}^{\circ} } ^{\theta _{0} +90 {}^{\circ} } f _{s} ( \theta ) \left| \omega - \frac{\omega ^{2} V}{g} \cos \theta \right| ^{ n} S( \omega |H _{s} , T _{z} , \theta )$
    using a spreading function usually defined as $f _{s} ( \theta ) = k \cos ^{2} ( \theta )$
    where $k$ is selected such that :
    $\sum _{\theta_0 - 90 {}^{\circ} } ^{\theta_0 + 90 {}^{\circ}}f_s (\theta) = 1$
    where,
    $\theta_0$ : Main wave heading
    $\theta$ : Relative spreading around the main wave heading
  - **(F)** Long-term analysis *(2020)*
    ![Fig 3 Definition of the extent of the North Atlantic](images/image130.png)
    **Fig 3 Definition of the extent of the North Atlantic**

    **Table 3 Probability of sea-states in the North Atlantic described as occurrence per 100000 observations. Derived from BMT's Global Wave Statistics**

    | $T _{Z}$<br>$H _{S}$ | 1.5 | 2.5 | 3.5 | 4.5 | 5.5 | 6.5 | 7.5 | 8.5 | 9.5 | 10.5 | 11.5 | 12.5 | 13.5 | 14.5 | 15.5 | 16.5 | 17.5 | 18.5 | SUM |
    | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
    | 0.5 | 0.0 | 0.0 | 1.3 | 133.7 | 865.6 | 1186.0 | 634.2 | 186.3 | 36.9 | 5.6 | 0.7 | 0.1 | 0.0 | 0.0 | 0.0 | 0.0 | 0.0 | 0.0 | 3050 |
    | 1.5 | 0.0 | 0.0 | 0.0 | 29.3 | 986.0 | 4976.0 | 7738.0 | 5569.7 | 2375.7 | 703.5 | 160.7 | 30.5 | 5.1 | 0.8 | 0.1 | 0.0 | 0.0 | 0.0 | 22575 |
    | 2.5 | 0.0 | 0.0 | 0.0 | 2.2 | 197.5 | 2158.8 | 6230.0 | 7449.5 | 4860.4 | 2066.0 | 644.5 | 160.2 | 33.7 | 6.3 | 1.1 | 0.2 | 0.0 | 0.0 | 23810 |
    | 3.5 | 0.0 | 0.0 | 0.0 | 0.2 | 34.9 | 695.5 | 3226.5 | 5675.0 | 5099.1 | 2838.0 | 1114.1 | 337.7 | 84.3 | 18.2 | 3.5 | 0.6 | 0.1 | 0.0 | 19128 |
    | 4.5 | 0.0 | 0.0 | 0.0 | 0.0 | 6.0 | 196.1 | 1354.3 | 3288.5 | 3857.5 | 2685.5 | 1275.2 | 455.1 | 130.9 | 31.9 | 6.9 | 1.3 | 0.2 | 0.0 | 13289 |
    | 5.5 | 0.0 | 0.0 | 0.0 | 0.0 | 1.0 | 51.0 | 498.4 | 1602.9 | 2372.7 | 2008.3 | 1126.0 | 463.6 | 150.9 | 41.0 | 9.7 | 2.1 | 0.4 | 0.1 | 8328 |
    | 6.5 | 0.0 | 0.0 | 0.0 | 0.0 | 0.2 | 12.6 | 167.0 | 690.3 | 1257.9 | 1268.6 | 825.9 | 386.8 | 140.8 | 42.2 | 10.9 | 2.5 | 0.5 | 0.1 | 4806 |
    | 7.5 | 0.0 | 0.0 | 0.0 | 0.0 | 0.0 | 3.0 | 52.1 | 270.1 | 594.4 | 703.2 | 524.9 | 276.7 | 111.7 | 36.7 | 10.2 | 2.5 | 0.6 | 0.1 | 2586 |
    | 8.5 | 0.0 | 0.0 | 0.0 | 0.0 | 0.0 | 0.7 | 15.4 | 97.9 | 255.9 | 350.6 | 296.9 | 174.6 | 77.6 | 27.7 | 8.4 | 2.2 | 0.5 | 0.1 | 1309 |
    | 9.5 | 0.0 | 0.0 | 0.0 | 0.0 | 0.0 | 0.2 | 4.3 | 33.2 | 101.9 | 159.9 | 152.2 | 99.2 | 48.3 | 18.7 | 6.1 | 1.7 | 0.4 | 0.1 | 626 |
    | 10.5 | 0.0 | 0.0 | 0.0 | 0.0 | 0.0 | 0.0 | 1.2 | 10.7 | 37.9 | 67.5 | 71.7 | 51.5 | 27.3 | 11.4 | 4.0 | 1.2 | 0.3 | 0.1 | 285 |
    | 11.5 | 0.0 | 0.0 | 0.0 | 0.0 | 0.0 | 0.0 | 0.3 | 3.3 | 13.3 | 26.6 | 31.4 | 24.7 | 14.2 | 6.4 | 2.4 | 0.7 | 0.2 | 0.1 | 124 |
    | 12.5 | 0.0 | 0.0 | 0.0 | 0.0 | 0.0 | 0.0 | 0.1 | 1.0 | 4.4 | 9.9 | 12.8 | 11.0 | 6.8 | 3.3 | 1.3 | 0.4 | 0.1 | 0.0 | 51 |
    | 13.5 | 0.0 | 0.0 | 0.0 | 0.0 | 0.0 | 0.0 | 0.0 | 0.3 | 1.4 | 3.5 | 5.0 | 4.6 | 3.1 | 1.6 | 0.7 | 0.2 | 0.1 | 0.0 | 21 |
    | 14.5 | 0.0 | 0.0 | 0.0 | 0.0 | 0.0 | 0.0 | 0.0 | 0.1 | 0.4 | 1.2 | 1.8 | 1.8 | 1.3 | 0.7 | 0.3 | 0.1 | 0.0 | 0.0 | 8 |
    | 15.5 | 0.0 | 0.0 | 0.0 | 0.0 | 0.0 | 0.0 | 0.0 | 0.0 | 0.1 | 0.4 | 0.6 | 0.7 | 0.5 | 0.3 | 0.1 | 0.1 | 0.0 | 0.0 | 3 |
    | 16.5 | 0.0 | 0.0 | 0.0 | 0.0 | 0.0 | 0.0 | 0.0 | 0.0 | 0.0 | 0.1 | 0.2 | 0.2 | 0.2 | 0.1 | 0.1 | 0.0 | 0.0 | 0.0 | 1 |
    | SUM | 0 | 0 | 1 | 165 | 2091 | 9280 | 19922 | 24879 | 20870 | 12898 | 6245 | 2479 | 837 | 247 | 66 | 16 | 3 | 1 | 100000 |
    | * The $H_S$ and $T _{Z}$ are class midpoints. |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |   |
    - **(a)** The long-term analysis can be performed using wave data and short-term analysis results obtained in above (E). The wave data used in the strength analysis are for the North Atlantic region corresponding to 8, 9, 15, and 16 in **Fig. 3**, and are shown in the **Table 3** (IACS Rec. No. 34). The wave data used for fatigue analysis is to be taken as the wave data considering the route of the ship or as recognized by the Society.
    - **(b)** The wave load for the global structural analysis can be used by multiplying the value of 10^-8 probability level calculated by the North Atlantic wave data condition with the coefficient ($f _{R} = 0.85$) related to the ship operation.

#### 6. Design waves (2020)

- **(1)** The target load is calculated according to (F) of **5.** (3) and can be replaced by the load specified in the Rules. For the beam sea condition (90° or 270°), the heading correction factor($f_{ \beta }=0.8$) can be additionally applied.
- **(2)** The design wave is defined as the regular wave that gives the same response level as the target load. The heading angle and the wave length of the design wave are chosen as the values where the relevant transfer function has its maximum and the design wave amplitude is chosen as the target load divided by the maximum value of the transfer function. If the wave steepness is too high (wave height/wave length>1/7) it is necessary to choose a slightly longer wave length and to apply corresponding wave amplitude.
- **(3)** Dominant Load Parameter (DLP), the basis of design wave determination, should be chosen to assure that structural members, where extreme wave loads may act on or severe stresses may occur, are safe. Following DLPs should be considered necessarily. In case where deemed necessary by the Society, additional dominant load parameters are to be considered.
  - Vertical bending moment at midship (including head sea and following sea conditions)
  - Horizontal bending moment at midship
  - Torsional moment at $L/4$, $L/2$ and $3L/4$
  - Vertical acceleration at FP
  - Roll
  - Dynamic pressure acting on ship draught at midship.
  It is necessary to chose other DLPs where the structural safety should be assured due to its weak structure like a large opening.

#### 7. Loads transfer

- **(1)** The design waves are to be determined according to each DLP, and the dynamic loads including inertia forces and the hydrodynamic pressures should be transfer to the structural model properly. It should be confirmed that the sectional loads acting on the structural model are the same values as the loads calculated in the hydrodynamic load analysis.
- **(2)** Hydrodynamic pressure transfer
  The hydrodynamic pressure calculated in the hydrodynamic load analysis may be transferred in type of force or pressure. The unbalance forces resulted from the difference between hydrodynamic model and the structural model should be minimized as far as possible.
- **(3)** Inertia force transfer
  - **(A)** Weight of structure itself
    The acceleration at the center of a element is calculated by the combination of motions in 6 degree-of-freedom. The inertia forces are obtained from the product of the acceleration by the mass of the element and are to be distributed on the relevant nodes properly.
  - **(B)** Solid cargo
    The acceleration of a solid cargo like a container should be calculated at the center of its real position and the inertia forces induced by the cargo should be distributed on the actual supporting nodes, which depend on the direction of the acceleration.
  - **(C)** Liquid cargo
    The acceleration of a liquid cargo may be calculated at its center of gravity and the internal pressures induced by the acceleration should be distributed on the boundary of the tank in the type of pressure. The reference location of pressure head is top of the tank boundary for the vertical acceleration and mid of the free surface for the axial and the lateral acceleration.
- **(4)** Unbalance force
  The unbalance forces may be resulted from a variety of sources such as the differences between the structural model and the hydrodynamic model, the non-consistent mass model, viscous damping forces due to roll motion and etc. These forces, which act on the fixation points of structural model should be documented and presented including the total amount, the sources and the procedures used to resolve.

#### 8. Structural analysis and acceptance criteria

- **(1)** Structural analysis
  - **(A)** The structural analysis is to be carried out with the Finite Element Method.
  - **(B)** An approved analysis program having adequate accuracy should be used. If deemed necessary, documents related to systems used in the analysis and documents for confirming the accuracy may be required to be submitted to the Society.
- **(2)** Structural members to be assessed *(2020)*
  - **(A)** Structural safety assurance targets hull structural members affected by global behavior due to wave loads. Superstructures and deckhouses which are not continuously arranged in the longitudinal direction of the ship shall not be considered. However, the parts connected with the hull and affected by global behavior are included in the evaluation.
  - **(B)** Areas of boundary condition in the fore and aft structure where local stress concentration is caused by unbalanced force are excluded from evaluation.
- **(3)** Acceptance criteria
  The results of global structural analysis is to be assessed for the failure mode of yielding according to the allowable stress shown in **Table 4**.

  | Element type | Allowable stress |
  | --- | --- |
  | Shell element | $\sigma _{e} \mathrm{LEFT} ( N/mm ^{2} \right)$ |
  | Shell element | $0.9 \beta \sigma _{Y} /K$ ^3. |
  | (Notes)<br>1. $\sigma _{Y}$ : 235 $\mathrm{N}/mm^2$<br>2. The equivalent stress $\sigma _{e}$ is to be as follows.<br>$\sigma _{e} = \sqrt {\sigma _{x} ^{2} + \sigma _{y} ^{2} - \sigma _{x} \sigma _{y} +3 \tau ^{2} }$<br>$\sigma _{x}$ : Normal stress in $x$-direction of element coordinate system<br>$\sigma _{y}$ : Normal stress in $y$-direction of element coordinate system<br>$\tau$ : Shear stress in $x-y$ plane of element coordinate system<br>3. $\beta$ : Mesh density factor taken as;<br>1.0 for longitudinal spacing mesh size,<br>1.15 for less than or equal to 200 x 200 mm mesh size,<br>1.25 for less than or equal to 100 x 100 mm mesh size,<br>1.5 for less than or equal to 50 x 50 mm mesh size,<br>1.7 for less than or equal to 2t x 2t mesh size,<br>where t is thickness of element, in mm. |   |

  | Steel grades | $K$ |
  | --- | --- |
  | *A, B, D* and *E* | 1.0 |
  | *AH32, DH32* and *EH32* | 0.78 |
  | *AH36, DH36* and *EH36* | 0.72 |
  | *AH40, DH40* and *EH40* | 0.68<sup>(1)</sup> |
  | *AH47, DH47* and *EH47* | 0.62<sup>(2)</sup> |
  | Note:<br><sup>(1)</sup> 0.66 for material factor provided that a fatigue assessment of the structure is performed to verify compliance with the requirements of **Annex 3-3** "Guidance for the Fatigue Strength Assessment of Ship Structures"<br><sup>(2)</sup> For the application of extremely thick steel for container ships in accordance with **Guidance Pt 7, Annex 7-8**. |   |

#### 9. Local structural strength analysis (2020)

- **(1)** Application
  In case of (A) to (C) below, local structural strength analysis may be required at the discretion of the Society.
  - **(A)** When the stress calculated by the structural analysis exceeds 95% of the allowable stress (when the element size exceeds $200 \times 200 \mathrm{mm}$).
  - **(B)** Areas where stress concentration is expected but cannot be assessed through **III. Guidance for the Hold Analysis** due to difficulties in applying loads and boundary conditions.
  - **(C)** When the mesh density is large and it is difficult to reflect the structure in the drawing.
- **(2)** Modelling
  - **(A)** The extent of the fine mesh zone is not to be less than 10 elements in all directions from the area under investigation.
  - **(B)** All plating within the fine mesh zone is to be represented by shell elements.
  - **(C)** The aspect ratio of elements within the fine mesh zone is to be kept as close to 1 as possible. In all cases, the elements within the fine mesh model are to have an aspect ratio not exceeding 3.
  - **(D)** Distorted elements, with element corner angles of less than 45° or greater than 135°, are to be avoided.
- **(3)** Stress assessment
  The results of local structural strength analysis should satisfy the allowable stress criteria in Table 4.

#### 10. Buckling strength (2020)

The buckling strength calculation for the structural analysis results is based on **Ⅳ. Buckling strength calculation**.


### III. Guidance for the Hold Analysis

#### 1. General

- **(1)** Application
  - **(A)** When determining the scantlings of each structural member by using a direct strength calculation, the scope and the procedure of the direct strength calculation may be defined in consultation with the Society.
  - **(B)** Even when the scantlings of each structural members are decided by the hold analysis, the requirements in **Ch 3** of the Rules are to be complied with.
  - **(C)** When the thickness of steel plate is decided by the direct strength calculations, the thickness is not to be less than minimum thickness specified in the Rules
  - **(D)** Analysis method and analysis program is able to consider the effect of bending deformation, shear deformation, axial deformation and torsional deformation.
  - **(E)** Analysis method and analysis program is able to express the movements of 2-D or 3-D structural models under the reasonable boundary conditions.
  - **(F)** Where hold analysis is executed, data specifying the conditions of calculations and data summarizing their results are to be submitted to the Society.
  - **(G)** When carrying out the hold analysis for other types of ships not specified in this guidance, the relevant requirements of this guidance may be applied as appropriate.
- **(2)** Procedure of hold analysis
  A general flow chart of the hold analysis is show in **Fig 4**
  ![](images/image131.png)
  **Fig 4 Procedure for hold analysis**
- **(3)** Modeling of structure
  - **(A)** The model of structure to be analysed is to include its surrounding members considered to have material influences on the behaviors of the members of which the scantlings are to be determined by direct strength calculations.
  - **(B)** The modeling is to be such that any proper elements chosen from among plate bending elements, beam elements, bar elements, etc. can reproduce the behaviors of the structure with the highest possible fidelity.
  - **(C)** The scantlings including corrosion allowances which are shown on the plans may be used for modelling.
  - **(D)** When the degree of division of a member into model elements is insufficient for the determination of scantlings by direct strength calculation, the member concerned is to be subject to the calculation by remeshing with fine meshes to enable further study on the basis of the results of the analysis.
  - **(E)** The structural models of bulk carriers, double hull tankers, container ships, Ro-Ro and car carrier, membrane tank LNG ships and LPG Carriers with Independent Tank Type A are to comply with the requirements in **3, 4, 5, 6, 7** and **8** respectively. *(2020)*
  - **(F)** The F.E model should be represented using a right handed cartesian co-ordinate system as shown in **Table 6.**

    |   | Direction | Remark |
    | --- | --- | --- |
    | $x$ | Longitudinal | Positive forward |
    | $y$ | Transverse | Positive to port |
    | $z$ | Vertical | Positive upwards from the baseline |
  - **(G)** Side shell, longitudinal bulkheads and other similar members subjected to large shearing force are preferably to be modelled into two or three dimensional structure by using shell elements.
  - **(H)** In meshing, proper sizes of meshes are to be selected in accordance with the stress distribution in the model which can be predicted and abnormally large aspect ratios of meshes are to be avoided.
  - **(I)** Girders and similar members having stress gradients along their depth are to be so meshed as to enable their discrimination.
  - **(J)** In principle, access openings and lightening holes, etc., are to be represented. Where openings are not represented in the structural model, both the mean shear stress and the element shear stress are to be increased in direct proportion to the modelled web shear area divided by the actual web area. But in areas of interest of shear stress, especially in double bottom girders and in floor plates adjacent to the hopper knuckle, etc., representing the opening using a fine mesh is to be required.
  - **(K)** When modelling into beam element, the plate of a width equal to 0.1 of span of the member on its each side may, as a rule, be included, provided that the plate to be included is effectively reinforced by other members or is recognized by the Society to have a sufficient thickness, and, in addition, this width equal to 0.1 of the span does not exceed half of the distance to the neighbouring member.
  - **(L)** Non-continuous stiffeners are to be represented by line elements with the cross sectional area according to the end connection as shown in **Table 1.**
- **(4)** Model check
  - **(A)** In order to confirm the proper modelling of the hull structure, the model is to be verified according to the following methods, or to be in accordance with the discretion of the Society.
  - **(B)** The difference between the section modulus calculated from F.E model and the midship drawing, is to be in ±1 % allowance.
  - **(C)** The hull girder bending stresses resulting from the finite element analysis are to be in good agreement with those calculated according to the beam theory. The hull girder bending stresses by the beam theory are calculated as $M/Z$, where $M$ is the sum of still water bending moment and wave bending moment and $Z$ is the section modulus at the considered position.
- **(5)** Boundary conditions
  Reasonable boundary conditions are to be applied to describe the behaviour of actual structure. The boundary conditions of bulk carriers, double hull tankers, container ships, Ro-Ro and car carrier, membrane tank LNG ships and LPG Carriers with Independent Tank Type A are to comply with the requirements in **3**, **4**, **5**, **6**, **7** and **8** respectively. *(2020)*
- **(6)** Design loads
  - **(A)** The loads due to longitudinal bending moment of hull girder at the forward and aft end boundaries of the structure model may, as a rule, not be taken into consideration. When these loads are taken into consideration, however, the allowable stress to be applied to the results of calculations is to be determined at the directions of the Society.
  - **(B)** The design loads to be taken into consideration are, as a rule, to be the loads due to cargo and water ballast loaded on board, hydrostatic pressure and wave loads.
  - **(C)** The load due to the inertia force of cargo is to be considered in addition to those specified in (B) above, when the Society considers it is necessary.
  - **(D)** The cargo holds, where dynamic impact loads such as sloshing loads are predicted, are to be specially considered and proper data in this connection are to be submitted.
  - **(E)** The design loads of bulk carriers, double hull tankers, container ships, Ro-Ro and car carrier and membrane tank LNG ships are to comply with the requirements in **3, 4, 5, 6** and **7** respectively.
- **(7)** Loads due to cargo and water ballast
  - **(A)** Loads due to liquid cargo, water ballast, etc.
    - **(a)** The upper end of water head for a tank is to be the mid-point of the distance between the top of tank and the top of overflow pipe.
    - **(b)** For the water head of large deep tanks, proper additional water head corresponding to the dynamical influence is to be considered in addition to the water head specified in (a) above.
    - **(c)** For the liquid cargo and water ballast to be loaded in harbours or similar quiet waters, the water head corresponding to the actual loading height may be used as the water head.
    - **(d)** Except where considered necessary, the loads due to fuel oil, fresh water and similar consumables may not be taken into consideration.
    - **(e)** The densities and water heads of cargoes are to be specified.
  - **(B)** Loads due to Ore Cargo, Grain Cargo, etc.
    Loads of bulk carriers are to comply with the requirements in **3.**
- **(8)** Hydrostatic pressure
  - **(A)** The water head at the scantling draught(m), corresponding to respective loading conditions is to be considered as hydrostatic pressure at the ships bottom and sides.
  - **(B)** Load for hydraulic pressure test
    - **(a)** The upper end of water head of a tank being subjected to hydraulic pressure test is to be a point at a height of 2.4 m above the top of tank.
    - **(b)** The water pressure at the bottom and sides under the condition of hydraulic pressure test is to be the hydrostatic pressure corresponding to a draught equal to 1/3 of the scantling draught.
- **(9)** Wave loads
  - **(A)** Wave induced loads
    $H_0 = 0.5 \times H_W$(m), $H_1 = 0.9 \times H_W$(m), $H_2 = 0.25 \times H_W$(m)
    where,
    $H _{W} = 0.61L ^{1/2}$ -------------------- #eqnID-1453150_s2 m
    $= 1.41L^1/3$ --------------------- 150 m#eqnID-1455250_s2 m
    $= 2.23L^1/4$ --------------------- 250 m#eqnID-1457300_s2 m
    $= 9.28$ --------------------- 300 m$< L$
    ![](images/image132.png)
    **Fig 5 Wave induced load**
    - **(a)** As the wave induced loads corresponding to the wave crest and trough, the water heads(m) corresponding to the variations $H _{0}$*,* $H _{1}$ and $H _{2}$ from the hydrostatic pressure at the still water draught, according to the following formulae are to be taken into consideration. (See **Fig 5**)
    - **(b)** The wave induced loads in harbours and similar quiet waters may be taken as equal to 1/2 of the values of $H _{0}$*,* $H _{1}$ and $H _{2}$ specified in (a) above.
    - **(c)** The wave induced loads may be assumed to be equally distributed throughout the ship's length.
- **(10)** Allowable stress
  When the loads and boundary conditions specified in from (5) to (9), preceding are to be applied to the structural model according to the (3) above, the scantlings of members are to be determined so that the values of stress in each of them may not exceed the values given below.
  - **(A)** Allowable stress for mild steel members
    For bulk carriers, double hull tankers, container ships, Ro-Ro and car carrier and membrane tank LNG ships are to comply with the requirements in **3, 4, 5, 6** and **7** respectively, are to be applied. Where nothing particular is provided for, the values are to be left to the Society's directions.
  - **(B)** Allowable stress for high tensile steel members
    Values according to (1) above divided by the coefficient $K$ in **Table 7** are to be used.

    **Table 7 Material factor** $K$

    | Steel grades | $K$ |
    | --- | --- |
    | *A, B, D* and *E* | 1.0 |
    | *AH* 32, *DH* 32 and *EH* 32 | 0.78 |
    | *AH* 36*, DH* 36 and *EH* 36 | 0.72 |
    | *AH 40, DH 40* and *EH 40* | 0.68 |

#### 3. Bulk Carrier

- **(1)** General
  - **(A)** When determining the scantlings of structural members of cargo hold of a bulk carrier by direct strength calculations, necessary materials and date on the calculation procedure are previously to be submitted to the Society for approval. The procedure is to comply with the following (2) to (5).
  - **(B)** Except for those specifically provided for in this part, **Par 1.** is to be applied.
- **(2)** Structural models
  - **(A)** Model extent
    The range of structure to be analyzed is, one side of the three(1/2+1+1/2) adjacent cargo tanks in the parallel body part, including whole length or half length of each cargo oil tank and transverse bulkhead between these two tanks. However, If there is asymmetry of the ship structure or cargo or ballast loading condition about the ship's centerline. Cargo hold length($l _{h}$) is described in **Pt 7, Ch 3, 301.2** of the Guidance.(See **Fig 8**)
    ![Fig 8 Hold model extent](images/image133.png)
    **Fig 8 Hold model extent**
  - **(B)** Structural modeling
    ![Fig 9 Example of hold model](images/image134.png)
    **Fig 9 Example of hold model**
    ![Fig 10 Example of corrugated bulkhead](images/image135.png)
    **Fig 10 Example of corrugated bulkhead** ![Fig 11 Example of typical web frame](images/image136.png)
    **Fig 11 Example of typical web frame**
    ![Fig 12 Example of fine-mesh](images/image137.png)
    **Fig 12 Example of fine-mesh**
    - **(a)** The structural modeling with shell elements mesh is : longitudinally, one element between every frame, transversely one element between longitudinal spacing and vertically three or more elements over the depth of double bottom girders and floors. Typical arrangements representing bulk carrier are shown in **Fig 9** to **11**
    - **(b)** For the calculation by remeshing with fine meshes, an example of meshing, as a standard, is shown in **Fig 12.** The depth of transverse web is to be meshed into 3 sub depths.
    - **(c)** The primary members including side shell, inner bottom, upper deck and corrugated bulkheads, etc. subjected to large shearing shell elements. Shedder plates in corrugated bulkhead are also to be modelled by using shell elements.
    - **(d)** Girders and similar members having stress gradients along their depth are to be so meshed as to enable their discrimination.
- **(3)** boundary condition
  The following descriptions of boundary conditions are to be applied for half breadth model. For a full breadth model, no constraints are required for the centerline plane. However, a node on the centerline at the keel at the both ends of the model are to be constrained in the transverse direction. The example of boundary conditions are shown in **Table 14** and **Fig 13.**
  - **(A)** End planes (①) : Symmetric condition
  - **(B)** Centerline plane (②) : Symmetric condition
  - **(C)** Vertical counter forces distributed to the side shell nodes at the oil tight BHDs to eliminate reaction at the vertical constraints.(③)
    ![Fig 13 Boundary condition](images/image138.png)
    **Fig 13 Boundary condition**

    | Coord.<br>Position | Displacement |   |   | Rotation |   |   |
    | --- | --- | --- | --- | --- | --- | --- |
    | Coord.<br>Position | $U_x$ | $U_y$ | $U_z$ | $\theta_x$ | $\theta_y$ | $\theta_z$ |
    | ① Both end of model | 1 | 0 | 0 | 0 | 1 | 1 |
    | ② Centerline | 0 | 1 | 0 | 1 | 0 | 1 |
    | ③ Top of Transverse BHD | 0 | 0 | 1 | 0 | 0 | 0 |
    | Remarks<br>1 : Restrainted<br>0 : Free |   |   |   |   |   |   |

     ![Fig 14 Assumed cargo surface](images/image139.png)
    **Fig 14 Assumed cargo surface**
- **(4)** Load
  - **(A)** General
    In principle, the cargo and ballast loads, still water loads and wave loads etc. are applied to the F.E model.
  - **(B)** Loading conditions
    The loading conditions to be taken into consideration are, as a rule, to be the full load condition and the ballast condition. When special loading conditions, such as alternate loading, multi-port loading or loading of cargo of specially high density are predicted, such conditions are to be contained in the calculations. **Table 16** gives an example.
  - **(C)** Internal loads
    - The shape of cargo surface is assumed to be horizontal longitudinally and transversely in the part near the ship's centreline and sloped down straight to the ship's sides with the angle of repose $\phi /2$.
    - The width of the horizontal part $b$ is assumed to be equal to 1/4 of the breadth of the hold.
    - The loading height $h_CL$ is determined in accordance with the mass, angle of repose and density of the cargo to be loaded. The shape of cargo surface may be assumed to be unchanged for the whole breadth above.
    - When the density and angle of repose of the cargo are not specified, they are to be taken as 3.0 (t/m^3) and 35° respectively.
    $9.81\gamma hk^2$(N/m^2)
    where:
    $\gamma$ = density of cargo (kg/m^3)
    $h$ = vertical height from the panel in question to the surface of cargo right above the panel (m)
    $k$ = values given in **Table 15.**
    $\beta$ = angle between slant plating of bilge hopper and inner bottom plating.(see **Fig 15**)

    **Table 15 Coefficient** $k$

    | angle $\beta$ (degree) | $k$ |
    | --- | --- |
    | $\beta$ ≤40° | 1.0 |
    | 40° < $\beta$ < 80° | 1.4 - 0.01$\beta$ |
    | $\beta$ ≥ 80° | 0.6 |

     ![Fig 15 Angle #eqnID-1488](images/image140.png)
    **Fig 15 Angle** #eqnID-1488

    | No | Description | Draft | Load pattern | Masses |   |   |
    | --- | --- | --- | --- | --- | --- | --- |
    | 1 | Full loaded | $T$ | ![](images/image141.png) | Cargo Mass | $i-1$ | $M_Full$ |
    | 1 | Full loaded | $T$ |   | Cargo Mass | $i$ | $M_Full$ |
    | 1 | Full loaded | $T$ |   | Cargo Mass | $i+1$ | $M_Full$ |
    | 1 | Full loaded | $T$ |   | DB Mass | $i-1$ | empty |
    | 1 | Full loaded | $T$ |   | DB Mass | $i$ | $M_DBFO$ |
    | 1 | Full loaded | $T$ |   | DB Mass | $i+1$ | empty |
    | 2 | Slack load 1 | $T$ | ![](images/image142.png) | Cargo Mass | $i-1$ | $M_Full$ |
    | 2 | Slack load 1 | $T$ |   | Cargo Mass | $i$ | $0.5 M_H$ |
    | 2 | Slack load 1 | $T$ |   | Cargo Mass | $i+1$ | $M_Full$ |
    | 2 | Slack load 1 | $T$ |   | DB Mass | $i-1$ | empty |
    | 2 | Slack load 1 | $T$ |   | DB Mass | $i$ | empty |
    | 2 | Slack load 1 | $T$ |   | DB Mass | $i+1$ | empty |
    | 3 | Slack load 2 | $T$ | ![](images/image143.png) | Cargo Mass | $i-1$ | $0.5 M_H$ |
    | 3 | Slack load 2 | $T$ |   | Cargo Mass | $i$ | $M_Full$ |
    | 3 | Slack load 2 | $T$ |   | Cargo Mass | $i+1$ | $0.5 M_H$ |
    | 3 | Slack load 2 | $T$ |   | DB Mass | $i-1$ | empty |
    | 3 | Slack load 2 | $T$ |   | DB Mass | $i$ | empty |
    | 3 | Slack load 2 | $T$ |   | DB Mass | $i+1$ | empty |
    | 4 | Normal ballast | $T _{BDmax}$ | ![](images/image144.png) | Cargo Mass | $i-1$ | empty |
    | 4 | Normal ballast | $T _{BDmax}$ |   | Cargo Mass | $i$ | empty |
    | 4 | Normal ballast | $T _{BDmax}$ |   | Cargo Mass | $i+1$ | empty |
    | 4 | Normal ballast | $T _{BDmax}$ |   | DB Mass | $i-1$ | $M_DBBW$ |
    | 4 | Normal ballast | $T _{BDmax}$ |   | DB Mass | $i$ | empty |
    | 4 | Normal ballast | $T _{BDmax}$ |   | DB Mass | $i+1$ | $M_DBBW$ |
    | 5 | Multi port 1 | $0.67 T$ | ![](images/image145.png) | Cargo Mass | $i-1$ | empty |
    | 5 | Multi port 1 | $0.67 T$ |   | Cargo Mass | $i$ | $M_Full$ |
    | 5 | Multi port 1 | $0.67 T$ |   | Cargo Mass | $i+1$ | empty |
    | 5 | Multi port 1 | $0.67 T$ |   | DB Mass | $i-1$ | empty |
    | 5 | Multi port 1 | $0.67 T$ |   | DB Mass | $i$ | $M_DBFO$ |
    | 5 | Multi port 1 | $0.67 T$ |   | DB Mass | $i+1$ | empty |
    | 6 | Multi port 2 | $0.83 T$ | ![](images/image146.png) | Cargo Mass | $i-1$ | $M_Full$ |
    | 6 | Multi port 2 | $0.83 T$ |   | Cargo Mass | $i$ | empty |
    | 6 | Multi port 2 | $0.83 T$ |   | Cargo Mass | $i+1$ | $M_Full$ |
    | 6 | Multi port 2 | $0.83 T$ |   | DB Mass | $i-1$ | empty |
    | 6 | Multi port 2 | $0.83 T$ |   | DB Mass | $i$ | empty |
    | 6 | Multi port 2 | $0.83 T$ |   | DB Mass | $i+1$ | empty |
    | 7 | Multi port 3a<br>Block loading | $0.67 T$ | ![](images/image147.png) | Cargo Mass | $i-1$ | empty |
    | 7 | Multi port 3a<br>Block loading | $0.67 T$ |   | Cargo Mass | $i$ | $M_Full$ |
    | 7 | Multi port 3a<br>Block loading | $0.67 T$ |   | Cargo Mass | $i+1$ | $M_Full$ |
    | 7 | Multi port 3a<br>Block loading | $0.67 T$ |   | DB Mass | $i-1$ | empty |
    | 7 | Multi port 3a<br>Block loading | $0.67 T$ |   | DB Mass | $i$ | $M_DBFO$ |
    | 7 | Multi port 3a<br>Block loading | $0.67 T$ |   | DB Mass | $i+1$ | $M_DBFO$ |
    | 8 | Multi port 3b<br>Block loading | $0.67 T$ | ![](images/image148.png) | Cargo Mass | $i-1$ | $M_Full$ |
    | 8 | Multi port 3b<br>Block loading | $0.67 T$ |   | Cargo Mass | $i$ | $M_Full$ |
    | 8 | Multi port 3b<br>Block loading | $0.67 T$ |   | Cargo Mass | $i+1$ | empty |
    | 8 | Multi port 3b<br>Block loading | $0.67 T$ |   | DB Mass | $i-1$ | $M_DBFO$ |
    | 8 | Multi port 3b<br>Block loading | $0.67 T$ |   | DB Mass | $i$ | $M_DBFO$ |
    | 8 | Multi port 3b<br>Block loading | $0.67 T$ |   | DB Mass | $i+1$ | empty |

    | No | Description | Draft | Load pattern | Masses |   |   |
    | --- | --- | --- | --- | --- | --- | --- |
    | 9 | Multi port 3c<br>Block loading | $0.67 T$ | ![](images/image149.png) | Cargo Mass | $i-1$ | empty |
    | 9 | Multi port 3c<br>Block loading | $0.67 T$ |   | Cargo Mass | $i$ | $M_BW$ |
    | 9 | Multi port 3c<br>Block loading | $0.67 T$ |   | Cargo Mass | $i+1$ | $M_Full$ |
    | 9 | Multi port 3c<br>Block loading | $0.67 T$ |   | DB Mass | $i-1$ | empty |
    | 9 | Multi port 3c<br>Block loading | $0.67 T$ |   | DB Mass | $i$ | $M_DBFO$ |
    | 9 | Multi port 3c<br>Block loading | $0.67 T$ |   | DB Mass | $i+1$ | $M_DBFO$ |
    | 10 | Multi port 3d<br>Block loading | $0.67 T$ | ![](images/image150.png) | Cargo Mass | $i-1$ | $M_Full$ |
    | 10 | Multi port 3d<br>Block loading | $0.67 T$ |   | Cargo Mass | $i$ | $M_BW$ |
    | 10 | Multi port 3d<br>Block loading | $0.67 T$ |   | Cargo Mass | $i+1$ | empty |
    | 10 | Multi port 3d<br>Block loading | $0.67 T$ |   | DB Mass | $i-1$ | $M_DBFO$ |
    | 10 | Multi port 3d<br>Block loading | $0.67 T$ |   | DB Mass | $i$ | $M_DBFO$ |
    | 10 | Multi port 3d<br>Block loading | $0.67 T$ |   | DB Mass | $i+1$ | empty |
    | 11 | Multi port 4a<br>Block loading | $0.75 T$ | ![](images/image151.png) | Cargo Mass | $i-1$ | empty |
    | 11 | Multi port 4a<br>Block loading | $0.75 T$ |   | Cargo Mass | $i$ | empty |
    | 11 | Multi port 4a<br>Block loading | $0.75 T$ |   | Cargo Mass | $i+1$ | $M_Full$ |
    | 11 | Multi port 4a<br>Block loading | $0.75 T$ |   | DB Mass | $i-1$ | empty |
    | 11 | Multi port 4a<br>Block loading | $0.75 T$ |   | DB Mass | $i$ | empty |
    | 11 | Multi port 4a<br>Block loading | $0.75 T$ |   | DB Mass | $i+1$ | empty |
    | 12 | Multi port 4b<br>Block loading | $0.75 T$ | ![](images/image152.png) | Cargo Mass | $i-1$ | $M_Full$ |
    | 12 | Multi port 4b<br>Block loading | $0.75 T$ |   | Cargo Mass | $i$ | empty |
    | 12 | Multi port 4b<br>Block loading | $0.75 T$ |   | Cargo Mass | $i+1$ | empty |
    | 12 | Multi port 4b<br>Block loading | $0.75 T$ |   | DB Mass | $i-1$ | empty |
    | 12 | Multi port 4b<br>Block loading | $0.75 T$ |   | DB Mass | $i$ | empty |
    | 12 | Multi port 4b<br>Block loading | $0.75 T$ |   | DB Mass | $i+1$ | empty |
    | 13 | Alter. 1 | $T$ | ![](images/image153.png) | Cargo Mass | $i-1$ | $M_HD$ |
    | 13 | Alter. 1 | $T$ |   | Cargo Mass | $i$ | empty |
    | 13 | Alter. 1 | $T$ |   | Cargo Mass | $i+1$ | $M_HD$ |
    | 13 | Alter. 1 | $T$ |   | DB Mass | $i-1$ | empty |
    | 13 | Alter. 1 | $T$ |   | DB Mass | $i$ | empty |
    | 13 | Alter. 1 | $T$ |   | DB Mass | $i+1$ | empty |
    | 14 | Alter. 2 | $T$ | ![](images/image154.png) | Cargo Mass | $i-1$ | empty |
    | 14 | Alter. 2 | $T$ |   | Cargo Mass | $i$ | $M_HD + 0.1 M_H$ |
    | 14 | Alter. 2 | $T$ |   | Cargo Mass | $i+1$ | empty |
    | 14 | Alter. 2 | $T$ |   | DB Mass | $i-1$ | empty |
    | 14 | Alter. 2 | $T$ |   | DB Mass | $i$ | empty |
    | 14 | Alter. 2 | $T$ |   | DB Mass | $i+1$ | empty |
    | 15 | Alter. 3a<br>Block loading<br>(according to a<br>design loading<br>condition) | $T$ | ![](images/image155.png) | Cargo Mass | $i-1$ | empty |
    | 15 | Alter. 3a<br>Block loading<br>(according to a<br>design loading<br>condition) | $T$ |   | Cargo Mass | $i$ | $M_Blk + 0.1M_H$ |
    | 15 | Alter. 3a<br>Block loading<br>(according to a<br>design loading<br>condition) | $T$ |   | Cargo Mass | $i+1$ | $M_Blk + 0.1M_H$ |
    | 15 | Alter. 3a<br>Block loading<br>(according to a<br>design loading<br>condition) | $T$ |   | DB Mass | $i-1$ | empty |
    | 15 | Alter. 3a<br>Block loading<br>(according to a<br>design loading<br>condition) | $T$ |   | DB Mass | $i$ | empty |
    | 15 | Alter. 3a<br>Block loading<br>(according to a<br>design loading<br>condition) | $T$ |   | DB Mass | $i+1$ | empty |
    | 16 | Alter. 3b<br>Block loading<br>(according to a<br>design loading<br>condition) | $T$ | ![](images/image156.png) | Cargo Mass | $i-1$ | $M_Blk + 0.1M_H$ |
    | 16 | Alter. 3b<br>Block loading<br>(according to a<br>design loading<br>condition) | $T$ |   | Cargo Mass | $i$ | $M_Blk + 0.1M_H$ |
    | 16 | Alter. 3b<br>Block loading<br>(according to a<br>design loading<br>condition) | $T$ |   | Cargo Mass | $i+1$ | empty |
    | 16 | Alter. 3b<br>Block loading<br>(according to a<br>design loading<br>condition) | $T$ |   | DB Mass | $i-1$ | empty |
    | 16 | Alter. 3b<br>Block loading<br>(according to a<br>design loading<br>condition) | $T$ |   | DB Mass | $i$ | empty |
    | 16 | Alter. 3b<br>Block loading<br>(according to a<br>design loading<br>condition) | $T$ |   | DB Mass | $i+1$ | empty |

    | No | Description | Draft | Load pattern | Masses |   |   |
    | --- | --- | --- | --- | --- | --- | --- |
    | 17 | Heavy ballast | $T_BDmin$ | ![](images/image157.png) | Cargo Mass | $i-1$ | empty |
    | 17 | Heavy ballast | $T_BDmin$ |   | Cargo Mass | $i$ | $M_BW$ |
    | 17 | Heavy ballast | $T_BDmin$ |   | Cargo Mass | $i+1$ | empty |
    | 17 | Heavy ballast | $T_BDmin$ |   | DB Mass | $i-1$ | $M_DBBW$ |
    | 17 | Heavy ballast | $T_BDmin$ |   | DB Mass | $i$ | $M_DBBW$ |
    | 17 | Heavy ballast | $T_BDmin$ |   | DB Mass | $i+1$ | $M_DBBW$ |
    | 18 | Harbour 1a | $0.67 T$ | ![](images/image158.png) | Cargo Mass | $i-1$ | empty |
    | 18 | Harbour 1a | $0.67 T$ |   | Cargo Mass | $i$ | $M_Full$ |
    | 18 | Harbour 1a | $0.67 T$ |   | Cargo Mass | $i+1$ | empty |
    | 18 | Harbour 1a | $0.67 T$ |   | DB Mass | $i-1$ | empty |
    | 18 | Harbour 1a | $0.67 T$ |   | DB Mass | $i$ | empty |
    | 18 | Harbour 1a | $0.67 T$ |   | DB Mass | $i+1$ | empty |
    | 19 | Harbour 1b | $0.67 T$ | ![](images/image159.png) | Cargo Mass | $i-1$ | empty |
    | 19 | Harbour 1b | $0.67 T$ |   | Cargo Mass | $i$ | $M_HD$ |
    | 19 | Harbour 1b | $0.67 T$ |   | Cargo Mass | $i+1$ | empty |
    | 19 | Harbour 1b | $0.67 T$ |   | DB Mass | $i-1$ | empty |
    | 19 | Harbour 1b | $0.67 T$ |   | DB Mass | $i$ | empty |
    | 19 | Harbour 1b | $0.67 T$ |   | DB Mass | $i+1$ | empty |
    | 20 | Harbour 2a<br>Block loading | $0.67 T$ | ![](images/image160.png) | Cargo Mass | $i-1$ | empty |
    | 20 | Harbour 2a<br>Block loading | $0.67 T$ |   | Cargo Mass | $i$ | $M_Full$ |
    | 20 | Harbour 2a<br>Block loading | $0.67 T$ |   | Cargo Mass | $i+1$ | $M_Full$ |
    | 20 | Harbour 2a<br>Block loading | $0.67 T$ |   | DB Mass | $i-1$ | empty |
    | 20 | Harbour 2a<br>Block loading | $0.67 T$ |   | DB Mass | $i$ | $M_DBFO$ |
    | 20 | Harbour 2a<br>Block loading | $0.67 T$ |   | DB Mass | $i+1$ | $M_DBFO$ |
    | 21 | Harbour 2b<br>Block loading | $0.67 T$ | ![](images/image161.png) | Cargo Mass | $i-1$ | $M_Full$ |
    | 21 | Harbour 2b<br>Block loading | $0.67 T$ |   | Cargo Mass | $i$ | $M_Full$ |
    | 21 | Harbour 2b<br>Block loading | $0.67 T$ |   | Cargo Mass | $i+1$ | empty |
    | 21 | Harbour 2b<br>Block loading | $0.67 T$ |   | DB Mass | $i-1$ | $M_DBFO$ |
    | 21 | Harbour 2b<br>Block loading | $0.67 T$ |   | DB Mass | $i$ | $M_DBFO$ |
    | 21 | Harbour 2b<br>Block loading | $0.67 T$ |   | DB Mass | $i+1$ | empty |
    | $T$ : scantling draught, $T _{BDmin}$ : heavy ballast draught, $T_BDmax$ : deepest ballast draught<br>$M_Full$ : the cargo mass in the cargo hold corresponding to cargo with virtual density(homogeneous mass/volume of the hold including its hatchway, minimum 1.0 ton/m3) filled to the top of the hatch coaming (ton). $M_Full$ is in no case to be less than $M _{H}$.<br>$M _{H}$ : the cargo mass in the cargo hold corresponding to a homogeneously loaded condition at designed maximum load draught (ton)<br>$M _{HD}$ : the maximum cargo mass allowed to be carried in a cargo hold according to design alternately cargo loaded condition (ton)<br>$M _{Blk}$ : the cargo mass in the cargo hold corresponding to a condition with high density cargo in two adjacent holds, if applicable (ton)<br>$M _{BW}$ : the water mass in ballast hold (ton)<br>$M _{DBFO}$ : the fuel mass in double bottom fuel oil tank (ton)<br>$M _{DBBW}$ : the water mass in double bottom ballast tank (ton)<br>$i$ : number of the cargo hold to be investigated<br>$i-1,i+1$ : number of the cargo hold aft of the cargo hold to be investigated and forward of the cargo hold to be investigated |   |   |   |   |   |   |

    In a cargo hold commonly used as a water ballast tank, the water head at a certain position is to be taken equal to the greater of the value obtained from the following formula and the value of $h$ in the same formula.
    $0.85(h+ \Delta h)$(m)
    where:
    $h$ = height from the position in question to the top of hatch coaming (m)
    $\Delta h$ = a value obtained from the following formula
    $\Delta h= \frac{16}{L} (l _{t} -10)+0.25( \frac{2}{3} B-10)$
    $l _{t}$ = length of tank (m), it is to be taken as 10 m, where it is less than 10 (m).
    $B$ = breadth of ship (m), it is to be taken as 15 m, where $B$ is less than 15 (m).
    - **(a)** Loads due to ore cargo grain cargo, etc.
    - **(i)** The height and surface of the cargo are to be determined in accordance with below as a standard.(See **Fig 14**)
      - **(ii)** The loads on the vertical walls of the hold are, in principle, to be determined by the following formula. The cargo load is not to be applied to the side platings.
    - **(b)** Loads due to liquid cargo, water ballast, etc.
  - **(D)** External load
    Still water load is to apply as specified in **1** (8).
    Wave induced load is to apply as specified in **1** (9).
    - **(a)** Still water load
    - **(b)** Wave induced load
- **(5)** Allowable stress for element types
  - **(A)** Allowable stress for element types
    The permissible values of normal stress $\sigma$ and equivalent stress $\sigma _{e}$ of each member are to be as given in **Table 17.** The allowable stresses in the fine meshes according to the **Table 18.**

    **Table 17 Allowable stress (N/mm ^2 )**

    | Structural members considered |   | $\sigma _{l}$ | $\sigma _{t}$*,* $\sigma _{v}$ | $\sigma _{e}$ |
    | --- | --- | --- | --- | --- |
    | Longitudinal strength members | Bottom shell plating; inner bottom plating; sloping plate of bilge hopper tanks or topside tanks | $110/K$ | $145/K$ | $145/K$ |
    | Longitudinal strength members | Girder |   | ─ | $175/K$ |
    | Transverse strength members | Sloping plate of stools, transverse bulkhead plating |   | $145/K$ | $175/K$ |
    | Transverse strength members | Floor |   | ─ | $175/K$ |
    | Notes:<br>1. The equivalent stress $\sigma _{e}$ is to be as follows.<br>$\sigma _{e} = \sqrt {\sigma _{l} ^{2} - \sigma _{l} \sigma _{t} + \sigma _{t} ^{2} +3 \tau ^{2}}$ : (for longitudinal strength members)<br>$\sigma _{e} = \sqrt {\sigma _{v} ^{2} - \sigma _{v} \sigma _{t} + \sigma _{t} ^{2} +3 \tau ^{2}}$ : (for transverse strength members)<br>$\sigma _{l}$ = normal stress in lengthwise direction<br>$\sigma _{t}$ = normal stress in breadthwise direction<br>$\sigma _{v}$ = normal stress in depthwise direction<br>$\tau$ = shearing stress<br>2. Openings in floors and girders, if any, are to be taken into consideration in evaluating the stresses.<br>3. The point of detecting stress is to the centre of the element.<br>4. $K$ : material factor given in **Table 7.** |   |   |   |   |
  - **(B)** Allowable Stress in the case where hull girder section modulus has a fair allowances.
    The allowable values of normal stress (N/mm^2) in lengthwise direction in the bottom shell and inner bottom plating may be as determined from the following formula.
    - For structural model by using shell elements : $\frac{145}{K} -35f _{B}$
  - **(C)** Allowable stress for loading / unloading conditions in the harbour
    The allowable stress for loading / unloading conditions in the harbour may be 110 % of the values given in **Table 17** and **Table 18**.
- **(6)** Buckling strength
  Buckling strength is to be calculated according to **Ⅳ. Buckling strength calculation**. Buckling strength is to satisfy the criteria defined in **1** (5) of **Ⅳ. Buckling strength calculation** based on static load combination. *(2020)*
- **(7)** Fatigue strength
  Fatigue strength assessment may be carried out in accordance with **Annex 3-3 "Guidance for the Fatigue Strength Assessment of Ship Structures"**.

  **Table 18 Allowable stress (N/mm ^2 ) (For results of the calculations by remeshing with fine meshes)**

  | Structural members considered |   | $\sigma _{a}$ | $\tau$ | $\sigma _{e}$ |
  | --- | --- | --- | --- | --- |
  | Transverse rings | Parallel part | ─ | ─ | $175/K$ |
  | Transverse rings | Corners | $195/K$ | ─ | $195/K$ |
  | Side frames | Middle of parallel part | $175/K$ | ─ | $175/K$ |
  | Side frames | Upper and lower ends of parallel part | $215/K$ | $70/K$ | $195/K$ |
  | Note:<br>1. $\sigma _{a}$ = normal stress of face plate<br>2. The equivalent stress $\sigma _{e}$ is to be as follows.<br>$\sigma _{e} = \sqrt {\sigma _{x} ^{2} - \sigma _{x} \sigma _{y} + \sigma _{y} ^{2} +3 \tau ^{2}}$<br>(The element coordinate system is to be $x­y$ rectangular coordinate system)<br>$\sigma _{x}$ = normal stress in $x­$direction of element coordinate system<br>$\sigma _{y}$ = normal stress in $y­$direction of element coordinate system<br>$\tau$ = shearing stress on the $x$ face in the $y­$direction of element coordinate system<br>3. The point of detecting stress is to be the centre of the element.<br>4. $K$ : material factor given in **Table 7.** |   |   |   |   |

#### 4. Double Hull Oil Tanker

- **(1)** General
  - **(A)** In case where scantlings of structural members of cargo oil tank in double hull tanker are determined by the hold analysis, necessary documents and data on the calculation method are to be submitted to the Society for obtaining approval beforehand.
  - **(B)** Except for those specifically provided for in this part, **Par 1** is to be applied.
- **(2)** Structural modeling
  - **(A)** The range of analysis
    The range of structure to be analyzed is, one side of the three adjacent cargo oil tanks in the parallel body part, including whole length or half length of each cargo oil tank and transverse bulkhead between these two tanks. However, this range is to be extended if necessary so that every condition can be reproduced considering the arrangement of ballast tanks in double hull structures, loading patterns of cargo oil and ballast, and longitudinal and transverse symmetries of the bulkheads and girders attached thereto.
  - **(B)** Structural modelling
    The structural modelling with shell element mesh is : longitudinally two or more elements between every web frame, transversely one element between longitudinal spacing and vertically three or more elements over the depth of double bottom girders an floors. Typical arrangements representing double hull tanker are shown in **Fig 16** to **Fig 17**.
    ![Fig 16 Example model for cargo oil tank structures](images/image162.png)
    **Fig 16 Example model for cargo oil tank structures**
    ![Fig 17 Example of model for side transverse structure](images/image163.png)
    **Fig 17 Example of model for side transverse structure**
- **(3)** Boundary conditions
  The boundary conditions described in this section are to be applied to the F.E model for symmetric load case, as shown in **Fig 18** and **Table 19.**
  - End planes (①) : Symmetric condition
  - Centerline plane (②) : Symmetric condition
  - Vertical counter forces distributed to the side shell nodes at the oil tight BHDs to eliminate reactions at the vertical constraints.(③)
  ![Fig 18 Boundary condition](images/image164.png)
  **Fig 18 Boundary condition**

  | Coord.<br>Position | Displacement |   |   | Rotation |   |   |
  | --- | --- | --- | --- | --- | --- | --- |
  | Coord.<br>Position | $U _{x}$ | $U _{y}$ | $U _{z}$ | $\theta _{x}$ | $\theta _{y}$ | $\theta _{z}$ |
  | ① Both ends of model | 1 | 0 | 0 | 0 | 1 | 1 |
  | ② Centerline | 0 | 1 | 0 | 1 | 0 | 1 |
  | ③ Top of side shell at<br>the oil tight<br>bulkheads | 0 | 0 | 1 | 0 | 0 | 0 |
  | Remark ; 1 : Fixed 0 : Free |   |   |   |   |   |   |
- **(4)** Applied load
  Load to be applied to structural models are to be a combination of internal loads and external loads specified below. In case where, however, another combination of loads is clearly severer than that specified, the latter may be omitted.
  - **(A)** Internal loads
    The water head is to be the vertical distance (m) from each point to a point 2.4 m above the deck at side (m). Examples relating to ship types are shown in **Table 20** to **24.**
    The loading conditions for consideration are, in principle, to be the full load condition and ballast condition. In case where special loading condition such as two-ports loading is predicted, such a special case is to be included. Examples relating to ship's types are shown in **Table 20** to **24.**
    $h ' = \rho (h+ \Delta h)$(m)
    where :
    $\rho$ = maximum designed specific gravity of cargo as given in the loading manual.
    $h$ = vertical distance measured from the position under consideration to the top of hatch (m). But, for lower cargo oil tanks in tankers having mid-decks, vertical distance measured from the position under consideration on the level of mid-deck (m).
    $\Delta h$ = Additional water head given by the following formula; For L-type, U-type of tanks, $h$ is to be determined as deemed appropriate by the Society (m)
    $\Delta h= \frac{16}{L} (l _{t} -10)+0.25(b _{t} -10)$
    $l _{t}$ = tank length (m). however, where it is less than 10 (m), it is to be taken as 10.
    $b _{t}$ = tank breadth (m). however, where it is less than 10 (m), it is to be taken as 10.
    $h ' = \rho h$(m)
    where :
    $\rho$ = sea water gravity (=1.025)
    $h$ = vertical distance measured from the position under consideration to the mid-point of distance between the top of tanks and the top of overflow pipes (m).
    - **(a)** Hydrostatic test condition
    - **(b)** Navigating condition
    - **(i)** Water head $h '$ at each position in cargo oil tanks is to be obtained from the following formula:
      - **(ii)** Water head $h '$ at each position in ballast tanks is to be obtained from the following formula:
      - **(iii)** Requirements prescribed in (b) also apply to cargo oil tanks which possibly utilized as ballast tanks at sea.
      - **(iv)** For water head $h '$ in ships in harbour or similar quiet waters, $\Delta h$ may not be considered.
  - **(B)** External loads
    The water pressure at the bottom and sides under the condition of hydraulic pressure test is to be the hydrostatic pressure corresponding to a draught equal to 1/3 of the designed maximum load draught. (9)
    $h=a(bf-y)$(kN/m^2)
    where :
    $\alpha$ = 2.25 (In case of longitudinal deck girders outside the line of hatchway opening of the strength deck for midship part) or 3.45 (In case of the other deck girders)
    $b$ = 1.0
    $f$ = as given in the following table

    | Ship Length | $f$ |
    | --- | --- |
    | #eqnID-1784150 m | $\frac{L}{10} e ^{- \frac{L}{300}} + \left( \frac{L}{150} \right) ^{2} -1.0$ |
    | 150 m#eqnID-1786300 m | $\frac{L}{10} e ^{- \frac{L}{300}}$ |
    | 300 m$\leq L$ | 11.03 |

    $y$ = vertical distance from the load line to weather deck at side (m).
    - **(a)** Hydrostatic test condition
    - **(b)** Navigating condition
    - **(i)** The water heads (m) of outer bottom and side shell are to apply as specified in **1** (9).
      - **(ii)** In case where cargo oil tanks are empty under the navigation condition and the wave induced load assumes wave crests, deck loads are to be taken into account. Deck loads in this case are to be of values given by the following formula referred to as deck girders(see **Ch 10, Table 3.10.1** of the Rules).
  - **(C)** Loading condition
    **Table 20** to **24** gives the standard load cases which are to be considered in the assessment.
- **(5)** Allowable stress
  Allowable stress for the modelling by using shell elements are shown in **Table 25.**
- **(6)** Deflection of transverses
  In case where the results of the hold analysis show that relative deformations on transverses and vertical web supporting longitudinals, longitudinal beams or bulkhead stiffeners or between bulkheads are large, the added stress due to their effects is to be considered by detail analysis.
- **(7)** Buckling Strength
  Buckling strength is to be calculated according to **Ⅳ. Buckling strength calculation**. Buckling strength is to satisfy the criteria defined in **1** (5) of **Ⅳ. Buckling strength calculation** based on static load combination. *(2020)*
- **(8)** Fatigue strength
  Fatigue strength assessment may be carried out in accordance with **Annex 3-3 "Guidance for the Fatigue Strength Assessment of Ship Structures".**

  | Load Case | Case | External load |   | Internal load |   |
  | --- | --- | --- | --- | --- | --- |
  | Load Case | Case | Static | Wave induced load | Caro oil tank | Ballast tank |
  | Hydrostatic test condition | T-1 | $1/3 d _{s}$^1) | - | $D+2.4$m | *-* |
  | Full loading conditions | F-1 | $d_s$^1) | $W_C$^2) | ^4) | - |
  | Full loading conditions | F-2 | $d_s$^1) | $W_T$^3) | ^4) | - |
  | Full loading conditions | F-3 | $d_s$^1) | $W_C$^2) | ^4) | - |
  | Full loading conditions | F-4 | 0.4$D$ | - | ^4) | - |
  | Ballast condition | B-1 | Ballast draft^6) | - | - | ^5) |
  | Ballast condition | B-2 | Ballast draft^6) | - | ^4) | ^5) |
  | Remark<br>^1) $d _{s}$ : scantling draught<br>^2) $W _{C}$ : wave induced load for wave crest<br>^3) $W _{T}$ : wave induced load for wave trough<br>^4) Water head of cargo oil tank is described in (4) (A) (b) (i)<br>^5) Water head of cargo oil tank is described in (4) (A) (b) (ii)<br>^6) Ballast draft in loading manual is to be applied |   |   |   |   |   |

  | Load case | Case | External load |   | Internal load |   |
  | --- | --- | --- | --- | --- | --- |
  | Load case | Case | Static | Wave induced load | Cargo oil tank | Ballast tank |
  | Hydrostatic test condition | T-1 | $1/3 d _{s}$^1^) | - | $D+2.4$m | - |
  | Hydrostatic test condition | T-2 | $1/3 d_s$^1^) | - | $D+2.4$m | - |
  | Full load and special loading condition | F-1 | $d_s$^1) | $W_C$^2) | ^4) | - |
  | Full load and special loading condition | F-2 | $d_s$^1) | $W_T$^3) | ^4) | - |
  | Full load and special loading condition | F-3 | $d_s$^1) | $W_C$^2) | ^4) | - |
  | Full load and special loading condition | F-4 | $d_s$^1) | $W_T$^3) | ^4) | - |
  | Full load and special loading condition | F-5 | $d_s$^1) | $W_C$^2) | ^4) | - |
  | Full load and special loading condition | F-6 | $d_s$^1) | $W_T$^3) | ^4) | - |
  | Full load and special loading condition | F-7 | $0.4 D$ | - | ^4) | - |
  | Full load and special loading condition | F-8 | $0.4 D$ | - | ^4) | - |
  | Full load and special loading condition | F-9 | $d_s$^1) | $W_C$^2) | ^4) | - |
  | Full load and special loading condition | F-10 | $d_s$^1) | $W_C$^2) | ^4) | - |
  | Full load and special loading condition | F-11 | $d_s$^1) | $W_C$^2) | ^4) | - |
  | Ballast condition | B-1 | Ballast draft^6) | - | - | ^5) |
  | Ballast condition | B-2 | Ballast draft^6) | - | ^5) | ^5) |
  | Ballast condition | B-3 | Ballast draft^6) | - | ^5) | ^5) |
  | Remark<br>^1) $d_s$ : scantling Draught<br>^2) $W_C$ : wave induced load for wave crest<br>^3) $W_T$ : wave induced load for wave trough<br>^4) Water head of cargo oil tank is described in (4) (A) (b) (i)<br>^5) Water head of cargo oil tank is described in (4) (A) (b) (ii)<br>^6) Ballast draft in loading manual is to be applied |   |   |   |   |   |

  | Load case |   | Loading pattern | Center tank |
  | --- | --- | --- | --- |
  | Hydrostatic test condition | T-1 | ![](images/image165.png) | ![](images/image166.png) |
  | Full load and special loading condition | F-1 | ![](images/image167.png) | ![](images/image168.png) |
  | Full load and special loading condition | F-2 | ![](images/image169.png) | ![](images/image170.png) |
  | Full load and special loading condition | F-3 | ![](images/image171.png) | ![](images/image172.png) |
  | Full load and special loading condition | F-4 | ![](images/image173.png) | ![](images/image174.png) |

  | Load case |   | Loading patter | Center tank |
  | --- | --- | --- | --- |
  | Ballast condition | B-1 | ![](images/image175.png) | ![](images/image176.png) |
  | Ballast condition | B-2 | ![](images/image177.png) | ![](images/image178.png) |

  | Load case |   | Loading pattern | Center tank |
  | --- | --- | --- | --- |
  | Hydrostatic test condition<br>Cargo Density: 1.025 | T-1 | ![](images/image179.png) | ![](images/image180.png) |
  | Full load and special loading conditions | F-1 | ![](images/image181.png) | ![](images/image182.png) |
  | Full load and special loading conditions | F-2 | ![](images/image183.png) | ![](images/image184.png) |
  | Full load and special loading conditions | F-3 | ![](images/image185.png) | ![](images/image186.png) |
  | Full load and special loading conditions | F-4 | ![](images/image187.png) | ![](images/image188.png) |

  | Load case |   | Loading pattern | Center tank |
  | --- | --- | --- | --- |
  | Full load and special loading conditions | F-5 | ![](images/image189.png) | ![](images/image190.png) |
  | Full load and special loading conditions | F-6 | ![](images/image191.png) | ![](images/image192.png) |
  | Ballast conditions | B-1 | ![](images/image193.png) | ![](images/image194.png) |
  | Ballast conditions | B-2 | ![](images/image195.png) | ![](images/image196.png) |

  | Load case |   | Loading pattern | Center tank |
  | --- | --- | --- | --- |
  | Hydrostatic test condition | T-1 | ![](images/image197.png) | ![](images/image198.png) |
  | Hydrostatic test condition | T-2 | ![](images/image199.png) | ![](images/image200.png) |
  | Full load and special loading conditions | F-1 | ![](images/image201.png) | ![](images/image202.png) |
  | Full load and special loading conditions | F-2 | ![](images/image203.png) | ![](images/image204.png) |
  | Full load and special loading conditions | F-3 | ![](images/image205.png) | ![](images/image206.png) |
  | Full load and special loading conditions | F-4 | ![](images/image207.png) | ![](images/image208.png) |

  | Load case |   | Loading pattern | Center tank |
  | --- | --- | --- | --- |
  | Full load and special loading conditions | F-5 | ![](images/image209.png) | ![](images/image210.png) |
  | Full load and special loading conditions | F-6 | ![](images/image211.png) | ![](images/image212.png) |
  | Full load and special loading conditions | F-7 | ![](images/image213.png) | ![](images/image214.png) |
  | Full load and special loading conditions | F-8 | ![](images/image215.png) | ![](images/image216.png) |
  | Full load and special loading conditions | F-9 | ![](images/image217.png) | ![](images/image218.png) |
  | Full load and special loading conditions | F-10 | ![](images/image219.png) | ![](images/image220.png) |

  | Load case |   | Loading pattern | Center tank |
  | --- | --- | --- | --- |
  | Full load and special loading conditions | F-22 | ![](images/image221.png) | ![](images/image222.png) |
  | Ballast conditions | B-1 | ![](images/image223.png) | ![](images/image224.png) |
  | Ballast conditions | B-2 | ![](images/image225.png) | ![](images/image226.png) |
  | Ballast conditions | B-3 | ![](images/image227.png) | ![](images/image228.png) |

  |   | Structural members considered |   | $\sigma_l$ | $\sigma_t$*,* $\sigma_v$ | $\sigma_e$ |   |
  | --- | --- | --- | --- | --- | --- | --- |
  | primary members in double hull structure | Longitudinal strength members | Shell plating, Longitudinal bulkhead | $145 / K - 35f$<br>max. $125 / K$ | $145/K$ | $145/K$ |   |
  | primary members in double hull structure | Longitudinal strength members | Girder, stringers |   | ― | $175/K$ |   |
  | primary members in double hull structure | Floor, transverse |   |   | ― | $175/K$ |   |
  | 1. $\sigma _{e}$ is as follows<br>horizontal longitudinal strength member :<br>$\sigma _{e} = \sqrt {\sigma _{l} ^{2} - \sigma _{l} \sigma _{t} + \sigma _{t} ^{2} +3 \tau ^{2}}$<br>vertical longitudinal strength member :<br>$\sigma _{e} = \sqrt {\sigma _{l} ^{2} - \sigma _{l} \sigma _{v} + \sigma _{v} ^{2} +3 \tau ^{2}}$<br>transverse strength member :<br>$\sigma _{e} = \sqrt {\sigma _{v} ^{2} - \sigma _{v} \sigma _{t} + \sigma _{t} ^{2} +3 \tau ^{2}}$<br>$\sigma _{l}$ : normal stress in lengthwise direction<br>$\sigma _{t}$ : normal stress in breadthwise direction<br>$\sigma _{v}$ : normal stress in depthwise direction<br>$\tau$ : shearing stress<br>2. Openings in floors and girders, if any, are to be taken into consideration in evaluating the stresses.<br>3. The point of detecting stress is to be the center of the element.<br>4. $f$ is to be 0 at the position of the horizontal neutral axis of the cross sectional area of hull, $f _{D}$ on upper deck, and $f _{B}$ on bottom shell plating, and to be determined by linear interpolation according to height from the neutral axis. |   |   | Coord.<br>Position ; Displacement ; Rotation<br>$\tau$ ; $x$ ; $y$ ; $U _{x}$ ; $U _{y}$ ; $U _{z}$<br>① Both ends of the model ; 1 ; 0 ; 0 ; 0 ; 1 ; 1<br>② Centerline plane ; 0 ; 1 ; 0 ; 1 ; 0 ; 1<br>③ Top of side shell at the oil tight bulkheads $\theta _{x}$ ; 0 ; 0 ; 1 ; 0 ; 0 ; 0<br>(Notes) 1 : Fixed 0 : Free<br>Structural members considered<br>$\sigma _{a}$<br>$\sigma _{e} (F)$<br>Primary members outside double hull structure<br>Face plate<br>Parallel part<br>$175/K$<br>―<br>Corners<br>$195/K$<br>―<br>Web plate<br>Parallel part<br>―<br>$175/K$<br>Corners<br>―<br>$195/K$<br>1. $\sigma _{a}$ : normal stress of face plate<br>2. $\sigma _{e}$ is as follows<br>$\sigma _{e} = \sqrt {\sigma _{x} ^{2} - \sigma _{x} \sigma _{y} + \sigma _{y} ^{2} +3 \tau ^{2}}$<br>$\sigma _{x}$ : normal stress in $x$-direction of element coordinate system<br>$\sigma _{y}$ : normal stress in $y$-direction of element coordinate system<br>$\tau$ : shearing stress on the $x$ face in $y$direction of element coordinate system<br>3. The point of detecting stress is to be the center of the element. |   |   |   |
  | Coord.<br>Position | Displacement |   |   | Rotation |   |   |
  | Coord.<br>Position | $\tau$ | $x$ | $y$ | $U _{x}$ | $U _{y}$ | $U _{z}$ |
  | ① Both ends of the model | 1 | 0 | 0 | 0 | 1 | 1 |
  | ② Centerline plane | 0 | 1 | 0 | 1 | 0 | 1 |
  | ③ Top of side shell at the oil tight bulkheads $\theta _{x}$ | 0 | 0 | 1 | 0 | 0 | 0 |
  | (Notes) 1 : Fixed 0 : Free |   |   |   |   |   |   |

#### 5. Container ship

- **(1)** General
  - **(A)** In case where scantlings of structural members of cargo hold in container ship are determined by the hold analysis, necessary documents and data on the calculation method are to be submitted to the Society for obtaining approval beforehand.
  - **(B)** Except for those specifically provided for in this part, **Par 1** is to be applied.
- **(2)** Structural modeling
  - **(A)** Model extent
    The extent of finite element model is to include four 40 ft container bays (2-holds length) located at amidship. The model is to represent the full depth of the ship and the half breadth. However if there is asymmetry about the ship's centerline for the primary structure and cargo loading, then full breadth model need to be represented. (see **Fig 19**)
    ![Fig 19 Model extent](images/image229.png)
    **Fig 19 Model extent**
  - **(B)** Structural modelling
    The structural modelling with shell element mesh is : longitudinally two or more elements between every web frame, transversely one element between longitudinal spacing and vertically three or more elements over the depth of double bottom girders and floors. Typical arrangements representing container ship are shown in **Fig 20** to **23.**
    ![Fig 20 Hold model](images/image230.png)
    **Fig 20 Hold model** ![Fig 21 Web frame model](images/image231.png)
    **Fig 21 Web frame model**
    ![Fig 22 Support BHD model](images/image232.png)
    **Fig 22 Support BHD model** ![Fig 23 W.T.BHD. model](images/image233.png)
    **Fig 23 W.T.BHD. model**
- **(3)** Boundary condition
  The boundary conditions described in this section are to be applied to the analysis model for symmetric load case, as shown in **Fig 24** and **Table 26**.
  - End planes (①) : symmetric condition
  - Centerline plane (②) : symmetric condition
  - Vertical counter forces distributed to the side shell nodes at the oil tight BHDs to eliminate reactions at the vertical constraints.(③)

  | Coord.<br>Position | Displacement |   |   | Rotation |   |   |
  | --- | --- | --- | --- | --- | --- | --- |
  | Coord.<br>Position | $U _{x}$ | $U _{y}$ | $U _{z}$ | $\theta _{x}$ | $\theta _{y}$ | $\theta _{z}$ |
  | ① Both ends of the model | 1 | 0 | 0 | 0 | 1 | 1 |
  | ② Centerline plane | 0 | 1 | 0 | 1 | 0 | 1 |
  | ③ Top of side shell at the oil tight bulkheads $P$ | 0 | 0 | 1 | 0 | 0 | 0 |
  | (Notes) 1 : Fixed 0 : Free |   |   |   |   |   |   |

  ![Fig 24 Boundary conditions (Symmetric)](images/image234.png)
  **Fig 24 Boundary conditions (Symmetric)**
  The boundary conditions described in this section are to be applied to the analysis model for asymmetric load case, as shown in **Fig 25** and **Table 27**.
  - Both ends of the model (①) : symmetric condition
  - Connection line of bottom shell and watertight bulkhead to be restrained in horizontal displacement (②)
  - Connection line of side shell and watertight bulkhead to be restrained in vertical displacement(③)

  | Coord.<br>Position | Displacement |   |   | Rotation |   |   |
  | --- | --- | --- | --- | --- | --- | --- |
  | Coord.<br>Position | $U _{x}$ | $U _{y}$ | $U _{z}$ | $\theta _{x}$ | $\theta _{y}$ | $\theta _{z}$ |
  | ① Both ends of the model | 1 | 0 | 0 | 0 | 1 | 1 |
  | ② Line $L$ | 0 | 1 | 0 | 0 | 0 | 0 |
  | ③ Line $S$ | 0 | 0 | 1 | 0 | 0 | 0 |
  | (Notes) 1 : Fixed 0 : Free |   |   |   |   |   |   |

  ![Fig 25 Boundary conditions (Asymmetric)](images/image235.png)
  **Fig 25 Boundary conditions (Asymmetric)**
- **(4)** Load
  - **(A)** Applied load
    The following load components are to be considered : container load, hydrostatic pressure, wave loads and ballast loads etc..
    Still water load is to apply as specified in **1** (8)
    Wave induced load is to apply s specified in **1** (9)
    Ballast load is to apply as specified in **1** (7)
    - **(a)** Container load
    - **(i)** Container loads according to design load are to be applied as point loads to the hull structure grid points nearest to the base of the container stacks. On hatch cover container stack load should be considered properly in account for actual force transfer to hull structure through girder system of hatch cover and support arrangement on hatch coaming.
      - **(ii)** According to the load case, acceleration components due to ship motion are to be considered. The formulas of acceleration factors are to be applied in accordance with the method deemed appropriate by the Society.
    - **(b)** Still water load
    - **(c)** Wave induced load
    - **(d)** Ballast load
  - **(B)** Loading conditions
    **Table 28** and **Table 29** gives the standard load cases which are to be considered in the assessment.
    ․ Wind load may be neglected
    ․ The moment about the stack base caused by the longitudinal force may be ignored
    ․ Container load of hatch cover over to be applied properly on the hatch coming.

    | Load case description | Case | External load |   | Container load |   |   |   |
    | --- | --- | --- | --- | --- | --- | --- | --- |
    | Load case description | Case | Still water load | Wave induced load | Cargo hold |   | Hatch cover over |   |
    | One bay empty condition | F-1 | #eqnID-18881) | $W _{C}$^2) | empty bay | - | empty bay above | 20 ft |
    | One bay empty condition | F-1 | #eqnID-18881) | $W _{C}$^2) | other bays | 20 ft | other covers | 20 ft |
    | One bay empty condition | F-2 | $d _{s}$^1) | $W _{C}$^2) | empty bay | - | empty bay above | 20 ft |
    | One bay empty condition | F-2 | $d _{s}$^1) | $W _{C}$^2) | other bays | 40 ft | other bays | 20 ft |
    | One bay empty condition | F-3 | $d _{s}$^1) | $W _{C}$^2) | empty bay | - | empty bay above | - |
    | One bay empty condition | F-3 | $d _{s}$^1) | $W _{C}$^2) | other bays | 40 ft | other bays | 20 ft |
    | One bay empty condition | F-4 | $d _{s}$^1) | $W _{C}$^2) | all bays | - | empty bay above | - |
    | One bay empty condition | F-4 | $d _{s}$^1) | $W _{C}$^2) | other bays | 40 ft | other bays | 40 ft |
    | Homogeneous loading condition | F-5 | $d _{s}$^1) | $W _{C}$^2) | all bays | 20 ft | all covers | 20 ft |
    | Homogeneous loading condition | F-6 | $d _{s}$^1) | $W _{C}$^2) | all bays | 40 ft | all covers | 40 ft |
    | Homogeneous loading condition | F-7 | $d _{s}$^1) | $W _{C}$^2) | all bays | 40 ft^6) | all covers | 40 ft^6) |
    | Homogeneous loading condition | F-8 | $d _{R}$^5) | $W _{T}$^3) | all bays | 20 ft | all covers | 20 ft |
    | Heeled condition | H-1 | 4) | - | all bays | 20 ft | all covers | 20 ft |
    | Heeled condition | H-2 | 4) | - | all bays | 40 ft | all covers | 20 ft |
    | Surge loading condition | S-1 | $d _{s}$^1) | $W _{C}$^2) | all bays | 40 ft | all covers | 20 ft |
    | Flooded condition | A-1 | $d _{s}$^1) | - | flooded hold | - | all covers | 20 ft |
    | Flooded condition | A-1 | $d _{s}$^1) | - | non-flooded hold | 20 ft | all covers | 20 ft |
    | Notes :<br>1) $d _{s}$ : scantling draught<br>2)$W _{C}$ : wave induced load for wave crest<br>3)$W _{T}$ : wave induced load for wave trough<br>4) Draft at the moment of freeboard deck immersion<br>5) Reduced draft ($d _{R}$) is to be 2/3 of the scantling draft.<br>6) Light cargo weight corresponds to the expected cargo weight when light cargo is loaded in the considered holds.<br>- Light cargo weight in hold is not to be taken more than 55% of design container weight.<br>- Light cargo weight on deck is not to be taken more than 90% of design container weight or 17 metric tons, whichever is the lesser. |   |   |   |   |   |   |   |

    | Load case |   | Loading pattern | Center tank |
    | --- | --- | --- | --- |
    | One bay empty condition | F-1 | ![](images/image236.png) | ![](images/image237.png) |
    | One bay empty condition | F-2 | ![](images/image238.png) | ![](images/image239.png) |
    | One bay empty condition | F-3 | ![](images/image240.png) | ![](images/image241.png) |
    | One bay empty condition | F-4 | ![](images/image242.png) | ![](images/image241.png) |
    | Homogeneous loading condition | F-5 | ![](images/image243.png) | ![](images/image244.png) |
    | Homogeneous loading condition | F-6 | ![](images/image245.png) | ![](images/image244.png) |
    | Homogeneous loading condition | F-7 | ![](images/image245.png) | ![](images/image244.png) |

    | Load case |   | Loading pattern | Center tank |
    | --- | --- | --- | --- |
    | Homogeneous loading condition | F-8 | ![](images/image246.png) | ![](images/image247.png) |
    | Heeld condition | H-1 | ![](images/image248.png) | ![](images/image249.png) |
    | Heeld condition | H-2 | ![](images/image250.png) | ![](images/image251.png) |
    | Surge loading condition | S-1 | ![](images/image252.png) | ![](images/image253.png) |
    | Flooded condition | A-1 | ![](images/image254.png) | ![](images/image255.png) |
    - **(a)** One bay empty condition (F-1)
    - **(i)** One 40 ft bay to be empty of containers. The remaining bays and hatch covers over to be filled with 20 ft containers.
      - **(ii)** The external pressure is to be taken scantling draft and wave induced loads corresponding to the wave crest.
    - **(b)** One bay empty condition (F-2)
    - **(i)** One 40 ft bay to be empty of containers. The remaining bays to be filled with 40 ft containers and hatch covers over to be filled with 20 ft containers.
      - **(ii)** The external pressure is to be taken scantling draft and wave induced loads corresponding to the wave crest.
    - **(c)** One bay empty condition (F-3)
    - **(i)** One 40 ft bay and hatch covers over to be empty of containers. The remaining bays to be filled with 40 ft containers and hatch covers over to be filled with 20 ft containers.
      - **(ii)** The external pressure is to be taken scantling draft and wave induced loads corresponding to the wave crest.
    - **(d)** One bay empty condition (F-4)
    - **(i)** One 40 ft bay and hatch covers over to be empty of containers. The remaining bays and hatch covers over to be filled with 40 ft containers.
      - **(ii)** The external pressure is to be taken scantling draft and wave induced loads corresponding to the wave crest.
    - **(e)** Homogeneous loading condition (F-5)
    - **(i)** All container bays in hold and hatch covers over to be filled with 20 ft containers.
      - **(ii)** The external pressure is to be taken scantling draft and wave induced loads corresponding to the wave crest.
    - **(f)** Homogeneous loading condition (F-6)
    - **(i)** All container bays in hold and hatch covers over to be filled with 40 ft containers.
      - **(ii)** The external pressure is to be taken scantling draft and wave induced loads corresponding to the wave crest.
    - **(g)** Homogeneous loading condition (F-7)
    - **(i)** All container bays in hold and hatch covers over to be filled with 40 ft containers(Light cargo weight, Refer to Table 28).
      - **(ii)** The external pressure is to be taken scantling draft and wave induced loads corresponding to the wave crest.
    - **(h)** Homogeneous loading condition (F-8)
    - **(i)** All container bays in hold and hatch covers over to be filled with 20 ft containers.
      - **(ii)** The external pressure is to be taken reduced draft($d _{R}$, Refer to Table 28) and wave induced loads corresponding to the wave trough.
    - **(i)** Heeled condition (H-1)
    - **(i)** All container bays in hold and hatch covers over to be filled with 20 ft containers. External sea pressure in the heeling condition are to be taken at the moment of freeboard deck immersion and no wave induced load to be applied.
      - **(ii)** Transverse loads caused by ship acceleration are to be calculated by the method deemed appropriate by the Society.
    - **(j)** Heeled condition (H-2)
    - **(i)** All container bays in hold to be filled with 40 ft containers and hatch covers over to be filled with 20 ft containers. External sea pressure in the heeling condition are to be taken at the moment of freeboard deck immersion and no wave induced load to be applied.
      - **(ii)** Transverse loads caused by ship acceleration are to be calculated by the method deemed appropriate by the Society.
    - **(k)** Surge loading condition (S-1)
    - **(i)** All container bays in hold to be filled with 40 ft containers and hatch covers over to be filled with 20 ft containers. The external pressure is to be taken scantling draft and wave induced loads corresponding to the wave crest.
      - **(ii)** The container loads to be considered longitudinal acceleration factor due to ship motion. The longitudinal force acting on containers within hold is to be calculated at the center of each container and is to be suitably distributed to the bulkhead primary members in way of the cell guides. The longitudinal force action on containers on hatch covers is to be calculated at the midheight of the stack. The following assumptions are to be made:
    - **(l)** Flooded condition (A-1)
    - **(i)** Two 40 ft bays over to be empty of containers. The remaining bays to be filled with 40 ft containers and hatch covers over to be filled with 20 ft containers.
      - **(ii)** This loading case is to ensure that the structural integrity of the transverse watertight bulkhead and stringers when the container hold is flooded as a result of collision or other accidental occurrence.
      - **(iii)** The external pressure may be taken at a draught equal to the scantling draught and internal pressure in damaged hold may be taken at a draught equal to 90 % of freeboard deck level.
- **(5)** Allowable stress
  Allowable stress for the modelling by using shell elements are shown in **Table 30.** But, The stresses resulting from Load case A-1 are given in **Table 31.**
- **(6)** Buckling strength calculation
  Buckling strength is to be calculated according to **Ⅳ. Buckling strength calculation**. Buckling strength is to satisfy the criteria defined in **1** (5) of **Ⅳ. Buckling strength calculation** based on static load combination. However, For LCA-1, allowable buckling utilization factor is to be applied 1.0. *(2020)*

  | Stress<br>Structural member considered | $\sigma _{l}$ | $\sigma _{t}$ , $\sigma _{v}$ | $\sigma _{e}$ | $\tau$ |
  | --- | --- | --- | --- | --- |
  | Bottom shell, Inner bottom | $110/K$ | $145/K$ | $145/K$ | - |
  | Longitudinal bulkhead, Side shell | - | $145/K$ | - | $83/K$ |
  | Girder | - | - | $175/K$ | $83/K$ |
  | Stringer | $110/K$ | - | $175/K$ | $83/K$ |
  | Water tight bulkhead | - | $145/K$ | $175/K$ | - |
  | Transverse web frame, floor | - | - | $175/K$ | - |
  | (Notes)<br>1. The equivalent stress $\sigma _{e}$ is to be as follows.<br>$\sigma _{e} = \sqrt {\sigma _{l} ^{2} - \sigma _{l} \cdot \sigma _{t} + \sigma _{t} ^{2} +3 \tau ^{2}}$ (for longitudinal strength members)<br>$\sigma _{e} = \sqrt {\sigma _{v} ^{2} - \sigma _{v} \cdot \sigma _{t} + \sigma _{t} ^{2} +3 \tau ^{2}}$ (for transverse strength members)<br>$\sigma _{l}$ : normal stress in lengthwise direction<br>$\sigma _{t}$ : normal stress in breadthwise direction<br>$\sigma _{v}$ : normal stress in depthwise direction<br>$\tau$ : shear stress<br>2. Opening in floors and girders, if any, are to be taken into consideration in evaluating the stresses.<br>3. The point detection stress is to the center of the element. |   |   |   |   |

  | Structural members considered | Steel grades | $\sigma _{e}$ | $\tau$ |
  | --- | --- | --- | --- |
  | Trans. water tight bulkhead, side transverse web frame, stringer and girder | *A, B, D* and *E* | 235 | 136 |
  | Trans. water tight bulkhead, side transverse web frame, stringer and girder | *AH* 32, *DH* 32 and *EH* 32 | 315 | 182 |
  | Trans. water tight bulkhead, side transverse web frame, stringer and girder | *AH* 36, *DH* 36 and *EH* 36 | 355 | 205 |

#### 6. Ro-Ro ship (2021)

- **(1)** General
  - **(A)** In case where scantlings of structural members of cargo hold in Ro-Ro ship are determined by direct strength calculation, necessary documents and data for its calculation are to be submitted to the Society for approval beforehand.
  - **(B)** Except for those specifically provided for in this part, **Par 1** is to be applied.
- **(2)** Structural modeling
  - **(A)** Model extent
    The extent of finite element model is to include two piller spaces(1/2+1+1/2) located amidship. The model is to represent the full breadth of the ship. (see **Fig 26**.)
    ![Fig 26 Analysis extent](images/image256.png)
    **Fig 26 Analysis extent**
  - **(B)** Structural modelling for finite elements
    Meshes for the structural modelling with shell elements is longitudinally two or more elements between every web frame, transversely one element between longitudinal spacings and vertically three or more elements over the depth of double bottom girders and floors. Typical arrangements representing pure car and truck carrier are shown in **Fig 27** to **29.**
    ![Fig 27 Hold model](images/image257.png)
    **Fig 27 Hold model**
    ![Fig 28 Web frame model](images/image258.png)
    **Fig 28 Web frame model** ![Fig 29 Pillar model](images/image259.png)
    **Fig 29 Pillar model**
- **(3)** Boundary condition
  Reasonable boundary conditions for the analysis model are to be applied to describe the same behaviour of actual structure. The boundary conditions described in this section are to be applied as shown in **Table 32** and **Fig 30.**
  - Both ends of the model (①) : symmetric condition
  - All nodes on line $L$ (②) are to be restrained in horizontal displacement
  - All nodes on line $S$ (③) are to be restrained in vertical displacement

  | Coord.<br>Position | Displacement |   |   | Rotation |   |   |
  | --- | --- | --- | --- | --- | --- | --- |
  | Coord.<br>Position | $U _{x}$ | $U _{y}$ | $U _{z}$ | $\theta _{x}$ | $\theta _{y}$ | $\theta _{z}$ |
  | ① Both ends of the model | 1 | 0 | 0 | 0 | 1 | 1 |
  | ② Line $L$ | 0 | 1 | 0 | 0 | 0 | 0 |
  | ③ Line $S$ | 0 | 0 | 1 | 0 | 0 | 0 |
  | (Note) 1 : Fixed 0 : Free |   |   |   |   |   |   |

  ![Fig 30 Boundary condition](images/image260.png)
  **Fig 30 Boundary condition**
- **(4)** Load
  - **(A)** Applied load
    The following load components are to be considered : cargo load, hydrostatic pressure, wave loads and ballast loads etc. as shown in **Table 33** and **34.**
    Still water load is to be applied as specified in **1** (8).
    Wave induced load is to be applied as specified in **1** (9).
    Ballast load is to be applied as specified in **1** (7).
    - **(a)** Cargo load
    - **(i)** Cargo loads are to be applied as the design uniform loads according to the vehicle, passenger, etc expected to be loaded on each deck.
      - **(ii)** According to the load case, acceleration components due to ship motion are to be considered. The formulas of acceleration factors are to be applied in accordance with the method deemed appropriate by the Society.
    - **(b)** Still water load
    - **(c)** Wave induced load
    - **(d)** Ballast load
  - **(B)** Loading conditions *(2021)*
    6 types of loading cases are to be considered and corresponding members are to be assessed according to each loading condition.

    | Load case | Case | External load |   | Cargo load |
    | --- | --- | --- | --- | --- |
    | Load case | Case | Still water load | Wave induced load | Cargo hold |
    | Maximum cargo on lower part of section in upright condition | F-1 | $d_s$^1) | $W_C$^2) | Design uniform load |
    | Maximum cargo on upper part of section in upright condition | F-2 | $d_s$^1) | $W_C$^2) | Design uniform load |
    | Ballast condition | B-1 | Ballast draft^3) | $W_C$^2) | - |
    | Transversely unsymmetrical deck load | H-1 | $d_s$^1) | $W_C$^2) | Design uniform load |
    | Longitudinally unsymmetrical deck load | H-2 | $d_s$^1) | $W_C$^2) | Design uniform load |
    | Flooding condition | A-1 | $d_s$^4) | - | - |
    | (Note)<br>^1) $d_s$ : scantling draught<br>^2) $W _{C}$ : wave induced load for wave crest<br>^3) Ballast draft in loading manual is to be applied.<br>^4) Flooding condition draft in damage stability data is to be applied. |   |   |   |   |

    | Load case | Case | Center cargo hold |
    | --- | --- | --- |
    | Maximum cargo on lower part of section in upright condition | F-1 | ![](images/image261.png) |
    | Maximum cargo on upper part of section in upright condition | F-2 | ![](images/image262.png) |
    | Ballast condition | B-1 | ballast<br>draft |

    | Load case | Case | Center cargo hold |
    | --- | --- | --- |
    | Transversely unsymmetrical deck load | H-1 | ![](images/image264.png)![](images/image265.png) |
    | Longitudinally unsymmetrical deck load | H-2 | ![](images/image266.png)![](images/image267.png) |
    | Flooding condition | A-1 | ![](images/image268.png) |
    - **(a)** Maximum cargo on lower part of section in upright condition
    - **(i)** The load case may be decisive for the lower decks and pillars(where relevant) subject to design uniform load of vehicle, passenger, etc on lower deck.
      - **(ii)** The external pressure is to be taken by scantling draft and wave induced loads corresponding to the wave crest.
    - **(b)** Maximum cargo on upper part of section in upright condition
    - **(i)** The load case may be decisive for the upper decks, double bottom and pillars(where relevant) subject to design uniform load of vehicle, passenger, etc on upper deck.
      - **(ii)** The external pressure is to be taken by scantling draft and wave induced loads corresponding to the wave crest.
    - **(c)** Ballast condition
    - **(i)** Design uniform load of vehicle, passenger, etc is not to be considered. However, the ballast water weight in the ballast tank is to be considered.
      - **(ii)** The external pressure is to be taken by actual draft according to the loading manual and wave induced loads corresponding to the wave crest.
    - **(d)** Transversely unsymmetrical deck load
    - **(i)** The load case may be decisive for the transverse deck girders subject to design uniform load of vehicle, passenger, etc on one side deck only (port or starboard).
      - **(ii)** The external pressure is to be taken by scantling draft and wave induced loads corresponding to the wave crest.
    - **(e)** Longitudinally unsymmetrical deck load
    - **(i)** The load case may be decisive for the longitudinal deck girders subject to design uniform load of vehicle, passenger, etc on deck between each piller only.
      - **(ii)** The external pressure is to be taken by scantling draft and wave induced loads corresponding to the wave crest.
    - **(f)** Flooding condition
    - **(i)** The damage flooding condition where the ship is floating on watertight decks is in general subject to special assessment with respect to the strength of the watertight deck in the final damage condition.
      - **(ii)** The external pressure is to be taken by actual draft according to the damage stability data.
- **(5)** Allowable stress
  Allowable stresses for the modelling using shell elements are shown in **Table 35.** However, The stresses resulting from load case A-1 are given in **Table 36.**
- **(6)** Buckling strength calculation
  Buckling strength is to be calculated according to **Ⅳ. Buckling strength calculation**. Buckling strength is to satisfy the criteria defined in **1** (5) of **Ⅳ. Buckling strength calculation** based on static load combination. *(2020)*

  | Stress<br>Structural member considered | $\sigma _{l}$ | $\sigma _{t}$ , $\sigma _{v}$ | $\sigma _{e}$ | $\tau$ |
  | --- | --- | --- | --- | --- |
  | Bottom shell, Inner bottom | $110/K$ | $145/K$ | $145/K$ | - |
  | Longitudinal bulkhead, Side shell | - | $145/K$ | - | $90/K$ |
  | Girder | - | - | $175/K$ | $90/K$ |
  | Stringer | $110/K$ | - | $175/K$ | $90/K$ |
  | Watertight bulkhead | - | $145/K$ | $175/K$ | - |
  | Transverse web frame, floor | - | - | $175/K$ | - |
  | (Note)<br>1. The equivalent stress $\sigma _{e}$ is to be as follows.<br>$\sigma _{e} = \sqrt {\sigma _{l} ^{2} - \sigma _{l} \cdot \sigma _{t} + \sigma _{t} ^{2} +3 \tau ^{2}}$ (for longitudinal strength members)<br>$\sigma _{e} = \sqrt {\sigma _{v} ^{2} - \sigma _{v} \cdot \sigma _{t} + \sigma _{t} ^{2} +3 \tau ^{2}}$ (for transverse strength members)<br>$\sigma _{l}$ : normal stress in lengthwise direction<br>$\sigma _{t}$ : normal stress in breadthwise direction<br>$\sigma _{v}$ : normal stress in depthwise direction<br>$\tau$ : shear stress<br>2. Openings in floors and girders, if any, are to be taken into consideration in evaluating the stresses.<br>3. The point of stress evaluation is to be the center of the element. |   |   |   |   |

  | Structural members considered | Steel grades | $\sigma _{v}$ | $\tau$ |
  | --- | --- | --- | --- |
  | Trans. watertight bulkhead, side transverse web frame, stringer and girder | *A, B, D* and *E* | 235 | 136 |
  | Trans. watertight bulkhead, side transverse web frame, stringer and girder | *AH* 32, *DH* 32 and *EH* 32 | 315 | 182 |
  | Trans. watertight bulkhead, side transverse web frame, stringer and girder | *AH* 36, *DH* 36 and *EH* 36 | 355 | 205 |
- **(7)** Racking Assessment *(2021)*
  - **(A)** Racking assessment in this Guidance is to be applied to vehicle carriers carrying over 6000 Car units, based on small car, and car ferries (RoPax) with Rule length over 130 m.
  - **(B)** Racking assessment should be performed for full ship model in accordance with **II.3** (refer to **Fig 30-1**). In case that hull section is asymmetry, racking assessment shall perform for each side of starboard and port side.
  - **(C)** Racking load is to be assessed for full loading condition defined in Trim and Stability Booklet. Loads for racking assessment are followed as below;
    $a _{j _{-} y _{-} env} = \sqrt {a _{sway}^{2} + \left\{ g \sin \theta +a _{roll} (z _{j _{-} deck} -0.41 \frac{D '}{f _{\sec}} ) \right\} ^{2}} (m/s ^{2} )$,
    horizontal acceleration at $j$-th deck
    where,
    $a _{sway} =0.45 a _{0} g (m/s ^{2} )$ , sway acceleration
    $a _{0} =(1.58-0.244 f _{\sec} ) \left( \frac{2.4}{\sqrt {L}} + \frac{34}{L} + \frac{600}{L ^{2}} \right) (m/s ^{2} )$, basic acceleration,
    $a _{roll} = \frac{1.72}{f _{\sec}} \theta \frac{\pi}{180} \left( \frac{2 \pi}{T _{\theta }} \right) ^{2} (rad/s ^{2} )$, roll acceleration
    $z _{j _{-} deck}$ : height of j-th deck from base line
    $f _{\sec} = \frac{\max(B, D ' )}{\min(B, D ' )}$
    $D '$ : height (m) between upper plane of cargo compartment and base line, see **Fig. 30-2**.
    $\theta = \frac{12150(1.25-0.025T _{\theta } )}{f _{\sec} (B+75) \pi} (deg)$
    $T _{\theta } =2.3 \pi \frac{kr}{\sqrt {gGM}} (\sec)$, roll period
    $kr = 0.42 B (m)$, inertia radius
    $GM =0.05f _{\sec} B (m)$, transverse metacentric height

    | ![](images/image269.png)<br>![](images/image270.png)<br>**Fig. 30-1 Full ship model and boundary condition of Ro-Ro ship** |
    | --- |

    | ![](images/image271.png)<br>![](images/image272.png)<br>**Fig. 30-2 Racking loads in heeling** |
    | --- |
    - **(a)** Vertical loads such as self-weight, liquid in tanks and cargo weight.
    - **(b)** Unsymmetrical external pressure based on center line considering heeling angle ($\theta$), see **Fig. 30-2.**
    - **(c)** Horizontal load induced from deck self weight and cargo weight (vehicle, passenger, etc) considering horizontal acceleration ($a _{y _{-} env}$) as below;
  - **(D)** For racking assessment, the harbour condition is to be applied without hull girder force balancing. However, the unbalance forces due to racking moment should be removed by using pair forces ($F _{i}$), see **Fig. 30-3**, on intersected location between side shell and upper deck. Racking moment can be calculated as below;
    $M <sub>xx</sub> = \sum <sub>j</sub> <sup>n <sub>decks</sub></sup> (W <sub>j _{-</sub> deck <sub>-</sub> self} +W <sub>j _{-</sub> deck <sub>-</sub> cargo} ) \sigma <sub>j _{-</sub> y <sub>-</sub> env} (z <sub>j _{-</sub> deck} -z <sub>bulkhead _{-</sub> deck} )\#

    \#

     = \sum <sub>i</sub> <sup>n <sub>web frames</sub></sup> (F <sub>i</sub> \cdot b <sub>i</sub> )$
    where,
    $W _{j _{-} deck _{-} self}$ : self weight of j-th deck
    $W _{j _{-} deck _{-} cargo}$ : cargo weight of j-th deck
    $a _{j _{-} y _{-} env}$ : horizontal acceleration of j-th deck
    $z _{j _{-} deck} , z _{bulkhead _{-} deck}$ : heights of j-th deck and bulkhead deck from base line
    $F _{i}$ : pair forces at i-th frame
    $b _{i}$ : half breadth of upper deck at i-th frame
    ![Fig. 30-3 Force balancing for racking moment](images/image273.png)
    **Fig. 30-3 Force balancing for racking moment**
  - **(E)** Target structural members for racking assessment are as below;
    - connection of racking constraining structure such as vertical web frames to bulkhead deck and deck transverse
    - connection of transverse member, deck or inner bottom between pillar support
    - connection of staircase or ventilation ducts between primary support members
    - other high stress zones such as deep racking frames, partial bulkheads, engine room casing and stairway/lift casings
  - **(F)** For racking assessment, the allowable stress of target structural members is to be 0.94⦁(235/K) of equivalent stress defined in (5).
  - **(G)** Fine-mesh analysis
    a) High stress concentrated areas where the stress concentration is more than 95% of the evaluation criteria defined in (F) need to be verified by fine mesh analysis with the criteria, 0.94⦁β⦁(235/K).
    β : mesh density factor
    - 1.15 for less than or equal to 200 x 200 mm mesh size
    - 1.25 for less than or equal to 100 x 100 mm mesh size
    - 1.5 for less than or equal to 50 x 50 mm mesh size
    - 1.7 for less than or equal to 2t x 2t mesh size
    - the below areas where the maximum stress from racking assessment in (F) is occurred at each deck;.
    ⦁the area where the face plate of support members of pillar meets deck.
    ⦁the area where the face plate of deck transverse (or floor) meets side transverse web frame,
    - the area where the fixed lamp meets forward wall of engine room.
    - **(b)** In the case of pure vehicle carrier, the following areas, regardless with (a), are to be modeled with 2t x 2t mesh size in order to check local stress concentration reflecting the shape of cruciform joints, back side supporting members in large structures, etc. The mesh density factor, β, is to be applied 1.35 for the element adjacent to weld and 1.53 for the element not adjacent to weld.

#### 7. Structural Analysis Procedure for Membrane Tank LNG Carriers

- **(1)** General
  - **(A)** This guidance apply to the Membrane Tank LNG Ships.
  - **(B)** In case where scantlings of structural members of cargo hold in Membrane Tank LNG Ships are determined by direct strength calculation, necessary documents and data for its calculation are to be submitted to the Society for approval beforehand.
  - **(C)** Except for those specifically provided for in this part, **Par 1** is to be applied.
- **(2)** Structural modelling
  - **(A)** Model extent
    - **(a)** The 3D finite element model is to cover midship and forward cargo tank regions. It is in order to verify the effect due to the change of hull structural arrangements and the change of the cargo tank structure according to the ship shape. Also it is in order to verify the effect of acceleration in the foremost cargo tank(hereinafter No. 1 cargo tank).
    - **(b)** The minimum longitudinal extent of the finite element model is to represent from the bow to the aft bulkhead of tank located in midship. If aft cargo tank of midship cargo tank and midship cargo tank have significantly different structural arrangement and scantling, the aft cargo tank of midship cargo tank is to be included in the modeling.
    - **(c)** The full depth of the ship is to be modeled.
    - **(d)** When the structure of cargo tank is symmetric with respect to the center line, only one side of the cargo tank may be modeled by imposing appropriate boundary conditions at the centerline. However, it is recommended that both sides of the ship to be modeled, as this will simplify the loading and analysis of the asymmetric heeled loading conditions.
    - **(e)** First, analysis with the model in accordance with (B) is to be carried out and detail analysis with fine mesh model in accordance with (C) is to be carried out, if necessary.
  - **(B)** Structural modeling
    - **(a)** Mesh size of cargo hold model is to follow as below(Refer to **Fig 31** to **38**).
    - **(i)** Longitudinally, two or more elements between every web frame
      - **(ii)** Transversely, one element between longitudinal spacing
      - **(iii)** Vertically, three or more element over the depth of double bottom girders and floors
    - **(b)** In principle, access opening is to be modeled by deleting the appropriate elements.
    - **(c)** After choosing the appropriate element for structural member, structure is to be modeled in order to simulate the performance properly.
    - **(i)** shell element : side shell, bottom shell, floors, transverse bulkhead, longitudinal bulkhead, deck, web plates of primary support members, etc.
      - **(ii)** beam element : longitudinal/transverse stiffeners, water tight bulkhead stiffeners, etc.
      - **(iii)** truss element : face plate of primary support members, etc.
  - **(C)** Fine mesh
    ![Fig 31 Example of Cargo Hold model(Mark III Type)](images/image274.png)
    **Fig 31 Example of Cargo Hold model(Mark III Type)**
    ![Fig 32 Example of Cargo Hold model(Mark III Type)](images/image275.png)
    **Fig 32 Example of Cargo Hold model(Mark III Type)**
    ![Fig 33 Example of Cargo Hold model(Mark III Type, Except outer hull)](images/image276.png)
    **Fig 33 Example of Cargo Hold model(Mark III Type, Except outer hull)**
    ![Fig 34 Example of Cargo Hold model(NO 96 Type)](images/image277.png)
    **Fig 34 Example of Cargo Hold model(NO 96 Type)**
    ![Fig 35 Example of Cargo Hold model(NO 96 Type)](images/image278.png)
    **Fig 35 Example of Cargo Hold model(NO 96 Type)**
    ![Fig 36 Example of Cargo Hold model(NO 96 Type, Except outer hull)](images/image279.png)
    **Fig 36 Example of Cargo Hold model(NO 96 Type, Except outer hull)**
    ![Fig 37 Typical F.E. Model of a web frame](images/image280.png)
    **Fig 37 Typical F.E. Model of a web frame**
    ![Fig 38 Typical F.E. Model of a transverse watertight bulkhead](images/image281.png)
    **Fig 38 Typical F.E. Model of a transverse watertight bulkhead**
    ![Fig 39 Sample 1 of fine mesh](images/image282.png)
    **Fig 39 Sample 1 of fine mesh**![Fig 40 Sample 2 of fine mesh](images/image283.png)
    **Fig 40 Sample 2 of fine mesh**
    ![Fig 41 Sample 3 of fine mesh](images/image284.png)
    **Fig 41 Sample 3 of fine mesh**
    - **(a)** In case where the mesh size of cargo hold model is not enough to simulate the high stress area, independent local model with fine mesh imposed by the boundary conditions from main model is to be assessed. Alternatively, the high stress area can be assessed by modeling through fine mesh directly in the cargo hold model.
    - **(b)** Notwithstanding (a), areas where a fine mesh is needed are as follows(Refer to **Fig 39** to **41**).
    - **(i)** The inner bottom to hopper side connections at mid-hold, including local floor and hopper web plating
      - **(ii)** The hopper side to inner side connection at mid-hold, including local hopper web and side transverse plating
      - **(iii)** Transverse bulkhead to inner bottom connection, including local vertical webs and girders
      - **(iv)** Transverse bulkhead to inner trunk deck connection, including local vertical webs and girders
    - **(v)** Transverse bulkhead to inner side structure connection, including horizontal girders
      - **(vi)** Connection to the Liquid dome
    - **(c)** In general, the minimum required mesh size in fine mesh areas is not to be greater than 200 x 200 mm. *(2018)*
- **(3)** Boundary conditions
  - **(A)** Boundary conditions under vertical dynamic loading conditions

    | Position | Displacement |   |   | Rotation |   |   |
    | --- | --- | --- | --- | --- | --- | --- |
    | Position | $\delta _{x}$ | $\delta _{y}$ | $\delta _{z}$ | $\theta _{x}$ | $\theta _{y}$ | $\theta _{z}$ |
    | ① All nodes of all longitudinal members at the section of model end | 1 | 0 | 0 | 0 | 1 | 1 |
    | ② Intersection of centerline and keel and deck at the section of model end | 0 | 1 | 0 | 0 | 0 | 0 |
    | ③ All nodes on line S | 0 | 0 | 1 | 0 | 0 | 0 |
    | Remark)<br>1 : Fixed 0 : Free<br>Line S : Line where watertight bulkhead connect to side shell and section of the model end connect to side shell and inner longitudinal bulkhead |   |   |   |   |   |   |

    ![](images/image285.png)
    **Fig 42 Boundary conditions for vertical dynamic loading condition**
    - **(a)** Boundary conditions in **Table 37** is applicable to vertical dynamic loading conditions(LC1 ~ LC4) in **Table 40**(Refer to **Fig 42**).
    - **(b)** These boundary conditions allow the model to be deformed globally under hull girder vertical shear force and bending moments are applied.
  - **(B)** Boundary conditions under impact loading conditions

    | Position | Displacement |   |   | Rotation |   |   |
    | --- | --- | --- | --- | --- | --- | --- |
    | Position | $\delta _{x}$ | $\delta _{y}$ | $\delta _{z}$ | $\theta _{x}$ | $\theta _{y}$ | $\theta _{z}$ |
    | ① All nodes of all longitudinal members at the section of model end | 1 | 0 | 0 | 0 | 1 | 1 |
    | ② Intersection of centerline and keel and deck at the section of model end | 0 | 1 | 0 | 0 | 0 | 0 |
    | ③ Top intersection of side shell and watertight bulkhead | 0 | 0 | 1 | 0 | 0 | 0 |
    | Remark)<br>1 : Fixed 0 : Free |   |   |   |   |   |   |

    ![Fig 43 Boundary conditions for impact loading condition](images/image286.png)
    **Fig 43 Boundary conditions for impact loading condition**
    - **(a)** Boundary conditions in **Table 38** is applicable to impact loading conditions(LC9 and LC10) in Table 40(Refer to **Fig 43**).
    - **(b)** Distributed vertical forces are applied to the intersection of watertight bulkhead and side shell to eliminate reaction forces due to the vertical constraints. These forces equal to the vertical imbalance of the model caused by the difference between the internal loads and the applied buoyancy. Alternatively, vertical direction spring elements may be applied to these intersection.
  - **(C)** Asymmetric boundary conditions(Transverse dynamic loading condition, static transverse heeled conditions)
    Boundary conditions in **Table 39** is applicable to transverse dynamic loading conditions and static transverse heeled conditions(LC5 ~ LC8) in **Table 40**(Refer to **Fig 44**).

    | Position | Displacement |   |   | Rotation |   |   |
    | --- | --- | --- | --- | --- | --- | --- |
    | Position | $\delta _{x}$ | $\delta _{y}$ | $\delta _{z}$ | $\theta _{x}$ | $\theta _{y}$ | $\theta _{z}$ |
    | ① All nodes of all<br>longitudinal members at the<br>section of model end | 1 | 0 | 0 | 0 | 1 | 1 |
    | ② All nodes on line L | 0 | 1 | 0 | 0 | 0 | 0 |
    | ③ All nodes on line S | 0 | 0 | 1 | 0 | 0 | 0 |
    | Remark)<br>Line L : Line where watertight bulkhead connect to inner bottom and trunk deck<br>Line S : Line where watertight bulkhead connect to side shell and section of the model end connect to side shell and inner longitudinal bulkhead<br>1 : Fixed, 0 : Free |   |   |   |   |   |   |

    ![Fig 44 Boundary condition for transverse dynamic loading condition and transverse heeled condition](images/image287.png)
    **Fig 44 Boundary condition for transverse dynamic loading condition and transverse heeled condition**
- **(4)** Applied load
  - **(A)** Loading conditions considered in direct strength analysis are to be applied by combining the loading components from (B) to (D) in accordance with **Table 40**.
  - **(B)** Internal loads
    ① Cargo load on still water
    $P = \rho _{c} gh _{z} + P _{o}$
    $\rho _{c}$ : Design density of LNG(ton/m^3)
    $P _{o}$ : Design vapor pressure of Cargo tank(MPa)
    $g$ : gravity acceleration, 9.81 (m/s^2)
    $h _{z}$ : Vertical distance from the highest point of Cargo Hold to a point under consideration(m)
    ② Cargo load under vertical dynamic loading conditions
    $P = 0.5 \rho _{c} gh _{z} a _{z} + 0.5 \rho _{c} gh _{x} a _{x}$
    $a _{x}$ : calculated acceleration in x-direction in accordance with (b)
    $a _{z}$ : calculated acceleration in z-direction in accordance with (b)
    $h _{x}$ : Distance in forward direction from after end of cargo hold under consideration to a point under consideration(m)
    ③ Cargo load under transverse dynamic loading conditions
    $P = P _{asym}$
    $P _{asym}$: Inertia load of cargo induced by transverse acceleration is to be determined as follows.
    $P _{asym} = 0.5 \rho _{c} gh _{y} a _{y}$
    $a _{y}$ : calculated acceleration in y-direction in accordance with (b)
    $h _{y}$ : Transverse distance from inner bulkhead of starboard to a point under consideration (m)
    ④ Impact load *(2018)*
    forward direction : $P = 0.5 \rho _{c} gh _{x}$
    aftward direction : $P = 0.25 \rho _{c} gh _{x}$
    - **(a)** The internal loads are to be considered the following load components.
    - **(i)** Cargo load
      - **(ii)** Ballast load
      - **(iii)** Self-weight of structural model
    - **(b)** Acceleration application
    - **(i)** Acceleration by hull motion is to be calculated by following **Pt 7, Ch 5, 428.** of the rules. Maximum acceleration among all loading conditions is to be applied as cargo load. Also, other equivalent methods of calculation(acceleration by ship motion) will be acceptable and methods to predict accelerations are to be submitted to the Society for approval. *(2018)*
      - **(ii)** For transverse dynamic load cases, transverse acceleration is to be calculated based on (i). However transverse acceleration is to be more than 0.5.
      - **(iii)** For impact load cases, 0.5 in forward direction is to be applied.
    - **(c)** Cargo load
    - **(i)** When cargo load is applied, the design vapor pressure of cargo tank is to be considered.
      - **(ii)** Cargo load, for load combination for design vapor pressure, static and dynamic load due to acceleration, is to be accordance with the following equation.
  - **(C)** External loads
    $P= \rho g(z \cos \theta + y \sin \theta )$
    $z$ : Draft under non heeled conditions
    $y$ : Transverse distance from centerline to a point under consideration, positive to port
    $\theta$ : Heel angle is applied as 30°.
    ![Fig 45 Hydrostatic pressure distribution for transverse heeled](images/image288.png)
    **Fig 45 Hydrostatic pressure distribution for transverse heeled**

    | Load Case |   | Load Description |   | Bending Moments^1) |   | Wave load | Draft | Cargo Load | Boundary Conditions |
    | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
    | Load Case |   | Loading condition | Acceleration | Still water | Wave | Wave load | Draft | Cargo Load | Boundary Conditions |
    | 1 | Vertical dynamic load case | Full Loaded | Vertical Download | M_sw | M_vw | Wave crest | T_sc^2) | ①+② | refer to<br>**Fig 42** |
    | 2 | Vertical dynamic load case | Full Loaded | Vertical Download | M_sw | M_vw | Wave trough | T_sc^2) | ①+② | refer to<br>**Fig 42** |
    | 3 | Vertical dynamic load case | Alternate hold<br>(odd number tanks full) | Vertical Download | M_sw | M_vw | Wave crest | T_act^3) | ①+② | refer to<br>**Fig 42** |
    | 4 | Vertical dynamic load case | Alternate hold<br>(even number tanks full) | Vertical Download | M_sw | M_vw | Wave crest | T_act^3) | ①+② | refer to<br>**Fig 42** |
    | 5 | Transverse dynamic load cases | Single No. 1<br>cargo tank loaded<br>(Transverse dynamic maximum acceleration) | Transverse<br>Port | - | - | Wave trough | T_act^3) | ①+③ | refer to<br>**Fig 44** |
    | 6 | Transverse dynamic load cases | Single No. 2<br>cargo tank loaded<br>(Transverse dynamic maximum acceleration) | Transverse<br>Port | - | - | Wave trough | T_act^3) | ①+③ | refer to<br>**Fig 44** |
    | 7 | Static heel load cases<br>(30° heel) | Only No. 1<br>cargo tank full | - | - | - | - | T_act^3) | ① | refer to<br>**Fig 44** |
    | 8 | Static heel load cases<br>(30° heel) | Only No. 2<br>cargo tank full | - | - | - | - | T_act^3) | ① | refer to<br>**Fig 44** |
    | 9 | Impact load cases<br>(Forward/aftward collision) | Full Loaded | Forward<br>0.5g | - | - | - | T_sc^2) | ①+④ | refer to<br>**Fig 43** |
    | 10 | Impact load cases<br>(Forward/aftward collision) | Full Loaded | Aftward 0.25g | - | - | - | T_sc^2) | ①+④ | refer to<br>**Fig 43** |
    | Remark)<br>^1) Bending moment in the same direction is to be applied dependent on hull girder performance (hogging/sagging) when applying the local load.<br>^2) T_sc : Scantling draught(m)<br>^3) T_act : The deepest draft in midship for alternate hold under consideration(m) |   |   |   |   |   |   |   |   |   |

    ![Fig 46 Loading condition(refer to Table 40) (2018)}](images/image289.png)
    **Fig 46 Loading condition(refer to Table 40)** ***(2018)***
    ![](images/image290.png)
    **Fig 46 Loading condition(refer to Table 40) (Continued)**
    ![Fig 46 Loading condition(refer to Table 40) (Continued)](images/image291.png)
    **Fig 46 Loading condition(refer to Table 40) (Continued)**
    - **(a)** The external loads are to be considered the following load components.
    - **(i)** Hydrostatic pressure
      - **(ii)** Hydrostatic pressure under transverse heeled condition
      - **(iii)** Wave induced load
      - **(iv)** Hull girder bending moment
    - **(b)** Hydrostatic pressure distribution for transverse heeled condition
    - **(i)** Transverse 30° heel at port is applied and the sign of loading is assumed to be positive for port heel.
      - **(ii)** Hydrostatic pressure under transverse heel condition at a point of shell plating under consideration is to be accordance with following equation(Refer to **Fig 45**).
    - **(c)** Wave induced load is to determined in accordance with **Par 1** (9).
    - **(d)** Hull girder bending moment
    - **(i)** Wave bending moment, $M _{w}$ and Still water bending moment, $M _{s}$ is to be applied in accordance with **Table 40**.
      - **(ii)** Hull girder bending moment induced in the model area by local load is to be adjusted in order to reach target value of design bending moment.
      - **(iii)** In order to induce the required vertical bending moment in the point considered along tank length, distributed load in length direction is to be applied to each frame position. Precaution must be taken on the sign of hogging and sagging.
      - **(iv)** This loading is to be applicable in order to get the required vertical bending moment stress. Afterward, this loading is to be applied as dynamic loading in **Table 40** for the analysis of stress and buckling.
- **(5)** Allowable stress
  - **(A)** The allowable stress of Load cases from LC1 to LC8 in **Table 40** is to be as given in **Table 41.**
  - **(B)** The allowable stress of Load cases from LC9 to LC10 in **Table 40** is to be in accordance with the discretion of the Society.
  - **(C)** Notwithstanding (A) and (B), the allowable stress for inner side plates(inner bottom, hopper tank and top side tank, slope plate, inner longitudinal bulkhead, inner deck) depending on the type of cargo tank is to be in compliance with the criteria presented by tank developer for each tank type.
  - **(D)** Members which have particularly large shear stress are to be specially considered in addition to (A) and (B).

    | Structural members | Load case | Allowable stress |
    | --- | --- | --- |
    | Structural members | Load case | The equivalent stress, $\sigma _{e}$ |
    | All structural members considered | LC 1 ~ LC 8 | $0.9 \beta \sigma _{Y}$ |
    | (Remark)<br>1. The equivalent stress is to be as follows.<br>$\sigma _{e} = \sqrt {\sigma _{x} ^{2} - \sigma _{x} \sigma _{y} + \sigma _{y} ^{2} +3 \tau ^{2}}$<br>$\sigma _{x}$ : Normal stress in x-direction of element coordinate system<br>$\sigma _{y}$ : Normal stress in y-direction of element coordinate system<br>$\tau$ : Sheer stress on the face in x-y plane of element coordinate system<br>2. $\sigma _{Y}$ : Yield stress of material($\mathrm{N}/mm^2$)<br>3. Position for stress reading is to be the center of element.<br>4. $\beta$ : mesh density factor taken as;<br>1.0 for longitudinal spacing mesh size<br>1.15 for less than or equal to 200 x 200 mm mesh size<br>1.25 for less than or equal to 100 x 100 mm mesh size<br>1.5 for less than or equal to 50 x 50 mm mesh size<br>1.7 for less than or equal to 2t x 2t mesh size |   |   |
- **(6)** Buckling strength calculation
  - **(A)** Buckling strength is to be calculated according to **Ⅳ. Buckling strength calculation**. Buckling criteria for all load cases in **Table 40** is to be in accordance with **Table 42**. *(2020)*
  - **(B)** Combining effect of biaxial compressive stress, shear stress and in-plane bending stress is to be considered in calculation of buckling strength.
  - **(C)** In general, mean stress in panel is to be used in calculation of buckling strength.

    | Structural members | Buckling factor, $\lambda$ |
    | --- | --- |
    | All structural members considered | 1.0 |

#### 8. LPG Carriers with Independent Tank Type A

- **(1)** General
  - **(A)** This guidance apply to the LPG carriers with independent tank type A.
  - **(B)** In case where scantlings of structural members of cargo hold in LPG carriers are verified by direct strength calculation, necessary documents and data for its calculation are to be submitted to the Society for approval beforehand.
  - **(C)** Except for those specifically provided for in this part, 1. is to be applied.
- **(2)** Structural modelling
  - **(A)** Model extent
    ![Fig 47 Model extent of cargo hold region for strength assessment](images/image292.png)
    **Fig 47 Model extent of cargo hold region for strength assessment**
    - **(a)** The model extent varies depending on the cargo hold numbers and arrangement. Main focus is on midship cargo area. The longitudinal model extent is to cover the 3 hold cargo length of midship area and 2 hold cargo length with E/R or Fore structure. The full breadth of the ship shall be used transversely. And, the full depth of the ship is to be modelled including primary supporting members above the upper deck, trunk and/or hatch coaming, if any.
    - **(b)** Basically, one cargo hold amidship and foremost hold shall be structurally assessed. The midship cargo hold model shall be such that the cargo hold amidship is located at the middle of the FE model. The Foremost or aftmost cargo hold shall be located at the middle of the corresponding FE model.
    - **(c)** If the finite element model of aftward of engine room bulkhead and forward of fore peak bulkhead is available and if ship has 3 cargo hold, the full cargo hold model can be used instead of using midship cargo hold and foremost cargo hold model. In that case, the all cargo hold region is to be evaluated.
    - **(d)** Aftmost cargo hold model shall be established to check the strength if the hull girder loads exceed the midship values or structural arrangement is significantly different from the midship area or the scantlings of aftmost cargo hold are not gradually tapered.
    - **(e)** In the foremost cargo hold model and the aftmost cargo hold model, the hull form aft of the middle of the machinery space or forward of the transverse section at the middle of the fore part may be modelled with a simplified geometry, which means that hull form can be extruded out to its aft bulkhead and FP.
  - **(B)** Structural modeling
    ![Fig 48 Transverse section](images/image293.png)
    **Fig 48 Transverse section**
    - **(a)** The used linear FE element is 4 node or 3 node shell elements and 2 node beam elements. 2D shell elements are used to represent the plate of the hull structure, and all stiffeners are modeled with beam elements having axial, torsional and bending stiffness.
    - **(b)** Face plate of primary supporting members are modeled using rod elements.
    - **(c)** The use of 3 node shell element is limited only for the mesh transition area as far as practicable. The aspect ratio of the shell elements is in general not to exceed 3 and the aspect ratio in areas where high stresses are expected is to be kept to 1 where possible.
  - **(C)** Properties and Corrosion Allowance
    - **(a)** The properties of FE models for cargo hold region including local structural strength are to be based on the gross scantling approach for yielding and net thickness approach for buckling. In net thickness application, only plate members are considered.
    - **(b)** For the independent tank structure made of stainless steel, there is no need to apply the thickness deduction in general.
  - **(D)** Supporting Structure Idealization
    - Vertical support for Z downward direction,
    - Anti-rolling supports for Y direction,
    - Anti-pitching and/or anti-collision support for X direction and
    - Antiflotation chocks for Z upward direction.
    **Fig** 49 shows the typical support arrangement of web section.
    ![Fig 49 Typical web section of FE model using spring elements](images/image294.png)
    **Fig 49 Typical web section of FE model using spring elements**

    | Type | Intact condition | Accidental condition |
    | --- | --- | --- |
    | Vertical support | 0.5 | N.A |
    | Other supports | 0.2 | N.A |

    ![Fig 51 Example of Cargo Hold Model (Midship)](images/image296.png)
    **Fig 51 Example of Cargo Hold Model (Midship)**
    ![Fig 52 Example of All Cargo Hold Model](images/image297.png)
    **Fig 52 Example of All Cargo Hold Model**
    ![Fig 54 Example of Independent Tank(All Cargo Hold except outer hull)](images/image300.png)
    **Fig 54 Example of Independent Tank****(All Cargo Hold except outer hull)**
    - **(a)** To minimized the movement of the independent tank in cargo hold of hull, 4 types of supports are installed generally;
    - **(b)** It is very important to get the force distribution on each support by independent tank. Therefore, all tank supports are to be idealized by shell elements according to the arrangement of tank supports. The spacer between upper and lower seat of the hull and tank supports should be considered using solid elements, gap elements or 1D element such as spring or rod element.
    - **(c)** If solid elements are used, contact elements should be defined for interface surface. In case of gap elements implementation, the upper and lower surface of tank support seat is to be rigidly linked respectively with 6 DOF constraints. If the gap elements or contact elements are used, analysis results should be obtained using a nonlinear analysis. **Fig 50** shows the typical implementation of gap elements with 6 DOF constraints.
    - **(d)** For the usage of linear 1D element, the spring or axial stiffness is to be calculated based on the actual elastic modulus of the spacer materials. And, an iterative procedure is required to eliminate any spring or rod element sustaining a tensile stress. Spring or rod element may require two or three elements to correctly represent the behaviour of the support.
    - **(e)** The coefficient of friction between the spacer between upper and lower seat of the tank supports is used according to Table 43 unless specifically defined in design stage by designer. In case of accidental loading condition i.e. collision and flooded, friction is not considered with a conservative viewpoint.
- **(3)** Boundary Conditions
  - **(A)** The principle is to minimize the boundary effect not to affect the result evaluation of concerning area.
  - **(B)** For the full cargo hold model and midship cargo hold model, the rigid link elements connecting the longitudinal members at the model ends with an independent node at neutral axis in centerline are used. The detail boundary conditions are given in Table 44, which is referred in **Table** 46 and 47 as ‘simple’. In case of asymmetric load cases, the Y direction is constrained at the deck and bottom of transverse bulkhead.

    | Location |   | Translation |   |   | Rotation |   |   |
    | --- | --- | --- | --- | --- | --- | --- | --- |
    | Location |   | $\delta_X$ | $\delta_Y$ | $\delta_Z$ | $\theta_X$ | $\theta_Y$ | $\theta_Z$ |
    | Aft End | Independent point | 0 | 1 | 1 | 0 | 0 | 0 |
    | Aft End | Cross section | 0 | Rigid link | Rigid link | Rigid link | 0 | 0 |
    | Aft End | Intersection of CL and inner bottom | 1 | 0 | 0 | 0 | 0 | 0 |
    | Fore End | Independent point | 0 | 1 | 1 | 1 | 0 | 0 |
    | Fore End | Cross section | 0 | Rigid link | Rigid link | Rigid link | 0 | 0 |
    | Deck and Bottom of<br>Transverse Bulkhead |   |   | 1 |   |   |   |   |
    | Note 1 : fixed 0 : free |   |   |   |   |   |   |   |
  - **(C)** For the foremost cargo hold model, aft end section of the model is fixed in all degrees of freedom. And, all fixation condition is applied to the fore end section of the aftmost cargo hold model. The other end of FE model is set free. **Table 45** shows the boundary condition for foremost cargo hold and aftmost cargo hold model.

    | Location |   | Translation |   |   | Rotation |   |   |
    | --- | --- | --- | --- | --- | --- | --- | --- |
    | Location |   | $\delta_X$ | $\delta_Y$ | $\delta_Z$ | $\theta_X$ | $\theta_Y$ | $\theta_Z$ |
    | Foremost cargo<br>hold model | Aft End | 1 | 1 | 1 | 1 | 1 | 1 |
    | Foremost cargo<br>hold model | Fore End | 0 | 0 | 0 | 0 | 0 | 0 |
    | Aftmost cargo<br>hold model | Aft End | 0 | 0 | 0 | 0 | 0 | 0 |
    | Aftmost cargo<br>hold model | Fore End | 1 | 1 | 1 | 1 | 1 | 1 |
    | Deck and Bottom of<br>Transverse Bulkhead |   |   | 1 |   |   |   |   |
    | Note 1 : fixed 0 : free |   |   |   |   |   |   |   |

    ![Fig 55 Example of Boundary conditions(Y-direction fixed, all cargo hold model)](images/image301.png)
    **Fig 55 Example of Boundary conditions****(Y-direction fixed, all cargo hold model)**
- **(4)** Local Structural Strength
  - **(A)** Local structural analysis can be carried out using separate local fine mesh model conjugated with the corresponding boundary condition or fine mesh model incorporated cargo hold model. The extent of separate fine mesh model is determined in order that the boundary conditions from the hold analysis do not affect the structural response of the considered location of local fine mesh model.
  - **(B)** The fundamental of mesh size is to be determined enough to represent the structural detail geometry. More fine mesh size is considered especially for the area where general mesh is too coarse to represent the geometry and high stressed area. The mesh density is to be kept at least 10 elements length in all direction. The transition from smaller mesh size to bigger mesh size is kept to be smoothly distributed.
  - **(C)** Typical connection or discontinuous areas between primary supporting members and/or secondary structural elements are to be investigated in detail by fine mesh model, in which typically the mesh size of 200mm x 200mm or 100 mm x 100 mm. If necessary, however, mesh size of 2t x 2t (where t is the plate thickness) or 50 mm x 50 mm may be introduced case by case in geometric transition areas so as to have a better representation of structure geometry. And all cut-out (lighting hole, access openings) are to be modelled by removing the appropriate number of elements to represent the dimension regardless of the size.
- **(5)** Fine Mesh Area
  - **(A)** The required areas for fine mesh analysis are as follows;
    - Large openings (tank dome, duct keel, etc.)
    - Typical connections of double bottom longitudinal stiffeners to transverse bulkheads
    - Typical vertical support at maximum reaction introduced
    - Typical Anti-rolling support at maximum reaction introduced
    - Typical Anti-pitching support at maximum reaction introduced
    - Typical Anti-flotation support at maximum reaction introduced
    - Other support not having typical support configuration
  - **(B)** High stress concentrated areas where the stress concentration is more than 95% of the evaluation criteria need to be verified by fine mesh analysis.
    ![Fig 56 Example of Fine Mesh (Hatch Corner)#imgID-298Fig 57 Example of Fine Mesh (Supporting member)](images/image302.png)
    **Fig 56 Example of Fine Mesh (Hatch Corner)**#imgID-298**Fig 57 Example of Fine Mesh (Supporting member)**
- **(6)** Loads
  - **(A)** Local loads required in IGC Code are to be fully compliant with applicable IGC Code.
  - **(B)** The design load cases are selected to give the maximum support reaction of each support type and configuration among defined in (E). The reaction forces are derived from cargo hold analysis and applied to the corresponding surface of fine mesh model using multi-point constraints. And, the relevant local loads should be applied simultaneously.
  - **(C)** The obtained reaction forces shall be used for the strength check for the wood spacer and the dam plate. The stress of wood spacer, vertical reaction force divided by wood spacer sectional area perpendicular to the force direction, should not exceed the 1/3 allowable wood compressive stress. And, the dam plate shear area shall be satisfied with the required shear area given by friction force with 10% margin divided by dam plate allowable shear stress.
  - **(D)** Internal pressure is to be calculated for each load cases in accordance with Pt 7, Ch 5, 403.2 of the Rule for internal independent tank pressure, with 1(7) for ballast tank pressure. External pressure is to be calculated for each load cases in accordance with 1(9).
  - **(E)** Hull Girder Loads
    The target vertical bending is the combined envelope of $M_S$ and $M_VW$ or $M_S$ itself depending on the load cases. Design $M_S$ and wave induced $M_VW$ are should be compliant with **Pt 3, Ch 3, Table 3.3.1** of the Rules.
    The target vertical shear force is the $Q_S$ or envelope of $Q_S$ and $Q_VW$ depending on the combined loads. Design $Q_S$ and wave induced $Q_VW$ are should be compliant with the requirements described in **Pt 3, Ch 3, 301** of the Rules.
    The vertical forces at the transverse web frame position to generate vertical shear forces $\Delta Q_a$, $\Delta Q_f$ at the transverse target positions are to be applied. The adjusted forces are distributed vertically to the nodes of the corresponding cross section according to the direct shear flow calculation method in **Pt13, Ch5, App 1** of the Rules.
    The required adjustments in hull girder shear force for midship cargo hold model should be made in accordance with relevant method described in **Pt13, Ch 7, Sec 2** of the Rules.
    In case of full cargo hold length model, the hull girder shear force adjustments should be done according to following equations as shown in **Fig 58**.
    $R_FR$ : Resultant force by local loads at FP
    $\Delta Q_f$ : Adjustment shear force at foward target bulkhead
    $\Delta Q_a$ : Adjustment shear force at aft target bulkhead
    $F_1 = \Sigma \delta f_1$, $F_2 = \Sigma \delta f_2$, $F_3 = \Sigma \delta f_3$
    $F_1 = \frac{-2(l_1 + l_2 + l_3 ) \Delta Q_a + (l_2 + 2l_3 )F_2 + l_1 F_3}{l_1}$
    $F _{2} = \Delta Q _{f} - \Delta Q _{a}$
    $F _{3} = \Delta Q _{f} + R _{FP}$
    In case of foremost or aftmost cargo hold model, the hull girder shear force adjustments should be done according to following equations as shown in **Fig 59** and **Fig 60**.
    $R_Fix$ : Resultant force by local loads and adjusting forces ($F_1$ & $F_2$) at fixed boundary position
    $F_Design$ : Design shear force at fixed boundary position
    $\Delta Q_f$ : Adjustment shear force at foward target bulkhead
    $\Delta Q_a$ : Adjustment shear force at aft target bulkhead
    $F_1 = \Sigma \delta f_1$, $F_2 = \Sigma \delta f_2$, $F_3 = \Sigma \delta f_3$
    $F_1 = \Delta Q_f$ for foremost cargo hold model, $F_1 = \Delta Q_a$ for aftmost cargo hold model
    $F_2 = \Delta Q_f - \Delta Q_a$ for foremost cargo hold model,
    $F_2 = \Delta Q_a - \Delta Q_f$ for aftmost cargo hold model
    Only when $R_Fix$ exceeds $F_Design$, $F_3 = \Delta Q_fix = R_Fix - F_Design$
    ![Fig 58 Target shear force adjustment by applying vertical forces for fullcargo hold](images/image304.png)
    **Fig 58 Target shear force adjustment by applying vertical forces for full****cargo hold**
    ![Fig 59 Target shear force adjustment by applying vertical forces forforemost cargo hold model](images/image305.png)
    **Fig 59 Target shear force adjustment by applying vertical forces for****foremost cargo hold model**
    ![Fig 60 Target shear force adjustment by applying vertical forcesfor aftmost cargo hold model](images/image306.png)
    **Fig 60 Target shear force adjustment by applying vertical forces****for aftmost cargo hold model**
    The vertical hull girder bending moment adjustments are to be applied to the considered cross section of the cargo hold FE model by distributing the longitudinal axial nodal forces to all hull girder bending effective members according to **Pt 13, Ch 7, Sec2 4.4.10** of the Rules.
    The required adjustments in hull girder bending moment shear force for midship cargo hold model should be made in accordance with relevant method described in **Pt 13, Ch 7, Sec 2 4.4.8** of the Rules.
    To obtain the vertical hull girder target values at each web frame and transverse bulkhead position, the vertical bending moment adjustments $M_vi$ ($m_vi$) are to be calculated and applied at web frames and transverse bulkhead position as described in **Pt 13, Ch 7, Sec 2 4.4.9** of the Rules.
    - **(a)** The local hull girder distribution by applied local loads including structural steel weight is to be obtained according to the **Pt 13, Ch 7, Sec 2 4.4.2** of the Rules. The final adjusted hull girder shear force and hull girder bending moment should not exceed the hull girder target values.
    - **(b)** Target Hull Girder Vertical Bending Moment
    - **(c)** Target Hull Girder Vertical Shear Force
    - **(d)** Hull Girder Shear Force Adjusting
    - **(i)** Midship Cargo Hold Model
      - **(ii)** Full Cargo Hold Model
      - **(iii)** Foremost or Aftmost Cargo Hold Model
    - **(e)** Hull Girder Bending Moment Adjusting
    - **(i)** Midship Cargo Hold Model
      - **(ii)** Full Cargo Hold Model, Foremost and Aftmost Cargo Hold Model
  - **(F)** Design Load Case

    | LC No | Loading condition | External pressure | Independent Tank Load | Ballast Tank | Hull Girder | Loading Patterns | SF Adjusting | BC |
    | --- | --- | --- | --- | --- | --- | --- | --- | --- |
    | LC1 | Full Load Homo | $T_s$- Trough | Static | - | $M _{S-S}$ + $M _{W-S}$ | ![](images/image307.png) |   | simple |
    | LC2 | Full Load Homo | $T_s$- Crest | Static | - | $M _{S-H}$ + $M _{W-H}$ | ![](images/image308.png) |   | simple |
    | LC3 | Alt Load | $T_LC$- Crest | Static | Rule Load in Annex III-2 | $M _{S-H}$ + $M _{W-H}$ | ![](images/image309.png) | Applied | simple |
    | LC4 | Alt Load | $T_LC$- Trough | Static | Rule Load in Annex III-2 | $M _{S-S}$ + $M_W-S$ | ![](images/image310.png) | Applied | simple |
    | LC5 | Ballast | $T_bal$- Static | - | Rule Load in Annex III-2 | $M_S-H$ + $M _{W-H}$ | ![](images/image311.png) |   | simple |
    | LC6 | Full Load Homo | $T_s$- Static | Static+ Dynamic with $a_z$ | - | $M _{S-S}$ + $M_WS$ | ![](images/image312.png) |   | simple |
    | LC7 | Full Load Homo | $T_s$- Static | Static+ Dynamic with $a_y$ | - | $M_S-H$ | ![](images/image313.png) |   | simple+y constraint at deck & bottom of TBHD |
    | LC8 | Alt Load | $T_s$- Static | Static+ Dynamic with $a_y$ | Rule Load in Annex III-2 | $M _{S-H}$ | ![](images/image314.png) | Applied | simple+y constraint at deck & bottom of TBHD |
    | LC9 | Harbour | $T_\min$- Static | Static | Rule Load in Annex III-2 | $M_S-H$ | ![](images/image315.png) |   | simple |
    | LC10 | Harbour | $T_\min$- Static | Static | Rule Load in Annex III-2 | $M_S-H$ | ![](images/image316.png) |   | simple |
    | LC11 | Full Load with Heeled(30°) | $T_s$- Static | Static | - | $M_S-H$ | ![](images/image317.png) |   | simple+y constraint at deck & bottom of TBHD |
    | LC12 | Full Load with Collision forward BHD(0.5g) | $T_s$- Static | Static+ Dynamic with $a_x$(0.5g) | - | $M_S-H$ | ![](images/image318.png) |   | simple |
    | LC13 | Full Load with Collision aftward BHD(0.25g) | $T_s$- Static | Static+ Dynamic with $a_x$(0.25g) | - | $M_S-H$ | ![](images/image319.png) |   | simple |
    | LC14 | Flooded | $T_s$- Static | Static loads opn 2nd barriers below $T_s$ |   | $M_S-H$ | ![](images/image320.png) | Applied | simple |

    | LC No | Loading condition | External pressure | Independent Tank Load | Ballast Tank | Hull Girder | Loading Patterns | SF Adjusting | BC |
    | --- | --- | --- | --- | --- | --- | --- | --- | --- |
    | LC1 | Full Load Homo | $T_s$- Trough | Static | - | $M _{S-S}$ + $M _{W-S}$ | ![](images/image321.png) | Applied | simple |
    | LC2 | Full Load Homo | $T_s$- Crest | Static | - | $M _{S-H}$ + $M _{W-H}$ | ![](images/image322.png) | Applied | simple |
    | LC3 | Alt Load | $T_LC$- Crest | Static | Rule Load in Annex III-2 | $M _{S-H}$ + $M_W-H$ | ![](images/image323.png) | Applied | simple |
    | LC4 | Alt Load | $T_LC$- Trough | Static | Rule Load in Annex III-2 | $M _{S-S}$ + $M_W-S$ | ![](images/image324.png) | Applied | simple |
    | LC5 | Ballast | $T_bal$- Static | - | Rule Load in Annex III-2 | $M_S-H$ + $M _{W-H}$ | ![](images/image325.png) | Applied | simple |
    | LC6 | Full Load Homo | $T_s$- Static | Static+ Dynamic with $a_z$ | - | $M _{S-S}$ | ![](images/image326.png) | Applied | simple |
    | LC7 | Full Load Homo | $T_s$- Static | Static+ Dynamic with $a_y$ | - | $M_S-H$ | ![](images/image327.png) | Applied | simple+y constraint at deck & bottom of TBHD |
    | LC8 | Alt Load | $T_s$- Static | Static+ Dynamic with $a_y$ | Rule Load in Annex III-2 | $M _{S-S}$ | ![](images/image328.png) | Applied | simple+y constraint at deck & bottom of TBHD |
    | LC9 | Harbour | $T_\min$- Static | Static | Rule Load in Annex III-2 | $M_S-H$ | ![](images/image329.png) |   | simple |
    | LC10 | Harbour | $T_\min$- Static | Static | Rule Load in Annex III-2 | $M_S-H$ | ![](images/image330.png) |   | simple |
    | LC11 | Full Load with Heeled(30°) | $T_\min$- Static | Static | - | $M_S-H$ | ![](images/image331.png) | Applied | simple+y constraint at deck & bottom of TBHD |
    | LC12 | Full Load with Collision forward BHD(0.5g) | $T_s$- Static | Static+ Dynamic with $a_x$ (0.5g) | - | $M_S-H$ | ![](images/image332.png) | Applied | simple |
    | LC13 | Full Load with Collision aftward BHD(0.25g) | $T_s$- Static | Static+ Dynamic with $a_x$ (0.25g) | - | $M_S-H$ | ![](images/image333.png) | Applied | simple |
    | LC14 | Flooded | $T_s$- Static | Static loads on 2nd barrier below $T_s$ |   | $M_S-H$ | ![](images/image334.png) | Applied | simple |

    | LC No | Loading condition | External pressure | Independent Tank Load | Ballast Tank | Hull Girder | Loading Patterns | SF Adjusting | BC |
    | --- | --- | --- | --- | --- | --- | --- | --- | --- |
    | LC1 | Full Load Homo | $T_s$- Trough | Static | - | $M_S$ + $M _{W-H}$ | ![](images/image335.png) | Applied | Aft fixed |
    | LC2 | Full Load Homo | $T_s$- Crest | Static | - | $M_S$ + $M_W-S$ | ![](images/image336.png) | Applied | Aft fixed |
    | LC3 | Alt Load | $T_LC$- Crest | Static | Rule Load in Annex III-2 | $M_S$ + $M_W-S$ | ![](images/image337.png) | Applied | Aft fixed |
    | LC4 | Alt Load | $T_LC$- Trough | Static | Rule Load in Annex III-2 | $M_S$ + $M _{W-H}$ | ![](images/image338.png) | Applied | Aft fixed |
    | LC5 | Ballast | $T_bal$- Static | - | Rule Load in Annex III-2 | $M_S-H$ + $M _{W-H}$ | ![](images/image339.png) | Applied | Aft fixed |
    | LC6 | Full Load Homo | $T_s$- Static | Static+ Dynamic with $a_z$ | - | $M _{S-S}$ | ![](images/image340.png) | Applied | Aft fixed |
    | LC7 | Full Load Homo | $T_s$- Static | Static+ Dynamic with $a_y$ | - | $M_S-H$ | ![](images/image341.png) | Applied | Aft fixed+y constraint at deck & bottom of BHD |
    | LC8 | Harbour | $T_\min$- Static | Static+ Dynamic with $a_y$ | Rule Load in Annex III-2 | $M_S-H$ | ![](images/image342.png) |   | Aft fixed |
    | LC9 | Harbour | $T_\min$- Static | Static | Rule Load in Annex III-2 | $M_S-H$ | ![](images/image343.png) |   | Aft fixed |
    | LC10 | Full Load with Heeled(30°) | $T_s$- Static | Static | - | $M_S-H$ | ![](images/image344.png) | Applied |   |
    | LC11 | Full Load with Collision forward BHD(0.5g) | $T_s$- Static | Static+ Dynamic with $a_x$ (0.5g) | - | $M_S-H$ | ![](images/image345.png) | Applied | Aft fixed |
    | LC12 | Full Load with Collision aftward BHD(0.25g) | $T_s$- Static | Static+ Dynamic with $a_x$ (0.25g) | - | $M_S-H$ | ![](images/image346.png) | Applied | Aft fixed |
    | LC13 | flooded | $T_s$- Static | Static loads on 2nd barrier below $T_s$ | - | $M_S-H$ | ![](images/image347.png) | Applied | Aft fixed |

    | LC No | Loading condition | External pressure | Independent Tank Load | Ballast Tank | Hull Girder | Loading Patterns | SF Adjusting | BC |
    | --- | --- | --- | --- | --- | --- | --- | --- | --- |
    | LC1 | Full Load Homo | $T_s$- Trough | Static | - | $M_S$ + $M _{W-H}$ | ![](images/image348.png) | Applied | Fwd fixed |
    | LC2 | Full Load Homo | $T_s$- Crest | Static | - | $M_S$ + $M_W-S$ | ![](images/image349.png) | Applied | Fwd fixed |
    | LC3 | Alt Load | $T_LC$- Crest | Static | Rule Load in Annex III-2 | $M_S$ + $M_W-S$ | ![](images/image350.png) | Applied | Fwd fixed |
    | LC4 | Alt Load | $T_LC$- Trough | Static | Rule Load in Annex III-2 | $M_S$ + $M _{W-H}$ | ![](images/image351.png) | Applied | Fwd fixed |
    | LC5 | Ballast | $T_bal$- Static | - | Rule Load in Annex III-2 | $M_S-H$ + $M _{W-H}$ | ![](images/image352.png) | Applied | Fwd fixed |
    | LC6 | Full Load Homo | $T_s$- Static | Static+ Dynamic with $a_z$ | - | $M _{S-S}$ | ![](images/image353.png) | Applied | Fwd fixed |
    | LC7 | Full Load Homo | $T_s$- Static | Static+ Dynamic with $a_y$ | - | $M_S-H$ | ![](images/image354.png) | Applied | Aft fixed+y constraint at deck & bottom of BHD |
    | LC8 | Harbour | $T_\min$- Static | Static | Rule Load in Annex III-2 | $M_S-H$ | ![](images/image355.png) |   | Fwd fixed |
    | LC9 | Harbour | $T_\min$- Static | Static | Rule Load in Annex III-2 | $M_S-H$ | ![](images/image356.png) |   | Fwd fixed |
    | LC10 | Full Load with Heeled(30°) |   | Static |   | $M_S-H$ | ![](images/image357.png) | Applied | Aft fixed+y constraint at deck & bottom of BHD |
    | LC11 | Full Load with Collision forward BHD(0.5g) | $T_s$- Static | Static+ Dynamic with $a_x$ (0.5g) | - | $M_S-H$ | ![](images/image358.png) | Applied | Fwd fixed |
    | LC12 | Full Load with Collision aftward BHD(0.25g) | $T_s$- Static | Static+ Dynamic with $a_x$ (0.25g) | - | $M_S-H$ | ![](images/image359.png) | Applied | Fwd fixed |
    | LC13 | Flooded | $T_s$- Static | Static loads on 2nd barrier below $T_s$ | - | $M_S-H$ | ![](images/image360.png) | Applied | Fwd fixed |
    - **(a)** In seagoing phase, full load condition with scantling draft, alternate load condition and ballast condition with minimum draft are to be check for structural strength.
    - **(b)** For the harbour phase, any alternate loading condition is to be assessed. In that case, the static sea pressure and internal pressure are used considering overflow height. However, if any alternate loading condition is not specified in Loading Manual, the assessment for alternate loading condition may be omitted.
- **(7)** Allowable Stress
  - **(A)** The stresses resulting from the application of the specified load cases are not to exceed the allowable stress obtained from following formula.
    $\sigma_act < \sigma_allow$
    $\sigma_act = \sqrt{\sigma_x ^2 - \sigma_x \sigma_y + \sigma_y ^2+ 3\tau_x^2}$
    $\sigma_allow = \eta \beta \sigma_yield$
    $\sigma_yield = 235 / k$
    $\eta$ : general yield utilization factor taken as;

#### 0.9 for intact load cases

#### 1.0 for accidental load cases (collision, flooded, damaged)

#### 0.8 for habour load case (Table 46∼49)

$\beta$ : mesh density factor taken as;

#### 1.0 for longitudinal spacing mesh size

#### 1.15 for less than or equal to 200 x 200 mm mesh size

#### 1.25 for less than or equal to 100 x 100 mm mesh size

#### 1.5 for less than or equal to 50 x 50 mm mesh size

#### 1.7 for less than or equal to 2t x 2t mesh size

$k$ : material factor
$\sigma_x$, $\sigma_y$ : Normal stress at element centroid ($\mathrm{N}/mm^2$)
$\tau_xy$ : Shear stress at element centroid ($\mathrm{N}/mm^2$)

- **(8)** Buckling Strength *(2020)*
  Buckling strength is to be calculated according to **Ⅳ. Buckling strength calculation**. Buckling strength is to satisfy the criteria defined in **1** (5) of **Ⅳ. Buckling strength calculation** based on static+dynamic load combination except below load cases.
  Load cases based on static load combination in 1 (5) of **Ⅳ. Buckling strength calculation**:
  - Table 46 and 47: LC9 and LC10
  - Table 48: LC8 and LC9
  - Table 49: LC8 and LC9
  However, for the cargo hold structural members under intact load cases, following enforced buckling criterion is to be applied.
  $\eta _{act} \leq 0.9 \eta _{all}$
  where:
  $\eta_{act}$, $\eta_{all}$ : refer to **1** (5) of **Ⅳ. Buckling strength calculation.**


### IV. Buckling strength calculation (2020)

#### 1. General

- **(1)** Assumption
  This Guidance includes buckling strength calculation and criteria for direct strength analysis results of all structural members. Unless otherwise specified, the scantling requirements of structural members are based on net scantling obtained by removing $t _{c}$ from the gross offered thickness, where $t _{c}$ is defined in **3** (2), compressive and shear stresses are to be taken as positive, tension stresses are to be taken as negative.
- **(2)** Application
  The buckling checks are to be performed according to:
  • **2**. for the buckling requirements of the FE analysis for the plates, stiffened panels and other structures.
  • **3**. for the buckling capacity of prescriptive and FE buckling requirements.
- **(3)** Definitions
  ‘Buckling’ is used as a generic term to describe the strength of structures, generally under in-plane compressions and/or shear and lateral load. The buckling strength or capacity can take into account the internal redistribution of loads depending on the load situation, slenderness and type of structure. Buckling capacity based on this principle gives a lower bound estimate of ultimate capacity, or the maximum load the panel can carry without suffering major permanent set. Buckling capacity assessment utilises the positive elastic post-buckling effect for plates and accounts for load redistribution between the structural components, such as between plating and stiffeners. For slender structures, the capacity calculated using this method is typically higher than the ideal elastic buckling stress (minimum Eigen value). Accepting elastic buckling of structural components in slender stiffened panels implies that large elastic deflections and reduced in-plane stiffness will occur at higher buckling utilisation levels.
- **(4)** Assessment methods
  The buckling assessment is carried out according to one of the two methods taking into account different boundary condition types:
  • Method A: All the edges of the elementary plate panel are forced to remain straight (but free to move in the in-plane directions) due to the surrounding structure/neighbouring plates.
  • Method B: The edges of the elementary plate panel are not forced to remain straight due to low in-plane stiffness at the edges and/or no surrounding structure/neighbouring plates.
- **(5)** Allowable buckling utilization factor
  A structural member is considered to have an acceptable buckling strength if it satisfies the following criterion:
  $\eta _{act} \leq \eta _{all}$
  $\eta_{act}$ : Buckling utilisation factor based on the applied stress, defined in **3**.
  $\eta_{all}$ : Allowable buckling utilisation factor as defined in **Table 50**.

  | Structural component | Allowable buckling utilisation factor $\eta_{all}$ |
  | --- | --- |
  | Plates and stiffeners<br>Stiffened and unstiffened panels<br>Vertically stiffened side shell plating of single side skin bulk carrier<br>Web plate in ways of openings | 1.00 for load combination: S+D<br>0.80 for load combination: S |
  | Struts, pillars and cross ties | 0.75 for load combination: S+D<br>0.65 for load combination: S |
  | Corrugation of vertically corrugated bulkheads with lower stool and horizontally corrugated bulkhead, under lateral pressure from liquid loads, for shell elements only.<br>Supporting structure in way of lower end of corrugated bulkheads without lower stool. | 0.90 for load combination: S+D<br>0.72 for load combination: S |
  | Corrugation of vertically corrugated bulkheads without lower stool under lateral pressure from liquid loads, for shell elements only. | 0.81 for load combination: S+D<br>0.65 for load combination: S |
  | Note 1: Supporting structure for a transverse corrugated bulkhead refers to the structure in longitudinal direction within half a web frame space forward and aft of the bulkhead, and within a vertical extent equal to the corrugation depth.<br>Note 2: Supporting structure for a longitudinal corrugated bulkhead refers to the structure in transverse direction within three longitudinal stiffener spacings from each side of the bulkhead, and within a vertical extent equal to the corrugation depth. |   |

#### 2. Buckling requirements for direct strength analysis

- **(1)** General
  The requirements of this Section apply for the buckling assessment of direct strength analysis subjected to compressive stress, shear stress and lateral pressure. All structural elements in the FE analysis are to be assessed individually. The buckling checks have to be performed for the following structural elements:
  • Stiffened and unstiffened panels, inclusive curved panels.
  • Web plate in way of openings.
  • Corrugated bulkhead.
  • Vertically stiffened side shell of single side skin bulk carrier.
  • Struts, pillars and cross ties.
- **(2)** Panel modeling and assessment
  The plate panel of hull structure is to be modelled as stiffened panel, SP or unstiffened panel, UP. Method A and Method B as defined in **1** (4) are to be used according to **Table 51** to **54** and **Fig 61** to **65**. Where the plate thickness along a plate panel is not constant, the panel used for the buckling assessment is to be modelled according to **III. Guidance for the Hold Analysis** with a weighted average thickness taken as:
  $t _{avr} = \frac{\sum _{1} ^{n} A _{i} t _{i}}{\sum _{1} ^{n} A _{i}}$
  $A _{i}$ : Area of the i-th plate element
  $t _{i}$ : Net thickness of the i-th plate element.
  $n$ : Number of finite elements defining the buckling plate panel.
  The panel yield stress ReH_P is taken as the minimum value of the specified yield stresses of the elements within the plate panel.

  | Structural elements | Assessment method | Normal panel definition |
  | --- | --- | --- |
  | Longitudinally stiffened panels, shell envelope, deck, inner hull, hopper tank side and longitudinal bulkheads | SP-A | Length : between web frames<br>Width : between primary supporting members |
  | Double bottom longitudinal girders in line with longitudinal bulkhead or connected to hopper tank side | SP-A | Length : between web frames<br>Width : full web depth |
  | Web of double bottom longitudinal girders not in line with longitudinal bulkhead or not connected to hopper tank side | SP-B | Length : between web frames<br>Width : full web depth |
  | Web of horizontal girders in double side space connected to hopper tank side | SP-A | Length : between web frames<br>Width : full web depth |
  | Web of horizontal girders in double side space not connected to hopper tank side | SP-B | Length : between web frames<br>Width : full web depth |
  | Web of single skin longitudinal girders or stringers (regular meshed area) | SP-B | Plate between local stiffeners/face plate/PSM |
  | Web of single skin longitudinal girders or stringers (irregular meshed area) | UP-B | Plate between local stiffeners/face plate/PSM |

  | Structural elements | Assessment method | Normal panel definition |
  | --- | --- | --- |
  | Web of transverse deck frames including brackets (regular meshed area) | SP-B | Plate between local stiffeners/face plate/PSM |
  | Web of transverse deck frames including brackets (irregular meshed area) | UP-B | Plate between local stiffeners/face plate/PSM |
  | Vertical web in double side space | SP-B | Length: full web depth<br>Width: between primary supporting members |
  | Irregularly stiffened panels, e.g. web panels in way of hopper tank and bilge | UP-B | Plate between local stiffeners/face plate/PSM |
  | Double bottom floors | SP-A | Length: full web depth<br>Width: between primary supporting members |
  | Vertical web frame including brackets<br>(regular meshed area) | SP-B | Plate between vertical web stiffeners/face plate/PSM |
  | Vertical web frame including brackets<br>(irregular meshed area) | UP-B | Plate between vertical web stiffeners/face plate/PSM |
  | Cross tie web plate (regular meshed area) | SP-B | Plate between vertical web stiffeners/face plate/PSM |
  | Cross tie web plate (irregular meshed area) | UP-B | Plate between vertical web stiffeners/face plate/PSM |

  | Structural elements | Assessment method | Normal panel definition |
  | --- | --- | --- |
  | Regularly stiffened bulkhead panels inclusive the secondary buckling stiffeners perpendicular to the regular stiffener (such as carlings) | SP-A | Length : between primary supporting members<br>Width : between primary supporting members |
  | Irregularly stiffened bulkhead panels, e.g. web panels in way of hopper tank and bilge | UP-A | Plate between local stiffeners/face plate |
  | Web plate of bulkhead stringers including brackets<br>(regular meshed area) | SP-B | Plate between web stiffeners /face plate |
  | Web plate of bulkhead stringers including brackets<br>(irregular meshed area) | UP-B | Plate between web stiffeners /face plate |

  | Structural elements | Assessment method | Normal panel definition |
  | --- | --- | --- |
  | Upper/lower stool including stiffeners | SP-A | Length: between internal web diaphragms<br>Width: length of stool side |
  | Stool internal web diaphragm (regular meshed area) | SP-B | Plate between local stiffeners /face plate /<br>PSM |
  | Stool internal web diaphragm (irregular meshed area) | UP-B | Plate between local stiffeners /face plate /<br>PSM |
  | Cross deck | SP-A | Plate between local stiffeners/ PSM |

  ![Fig 61 Longitudinal plates in LPG carrier (Type A)](images/image361.png)
  **Fig 61 Longitudinal plates in LPG carrier (Type A)**
  ![Fig 62 Transverse web frame in LPG carrier (Type A)](images/image362.png)
  **Fig 62 Transverse web frame in LPG carrier (Type A)**
  ![Fig 63 Transverse bulkhead in LPG carrier (Type A)](images/image363.png)
  **Fig 63 Transverse bulkhead in LPG carrier (Type A)**

  | ![](images/image364.png) | ![](images/image365.png) |
  | --- | --- |
  | **Fig 64 Longitudinal plate in car ferry** | **Fig 65 Transverse web frame in car ferry** |
- **(3)** Stiffened panels
  To represent the overall buckling behaviour, each stiffener with attached plate is to be modelled as a stiffened panel. If the stiffener properties or stiffener spacing varies within the stiffened panel, the calculations are to be performed separately for all configurations of the panels, i.e. for each stiffener and plate between the stiffeners. Plate thickness, stiffener properties and stiffener spacing at the considered location are to be assumed for the whole panel.
- **(4)** Unstiffened panels
  - **(A)** Irregular plate panel
    In way of web frames, stringers and brackets, the geometry of the panel (i.e. plate bounded by web stiffeners/face plate) may not have a rectangular shape. In this case, an equivalent rectangular panel is to be defined according to (B) for irregular geometry and (C) for triangular geometry and to comply with buckling assessment.
  - **(B)** Modelling of an unstiffened panel with irregular geometry is to be based on **Pt 13**, **Sub-pt 1**, **Ch 8**, **Sec 4**, **2.3.2**.
  - **(C)** Modelling of an unstiffened plate panel with triangular geometryis to be based on **Pt 13**, **Sub-pt 1**, **Ch 8**, **Sec 4**, **2.3.3**.
- **(5)** Reference stress
  The stress distribution is to be taken from the direct strength analysis and applied to the buckling panel model. The reference stresses of buckling panel as shown in **Fig 12** are to be calculated using the Stress based reference stresses as defined in **Pt 13**, **Sub-pt 1**, **Ch 8**, **App 1**.
  ![Fig 66 Example of buckling panel](images/image366.png)
  **Fig 66 Example of buckling panel**
- **(6)** Lateral pressure
  The lateral pressure applied to the direct strength analysis is also to be applied to the buckling assessment. Where the lateral pressure is not constant over a buckling panel defined by a number of finite plate elements, an average lateral pressure, $\mathrm{N}/mm ^{2}$, is calculated using the following formula:
  $P _{avr} = \frac{\sum _{1} ^{n} A _{i} P _{i}}{\sum _{1} ^{n} A _{i}}$
  where :
  $A _{i}$ : Area of the i-th plate element, in $\mathrm{mm} ^{2}$.
  $P _{i}$ : Lateral pressure of the i-th plate element, in $\mathrm{N}/mm ^{2}$
  $n$ : Number of finite elements in the buckling panel.
- **(7)** Buckling criteria of panel
  Buckling strength of panel is satisfy the criterion defined in **Pt 13**, **Sub-pt 1**, **Ch 8**, **Sec 4**, **2**.
- **(8)** Buckling criteria of corrugated bulkhead
  Buckling strength of corrugated bulkhead is satisfy the criterion defined in **Pt 13**, **Sub-pt 1**, **Ch 8**, **Sec 4**, **3**.
- **(9)** Buckling criteria of vertically stiffened side shell
  Buckling strength of vertically stiffened side shell is satisfy the criterion defined in **Pt 13**, **Sub-pt 1**, **Ch 8**, **Sec 4**, **4**. (refer to **Fig 67**).
- **(10)** Buckling criteria of strut, pillar and cross ties
  Buckling strength of strut, pillar and cross ties is satisfy the criterion defined in **Pt 13**, **Sub-pt 1**, **Ch 8**, **Sec 4**, **5**.
  ![Fig 67 Vertically stiffened side shell](images/image367.png)
  **Fig 67 Vertically stiffened side shell**

#### 3. Buckling capacity

- **(1)** Assessment
  Assessment of bucking capacity for panel, stiffener, primary support members, strut, pillar, cross ties anf corrugated bulkhead is to perform according to **Pt 13**, **Sub-pt** 1, **Ch 9**, **Sec 5**. As determined by the Society. assessment of local plate panel can only be performed according to **Pt 11**, **Ch 6**, **Sec 3** or **Pt 13**, **Sub-pt 1**, **Ch 9**, **Sec 5**.
- **(2)** Application of net thickness
  Assessment of buckling capacity is to be based on net thickness extracted by corrosion addition, as shown in **Table 55**, from gross thickness. If the specific corrosion addition depending on a ship type based on measurement data is provided, this corrosion addition can be applied.

  | Compartment type | Corrosion addition |
  | --- | --- |
  | Ballast water tank, bilge tank, drain storage tank, chain locker(1) | 1.0 |
  | Exposed to atmosphere | 1.0 |
  | Exposed to sea water | 1.0 |
  | Fuel oil and lube oil tank | 0.5 |
  | Fresh water tank | 0.5 |
  | Void spaces and dry spaces(2)(3) | 0.0 |
  | Accommodation spaces | 0.0 |
  | Compartments other than those mentioned above | 0.5 |
  | Note:<br>(1) 1.0 mm is to be added to the plate surface within 3 m above the upper surface of the chain locker bottom.<br>(2) For the determination of the corrosion addition of the outer shell plating, the pipe tunnel is considered as for a ballast water tank.<br>(3) For bottom plate of compartment, corrosion addition is to be taken equal to 0.5mm. |   |

  ![](images/image368.png)
