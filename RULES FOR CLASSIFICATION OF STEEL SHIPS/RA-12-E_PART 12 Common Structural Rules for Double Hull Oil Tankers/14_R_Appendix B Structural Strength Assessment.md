# PART 12 Common Structural Rules for Double Hull Oil Tankers

> RULES FOR CLASSIFICATION OF STEEL SHIPS / RA-12-E / 2025 / EN / Rules

## Appendix B Structural Strength Assessment

### 1 General

#### 1.1 Application

- **1.1.1** General

#### 1.1.1.1

In accordance with Sec 9/2.1, a finite element (FE) assessment is to be carried out to verify the strength of the hull structure.

#### 1.1.1.2

The structural assessment is to be carried out in accordance with the requirements given in this Appendix. The structural assessment is to verify that the acceptance criteria specified are complied with.

#### 1.1.1.3

The requirements in this Appendix apply to the assessment of longitudinal hull girder structural members, primary supporting structural members and transverse bulkheads of the tanks in the midship cargo region and, in addition, the assessment of strengthening of longitudinal hull girder shear structural members, as defined in Sec 9/2.2.1.1 and Sec 4/Table 4.1.1, in way of transverse bulkheads for hull girder vertical shear loads in the forward and aft cargo regions. The strength assessment of longitudinal hull girder shear structural members given in this Appendix is not applicable for forward transverse collision bulkhead, engine room transverse bulkhead and slop tank transverse bulkheads.

#### 1.1.1.4

For the purpose of the FE structural assessment the cargo tank regions are as defined in Fig B.1.1.

#### 1.1.1.5

Cargo tank structural strength analysis, in accordance with Appendix B/2, for the assessment of scantlings of longitudinal hull girder structural members, primary supporting structural members and transverse bulkheads in tanks within the midship cargo region, is mandatory. The assessment is to be based on the maximum permissible still water (load combination S) and combined permissible still water and wave hull girder vertical shear forces (load combination S+D) between and including the forward bulkhead of the aft most cargo tank and 0.65 L from AP, but not including the engine room and slop tank transverse bulkheads, see Fig B.1.1(a).

#### 1.1.1.6

The assessment of longitudinal hull girder shear structural members in the forward cargo region, in accordance with Appendix B/2, is mandatory. The strengthening of these structural members in way of transverse bulkheads in the tanks of the forward cargo region may be based on the maximum permissible still water (load combination S) and combined permissible still water and wave hull girder vertical shear forces (load combination S+D) at the bulkhead positions forward of 0.65 L from AP, but not including the forward collision bulkhead, see Fig B.1.1(b).

#### 1.1.1.7

Strengthening of longitudinal hull girder shear structural members in way of transverse bulkheads of the tanks in the midship cargo region and the aft cargo region, in accordance with Appendix B/2, may be based on the scantling result obtained from the midship cargo tank analysis as described in 1.1.1.5.

#### 1.1.1.8

Alternatively, optional assessment may be carried out to determine the strengthening requirement of longitudinal hull girder shear structural members in way of individual transverse bulkheads based on the permissible still water (load combination S) and combined permissible still water and wave hull girder vertical shear forces (load combination S+D) at the transverse bulkhead position under consideration, see Fig B.1.1(b).

#### 1.1.1.9

Fine mesh finite element analysis, in accordance with Appendix B/3, and the finite element based fatigue assessment of lower hopper knuckle joint, in accordance with Appendix B/4, are mandatory for the midship cargo region.

| Fig B.1.1<br>Definition of Cargo Tank Regions for FE Structural Assessment |
| --- |
| (a) Midship cargo tank strength assessment<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image893.png) |
| (b) Assessment of longitudinal hull girder shear structural members<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image894.png) |
| #underline{Note}<br>1. Tanks in the forward cargo region are defined as tanks with their longitudinal centre of gravity position forward of 0.7 *L* from A.P.<br>2. Tanks in the midship cargo region are defined as tanks with their longitudinal centre of gravity position at or forward of 0.3 *L* from AP and at or aft of 0.7 *L* from A.P.<br>3. Tanks in the aft cargo region are defined as tanks with their longitudinal centre of gravity position aft of 0.3 *L* from A.P. |

#### 1.2 Symbols, Units and Definitions

- **1.2.1** General

#### 1.2.1.1

The symbols and definitions, applicable to this section, are given in Sec 4/1, Sec 7 and as follows:
*a_v* vertical acceleration, taken at centre of gravity of tank
*a_t* transverse acceleration, taken at centre of gravity of tank
*a_lng* longitudinal acceleration, taken at centre of gravity of tank
*E* Modulus of Elasticity of steel, 2.06 × 105 $\mathrm{N}/mm ^{2}$
*M_wv* vertical wave bending moment for a dynamic load case
*M_sw* vertical still water bending moment for a finite element loading pattern
*M_h* horizontal wave bending moment for a dynamic load case
*Q_wv* vertical wave shear force for a dynamic load case
*Q_sw* vertical still water shear force for a finite element loading pattern
*T_LC* draught at the loading condition being considered
*T_sc* scantling draught, as defined in Sec 4/1.1.5.5
*T_bal-em* emergency draught of ship
*t_grs* proposed new building gross thickness excluding Owner’s extras, see Sec 2/4.3.4
*t_corr* corrosion addition, as defined in Sec 6/3.2
*σ_yd* specified minimum yield stress of the material, $\mathrm{N}/mm ^{2}$
*σ_vm* von Mises stress
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image895.png)
*σ_x* axial stress in element *x* direction
*σ_y* axial stress in element *y* direction
*τ_xy* element shear stress in *x-y* plane
*δ_x* displacement in *x* direction, in accordance with the coordinate system defined in Sec 4/1.4
*δ_y* displacement in *y* direction, in accordance with the coordinate system defined in Sec 4/1.4
*δ_z* displacement in *z* direction, in accordance with the coordinate system defined in Sec 4/1.4
*θ_x* rotation about *x* axis, in accordance with the coordinate system defined in Sec 4/1.4
*θ_y* rotation about *y* axis, in accordance with the coordinate system defined in Sec 4/1.4
*θ_z* rotation about *z* axis, in accordance with the coordinate system defined in Sec 4/1.4

#### 1.2.1.2

The nomenclature of structural components is defined in Sec 4/1.5.

#### 1.2.1.3

Consistent co-ordinate and unit systems are to be used throughout all parts of the structural analysis. However, in calculations using Rule Formulae, the units and co-ordinate system as specified are to be used. Where output values from Rule formulae are in a different unit and/or co-ordinate system as used in the structural analysis, the output values are to be converted to the appropriate unit and co-ordinate system.

- **1.2.2** Finite element types

#### 1.2.2.1

The structural assessment is to be based on linear finite element analysis of three dimensional structural models. The general types of finite elements to be used in the finite element analysis are given in Table B.1.1.

#### 1.2.2.2

Two node line elements and three or four node plate/shell elements are considered sufficient for the representation of the hull structure. The mesh requirements given in this Appendix are based on the assumption that these elements are used in the finite element models. However, higher order elements may also be used.

**Table B.1.1<br>Types of Finite Element**

| Rod (or truss) element | Line element with axial stiffness only and constant cross-sectional area along the length of the element |
| --- | --- |
| Beam element | Line element with axial, torsional and bi-directional shear and bending stiffness and with constant properties along the length of the element |
| Membrane (or plane-stress) plate element | Plate element with bi-axial and in-plane plate element stiffness with constant thickness |
| Shell (or bending plate) element | Plate element with in-plane stiffness and out-of-plane bending stiffness with constant thickness |

#### 1.2.2.3

For the cargo tank and fine mesh strength analyses as specified in Appendix B/2 and B/3*,* the assessment against stress acceptance criteria is to be based on membrane (or in-plane) stresses of plate elements. For the fatigue assessment as specified in Appendix B/4, the calculation of dynamic stress range for the determination of fatigue life is to be based on surface stresses of plate elements.


### 2 Cargo Tank Structural Strength Analysis

#### 2.1 Assessment

- **2.1.1** General

#### 2.1.1.1

For tankers of conventional arrangements, the finite element strength assessment of the hull girder and primary supporting structural members is to be in accordance with the requirements in this section.

#### 2.2 Structural Modelling

- **2.2.1** General

#### 2.2.1.1

The longitudinal extent of the midship cargo tank finite element (FE) model is to cover three cargo tank lengths about midships. Where the tanks in the midship cargo region are of different lengths, the middle tank of the finite element model is to represent the cargo tank of the greatest length. The finite element model may be prismatic. The transverse bulkheads at the ends of the model are to be represented. Where corrugated transverse bulkheads are fitted, the model is to include the extent of the bulkhead stool structure forward and aft of the tanks at the model ends. The length of the model extending beyond the end transverse bulkheads is to be kept equal, at both ends. The web frames at the ends of the model are to be modelled. Typical finite element models representing the midship cargo tank region of different tanker configurations are shown in Fig B.2.1.

#### 2.2.1.2

The assessment of longitudinal hull girder shear structural members, as defined in Sec 9/2.2.1.1 and Sec 4/Table 4.1.1, against hull girder vertical shear loads in the forward and aft cargo regions may be based on the midship cargo tank finite element model with modification of plate and stiffener properties where appropriate. Where a separate cargo tank finite element model is used for the assessment of shear strength, the model is to cover three tank lengths.

#### 2.2.1.3

Both port and starboard sides of the ship are to be modelled. The full depth of the ship is to be modelled.

#### 2.2.1.4

All main longitudinal and transverse structural elements are to be modelled. These include inner and outer shell, double bottom floor and girder system, transverse and vertical web frames, stringers and transverse and longitudinal bulkhead structures. All plates and stiffeners on the structure, including web stiffeners, are to be modelled, see 2.2.1.11.

#### 2.2.1.5

The reduced thickness used in the FE model of the cargo tanks, applicable to all plating and stiffener’s web and flanges is to be calculated as follows:
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image896.png)
Where:
*t_grs* gross thickness, as defined in 1.2
*t_corr* corrosion addition, as defined in Sec 6/3.2

| Fig B.2.1<br>Typical 3-Tank FE Models Representing Midship Cargo Tank Region of Tankers |
| --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image897.png)<br>Typical Cargo Tank Model of an AfraMax Oil Tanker (shows only starboard side of the full breadth model)<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image898.png)<br>Typical Cargo Tank Model of a VLCC (shows only port side of the full breadth model)<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image899.png)<br>Typical Cargo Tank Model of a Product Tanker (shows only port side of the full breadth model) |

#### 2.2.1.6

The plate element mesh is to follow the stiffening system as far as practicable, hence representing the actual plate panels between stiffeners. In general, the plate element mesh is to satisfy the following requirements:

- **(a)** one element between every longitudinal stiffener, see Fig B.2.2. Longitudinally, the element length is not to be greater than 2 longitudinal spaces
- **(b)** one element between every vertical stiffener on transverse bulkheads, see Fig B.2.3
- **(c)** one element between every web stiffener on transverse and vertical web frames, cross ties and stringers, see Fig B.2.2 and Fig B.2.4
- **(d)** at least three elements over the depth of double bottom girders and floors, transverse web frames, vertical web frames and horizontal stringers on transverse bulkheads. For cross ties, deck transverse and horizontal stringers on transverse wash bulkheads and longitudinal bulkheads with a smaller web depth, representation using two elements over the depth is acceptable provided that there is at least one element between every web stiffener. The mesh size of adjacent structure is to be adjusted to suit
- **(e)** the mesh on the hopper tank web frame shall be fine enough to represent the shape of the web ring opening, see Fig B.2.2
- **(f)** the curvature of the free edge on large brackets of primary support members is to be modelled accurately to avoid unrealistic high stress due to geometry discontinuities. In general, a mesh size equal to the stiffener spacing is acceptable. The bracket toe may be terminated at the nearest nodal point provided that the modelled length of the bracket arm does not exceed the actual bracket arm length. The bracket flange is not to be connected to the plating, see Fig B.2.5. The modelling of the tapering part of the flange is to be in accordance with 2.2.1.14. An acceptable mesh is shown in Fig B.2.5. A finer mesh is to be used for the determination of detailed stress at the bracket toe, see Appendix B/3.

#### 2.2.1.7

Corrugated bulkheads and bulkhead stools are to be modelled using shell plate elements, see Fig B.2.6. Diaphragms in the stools and internal longitudinal and vertical stiffeners on the stool plating are to be included in the model. Modelling is to be carried out as follows:

- **(a)** the shell element mesh on the flange and web of the corrugation is in general to follow the stiffener spacing inside the bulkhead stool
- **(b)** where difficulty occurs in matching the mesh on the corrugations directly with the mesh on the stool, it is acceptable to adjust the mesh on the stools in way of the corrugations in order that the corrugation bulkhead will retain its original geometrical shape. However, if the shape of the corrugation is adjusted in order to simplify the modelling procedure, this effect is to be taken into account in evaluation of stresses as described in 2.7.2.6.
- **(c)** for a corrugated bulkhead without an upper stool and/or lower stool, it may be necessary to adjust the geometry in order to simplify the modelling. The adjustment is to be made such that the shape and position of the corrugations and primary support members are retained. Hence, the adjustment is to be made on stiffeners and plate seams if necessary.

#### 2.2.1.8

The aspect ratio of the plate elements is in general not to exceed three. The use of triangular plate elements is to be kept to a minimum. Where possible, the aspect ratio of plate elements in areas where there are likely to be high stresses or a high stress gradient is to be kept close to one and the use of triangular elements is to be avoided.

#### 2.2.1.9

Typical mesh arrangements of the cargo tank structure are shown in Fig B.2.7.

#### 2.2.1.10

Shell elements, in association with beam elements, are to be used to represent stiffened panels in areas under lateral pressure. Shell elements are to be used to represent unstiffened panels in areas under lateral pressure. Membrane and rod elements may be used to represent non-tight structure under no pressure loads.

| Fig B.2.2<br>Typical Finite Element Mesh on Web Frame |
| --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image900.png) |

| Fig B.2.3<br>Typical Finite Element Mesh on Transverse Bulkhead |
| --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image901.png) |

| Fig B.2.4<br>Typical Finite Element Mesh on Horizontal Transverse Stringer on Transverse Bulkhead |
| --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image902.png) |

| Fig B.2.5<br>Typical Finite Element Mesh on Transverse Web Frame Main Bracket |
| --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image903.png) |

| Fig B.2.6<br>Typical Finite Element Mesh on Transverse Corrugated Bulkhead Structure |
| --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image904.png) |

| Fig B.2.7<br>Typical Finite Element Mesh Arrangements of Cargo Tank Structure |
| --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image905.png) |

| Fig B.2.7 (Continued)<br>Typical Finite Element Mesh Arrangements of Cargo Tank Structure |
| --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image906.png)<br>VLCC<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image907.png)<br>Product tanker |

#### 2.2.1.11

All local stiffeners are to be modelled. These stiffeners may be modelled using line elements positioned in the plane of the plating. Beam elements are to be used in areas under the action of lateral loads whilst rod (truss) elements may be used to represent local stiffeners on internal structural members under no lateral loads. The line elements are to have the following properties:

- **(a)** for beam elements, out of plane bending properties are to represent the inertia of the combined plating and stiffener. The width of the attached plate is to be taken as ½ + ½ stiffener spacing on each side of the stiffener. The eccentricity of the neutral axis is not required to be modelled.
- **(b)** for beam and rod elements, other sectional properties are to be based on a cross sectional area representing the stiffener area, excluding the area of the attached plating.

#### 2.2.1.12

The effective cross sectional area of non-continuous stiffeners is to be calculated in accordance with Table B.2.1.

**Table B.2.1<br>Effective Cross Sectional Area of Stiffener Line Elements**

| Structure represented by line element | Effective area $A _{e}$ |   |
| --- | --- | --- |
| Stiffener within a distance 2 $d _{w}$ from a sniped (non-continuous) end | All sections | $A _{e}$=25%$A _{n-n et50}$ |
| Stiffener outside a distance 2 $d _{w}$ from a sniped (non-continuous) end | All sections | $A _{e}$=100%$A _{n-n et50}$ |
| Where:<br>$A _{n-n et50}$ average cross sectional area over length of line element<br>$d _{w}$ depth of stiffener web, excluding attached plate |   |   |

#### 2.2.1.13

Web stiffeners on primary support members are to be modelled. Where these stiffeners are not in line with the primary FE mesh, it is sufficient to place the line element along the nearby nodal points provided that the adjusted distance does not exceed 0.2 times the stiffener spacing under consideration. The stresses and buckling utilisation factors obtained need not be corrected for the adjustment. Buckling stiffeners on large brackets, deck transverses and stringers parallel to the flange are to be modelled. These stiffeners may be modelled using rod elements.

#### 2.2.1.14

Face plates of primary support members and brackets may be modelled using rod elements. The effective cross sectional area at the curved part of the face plate is to be calculated in accordance with Sec 4/2.3.4. The cross sectional area of a rod element representing the tapering part of the face plate is to be based on the average cross sectional area of the face plate in way of the element length.

#### 2.2.1.15

Methods of representing openings in webs of primary support members are to be in accordance with Table B.2.2. Cut-outs for local stiffeners, scallops, drain and air holes need not be represented.

**Table B.2.2<br>Representation of Openings in Primary Support Member Webs**

| $h _{0}$/$h$ < 0.35 and $\mathrm{g} _{0}$ < 1.2 | Openings do not need to be modelled |
| --- | --- |
| 0.5 > $h _{0}$/$h$ ≥ 0.35 and $\mathrm{g} _{0}$ < 1.2 | The plate modelled with mean thickness *t_1-net50* |
| $h _{0}$/$h$ < 0.5 and 2 > $\mathrm{g} _{0}$ ≥ 1.2 | The plate modelled with mean thickness *t_2-net50* |
| $h _{0}$/$h$ ≥ 0.5 or$\mathrm{g} _{0}$ ≥ 2.0 | The geometry of the opening is to be modelled |
| Where:<br>$\mathrm{g} _{0}$ = ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image908.png)<br>*t_1-net50* = ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image909.png)<br>*t_2-net50* = ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image910.png)<br>*t_w-net50* net web thickness<br>$l _{0}$ length of opening parallel to primary support member web direction, see Fig B.2.8<br>$h _{0}$ height of opening parallel to depth of web, see Fig B.2.8<br>$h$ height of web of primary support member in way of opening, see Fig B.2.8<br>*t_corr* corrosion addition, as defined in Sec 6/3.2 |   |
| Note<br>1. For sequential openings where the distance, $d _{0}$, between openings is less than 0.25 $h$, the length $l _{0}$ is to be taken as the length across openings as shown in Fig B.2.9.<br>2. The same unit is to be used for $l _{0}$, $h _{0}$ and $h$. |   |

| Fig B.2.8<br>Openings in Web |
| --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image911.png) |

| Fig B.2.9<br>Length $l _{0}$ for Sequential Openings with $d _{0} < \frac{h}{4}$ |
| --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image912.png) |

#### 2.3 Loading Conditions

- **2.3.1** Finite element load cases

#### 2.3.1.1

The standard design load combinations to be used in the structural analysis are given in Tables B.2.3 and B.2.4 for tankers with two oil-tight longitudinal bulkheads and one centreline oil-tight longitudinal bulkhead respectively.

#### 2.3.1.2

For S+D design load combinations (seagoing load cases) the number of dynamic load cases required to be investigated for each loading pattern is indicated by the dynamic load case numbers specified for each loading pattern in Tables B.2.3 and B.2.4. Each S+D design load combination consists of two parts:

- **(a)** static loads, as described by the loading pattern, ship draught, hull girder still water bending moment and shear force specified, and
- **(b)** dynamic loads defined in Sec 7/Table 7.6.2 for the dynamic load case number specified.

#### 2.3.1.3

For tankers with two oil-tight longitudinal bulkheads and a cross tie arrangement in the centre cargo tanks, loading patterns A7 and A12 in Table B.2.3 are to be examined for the possibility that unequal filling levels in transversely paired wing cargo tanks would result in a more onerous stress response. Loading pattern A7 is required to be analysed only if such a non-symmetric seagoing loading conditionis included in the ship loading manual. Loading patterns A7 and A12 need not be examined for tankers without a cross tie arrangement in the centre cargo tanks.

#### 2.3.1.4

For tankers with two oil-tight longitudinal bulkheads, seagoing loading pattern A3 and harbour loading pattern A13, with all cargo tanks abreast empty, are to be analysed with a ship draught of 0.55 $T _{sc}$ and 0.65 $T _{sc}$ respectively. If conditions in the ship loading manual specify greater draughts for loading pattern A3 or A13, then the maximum specified draught in the ship’s loading manual for the loading pattern is to be used.

#### 2.3.1.5

For tankers with two oil-tight longitudinal bulkheads, seagoing loading pattern A5 and harbour loading pattern A11, with all cargo tanks abreast fully loaded, are to be analysed with a ship draught of 0.8 $T _{sc}$ and 0.7 $T _{sc}$ respectively. If conditions in the ship loading manual specify lesser draughts for loading pattern A5 or A11, then the minimum specified draught in the ship’s loading manual for the loading pattern is to be used.

#### 2.3.1.6

For loading patterns A1, A2, B1, B2 and B3, with cargo tank(s) empty, a minimum ship draught of 0.9 $T _{sc}$ is to be used in the analysis. If conditions in the ship loading manual specify greater draughts for loading patterns with empty cargo tank(s), then the maximum specified draught for the actual condition is to be used.

#### 2.3.1.7

Where a ballast condition is specified in the ship loading manual with ballast water filled in one or more cargo tanks, loading patterns A8 and B7 in Tables B.2.3 and B.2.4 are to be examined. If this loading is un-symmetrical then additional strength assessment is to be carried out according to the requirements of the individual Classification Society.

**Table B.2.3<br>FE Load Cases for Tankers with Two Oil-tight Longitudinal Bulkheads**

| Loading<br>pattern | Figure | Still water loads |   |   | Dynamic load cases |   |   |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Loading<br>pattern | Figure | Draught | % of Perm. SWBM<sup>(2)</sup> | % of Perm. SWSF<sup>(2)</sup> | Strength assessment ^(1a) | Strength assessment against hull girder shear loads^(1b) |   |
| Loading<br>pattern | Figure | Draught | % of Perm. SWBM<sup>(2)</sup> | % of Perm. SWSF<sup>(2)</sup> | Midship region | Forward region | Midship and aft regions |
| Design load combination S + D (Sea-going load cases) |   |   |   |   |   |   |   |
| A1 | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image913.png) | 0.9$T _{sc}$ | 100 %<br>(sag) | See note 3 | 1 | \ | \ |
| A1 |   | 0.9$T _{sc}$ | 100 %<br>(hog) | 100 %<br>(-ve fwd)<br>See note 4 | 2, 5a | \ | \ |
| A2 | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image914.png) | 0.9$T _{sc}$ | 100 %<br>(sag) | See note 3 | 1 | \ | \ |
| A2 |   | 0.9$T _{sc}$ | 100 %<br>(hog) | 100 %<br>(-ve fwd)<br>See note 4 | 2, 5a | \ | \ |
| A3 | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image915.png) | 0.55$T _{sc}$<br>see note 6 | 100 %<br>(hog) | 100 %<br>(-ve fwd)<br>See note 5 | 2 | 4 | 2 |
| A3 |   | 0.55$T _{sc}$<br>see note 6 | 100 %<br>(hog) | 100 %<br>(-ve fwd)<br>See note 4 | 5a | \ | \ |
| A4 | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image916.png) | 0.6$T _{sc}$ | 100 %<br>(sag) | 100 %<br>(+ve fwd)<br>See note 4 | 1, 5a | \ | \ |
| A5 | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image917.png) | 0.8$T _{sc}$<br>See note 7 | 100 %<br>(sag) | 100 %<br>(+ve fwd)<br>See note 5 | 1 | 3 | 1 |
| A5 |   | 0.8$T _{sc}$<br>See note 7 | 100 %<br>(sag) | 100 %<br>(+ve fwd)<br>See note 4 | 5a | \ | \ |
| A6 | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image918.png) | 0.6$T _{sc}$ | 100 %<br>(hog) | 100 %<br>(-ve fwd)<br>See note 4 | 5a | \ | \ |
| A7<sup>(8)</sup> | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image919.png) | $T _{LC}$ | 100 %<br>(hog) | 100 %<br>(-ve fwd)<br>See note 4 | 5a | \ | \ |
| A8<sup>(9)</sup> | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image920.png) | $T _{bal-em}$ | 100 %<br>(sag) | 100 %<br>(+ve fwd)<br>See note 4 | 1 | \ | \ |
| Design load combination S (Harbour and tank testing load cases) |   |   |   |   |   |   |   |
| A9<sup>(13)</sup> | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image921.png) | 1/4$T _{sc}$ | 100 % (sag) | 100 %<br>(+ve fwd)<br>See note 4 | Only applicable to strength assessment of midship region (see note 1(a)) |   |   |
| A10<sup>(13)</sup> | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image922.png) | 1/4$T _{sc}$ | 100 % (sag) | 100 %<br>(+ve fwd)<br>See note 4 | Only applicable to strength assessment of midship region (see note 1(a)) |   |   |
| A11^(12,13) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image923.png) | 0.7$T _{sc}$<br>see note 12 | 100 % (sag) | 100 %<br>(+ve fwd)<br>See note 5 | Applicable to strength assessment of midship region (see 1(a)) and strength assessment against hull girder shear loads (see 1(b)) |   |   |
| A12^(10,13) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image924.png) | 1/3$T _{sc}$ | See note 10 | See note 10 | Only applicable to strength assessment of midship region (see note 1(a)) |   |   |
| A13^(11,13) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image925.png) | 0.65$T _{sc}$<br>see note 11 | 100 % (Hog) | 100 %<br>(-ve fwd)<br>See note 5 | Applicable to strength assessment of midship region (see 1(a)) and strength assessment against hull girder shear loads (see 1(b)) |   |   |
| A14<sup>(13)</sup> | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image926.png) | $T _{sc}$ | 100 % (Hog) | 100 %<br>(-ve fwd)<br>See note 4 | Only applicable to strength assessment of midship region (see note 1(a)) |   |   |

| Table B.2.3 (Continued)<br>FE Load Cases for Tankers with Two Oil-tight Longitudinal Bulkheads |
| --- |
| #underline{Note}<br>1.<br>(a) For the assessment of scantlings of longitudinal hull girder structural members, primary supporting structural members and transverse bulkheads within midship cargo region, see 1.1.1.5.<br>(b) For the assessment of strengthening of longitudinal hull girder shear structural members in way of transverse bulkheads for hull girder vertical shear loads, see 1.1.1.6, 1.1.1.7 and 1.1.1.8.<br>2. The selection of permissible SWBM and SWSF for the assessment of different cargo regions of the ship is to be in accordance with Table B.2.6. The percentage of the permissible SWBM and SWSF to be applied are to be in accordance with this table.<br>3. The actual shear force that results from the application of static and dynamic local loads to the FE model are to be used.<br>4. The actual shear force that results from the application of static and dynamic local loads to the FE model are to be used. Where this shear force exceeds the target SWSF (design load combination S) or target combined SWSF and VWSF, calculated in accordance with 2.4.5.2, (design load combination S+D) as specified in the table, correction vertical loads are to be applied to adjust the shear force down to the required value.<br>5. Correction vertical loads are to be applied to adjust the shear force to the required value specified.<br>6. For loading pattern A3, with all cargo tanks abreast empty in sea-going condition, a draught of 0.55$T _{sc}$ is to be used in the analysis. Where such conditions are specified in the ship’s loading manual with a draught greater than 0.55$T _{sc}$, the maximum specified draught for those loading conditions is to be used in the FE analysis.<br>7. For loading pattern A5, with all cargo tanks abreast fully loaded in sea-going condition, a draught of 0.8$T _{sc}$ is to be used in the analysis. Where such conditions are specified in the ship’s loading manual with a draught lesser than 0.8$T _{sc}$, the minimum specified draught for those loading conditions is to be used in the FE analysis.<br>8. Loading pattern A7 is only required to be analysed for tankers with a cross tie arrangement in the centre cargo tanks if the ship’s loading manual includes a non-symmetrical loading condition with only one of the wing tanks filled. The actual draught from the loading manual for the condition is to be used in the analysis, see Table B.2.5.<br>9. Ballast loading pattern A8 with ballast filled in one or more cargo tanks (i.e. gale ballast/emergency ballast conditions etc.) is only required to be analysed if the condition is specified in the ship’s loading manual. The actual loading pattern and draught from the loading manual for the condition is to be used in the analysis, see Table B.2.5.<br>10. Loading patterns A12 is only required for tankers with a cross tie arrangement in the centre cargo tanks. The actual shear force and bending moment that results from the application of local loads to the FE model are to be used. Adjusting vertical loads and bending moments are not applied.<br>11. For loading pattern A13, with all cargo tanks abreast empty in harbour condition, a draught of 0.65$T _{sc}$ is to be used in the analysis. Where such conditions are specified in the ship’s loading manual with a draught greater than 0.65$T _{sc}$, the maximum specified draught for those loading conditions is to be used in the FE analysis.<br>12. For loading pattern A11, with all cargo tanks abreast fully loaded in harbour condition, a draught of 0.7$T _{sc}$ is to be used in the analysis. Where such conditions are specified in the ship’s loading manual with a draught less than 0.7$T _{sc}$, the minimum specified draught for those loading conditions is to be used in the FE analysis.<br>13. No dynamic loads are to be applied to Design Load Combination S (harbour and tank testing load cases). |

**Table B.2.4<br>Load Cases for Tankers with One Centreline Oil-tight Longitudinal Bulkhead**

| Loading<br>pattern | Figure | Still water loads |   |   | Dynamic load cases |   |   |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Loading<br>pattern | Figure | Draught | % of Perm. SWBM<sup>(2)</sup> | % of Perm. SWSF<sup>(2)</sup> | Strength assessment ^(1a) | Strength assessment against hull girder shear loads^(1b) |   |
| Loading<br>pattern | Figure | Draught | % of Perm. SWBM<sup>(2)</sup> | % of Perm. SWSF<sup>(2)</sup> | Midship region | Forward region | Midship and aft regions |
| Design load combination S + D (Sea-going load cases) |   |   |   |   |   |   |   |
| B1 | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image927.png) | 0.9$T _{sc}$ | 100 % (sag) | See note 3 | 1 | \ | \ |
| B1 |   | 0.9$T _{sc}$ | 100 % (hog) | 100 %<br>(-ve fwd) See note 4 | 2, 5a | \ | \ |
| B2<sup>(6)</sup> | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image928.png) | 0.9$T _{sc}$ | 100 % (sag) | See note 3 | 1 | \ | \ |
| B2<sup>(6)</sup> |   | 0.9$T _{sc}$ | 100 % (hog) | 100 %<br>(-ve fwd) See note 4 | 2, 5b | \ | \ |
| B3 | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image929.png) | 0.9$T _{sc}$ | 100 % (hog) | 100 %<br>(-ve fwd)<br>See note 5 | 2 | 4 | 2 |
| B3 |   | 0.9$T _{sc}$ | 100 % (hog) | 100 %<br>(-ve fwd)<br>See note 4 | 5a, 5b, 6a, 6b | \ | \ |
| B4 | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image930.png) | 0.6$T _{sc}$ | 100 % (sag) | 75 %<br>(+ve fwd)<br>See note 4 | 1, 5a | \ | \ |
| B5<sup>(6)</sup> | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image931.png) | 0.6$T _{sc}$ | 100 % (sag) | 75 %<br>(+ve fwd)<br>See note 4 | 1, 5b | \ | \ |
| B6 | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image932.png) | 0.6$T _{sc}$ | 100 % (sag) | 100 %<br>(+ve fwd)<br>See note 5 | 1 | 3 | 1 |
| B6 |   | 0.6$T _{sc}$ | 100 % (sag) | 100 %<br>(+ve fwd)<br>See note 4 | 5a, 5b | \ | \ |
| B7<sup>(7)</sup> | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image933.png) | $T _{bal-em}$ | 100 % (sag) | 100 %<br>(+ve fwd)<br>See note 4 | 1 | \ | \ |
| Design load combination S (Harbour and tank testing load cases) |   |   |   |   |   |   |   |
| B8<sup>(8)</sup> | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image934.png) | 1/3$T _{sc}$ | 100 % (sag) | 100 %<br>(+ve fwd)<br>See note 5 | Applicable to strength assessment of midship region (see 1(a)) and strength assessment against hull girder shear loads (see 1(b)) |   |   |
| B9<sup>(8)</sup> | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image935.png) | 1/3$T _{sc}$ | 100 % (sag) | 75 %<br>(+ve fwd)<br>See note 4 | Only applicable to strength assessment of midship region (see note 1(a)) |   |   |
| B10^(6,8) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image936.png) | 1/3$T _{sc}$ | 100 % (sag) | 75 %<br>(+ve fwd)<br>See note 4 | Only applicable to strength assessment of midship region (see note 1(a)) |   |   |
| B11<sup>(8)</sup> | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image937.png) | $T _{sc}$ | 100 % (Hog) | 100 %<br>(-ve fwd)<br>See note 5 | Applicable to strength assessment of midship region (see 1(a)) and strength assessment against hull girder shear loads (see 1(b)) |   |   |
| #underline{Note}<br>1.<br>(a) For the assessment of scantlings of longitudinal hull girder structural members, primary supporting structural members and transverse bulkheads within midship region, see 1.1.1.5.<br>(b) For the assessment of strengthening of longitudinal hull girder shear structural members in way of transverse bulkheads for hull girder vertical shear loads, see 1.1.1.6, 1.1.1.7 and 1.1.1.8.<br>2. The selection of permissible SWBM and SWSF for the assessment of different cargo regions of the ship is to be in accordance with Table B.2.6. The percentage of the permissible SWBM and SWSF to be applied are to be accordance with this table.<br>3. The actual shear force that results from the application of static and dynamic local loads to the FE model are to be used.<br>4. The actual shear force that results from the application of static and dynamic local loads are to be used. Where this shear force exceeds the target SWSF (design load combination S) or target combined SWSF and VWSF, calculated in accordance with 2.4.5.2, (design load combination S+D) as specified in the table, correction vertical loads are to be applied to adjust the shear force down to the required value.<br>5. Correction vertical loads are to be applied to adjust the shear force to the required value specified.<br>6. Load cases B2, B5 and B10 are only required if the structure is not symmetrical about the ship’s centreline.<br>7. Ballast loading pattern B7 with ballast filled in cargo tanks (i.e. gale ballast/emergency ballast conditions etc.) is only required to be analysed if the condition is specified in the ship’s loading manual. The actual loading pattern and draught from the loading manual for the condition is to be used in the analysis, see Table B.2.5. If the actual loading pattern is different from load case B7 then:<br>(a) An operational restriction corresponding to the analysed condition is to be added in the Loading Manual.<br>(b) 100 % of the permissible SWBM is to be applied when analyzing loading pattern with ballast in cargo tanks.<br>8. No dynamic loads are to be applied to Design Load Combination S (harbour and tank testing load cases). |   |   |   |   |   |   |   |

- **2.3.2** Dynamic load cases

#### 2.3.2.1

The dynamic load cases to be used for the finite element analysis are specified in Sec 7/6.4.

#### 2.4 Application of Loads

- **2.4.1** General

#### 2.4.1.1

The application of loads to the finite element model is to be in accordance with Sec 7/6 and the requirements specified in B/2.4.

#### 2.4.1.2

The load parameters and locations to be used for the calculation of the applied loads and accelerations are to be in accordance with Table B.2.5 and Table B.2.6.

#### 2.4.1.3

Constant pressure load, evaluated at the element’s centroid, may be applied to a finite plate element. Alternately, a linear pressure distribution between the element’s nodal points can be applied.

**Table B.2.5<br>Parameters for Calculation of Loads and Accelerations**

| Parameter | Standard conditions |   |   | Optional conditions |   |
| --- | --- | --- | --- | --- | --- |
| Parameter | Draught<br>$T _{sc}$ | Draught<br>0.9$T _{sc}$ | Draught<br>0.6$T _{sc}$ | Loaded conditions:<br>A3 (draught > 0.6$T _{sc}$) and A7 | Gale/emergency ballast conditions:<br>A8 and B7 |
| $L$ | Rule Length |   |   | Rule Length |   |
| $C _{b}$ | block coefficient, as defined in Sec 4/1.1.9.1 |   |   | block coefficient, as defined in Sec 4/1.1.9.1 |   |
| Ship speed | 0.0 |   |   | 0.0 |   |
| Roll response |   |   |   |   |   |
| GM | 0.12$B$ | 0.12$B$ | 0.24$B$ | Corrected GM in the ship’s loading manual for the loaded or gale/emergency ballast pattern under consideration, see Note 1 |   |
| $r _{roll-gyr}$ | 0.35$B$ | 0.35$B$ | 0.4$B$ | See Note 2 |   |
| Pitch response, longitudinal and transverse accelerations, horizontal wave bending moment and sea pressures |   |   |   |   |   |
| Ship draught | $T _{sc}$ | 0.9$T _{sc}$ | 0.6$T _{sc}$ | Maximum mean draught in the loading manual for the loading pattern under consideration | Minimum mean draught in the loading manual for the loading pattern under consideration |
| #underline{Note}<br>1. Where GM for optional loaded or gale/emergency ballast conditions is not given in the ship’s loading manual, GM is to be determined in accordance with Sec 7/3.1.3.2.<br>2. Where $r _{roll-gyr}$ for optional loaded or gale/emergency ballast conditions is not given in the ship’s loading manual, $r _{roll-gyr}$ is to be determined in accordance with Sec 7/3.1.3.3.<br>3. A gale/emergency ballast condition is defined as a ballast condition with one or more cargo tanks filled with ballast. |   |   |   |   |   |

**Table B.2.6<br>Locations for the Determination of Loads and Accelerations**

|   | Strength assessment^(1a) | Strength assessment against hull girder shear loads(^1b) |   |   |
| --- | --- | --- | --- | --- |
|   | Midship cargo<br>region | Forward<br>cargo region | Midship<br>cargo region | Aft<br>cargo region |
| Design load combinations S + D (Sea-going load cases) |   |   |   |   |
| Dynamic wave pressure and green sea load | Transverse section at 0.5$L$ from AP | Transverse section at 0.75$L$ from AP | Transverse section at 0.5$L$ from AP | Transverse section at 0.25$L$ from AP |
| Acceleration<br>$a _{v}$, $a _{t}$, $a _{l ng}$ | at CG position of midship tanks (i.e. 0.5$L$ from AP is within the tank boundary) | at CG position of forward tanks (i.e. 0.75$L$ from AP is within the tank boundary) | at CG position of midship tanks (i.e. 0.5$L$ from AP is within the tank boundary) | at CG position of aft tanks (i.e. 0.25$L$ from AP is within the tank boundary) |
| VWBM and SWBM (SWBM is to be based on sea-going permissible values, as defined in Sec 7/2.1.1 and 2.1.2) | at 0.5$L$ from AP | at 0.75$L$ from AP | at 0.5$L$ from AP | at 0.25$L$ from AP |
| HWBM | at 0.5$L$ from AP | \ | \ | \ |
| VWSF and SWSF (SWSF is to be based on sea-going permissible values, as defined in Sec 7/2.1.3 and 2.1.4) | at the transverse bulkhead with maximum combined seagoing permissible SWSF and VWSF in the region (see 1.1.1.5) | at the transverse bulkhead with maximum combined seagoing permissible SWSF and VWSF in the region (see 1.1.1.6) or at individual bulkhead position (see 1.1.1.8) | based on midship cargo tank strength assessment (see 1.1.1.7) or seagoing permissible SWSF and VWSF at individual transverse bulkhead position (see 1.1.1.8) |   |
| Design load combination S (Harbour and tank testing load cases) |   |   |   |   |
| SWBM<br>(SWBM is to be based on harbour permissible values, as defined in Sec 7/2.1.1 and 2.1.2) | at 0.5$L$ from AP | at 0.75$L$ from AP | at 0.5$L$ from AP | at 0.25$L$ from AP |
| SWSF<br>(SWSF is to be based on harbour permissible values, as defined in Sec 7/2.1.3 and 2.1.4) | maximum harbour permissible SWSF in the region (see 1.1.1.5) | maximum harbour permissible SWSF in the region (see 1.1.1.6) or at individual bulkhead position (see 1.1.1.8) | based on midship cargo tank strength assessment (see 1.1.1.7) or harbour permissible SWSF at individual transverse bulkhead position (see 1.1.1.8) |   |
| Note<br>1. The following assessments are to be carried out:<br>(a) for the assessment of scantlings of longitudinal hull girder structural members, primary supporting structural members and transverse bulkheads in tanks within midship cargo region, see 1.1.1.5<br>(b) for the assessment of strengthening of longitudinal hull girder shear structural members in way of individual transverse bulkheads for hull girder shear loads, see 1.1.1.6, 1.1.1.7 and 1.1.1.8.<br>2. For each FE load case, accelerations are to be calculated at the centre of gravity position of the ballast and/or cargo in accordance with this table. The acceleration calculated for each reference tank is to be applied to the 3 corresponding cargo or ballast tanks along the length of the FE model.<br>3. Longitudinal distances used in the calculation of loads refer to distance measured forward from the A.P., as defined in Sec 4/1.1.12<br>4. Dynamic wave pressure calculated at the specified section is to be applied to the full length of the FE model<br>5. Dynamic load combination factors applied to dynamic loads for design load combination S+D (sea-going load cases) as defined in Sec 7/6.4.<br>6. The SWBM and SWSF to be applied are to be in accordance with Tables B.2.3 and B.2.4. |   |   |   |   |

- **2.4.2** Structural weight, cargo and ballast density

#### 2.4.2.1

The design cargo density is to be taken as 1.025 tonnes/$\mathrm{m} ^{3}$, see 2.4.7.2.

#### 2.4.2.2

The density of sea water is to be taken as 1.025 tonnes/$\mathrm{m} ^{3}$.

#### 2.4.2.3

The weight of the structure is to be included in the FE analysis. The density of steel is to be taken as 7.85 tonnes/$\mathrm{m} ^{3}$.

- **2.4.3** Static sea pressure

#### 2.4.3.1

The static sea pressure applied to a plate element due to draught immersion is to be calculated in accordance with Sec 7/2.2.2.

#### 2.4.3.2

The still water draught to be considered for each finite element load case is to be in accordance with Tables B.2.3 and B.2.4. A constant draught is to be applied over the full length of the cargo tank FE model.

#### 2.4.3.3

The static sea pressure due to immersed draught for the ship in an upright condition is to be applied for all finite element load cases. The static sea pressure change due to rolling of the ship is included in the dynamic wave pressure formulation.

- **2.4.4** Dynamic wave pressure

#### 2.4.4.1

The dynamic wave pressure distribution is to be determined at a transverse section of the hull at the longitudinal position as defined in Table B.2.6. The dynamic wave pressure distribution is to be calculated in accordance with Sec 7/6.3.5. This pressure distribution is to be applied over the full length of the FE model.

#### 2.4.4.2

The pressure distribution due to green sea load on the weather deck is to be calculated in accordance with Sec 7/6.3.6 at the longitudinal position as defined in Table B.2.6. This pressure distribution is to be applied to the weather deck over the full length of the FE model.

- **2.4.5** Hull girder vertical bending moment and vertical shear force

#### 2.4.5.1

The hull girder vertical bending moment is to reach the following required value, *M_v-targ*, at a section within the length of the middle tank of the three tanks FE model:
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image938.png)
Where:
*M_sw* is the still water bending moment to be applied to the FE load case, as specified in Tables B.2.3 and B.2.4.
*M_wv* is the vertical wave bending moment for the dynamic load case under consideration, calculated in accordance with Sec 7/6.3.2

#### 2.4.5.2

Hull girder vertical shear force is to reach the following required *Q_targ* value at the forward transverse bulkhead position of the middle tank:
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image939.png)
Where:
*Q_sw* is the vertical still water shear force to be applied to the FE load case, as specified in Tables B.2.3 and B.2.4.
*Q_wv* is the vertical wave shear force for the dynamic load case under consideration, calculated in accordance with Sec 7/6.3.4.

#### 2.4.5.3

The required hull girder vertical bending moment and shear force are to be achieved in the same load case where required by Tables B.2.3 and B.2.4. The procedure to apply the required shear force and bending moment distributions is described in 2.5.

- **2.4.6** Hull girder horizontal wave bending moment

#### 2.4.6.1

Hull girder horizontal wave bending moment at a section within the length of the middle tank of the three tanks FE model is to reach the value required by the dynamic load case under consideration, calculated in accordance with Sec 7/6.3.3.

#### 2.4.6.2

The procedure to adjust the required hull girder horizontal bending moment is described in 2.5.

- **2.4.7** Pressure in cargo and ballast tanks

#### 2.4.7.1

The total tank pressure, *P_in*, to be applied at the boundary of a cargo or ballast tank in the finite element analysis is to include the static and dynamic components specified in Sec 7/Table 7.6.1 and Table B.2.6.

#### 2.4.7.2

For the seagoing load cases (design combination S + D) the cargo tank pressure is to be taken as:
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image940.png) $\mathrm{kN}/m ^{ 2}$
where:
*f_density* factor for joint probability of occurrence of cargo density and maximum sea state in 25 years design life
= *r_max-LM* / *r_allowable*
*r_max-LM* maximum cargo density associated with a full tank from any loading condition in the ship's loading manual. *r_max-LM* is not to be taken as less than 0.9 tonnes/$\mathrm{m} ^{3}$ for cargo loaded conditions and 1.025 tonnes/$\mathrm{m} ^{3}$ for the optional emergency ballast condition (i.e. A8 and B7 in Tables B.2.3 and B.2.4 respectively)
*r_allowable* design cargo density associated with a full tank to be taken as 1.025 tonnes/$\mathrm{m} ^{3}$ unless a higher density is specified by the builder, see Sec 2/3.1.8.1
*Pi_n-tk* static tank pressure as given in Sec 7/2.2.3.1, in $\mathrm{kN}/m ^{ 2}$, and with density of fluid in tank equal to the design cargo density, *r_allowable*
*P_in-dyn* simultaneously acting dynamic pressure given in Sec 7/6.3.7.1, in $\mathrm{kN}/m ^{ 2}$, with simplification given in 2.4.7.3 and with density of fluid in tank equal to the design cargo density, *r_allowable*

#### 2.4.7.3

The envelope vertical acceleration, *a_v*, at the centre of gravity of tanks is calculated in accordance with Sec 7/3.3.3 with the following simplifications:

- **(a)** for head sea conditions, *a_roll-z* is taken as 0
- **(b)** for beam sea conditions, *a_pitch-z* is taken as 0.

#### 2.4.7.4

The vertical, transverse and longitudinal accelerations are to be calculated at the centre of gravity of the abreast tanks at the longitudinal position as specified in Table B.2.6. These accelerations are to be applied to all corresponding tanks along the length of the three-tank FE model.

#### 2.4.7.5

The dynamic tank pressure is to be calculated in accordance with Sec 7/6.3.7.1, also see Table B.2.6.

#### 2.4.7.6

For ballast tanks which utilise ballast water exchange by flow-through method, the following are to be considered when calculating tank pressure for seagoing load cases (design combination S + D) as required by Sec 7/Table 7.6.1:
• Maximum vertical height of the air pipe or overflow pipe, i.e. *h_air* as defined in Sec 7/2.2.3.2 and Fig 7.2.3, of all ballast tanks in the cargo region is to be used in the calculation of the dynamic tank pressure due to vertical acceleration (see Sec 7/6.3.7.1).
• Maximum value of *h_air* and *P_drop*, as defined in Sec 7/2.2.3.3, of all ballast tanks in the cargo region are to be used to calculate the static tank pressure.

#### 2.4.7.7

The following are to be considered when calculating the static tank pressure in cargo tanks for harbour/tank testing load cases (design combination S) as required by Sec 7/Table 7.6.1:
• maximum *h_air*, as defined in Sec 7/2.2.3.2 and Fig. 7.2.3, of all cargo tanks in the cargo region are to be considered in the calculation of $P _{i n-test}$, see Sec 7/2.2.3.5.

#### 2.4.7.8

Where the length of the model is extended beyond the end transverse bulkheads, see 2.2.1.1, tank pressure is only to be applied to the complete tanks within the model length.

#### 2.4.7.9

Maximum setting of pressure relief valve, *P_valve*, as defined in Sec 7/2.2.3.5 are to be considered in design combination S and S+D as required by Sec 7/Table 7.6.1.

#### 2.5 Procedure to Adjust Hull Girder Shear Forces and Bending Moments

- **2.5.1** General

#### 2.5.1.1

The procedure described in this section is to be applied to adjust the hull girder horizontal bending moment, vertical shear force and vertical bending moment distributions on the three cargo tanks FE model to achieve the required values.

#### 2.5.1.2

Vertical distributed loads are applied to each frame position, together with a vertical bending moment applied to the model ends to produce the required value of vertical shear force at both the forward and aft bulkhead of the middle tank of the FE model, and the required value of vertical bending moment at a section within the length of the middle tank of the FE model. The required values are specified in 2.4.5.

#### 2.5.1.3

A horizontal bending moment is applied to the ends of the model to produce the required target value of horizontal bending moment at a section within the length of the middle tank of the FE model. The required values are specified in 2.4.6.

- **2.5.2** Shear force and bending moment due to local loads

#### 2.5.2.1

The vertical shear forces generated by the local loads are to be calculated at the transverse bulkhead positions of the middle tank of the FE model. The maximum absolute shear force at the bulkhead position of the middle tank of the FE model is to be used to obtain the required adjustment in shear forces at the transverse bulkhead, see 2.5.3. The vertical bending moment distribution generated by the local loads is to be calculated along the length of the middle tank of the three cargo tank FE model. The FE model can be used to calculate the shear forces and bending moments. Alternatively, a simple beam model representing the length of the 3-tank FE model with simply supported ends may be used to determine the shear force and bending moment values.

#### 2.5.2.2

For beam and oblique sea conditions, the horizontal bending moment distribution due to dynamic sea pressure and dynamic tank pressure is to be calculated along the length of the middle tank of the FE model.

#### 2.5.2.3

The following local loads are to be applied for the calculation of hull girder shear forces and bending moments:

- **(a)** ship structural weight distribution over the length of the 3-tank model (static loads). Where a simple beam model is used, the weight of the structure of each tank can be distributed evenly over the length of the cargo tank. The structural weight is to be calculated based on a thickness deduction of 0.5 *t_corr*, as used in the construction of the cargo tank FE model, see 2.2.1.5.
- **(b)** weight of cargo and ballast (static loads)
- **(c)** static sea pressure, dynamic wave pressure and, where applicable, green sea load. For the Design Load Combination S (harbour/tank testing load cases), only static sea pressure needs to be applied
- **(d)** dynamic tank pressure load for Design Load Combination S + D (seagoing load cases).
- **2.5.3** Procedure to adjust vertical shear force distribution

#### 2.5.3.1

The required adjustment in shear forces at the transverse bulkhead positions ($\Delta Q _{aft}$ and $\Delta Q _{fwd}$ as shown in Fig B.2.10) are to be generated by applying vertical load at the frame positions as shown in Fig B.2.11. It is to be noted that vertical correction loads are not to be applied to any transverse tight bulkheads, any frames forward of the forward tank and any frames aft of the aft tank of the FE model. The sum of the total vertical correction loads applied is equal to zero.

#### 2.5.3.2

The required adjustment in shear forces at the aft and forward transverse bulkheads of the middle tank of the FE model in order to generate the required shear forces at the bulkheads are given by:
$\Delta Q _{aft}$ = - $Q _{targ}$ - $Q _{aft}$
$\Delta Q _{fwd}$ = $Q _{targ}$ - $Q _{fwd}$
Where:
$\Delta Q _{aft}$ required adjustment in shear force at aft bulkhead of middle tank based on the maximum absolute shear force at the bulkhead
$\Delta Q _{fwd}$ required adjustment in shear force at fore bulkhead of the middle tank based on the maximum absolute shear force at the bulkhead
$Q _{targ}$ required shear force value to be achieved at forward bulkhead of middle tank, see 2.4.5.
$Q _{aft}$ shear force due to local loads at aft bulkhead of middle tank, see 2.5.2
$Q _{fwd}$ shear force due to local loads at fore bulkhead of middle tank, see 2.5.2

**Fig B.2.10<br>Position of Target Shear Force and Required Shear Force Adjustment at Transverse Bulkhead Positions**

| Condition | Target |   |   | Aft Bkhd |   | Fore Bkhd |   |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Condition | BM | SF | Bkhd<br>pos | SF | $\Delta Q _{aft}$ | SF | $\Delta Q _{fwd}$ |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image941.png) | *Hog* | *-ve* | *Fore* | *-Q_targ* | *-Q_targ* *- Q_aft* | *Q_targ* *(-ve)* | *Q_targ* *– Q_fwd* |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image942.png) | *Hog* | *-ve* | *Fore* | *-Q_targ* | *-Q_targ* *– Q_aft* | *Q_targ* *(-ve)* | *Q_targ* *– Q_fwd* |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image943.png) | *Sag* | *+ve* | *Fore* | *-Q_targ* | *-Q_targ* *- Q_aft* | *Q_targ* *(+ve)* | *Q_targ* *- Qf_wd* |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image944.png) | *Sag* | *+ve* | *Fore* | *-Q_targ* | *-Q_targ* *- Q_aft* | *Q_targ* *(+ve)* | *Q_targ* *- Q_fwd* |
| #underline{Note}<br>For definition of symbols, see 2.5.3.2. |   |   |   |   |   |   |   |

| Fig B.2.11<br>Distribution of Adjusting Vertical Force at Frames and Resulting Shear Force Distributions |
| --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image945.png) |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image946.png)<br>Shear Force distribution due to adjusting vertical force at frames |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image947.png) |
| #underline{Note}<br>For definition of symbols, see Table B.2.7. |

#### 2.5.3.3

The value of the vertical loads to be applied to each frame to generate the increase in shear force at the bulkheads maybe calculated using a simple beam model. For the case where an uniform frame spacing is used within each tank, the amount of vertical force to be distributed at each frame may be calculated in accordance with Table B.2.7. The length and frame spacing of individual cargo tanks may be different.

**Table B.2.7<br>Formulae for Calculation of Vertical Loads for Adjusting Vertical Shear Forces**

| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image948.png) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image949.png) |
| --- | --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image950.png) |   |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image951.png) |   |
| Where:<br>$l _{1}$ length of aft cargo tank of model<br>$l _{2}$ length of middle cargo tank of model<br>$l _{3}$ length of forward cargo tank of model<br>$\Delta Q _{aft}$ required adjustment in shear force at aft bulkhead of middle tank, see Fig B.2.10<br>$\Delta Q _{fwd}$ required adjustment in shear force at fore bulkhead of middle tank, see Fig B.2.10<br>$F$ end reactions due to application of vertical loads to frames, see 2.5.3<br>$W1$ total evenly distributed vertical load applied to aft tank of FE model, $(n _{1} -1) \delta w _{1}$<br>$W2$ total evenly distributed vertical load applied to middle tank of FE model, $(n _{2} -1) \delta w _{2}$<br>$W3$ total evenly distributed vertical load applied to forward tank of FE model, $(n _{3} -1) \delta w _{3}$<br>$n _{1}$ number of frame spaces in aft cargo tank of FE model<br>$n _{2}$ number of frame spaces in middle cargo tank of FE model<br>$n _{3}$ number of frame spaces in forward cargo tank of FE model<br>$\delta w _{1}$ distributed load at frame in aft cargo tank of FE model<br>$\delta w _{2}$ distributed load at frame in middle cargo tank of FE model<br>$\delta w _{3}$ distributed load at frame in forward cargo tank of FE model<br>$\Delta l _{end}$ distance between end bulkhead of aft cargo tank to aft end of FE model<br>$\Delta l _{fo re}$ distance between fore bulkhead of forward cargo tank to forward end of FE model<br>$l$ total length of FE model (beam) including portions beyond end bulkheads:<br>= $l _{1} +l _{2} +l _{3} + \Delta l _{end} + \Delta l _{fo re}$ |   |
| #underline{Notes}<br>1. Positive direction of loads, shear forces and adjusting vertical forces in the formulae is in accordance with Fig B.2.10 and B.2.11.<br>2. $W 1$ + $W 3$ = $W 2$<br>3. Note that the above formulae are only applicable if an uniform frame spacing is used within each tank, see 2.5.3.3. The length and frame spacing of individual cargo tanks may be different. |   |

#### 2.5.3.4

The amount of adjusting load to be applied to the structural parts of each transverse frame section to generate the vertical load, $\delta w _{1}$, is to be in accordance with Fig B.2.12. This load is to be distributed at the finite element grid points of the structural parts. Where 4-node or 3-node finite plate elements are used, the load to be applied at each grid point of a plate element is given by:
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image952.png)
Where:
$F _{i-grid}$ load to be applied to the *i^th* FE grid point on the individual structural member under consideration, i.e. side shell, longitudinal bulkheads and bottom girders, inner hull longitudinal bulkheads, hopper plates, upper slope plates of inner hull and outboard girders as defined in Fig B.2.12
$A _{i-elem-n et50}$ sectional area of each plate element in the individual structural member under consideration (see Fig B.2.12), which is connected to the *i^th* grid point
$n$ number of plate elements connected to the *i^th* grid point
$F _{s}$ total load applied to individual structural member under consideration, as specified in Fig B.2.12
$A _{s-n et50}$ plate sectional area of the individual structural member under consideration, i.e. side shell, longitudinal bulkheads, bottom girders, inner hull longitudinal bulkheads, hopper plates, upper slope plates of inner hull and outboard girders as defined in Fig B.2.12

**Fig B.2.12<br>Distribution of Adjusting Load on a Transverse Section**

| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image953.png) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image954.png) |   |
| --- | --- | --- |
| Structural member |   | Applied load $F _{s}$ |
| Side shell |   | $f \cdot \delta w _{i}$ |
| Longitudinal bulkhead including bottom girder beneath |   | $f \cdot \delta w _{i}$ |
| Inner hull longitudinal bulkhead (vertical part) |   | $f \cdot \delta w _{i} \cdot \frac{A _{Ih-n et50}}{A _{2-n et50}}$ |
| Hopper plate |   | $f \cdot \delta w _{i} \cdot \frac{A _{Hp-n et50}}{A _{2-n et50}}$ |
| Upper slope plating of inner hull |   | $f \cdot \delta w _{i} \cdot \frac{A _{Usp-n et50}}{A _{2-n et50}}$ |
| Outboard girder |   | $f \cdot \delta w _{i} \cdot \frac{A _{Og-n et50}}{A _{2-n et50}}$ |
| Where<br>$\delta w _{i}$ vertical load to be applied to each transverse frame section, see 2.5.3.3 and Table B.2.7<br>$f$ shear force distribution factor of structural part calculated at the mid-tank position in accordance with Table B.2.8<br>$A _{Ih-n et50}$ plate sectional area of individual inner hull longitudinal bulkhead<br>$A _{Hp-n et50}$ plate sectional area of individual hopper plate<br>$A _{Usp-n et50}$ Plate sectional area of individual upper slope plate of inner hull<br>$A _{Og-n et50}$ plate sectional area of individual outboard girder<br>$A _{2-n et50}$ plate sectional area calculated in accordance with Table B.2.8 |   |   |
| #underline{Note}<br>1. Adjusting load is to be applied in plane to the hopper slope plate and upper slope plate of inner hull.<br>2. Adjusting load given is to be applied to individual structural member. |   |   |

**Table B.2.8<br>Shear Force Distribution Factors**

| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image955.png) | Side shell | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image956.png) |
| --- | --- | --- |
|   | Inner hull | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image957.png) |
|   | CL longitudinal bulkhead | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image958.png) |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image959.png) | Side shell | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image960.png) |
|   | Inner hull | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image961.png) |
|   | Longitudinal bulkhead | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image962.png) |
| Where:<br>$A _{1-n et50}$ plate sectional area of individual side shell (i.e. on one side), including bilge<br>$A _{2-n et50}$ plate sectional area of individual inner hull longitudinal bulkhead (i.e. on one side), including hopper slope plate, double bottom side girder in way and, where fitted, upper slope plating of inner hull.<br>$A _{3-n et50}$ plate sectional area of individual longitudinal bulkhead, including double bottom girder in way |   |   |
| #underline{Note}<br>1. Where part of the structural member is not vertical, the area is to be calculated using the projected area in the vertical direction.<br>2. All plate areas are to be calculated based on the modelled thickness of the cargo tank FE model, see 2.2.1.5.<br>3. For corrugated longitudinal bulkheads, the corrugation thickness for the calculation of shear force distribution factor, $f$, is to be corrected according to Sec 4/2.6.4. |   |   |

- **2.5.4** Procedure to adjust vertical and horizontal bending moments

#### 2.5.4.1

An additional vertical bending moment is to be applied at both ends of the cargo tank finite element model to generate the required vertical bending moment in the middle tank of the model. This end vertical bending moment can be calculated as follows:
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image963.png)
Where:
*M_v-end* additional vertical bending moment to be applied at both ends of finite element model
*M_v-targ* required hogging (positive) or sagging (negative) vertical bending moment, as specified in 2.4.5
*M_v-peak* maximum or minimum bending moment within the length of the middle tank due to the local loads described in 2.5.2.3 and the additional vertical loads applied to generate the required shear force, see 2.5.3. *M_v-peak* is to be taken as the maximum bending moment if *M_v-targ* is hogging (positive) and as the minimum bending moment if *M_v-targ* is sagging (negative). *M_v–peak* can be obtained from FE analysis. Alternatively, *M_v-peak* may be calculated as follows based on a simply supported beam model:
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image964.png)
*M_o* vertical bending moment at position *x*, due to the local loads described in 2.5.2.3.
*M_lineload* vertical bending moment at position *x*, due to application of vertical line loads at frames to generate required shear force, see 2.5.3
*F* reaction force at ends due to application of vertical loads to frames, see 2.5.3
*x* longitudinal position of frame in way of the middle tank of FE model from end, see 2.5.4.2

#### 2.5.4.2

For beam and oblique sea load cases, an additional horizontal bending moment is to be applied at the ends of the cargo tank FE model to generate the required horizontal bending moment at a section within the length of the middle tank of the model. The additional horizontal bending moment can be calculated as follows:
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image965.png)
Where:
*M_h-end* additional horizontal bending moment to be applied to ends of FE model
*M_h-targ* required positive or negative horizontal bending moment, see 2.4.6
*M_h-peak* maximum or minimum horizontal bending moment within the length of the middle tank due to the local loads described in 2.5.2.3. *M_h-peak* is to be taken as the maximum horizontal bending moment if *M_h-targ* is positive (starboard side in tension) and as the minimum horizontal bending moment if *M_h-targ* is negative (port side in tension).

#### 2.5.4.3

The vertical and horizontal bending moments should be calculated over the length of the middle tank of the FE model to identify the position and value of each maximum/minimum bending moment as specified in 2.5.4.1 and 2.5.4.2.

#### 2.5.4.4

The additional vertical bending moment, *M_v-end*, and horizontal bending moment, *M_h-end*, are to be applied to both ends of the cargo tank model. The bending moments may be applied by either of the methods described in 2.5.4.5 and 2.5.4.6.

#### 2.5.4.5

The vertical and horizontal bending moments may be applied at the model ends by distributing axial nodal forces to all longitudinal elements according to the simple beam theory as follows:
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image966.png) for vertical bending moment
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image967.png) for horizontal bending moment
Where:
*M_v-end* vertical bending moment to be applied to the ends of the model
*M_h-end* horizontal bending moment to be applied to the ends of the model
*(F_x)_i* axis force applied to a node of the *i^th* element
*I_y-net50* hull girder vertical moment of inertial of the end section about its horizontal neutral axis
*I_z-net50* hull girder horizontal moment of inertial of the end section about its vertical neutral axis (normally centreline)
*z_i* vertical distance from the neutral axis to the centre of the cross sectional area of the *i^th* element
*y_i* horizontal distance from the neutral axis to the centre of the cross sectional area of the *i^th* element
*A_i-net50* cross sectional area of the *i^th* element
*n_i* number of nodal points of *i^th* element on the cross section, *n_i* = 2 for 4-node plate element

#### 2.5.4.6

The vertical and horizontal bending moments may alternatively be applied to an independent grid point at the intersection of the vertical neutral axis (normally centreline) and the horizontal neutral axis, see Fig B.2.13. All nodal points of the longitudinal elements on the end section are to be rigidly linked to the independent point in $\theta_y$ (for vertical bending), $\theta_z$ (for horizontal bending) and $\delta_x$. This independent point is not to be connected to the model except by the rigid link. The rigid links are to maintain the end plane of the model in keeping plane under the action of the applied bending moment, which is equivalent to imposing a prescribed displacement to the nodal points in accordance with the simple beam theory.

#### 2.6 Boundary Conditions

- **2.6.1** General

#### 2.6.1.1

All boundary conditions described in this section are in accordance with the global co-ordinate system defined in Sec 4/1.4. The boundary conditions to be applied at the ends of the cargo tank FE model are given in Table B.2.9. The analysis may be carried out by applying all loads to the model as a complete load case or by combining the stress responses resulting from several separate sub-cases.

#### 2.6.1.2

Ground spring elements, i.e. spring elements with one end constrained in all 6 degrees of freedom, with stiffness in global y degree of freedom are to be applied to the grid points along deck, inner bottom and bottom shell as shown in Fig B.2.13.

#### 2.6.1.3

Ground spring elements with stiffness in global z degree of freedom are to be applied to the grid points along the vertical part of the side shells, inner hull longitudinal bulkheads and oil-tight longitudinal bulkheads as shown in Fig B.2.13.

**Fig B.2.13<br>Spring Constraints at Model Ends**

| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image968.png) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image969.png) |
| --- | --- |

**Table B.2.9<br>Boundary Constraints at Model Ends**

| Location | Translation |   |   | Rotation |   |   |
| --- | --- | --- | --- | --- | --- | --- |
| Location | $\delta _{x}$ | $\delta _{y}$ | $\delta _{z}$ | $\theta _{x}$ | $\theta _{y}$ | $\theta _{z}$ |
| Aft End |   |   |   |   |   |   |
| Aft end<br>(all longitudinal elements) | *RL* | - | - | - | *RL* | *RL* |
| Independent<br>Point aft end, see Figure B.2.13 | Fix | - | - | - | *M_v-end* | *M_h-end* |
| Deck, inner bottom and outer shell | - | Springs | - | - | - | - |
| Side, inner skin and longitudinal bulkheads | - | - | Springs | - | - | - |
| Fore End |   |   |   |   |   |   |
| Fore end<br>(all longitudinal elements) | *RL* | - | - | - | *RL* | *RL* |
| Independent point fore end, see Figure B.2.13 | - | - | - | - | *M_v-end* | *M_h-end* |
| Deck, inner bottom and outer shell | - | Springs | - | - | - | - |
| Side, inner skin and longitudinal bulkheads | - | - | Springs | - | - | - |
| Where:<br>- no constraint applied (free)<br>*RL* nodal points of all longitudinal elements rigidly linked to independent point at neutral axis on centreline |   |   |   |   |   |   |
| #underline{Note}<br>1. All translation and rotation displacements are in accordance with the global coordinate system defined in Sec 4/1.4.<br>2. Where *M_h-end* is not applied, the independent points at the fore and aft ends are to be free in $\theta _{z}$.<br>3. Where *M_v-end* is not applied, the independent points at the fore and aft ends are to be free in $\theta _{y}$.<br>4. Where no bending moment is applied, the independent points at the fore and aft ends are to be free in $\theta _{y}$ and $\theta _{z}$.<br>5. Where bending moment is applied as nodal forces, the independent points at the fore and aft ends are to be free in the corresponding degree of freedom of rotations (i.e. $\theta _{y}$ and/or $\theta _{z}$). |   |   |   |   |   |   |

- **2.6.2** Calculation of spring stiffness

#### 2.6.2.1

The stiffness, *c*, of individual spring elements for each structural member, to be applied at each end of the cargo tank model, is given by:
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image970.png) N/mm
Where:
*A_s-net50* shearing area of the individual structural member under consideration, i.e. plating of deck, inner bottom, bottom shell, side shell, inner hull longitudinal bulkheads or oil-tight longitudinal bulkhead. *A_s-net50* is to be calculated based on the thickness of the cargo tank finite element model for areas indicated in Table B.2.10 for the appropriate structural member under consideration, in $\mathrm{mm} ^{2}$
*v* Poisson's ratio of the material
*l_tk* length of cargo tank, between bulkheads of the middle tank of the FE model, in $\mathrm{mm} ^{2}$
*E* Modulus of Elasticity, in $\mathrm{N}/mm ^{2}$
*n* number of nodal points to which the spring elements are applied to the structural member under consideration

**Table B.2.10<br>Shear Areas to be Considered for the Calculation of Spring Stiffness**

| Vertical springs |   |   |   |
| --- | --- | --- | --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image971.png) | Side |   | Area of side shell plating, including bilge |
|   | Inner hull longitudinal bulkheads |   | Area of inner skin plating, including hopper slope plate and double bottom side girder in way |
|   | Longitudinal bulkheads |   | Area of longitudinal bulkhead plating, including double bottom girder in way |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image972.png) | #underline{Note}<br>Where part of the structural member is not vertical, the area is to be calculated using the projected area in the vertical direction. |   |   |
| Horizontal springs |   |   |   |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image973.png) | Deck | Area of deck plating |   |
|   | Inner bottom | Area of inner bottom plating, including hopper slope plate and horizontal stringer in way |   |
|   | Bottom shell | Area of bottom shell plating, including bilge |   |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image974.png) | #underline{Note}<br>Where part of the structural member is not horizontal the area is to be calculated using the projected area in the horizontal direction. |   |   |

#### 2.6.2.2

For vertical corrugated longitudinal bulkheads, the corrugation thickness for the calculation of spring stiffness, *c*, shall be calculated according to Sec 4/2.6.4.

#### 2.6.2.3

Alternatively, rod elements may be used instead of spring elements, the equivalent cross section area of the rod is $\left( c \cdot l \right) /E$, where *l* is the length of the rod. One end of the rod is to be constrained in all 6 degrees of freedom.

#### 2.7 Result Evaluation

- **2.7.1** General

#### 2.7.1.1

Verification of result against acceptance criteria is to be carried out for structural members within longitudinal extent shown in Fig B.2.14, which includes the middle tanks of the three cargo tanks FE model and the region forward and aft of the middle tanks up to the extent of the transverse bulkhead stringer and buttress structure. For the strength assessment of tanks in the midship cargo region, stress level and buckling capability of longitudinal hull girder structural members, primary supporting structural members and transverse bulkheads are to be verified. For the assessment of required strengthening in way of transverse bulkheads against hull girder shear load, stress level and buckling capability of inner hull longitudinal bulkheads including upper sloped plate where fitted, side shell, hopper, bottom girders and longitudinal bulkheads are to be verified.

#### 2.7.1.2

Assessment of results is to be carried out for the standard load cases specified in 2.3.1, and any other load cases specially considered as required by Sec 9/2.2.3.

| Fig B.2.14<br>Extent of FE Model for Verification against Acceptance Criteria |
| --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image975.png) |

- **2.7.2** Stress assessment

#### 2.7.2.1

Stresses are not to exceed the permissible values given in Sec 9/2.2.5.

#### 2.7.2.2

The maximum permissible stresses are based on the mesh sizes and element types described in 2.2.

#### 2.7.2.3

The von Mises stress, *σ_vm*, is to be calculated based on the membrane direct and shear stresses of the plate element. Where shell elements are used, the stresses are to be evaluated at the mid plane of the element. Where plate elements are used, the stresses are to be evaluated at the element centroid.

#### 2.7.2.4

Except as indicated in 2.7.2.5, the element shear stress in way of openings in webs is to be corrected for loss in shear area in accordance with the following formula. The corrected element shear stress is to be used to calculate the von Mises stress of the element for verification against the acceptance criteria.
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image976.png)
Where:
*t_cor* corrected element shear stress
*h* height of web of girder in way of opening, see Fig B.2.8. Where the geometry of the opening is modelled, h is to be taken as the net height with the height of the modelled opening deducted.
*t_mod-net50* modelled web thickness in way of opening, see Table B.2.2.
*A_s-net50* actual effective shear area of web, including area lost due to slots for stiffeners, calculated in accordance with Sec 4/2.5. The thickness of the web is to be based on net thickness obtained by deducting 0.5 *t_corr* from the gross thickness
*t_elem* element shear stress before correction

#### 2.7.2.5

Correction of element shear stress due to presence of openings is not required provided that:

- **(a)** all slots for local support stiffeners are fitted with lugs or collar plates;
- **(b)** the difference between the modelled shear area of the plate and the actual effective shear area, As-net50calculated in accordance with Sec 4/2.5.1, is less than 20 % of the modelled shear area, and
- **(c)** the yield utilisation factor is less than 80% of the permissible yield utilisation factor given in Sec 9/Table 9.2.1.

#### 2.7.2.6

Where the corrugation is not modelled with its exact geometric shape, the corrected axial stress in the flange of the corrugation, *s_fl-act*, is to be taken as the greater of:
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image977.png)
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image978.png)
Where:
*s_fl-FEM* axial stress obtained from the finite element analysis, see Fig B.2.15
*Z_corr-FEM-net50* is the section modulus of the modelled corrugation calculated in accordance with Fig B.2.15
*Z_corr-act-net50* is the section modulus of the actual corrugation calculated in accordance with Fig B.2.15
*l_corr-act* length of corrugation section, as given in Fig B.2.15
*l_corr-FEM* length of corrugation section, as given in Fig B.2.15

| Fig B.2.15<br>Axial Bending Stress in Flange Corrugation |
| --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image979.png) |
| #underline{Note}<br>*l_corr-act* = length of corrugation section, for the calculation of *Z_corr-act-net50*<br>*l_corr-FEM* = length of corrugation section, for the calculation of *Z_corr-FEM-net50* |

- **2.7.3** Buckling assessment

#### 2.7.3.1

Buckling capability is to be assessed for the plating and stiffened panels of longitudinal hull girder structural members, primary support members and transverse bulkheads, including deck, double side, side, bottom, double bottom, hopper, transverse and vertical web frames, stringers, transverse and longitudinal bulkhead structures. Buckling capability of curved panels (e.g. bilge), face plate of primary support members and tripping brackets is not assessed based on stress result obtained by the finite element analysis.

#### 2.7.3.2

The utilisation factor against buckling for all plates and stiffened panels is not to exceed the permissible values given in Sec 9/2.2.5. The method for carrying out buckling assessment of plates and stiffened panels is described in Appendix D/5.

#### 2.7.3.3

The buckling assessment is to be based on the stresses obtained from the finite element analysis in conjunction with buckling capacity model based on net thickness obtained by deducting the full corrosion addition, *t_corr*, and any Owner’s extras from the proposed thickness. This thickness deduction applies to all plating, stiffener webs and face plates.

#### 2.7.3.4

The buckling assessment is to be based on membrane stress evaluated at the centroid of the plate elements. Where shell elements are used, stresses at the mid plane of the element are to be used for the buckling assessment.

#### 2.7.3.5

The combined interaction of bi-axial compressive stresses, shear stress and lateral pressure loads are to be considered in the buckling calculation. Where a stress correction is to be applied to the finite element stresses as required by 2.7.2, the buckling assessment is to be based on the corrected stresses.

#### 2.7.3.6

For tankers with a cross tie arrangement, the pillar buckling capability of the cross tie structure is to be assessed based on the buckling formulae given in Sec 10/3.5.1. The average axial compressive stress at the mid span of the cross tie in the ship's transverse direction, weighted by cross section area, is to be used for the buckling assessment.

#### 2.7.3.7

In the absence of a suitable advanced buckling method described in Appendix D/5 for the modelling of bulkhead corrugation, assessment of local buckling of unit corrugation flanges is to be in accordance with Sec 10/3.5.2 and criteria given in Sec 9/2.2.5. The assessment is to be based only on uni-axial stress (membrane stress evaluated at element centroid) parallel to the corrugation knuckles. Averaged stress between elements is not to be used. For the part of the corrugated plate flange from the lower bulkhead stool top to a level of *s*/2 above, where *s* is the breadth of the flange, the stress used for the buckling assessment needs not be taken as greater than the value obtained at *s*/2 above the bulkhead stool top. The stress value at *s*/2 may be obtained by interpolation if the stress value cannot be obtained directly from a plate element.

#### 2.7.3.8

In the absence of a suitable advanced buckling assessment method described in Appendix D/5 for the modelling of panel with opening, local buckling of web plates of primary support members in way of openings is to be assessed in accordance with Sec 10/3.4 based on acceptance criteria on buckling utilisation factor given in Sec 9/2.2.5. The assessment is to be based on FE membrane stress evaluated at the centroid of plate elements. Stresses in the area of the web required for buckling assessment are to be obtained as averaged stresses of the plate elements within the required area. Stress obtained from either the cargo tank analysis or local fine mesh analysis may be used for the assessment. Where the effect of opening is not taken into account in the cargo tank analysis, the stresses obtained from the finite element analysis are to be corrected in accordance with 2.7.2.4 and 2.7.2.5.


### 3 Local Fine Mesh Structural Strength Analysis

#### 3.1 General

- **3.1.1** Application

#### 3.1.1.1

For tankers of conventional arrangements, finite element fine mesh analysis of structural details is to be in accordance with the requirements given in this section.

#### 3.1.1.2

Additional requirements of fine mesh analysis are to be in accordance with Sec 9/2.3.1.3 and Sec 9/2.3.1.4.

- **3.1.2** Transverse web frame and wash bulkhead

#### 3.1.2.1

Upper hopper knuckle connections as indicated in Fig B.3.1 are to be evaluated by fine mesh analysis on a typical transverse web frame in the middle tank of the cargo tank model. Main bracket toes and openings as indicated in Fig B.3.1 are to be evaluated by fine mesh analysis if the screening criteria given in 3.1.6 are not complied with.

#### 3.1.2.2

Where a wash bulkhead is fitted, main bracket toes and openings of the transverse and vertical webs as indicated in Fig B.3.1 are to be evaluated by fine mesh analysis if the screening criteria given in 3.1.6 are not complied with.

#### 3.1.2.3

The web frame which indicates highest von Mises stresses in way of each structural detail from the cargo tank analysis is to be selected for the fine mesh analysis.

| Fig B.3.1<br>Areas Requiring Consideration for Fine Mesh Analysis on a Typical Transverse Web Frame, Wash Bulkhead and Web Frame adjacent to Transverse Bulkhead |
| --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image980.png) |

| Fig B.3.1 (Continued)<br>Areas Requiring Consideration for Fine Mesh Analysis on a Typical Transverse Web Frame, Wash Bulkhead and Web Frame adjacent to Transverse Bulkhead |
| --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image981.png) |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image982.png) |

**Fig B.3.1 (Continued)<br>Areas Requiring Consideration for Fine Mesh Analysis on a Typical Transverse Web Frame, Wash Bulkhead and Web Frame adjacent to Transverse Bulkhead**

| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image983.png) |   |   |
| --- | --- | --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image984.png) | Upper hopper knuckle | Fine mesh analysis of upper hopper knuckle is required for cargo tank typical web frame, see 3.1.2. Fine mesh analysis is not required for upper hopper knuckles on web frame adjacent to transverse bulkhead. |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image985.png) | Bracket toes | Fine mesh analysis is to be carried out where the screening criteria given in 3.1.6 are not complied with |
| ![](images/image986.png) | Openings (shaded regions) | Fine mesh analysis is to be carried out for all openings in shaded regions where the screening criteria given in 3.1.6 are not complied with |
| ![](images/image987.png) | Openings (un-shaded regions) | Fine mesh analysis or evaluation based on screening criteria given in 3.1.6 is not required for openings in un-shaded regions if:<br>• $h _{o}$/$h$ < 0.35 and $g _{o}$ < 1.2, and,<br>• each end of the opening forms a semi circle arc (i.e. radius of opening equal to *b*/2).<br>where $h _{o}$, $h$ and $g _{o}$ are defined in Table B.2.2 and *b* is the smallest of the length and breadth of the opening. Other openings in the un-shaded regions are subjected to fine mesh analysis where the screening criteria given in 3.1.6 are not complied with. |

**Fig B.3.2<br>Areas Requiring Consideration for Fine Mesh Analysis on Horizontal Stringer and Transverse Bulkhead to Double Bottom Connections**

| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image988.png) |   |   |   |   |
| --- | --- | --- | --- | --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image989.png) |   |   | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image990.png) | Area requiring consideration for fine mesh analysis |
|   |   |   | Fine mesh analysis is to be carried out where the screening criteria given in 3.1.6 are not complied with. |   |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image990.png) | Bracket toes and heels | Fine mesh analysis is to be carried out where the screening criteria given in 3.1.6 are not complied with |   |   |
| ![](images/image986.png) | Openings (shaded regions) | Fine mesh analysis is to be carried out for all openings in shaded regions where the screening criteria given in 3.1.6 are not complied with |   |   |
| ![](images/image987.png) | Openings (un-shaded regions) | Fine mesh analysis or evaluation based on screening criteria given in 3.1.6 is not required for openings in un-shaded regions if:<br>• $h _{o}$/$h$ < 0.35 and $g _{o}$ < 1.2, and,<br>• each end of the opening forms a semi circle arc (i.e. radius of opening equal to *b*/2).<br>where $h _{o}$, $h$ and $g _{o}$ are defined in Table B.2.2 and *b* is the smallest of the length and breadth of the opening. Other openings in the un-shaded regions are subjected to fine mesh analysis where the screening criteria given in 3.1.6 are not complied with. |   |   |

- **3.1.3** Transverse bulkhead stringers, buttress and adjacent web frame

#### 3.1.3.1

Fine mesh analysis is to be carried out for the following locations where the screening criteria given in 3.1.6 are not complied with:

- **(a)** main bracket toes, heels and openings on horizontal stringers of a transverse bulkhead specified in Fig B.3.2. The stringers of the forward and aft transverse bulkheads of the middle tank of the FE model which indicate highest von Mises stresses in way of the structural details from the cargo tank analysis is to be selected for the fine mesh analysis.
- **(b)** main bracket toes and openings on transverse bulkhead to double bottom connection or buttress structure specified in Fig B.3.2. The double bottom connection/buttress structure in way of the forward and aft transverse bulkheads of the middle tank of the FE model which indicates highest von Mises stresses in way of the structural details from the cargo tank analysis is to be selected for the fine mesh analysis.
- **(c)** main bracket toes and openings specified in Fig B.3.1 on a web frame adjacent to the transverse bulkhead. Both web frames in way of the horizontal stringers of the forward and aft transverse bulkheads of the middle tank of the cargo tank FE model are to be considered. The web frame which indicates highest von Mises stresses in way of the structural details from the cargo tank analysis is to be selected for the fine mesh analysis.

#### 3.1.3.2

Where the stress level at the heel connection of the transverse bulkhead horizontal stringer to the side horizontal girder exceeds the permissible criteria, it is recommended that a backing bracket be fitted in accordance with Appendix C/2.5 to reduce the stresses.

- **3.1.4** Deck, double bottom longitudinal and adjoining transverse bulkhead vertical stiffeners

#### 3.1.4.1

End connections and attached web stiffeners of the following structural members are to be assessed:

- **(a)** at least one pair of inner and outer bottom longitudinal stiffeners and adjoining vertical stiffener of transverse bulkhead
- **(b)** at least one longitudinal stiffener on deck and adjoining vertical stiffener of transverse bulkhead

#### 3.1.4.2

The selection of the longitudinal and vertical stiffeners to be analysed is to be based on the maximum relative deflection between supports, e.g. between floor and transverse bulkhead. Where there is a significant variation in end connection arrangement and scantlings between stiffeners, analysis of additional stiffeners may be required. Fig B.3.3 shows the areas that require fine mesh analysis in way of deck, inner bottom and bottom longitudinal and transverse bulkhead vertical stiffeners.

- **3.1.5** Corrugated bulkheads

#### 3.1.5.1

Where no shedder plate or shedder plate without a gusset plate is fitted to a corrugated transverse or longitudinal corrugated bulkhead, connection of corrugation and below supporting structure to lower stool shelf plate, as shown in Fig B.3.4*,* is to be evaluated by fine mesh analysis*.* Where no lower stool is fitted, connection of corrugation and below supporting structure to inner bottom plate is to be evaluated by fine mesh analysis.

#### 3.1.5.2

Where shedder plate with a gusset plate is fitted to a corrugated transverse or longitudinal corrugated bulkhead, connection of the corrugation at the upper corner of the gusset plate is to be evaluated by fine mesh analysis.

#### 3.1.5.3

The selection of the location of the corrugation unit for fine mesh analysis is to be based on the stress result from the cargo tank analysis. The location with the highest von Mises stress in way of the corrugation connection is to be selected for the analysis.

#### 3.1.5.4

Where transverse and longitudinal corrugated bulkheads are of different arrangements or scantlings, the fine mesh analysis is to be carried out for both bulkheads.

#### 3.1.5.5

Where the stress level at the connection of corrugation to the lower stool exceeds the permissible criteria, it is recommended that shedder plate and gusset plate be fitted in accordance with Appendix C/2.5 to reducethe stresses. See Sec 8/2.5.7.9 for required arrangement of supporting structure for corrugated bulkhead without a lower stool.

**Fig B.3.3<br>Areas Requiring Fine Mesh Analysis on Deck, Inner and Outer Bottom Longitudinals**

| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image991.png) |   |   |
| --- | --- | --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image992.png) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image993.png) | Area requiring fine mesh analysis |

| Fig B.3.4<br>Areas Requiring Fine Mesh Analysis at Connections of Corrugated Bulkhead to Bottom Stool |
| --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image994.png) |
| #underline{Note}<br>Exact location of corrugation unit to be examined using fine mesh analysis is to be selected based on stress result from cargo tank analysis. |

- **3.1.6** Screening criteria for Fine Mesh Analysis

#### 3.1.6.1

The criteria given in this section are intended to identify areas that require to be investigated by means of fine mesh finite element analysis. These criteria apply to openings, bracket toes and heels of transverse web frames, vertical and transverse webs of wash bulkheads, horizontal stringers of transverse bulkhead and adjoining side horizontal girders, buttress and bottom girders.

#### 3.1.6.2

Where the criteria given in this section for the structural detail are complied with, fine mesh finite element analysis of the structural detail may be waived with the exception of 3.1.6.3*.* The compliance with these criteria is to be verified for all finite element load cases.

#### 3.1.6.3

Large openings, for which their geometry is required to be represented in the cargo tank FE model in accordance with Table B.2.2, are to be investigated by fine mesh analysis.

| Table B.3.1<br>Fine Mesh Analysis Screening Criteria for Openings in Primary Support Members |
| --- |
| A fine mesh finite element analysis is to be carried out where:<br>$\lambda _{y}$ > 1.7 (load combination S + D)<br>$\lambda _{y}$ > 1.36 (load combination S) |
| Where:<br>$\lambda _{y}$ yield utilisation factor<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image995.png)<br>$C _{h}$ ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image996.png)<br>for openings in vertical web and horizontal girder of wing ballast tank, double bottom floor and girder and horizontal stringer of transverse bulkhead<br>= 1.0 for opening in web of main bracket and buttress (see figures below)<br>$r$ radius of opening, in mm<br>$h _{0}$ height of opening parallel to depth of web, in mm<br>$l _{0}$ length of opening parallel to girder web direction, in mm<br>$h$ height of web of girder in way of opening, in mm<br>$\sigma _{x}$ axial stress in element *x* direction determined from cargo tank FE analysis according to the coordinate system shown, in $\mathrm{N}/mm ^{2}$<br>$\sigma _{y}$ axial stress in element *y* direction determined from cargo tank FE analysis according to the coordinate system shown, in $\mathrm{N}/mm ^{2}$<br>$\tau _{xy}$ element shear stress determined from cargo tank FE analysis, in $\mathrm{N}/mm ^{2}$,<sup>(2)</sup><br>$k$ higher strength steel factor, as defined in Sec 6/1.1.4 but not to be taken as less than 0.78 for load combination S+D |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image997.png) |

**Table B.3.1 (Continued)<br>Fine Mesh Analysis Screening Criteria for Openings in Primary Support Members**

| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image998.png) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image999.png) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1000.png) |
| --- | --- | --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1001.png) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1002.png) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1003.png)<br>Individual element in web to be verified against criteria |
| #underline{Notes}<br>1. For opening where the modelled shear area in way of the opening is different from the actual net shear area the element shear stress is to be adjusted using the formula given in B.2.7.2.4 prior to the evaluation of yield utilisation factor for verification against the screening criteria.<br>2. Where the geometry of the opening is required to be modelled in accordance with Table B.2.2, fine mesh FE analysis is to be carried out to determine the stress level. The screening criteria given in this table are not applicable.<br>3. Screening criteria is only valid if the cargo tank finite element analysis and the derivation of element stresses is carried out in accordance with B/2. |   |   |

**Table B.3.2<br>Fine Mesh Analysis Screening Criteria for Bracket Toes of Primary Support Members**

| A fine mesh finite element analysis is to be carried out where:<br>$\lambda _{y}$ > 1.5 (load combination S + D)<br>$\lambda _{y}$ > 1.2 (load combination S) |   |
| --- | --- |
| Where:<br>$\lambda _{y}$ yield utilisation factor<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1004.png)<br>$C _{a}$ ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1005.png)<br>$b _{1}$, $b _{2}$ height of plate element in way of bracket toe in cargo tank FE model, in mm<br>$A _{b ar-n et50}$ sectional area of bar element in cargo tank FE model representing the face plate of bracket, in $\mathrm{mm} ^{2}$<br>$\sigma _{b ar}$ bar element axial stress determined from cargo tank FE analysis, in $\mathrm{N}/mm ^{2}$<br>$\sigma _{vm}$ von Mises stress of plate element in way of bracket toe determined from cargo tank FE analysis, in $\mathrm{N}/mm ^{2}$<br>$t _{n et50}$ thickness of plate element in way of bracket toe, in mm<br>$R _{a}$ leg length distance in mm, not to be taken as greater than 1400 mm<br>$k$ higher strength steel factor, as defined in Sec 6/1.1.4, but not to be taken as less than 0.78 for load combination S+D |   |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1006.png) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1007.png) |
| #underline{Note}<br>1. Screening criteria is only valid if the cargo tank finite element analysis and the derivation of element stresses is carried out in accordance with B/2. |   |

| Table B.3.3<br>Fine Mesh Analysis Screening Criteria for Heels of Transverse Bulkhead Horizontal Stringers |
| --- |
| A fine mesh finite element analysis is to be carried out where:<br>$\lambda _{y}$ > 1.5 (load combination S + D)<br>$\lambda _{y}$ > 1.2 (load combination S) |
| Where:<br>$\lambda _{y}$ yield utilisation factor<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1008.png)<br>for heels at side horizontal girder and transverse bulkhead horizontal stringer, i.e. locations 1, 2 and 3 in figures.<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1009.png) for heel at longitudinal bulkhead horizontal stringer, i.e. location 4.<br>$\sigma _{x}$ axial stress in element *x* direction determined from cargo tank FE analysis in accordance with the coordinate system shown, in $\mathrm{N}/mm ^{2}$<br>$\sigma _{vm}$ von Mises stress of plate element in way of heel determined from cargo tank FE analysis, in $\mathrm{N}/mm ^{2}$<br>$k$ higher strength steel factor, as defined in Sec 6/1.1.4, but not to be taken as less than 0.78 for load combination S+D |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1010.png)<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1011.png) Individual element in web to be verified against criteria |
| #underline{Note}<br>1. Screening criteria is only valid if the cargo tank finite element analysis and the derivation of element stresses is carried out in accordance with B/2. |

#### 3.2 Structural Modelling

- **3.2.1** General

#### 3.2.1.1

Evaluation of detailed stresses requires the use of refined finite element mesh in way of areas of high stress. This fine mesh analysis can be carried out by means of separate local finite element model with fine mesh zones in conjunction with the boundary conditions obtained from the cargo tank model. Alternatively, fine mesh zones incorporated into the cargo tank model may be used.

#### 3.2.1.2

The extent of the local finite element model is to be such that the calculated stresses at the areas of interest are not significantly affected by the imposed boundary conditions and application of loads. The boundary of the fine mesh model is to coincide with primary support members, such as girders, stringers and floors, in the cargo tank model.

#### 3.2.1.3

The mesh size in the fine mesh zones is not to be greater than 50 mm × 50 mm. In general, the extent of the fine mesh zone is not to be less than 10 elements in all directions from the area under investigation.

#### 3.2.1.4

All plating within the fine mesh zone is to be represented by shell elements. A smooth transition of mesh density is to be maintained. The aspect ratio of elements within the fine mesh zone is to be kept as close to 1 as possible. Variation of mesh density within the fine mesh zone and the use of triangular elements are to be avoided. In all cases, the elements are to have an aspect ratio not exceeding 3. Distorted elements, with element corner angle less than 60° or greater than 120^°, are to be avoided. Stiffeners inside the fine mesh zone are to be modelled using shell elements. Stiffeners outside the fine mesh zones may be modelled using beam elements.

#### 3.2.1.5

The element inside the fine mesh zone is to be modelled based on the net thickness, obtained by deducting the full corrosion addition, *t_corr*, from the gross thickness. The structure outside the fine mesh zone is to be modelled based on the net thickness obtained by deducting half the corrosion addition, *0.5 t_corr*, from the gross thickness, as specified in 2.2.1.5, for use in the cargo tank FE analysis.

#### 3.2.1.6

Where fine mesh analysis is required for main bracket end connections, the fine mesh zone is to be extended at least 10 elements in all directions from the area of interest, see Fig B.3.5. The modelling scantlings in the fine mesh zone are to be in accordance with 3.2.1.5.

#### 3.2.1.7

Where fine mesh analysis is required for an opening, the first two layers of elements around the opening are to be modelled with mesh size not greater than 50 mm × 50 mm, based on the net thickness with deduction of full corrosion addition, *t_corr*,. The elements outside the first two layers are to be based on the net thickness with a deduction of corrosion addition, *0.5 t_corr*, see 3.2.1.5. A smooth transition from the fine mesh to the coarser mesh is to be maintained. Edge stiffeners which are welded directly to the edge of an opening are to be modelled with plate elements. Web stiffeners close to an opening may be modelled using rod or beam elements located at a distance of at least 50 mm from the edge of the opening. Typical fine mesh zone around an opening is shown in Fig B.3.6.

#### 3.2.1.8

Face plates of openings, primary support members and associated brackets are to be modelled with at least three elements across their width.

**Fig B.3.5<br>Fine Mesh Zone Around Bracket Toes**

| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1012.png) |   |
| --- | --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1013.png) | Fine mesh zone<br>Element size ≤ 50 mm × 50 mm<br>Extent - at least 10 elements in all directions<br>Face plate modelled by plate elements |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1014.png) |   |

**Fig B.3.6<br>Fine Mesh Zone Around an Opening**

| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1015.png) |   |
| --- | --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1016.png) | Fine mesh zone<br>Element size ≤ 50 mm × 50 mm |

- **3.2.2** Transverse web frames

#### 3.2.2.1

In addition to the requirements of 3.2.1, the modelling requirements in this sub-section are applicable to the analysis of typical transverse web frame.

#### 3.2.2.2

Where a FE sub model is used, the model is to have an extent of at least 1 + 1 web frame spaces, i.e. one web frame space extending either side of the transverse web frame under investigation. The transverse web frames forward and aft of the web frame under investigation need not be included in the sub model.

#### 3.2.2.3

The full depth and full breadth of the ship shall be modelled, see Fig B.3.7.

#### 3.2.2.4

Fig B.3.8 shows a close up view of the finite element mesh at the lower part of the vertical web and backing brackets.

| Fig B.3.7<br>Extent of Sub-Model for Fine Mesh Analysis of Web Frame Bracket Connections and Openings |
| --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1017.png) |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1018.png) |

| Fig B.3.8<br>Close-up View of Finite Element Mesh at the Lower Part of a Vertical Web Frame and Backing Brackets |
| --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1019.png) |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1020.png) |

- **3.2.3** Transverse bulkhead stringers, buttress and adjacent web frame

#### 3.2.3.1

In addition to 3.2.1, the modelling requirements in this sub-section are applicable to the analysis of transverse bulkhead and adjacent web frame as described in 3.1.3.

#### 3.2.3.2

Due to the structural interaction between the transverse bulkhead, horizontal stringers, web frames, deck and bottom, it is recommended that the FE sub-model represents a full section of the hull. Longitudinally, the ends of the model should at least be extended one web frame space beyond the areas that require investigation, see Fig B.3.9. The full breadth and depth of the ship should be modelled.

#### 3.2.3.3

Alternatively, it is acceptable to use a number of sub-models, as shown in Fig B.3.10, to analyse different parts of the structure. For the analysis of the transverse bulkhead horizontal stringers the full breadth of the ship should be modelled. For the analysis of buttress structure, the sub-model width should be at least 4 + 4 longitudinal spaces, i.e. four longitudinal spaces at each side of the buttress.

#### 3.2.3.4

Fig B.3.11 shows the finite element mesh on a Fig B.3.12 shows the sub-model for the analysis of buttress connections to transverse bulkhead and double bottom structure, and openings.

| Fig B.3.9<br>Extent of Sub-Model for Fine Mesh Analysis of Transverse Bulkhead and Adjacent Structure |
| --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1021.png) |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1022.png) |

| Fig B.3.10<br>Analysis of Transverse Bulkhead Structure Using Sub-Models |
| --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1023.png) |

| Fig B.3.11<br>Finite Element Mesh on Transverse Bulkhead Horizontal Stringer<br>(figure shows port side of model) |
| --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1024.png) |

| Fig B.3.12<br>Sub-Model for the Analysis of Buttress Connections to Bulkhead and Double Bottom Structure (figure shows port half of model) |
| --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1025.png) |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1026.png) |

- **3.2.4** Deck, double bottom longitudinal and adjoining transverse bulkhead vertical stiffeners

#### 3.2.4.1

The modelling requirements in this sub-section are applicable specifically to the analysis of longitudinal and vertical stiffener end connections and attached web stiffeners as described in 3.1.4.

#### 3.2.4.2

Where a local FE model is used, each end of the model is to be extended longitudinally at least two web frame spaces from the areas under investigation. The model width is to be at least 2 + 2 longitudinal spaces. Fig B.3.13 shows the longitudinal extent of the sub-model for the analysis of deck and double bottom longitudinal stiffeners and adjoining transverse bulkhead vertical stiffener.

#### 3.2.4.3

The prescribed displacements or forces obtained from the cargo tank FE model should be applied to all boundary nodes which coincide with the cargo tank model.

#### 3.2.4.4

The longitudinal and vertical stiffeners under investigation, including web, face plate, attached plating (within ½ + ½ longitudinal spaces) and associated brackets are to be modelled based on the gross thickness with deduction of the full corrosion addition *t_corr*. Other areas are to be based on gross thickness with deduction of half corrosion addition, 0.5 *t_corr*.

#### 3.2.4.5

The web of the longitudinal stiffeners should be represented by at least 3 shell elements across its depth. Similar size elements should be used to represent the plating of the bottom shell and inner bottom. The face plate of the longitudinal stiffeners and brackets should be modelled with at least three elements across its width.

#### 3.2.4.6

The mesh size and extent of the fine mesh zone is to be in accordance with 3.2.1.3, see also Fig B.3.13.

| Fig B.3.13<br>Sub-Model for Fine Mesh Analysis of End Connections and Web Stiffeners of Deck and Double Bottom Longitudinals |
| --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1027.png) |

**Fig B.3.13 (Continued)<br>Sub-Model for Fine Mesh Analysis of End Connections and Web Stiffeners of Deck and Double Bottom Longitudinals**

| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1028.png) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1029.png) Fine mesh zone<br>Element size ≤ 50 mm × 50 mm |
| --- | --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1030.png) |   |

- **3.2.5** Corrugated bulkheads

#### 3.2.5.1

In addition to 3.2.1, the modelling requirements in this sub-section are applicable to the analysis of connections of corrugated bulkheads to lower bulkhead stools as described in 3.1.5.

#### 3.2.5.2

The minimum extent of the sub-model is as follows, see also Fig B.3.14:

- **(a)** vertically, from the bottom of the bottom bulkhead stool to a level at least 2 m above the connection of the corrugation to the upper part of the bulkhead stool. The upper boundary of the sub-model should be coincident with the horizontal mesh line of the cargo tank FE model
- **(b)** for transverse corrugated bulkheads, the sub-model is to be extended transversely to the nearest diaphragm web in the lower stool on each side of the fine mesh zone (i.e. the sub-model covers two bulkhead stool transverse web spaces). The end diaphragms need not be modelled
- **(c)** for longitudinal corrugated bulkheads, the sub-model is to be extended to the nearest web frame on each side of the fine mesh zone (i.e. the sub-model covers two frame spaces). The end web frames need not be modelled
- **(d)** where the area under investigation is located close to the intersection of transverse and longitudinal corrugated bulkheads, the sub-model should cover the structure between the diaphragms (in transverse direction) and web frames (in longitudinal direction) closest to the detail, whichever relevant. In addition the sub-model is to be extended at least one diaphragm/web frame outside the intersection of the stools.

#### 3.2.5.3

The fine mesh zone is to be extended at least 500 mm (10 elements) from the corrugation connection in a vertical direction, see Fig B.3.1.4. In a horizontal direction, the fine mesh zone is to cover at least the corrugation flange under investigation, the adjacent corrugation webs and a further extension of 500 mm from each end of the corrugation web (i.e. the fine mesh zone covers four corrugation knuckles), see Fig B.3.14. The mesh size within the fine mesh zone is not to be greater than 50 mm × 50 mm.

#### 3.2.5.4

Diaphragm webs, brackets inside the lower stool and vertical stiffeners on the stool side plate are to be modelled at their actual positions within the extent of the sub-model. Shell elements are to be used for modelling of diaphragm, bracket and stiffener webs. Beam elements may be used to represent the flange of stiffeners and brackets.

#### 3.2.5.5

Horizontal stiffeners on the lower stool side plate are to be represented by beam elements.

#### 3.2.5.6

Fig B.3.15 shows the finite element sub-model for the fine mesh analysis of longitudinal bulkhead to lower stool connection.

| Fig B.3.14<br>Extent of Sub-Model and Fine Mesh Zone for the Analysis of Corrugated Bulkhead Connection to Lower Stool |
| --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1031.png) |
| #underline{Note}<br>Above figures show extent of sub-model and fine mesh zone on longitudinal corrugated bulkhead connection to lower stool. Similar extent applies to transverse corrugated bulkhead. |

**Fig B.3.15<br>Sub-Model for the Analysis of Connection of Longitudinal Corrugated Bulkhead to Lower Stool**

| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1032.png) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1033.png) |
| --- | --- |

#### 3.3 Loading Conditions

- **3.3.1** Stress analysis

#### 3.3.1.1

The fine mesh detailed stress analysis is to be carried out for the standard load cases specified in 2.3.1, and any other load cases specially considered as required by Sec 9/2.2.3.

#### 3.4 Application of Loads and Boundary Conditions

- **3.4.1** General

#### 3.4.1.1

Where a separate local finite element model is used for the fine mesh detailed stress analysis, the nodal displacements from the cargo tank model are to be applied to the corresponding boundary nodes on the local model as prescribed displacements. Alternatively, equivalent nodal forces from the cargo tank model may be applied to the boundary nodes.

#### 3.4.1.2

Where there are nodes on the local model boundaries which are not coincident with the nodal points on the cargo tank model, it is acceptable to impose prescribed displacements on these nodes using multi-point constraints. The use of linear multi-point constraint equations connecting two neighbouring coincident nodes is considered sufficient.

#### 3.4.1.3

All local loads, including any vertical loads applied for hull girder shear force correction, in way of the structure represented by the separate local finite element model are to be applied to the model.

#### 3.5 Result Evaluation and Acceptance Criteria

- **3.5.1** Stress assessment

#### 3.5.1.1

Stress assessment of the fine mesh analysis is to be carried out for the load cases specified in 3.3.1.

#### 3.5.1.2

The von Mises stress, *σ_vm*, is to be calculated based on the membrane direct axial and shear stresses of the plate element evaluated at the element centroid. Where shell elements are used, the stresses are to be evaluated at the mid plane of the element.

#### 3.5.1.3

The resulting von Mises stresses are not to exceed the permissible membrane values specified in Sec 9/2.3.5.

#### 3.5.1.4

The maximum permissible stresses are based on the mesh size of 50 mm × 50 mm as specified in 3.2.1. Where a smaller mesh size is used, an average von Mises stress calculated over an area equal to the specified mesh size may be used to compare with the permissible stresses. The averaging is to be based only on elements with their entire boundary located within the desired area. The average stress is to be calculated based on stresses at element centroid; stress values obtained by interpolation and/or extrapolation are not to be used. Stress averaging is not to be carried across structural discontinuities and abutting structure.


### 4 Evaluation of Hot Spot Stress for Fatigue Analysis

#### 4.1 Application

- **4.1.1** General

#### 4.1.1.1

This Section describes the procedure to perform a finite element analysis using very fine meshes for the evaluation of geometric hot spot stresses for use in the determination of fatigue damage ratio in accordance with Appendix C/2.

#### 4.1.1.2

The locations where a finite element analysis based fatigue assessment is to be carried out are specified in Sec 9/3.3.

#### 4.2 Structural Modelling

- **4.2.1** General

#### 4.2.1.1

Evaluation of hot spot stresses for fatigue assessment requires the use of very fine finite element meshes in way of areas of high stress concentration. This very fine mesh analysis can be carried out by means of separate local finite element models with very fine mesh zones in conjunction with the boundary conditions obtained from a cargo tank model. Alternatively, very fine mesh zones incorporated into the cargo tank model may be used.

#### 4.2.1.2

All structural parts, within an extent of at least 500 mm in all directions leading up to the fatigue hot spot position, are to be modelled based on the net thickness, obtained by deducting half the corrosion addition (i.e. 0.5 *t_corr*) from the gross thickness.

#### 4.2.1.3

The cargo tank finite element model for fatigue assessment is to be modelled in accordance with 2.2, but based on net thickness obtained by deducting a quarter of the corrosion addition (i.e. 0.25 *t_corr*) from the proposed thickness. Alternatively, if the cargo tank FE model for the strength assessment is used, which is based on a thickness deduction of 0.5 *t_corr*, the calculated stresses are to be corrected using the modelling reduction factor, *f_model*, given in Appendix C/2.4.2.7.

#### 4.2.1.4

Where a separate local finite element model is used, the extent of the local model is to be such that the calculated stresses are not significantly affected by the imposed boundary conditions and application of loads. The boundary of the fine mesh model is to coincide with the primary support members, such as girders, stringers and floors, in the cargo tank model. The extent of the local finite element model of a hopper knuckle is described in 4.2.2.

#### 4.2.1.5

The evaluation of hot spot stress is to be based on shell element of mesh size *t_net50* × *t_net50*, where *t_net50* is the net thickness of the plate where a potential fatigue crack is most likely to initiate. This mesh size is to be maintained within the very fine mesh zone, extending over at least 10 elements in all directions leading to the fatigue hot spot position. A uniform quadratic mesh is to be used within the very fine mesh zone. A smooth transition of mesh density leading up to the very fine mesh zone is to be maintained.

#### 4.2.1.6

Four-node shell elements with bending and membrane properties are to be used inside the very fine mesh zone. The shell elements are to represent the mid plane of the plating and the bending properties of the plate. The geometry of the weld and structural misalignment is not required to be modelled.

#### 4.2.1.7

Where stresses are to be evaluated on a free edge or corner welds, such as cut-outs for stiffener connections at web frames, butt welds on edge of plating and around hatch corners, a rod element of negligible cross-section area, e.g. 1 $\mathrm{mm} ^{2}$, is to be used to obtain the required stress value.

#### 4.2.1.8

All structure in close proximity to the very fine mesh zones is to be modelled explicitly with shell elements. Triangular elements are to be avoided where possible. Use of extreme aspect ratio (e.g. aspect ratio greater than 3) and distorted elements (e.g. element's corner angle less than 60° or greater than 120°) are to be avoided.

- **4.2.2** Hopper knuckle connection

#### 4.2.2.1

In addition to the general requirements in 4.2.1, the modelling requirements in this sub-section are applicable to the modelling of welded hopper knuckle connections.

#### 4.2.2.2

Fatigue assessment is to be carried out for the knuckle joint between inner bottom and hopper plate for at least one transverse frame in the midship cargo tank region, see Sec 9/3.3.2. The fatigue assessment is only required to be carried out on the structural detail at one side of the hull.

#### 4.2.2.3

In general, the hopper knuckle connection at the mid position between transverse bulkheads is to be assessed. Where a wash bulkhead exists, the hopper knuckle connection at the mid position between the wash bulkhead and cargo tank end bulkhead is generally to be assessed. The results from the cargo tank FE analysis described in 2.2 should be examined for the highest transverse in-plane stress on the inner bottom plate adjacent to the lower hopper knuckle line to identify the exact frame position and the side of the hull where the fatigue assessment should be carried out.

#### 4.2.2.4

Where a separate local finite element model is used, the minimum extent of the local model is as follows:

- **(a)** longitudinally, the model is to cover two web frame spaces (i.e. one web frame space extending either side of the transverse web frame of interest). Transverse web frames at the end of the local model need not to be represented in the sub-model
- **(b)** vertically, the model is to extend from the base line to the lower stringer in the double side water ballast tank. Where a fatigue assessment is also carried out for the upper knuckle connection, the model is to be extended to 4 longitudinal spaces above the lower stringer in the double side ballast tank
- **(c)** transversely, the model is to extend from the ship side to 4 longitudinal spaces inboard of the double bottom side girder.

#### 4.2.2.5

Mesh size in way of the knuckle connection is to be *t_net50* × *t_net50*, where *t_net50* is the net thickness of the inner bottom plate in way of the connection obtained by deducting 0.5 *t_corr* from the gross thickness as specified in 4.2.1.2. The minimum extent of the *t_net50* × *t_net50* mesh is to be (see also Fig B.4.1):

- **(a)** inner bottom plate - 10 elements from knuckle in transverse direction, 10 elements forward and aft of the floor in the longitudinal direction
- **(b)** scarfing bracket/inner bottom overhang - 10 elements from knuckle in transverse direction, 10 elements forward and aft of the floor in the longitudinal direction
- **(c)** hopper sloping plate - 10 elements from knuckle in transverse direction, 10 elements forward and aft of the hopper web in the longitudinal direction
- **(d)** girder - 10 elements from knuckle in vertical direction, 10 elements forward and aft of the floor/hopper web in the longitudinal direction
- **(e)** floor/hopper web - 10 elements from the hopper knuckle in transverse and vertical directions respectively.

#### 4.2.2.6

Any scarfing brackets on the web frame adjoining the inner bottom plating, the first longitudinal stiffeners away from the knuckle as well as any carlings and brackets offset from the main frames are to be modelled explicitly using shell elements. Longitudinal stiffeners further away from the knuckle may be modelled by beam elements. The inner bottom plate "overhang" outboard of the girder is to be modelled using shell elements up to the extent of the scarfing bracket. Away from the scarfing bracket, the inner bottom plate "overhang"may be modelled using line elements of equivalent area. Any perforations, such as cut-outs for cabling, pipes and access that are within one stiffener space from the knuckle point are to be modelled explicitly.

#### 4.2.2.7

Fig B.4.1 shows extent of the *t_net50* × *t_net50* mesh zone and extension of the areas of local thickness reduction.

#### 4.2.2.8

Fig B.4.2 to B.4.4 show typical local finite element models of the hopper knuckle connection and close-up views of the *t_net50* × *t_net50* mesh zone.

| Fig B.4.1<br>Minimum Extent of *t_net50* x *t_net50* Mesh Zone and Local Thickness Reduction Zone at Lower Hopper Joint |
| --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1034.png)<br>Floor and hopper web<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1035.png)<br>Girder, inner bottom and hopper sloping plate |

| Fig B.4.2<br>Typical Local Finite Element Model of Hopper Knuckle Connection<br>*t_net50* x *t_net50* Mesh on Inner Bottom and Hopper Plate |
| --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1036.png) |

| Fig B.4.3<br>Typical Local Finite Element Model of Hopper Knuckle Connection<br>*t_net50* x *t_net50* Mesh on Hopper Plate, Web Frame, Girder and Bracket in way |
| --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1037.png) |

#### 4.3 Loading Conditions

- **4.3.1** General

#### 4.3.1.1

The ship loading conditions to be used to evaluate dynamic stress ranges for fatigue assessment are to be in accordance with Appendix C/1.3.2.

#### 4.3.1.2

The cargo density to be used for the fatigue assessment is to be:

| Fig B.4.4<br>Typical Local Finite Element Model of Hopper Knuckle Connection<br>*t_net50* x *t_net50* Mesh on Hopper Plate, Web Frame, Girder and Bracket in way |
| --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1038.png) |

- **(a)** longitudinal end connections - the greater of the cargo density specified for the homogeneous scantling draught condition and 0.9 $\mathrm{t}/m ^{3}$
- **(b)** connection between inner bottom and hopper plate - 0.9 $\mathrm{t}/m ^{3}$
- **4.3.2** Finite element load cases for hopper knuckle connection

#### 4.3.2.1

The requirements given in this sub-section are specifically applicable to the evaluation of hot spot stress range at hopper knuckle connection.

#### 4.3.2.2

Only dynamic loads are considered for the evaluation of fatigue stress range. Static loads need not be included in the finite element analysis.

#### 4.3.2.3

The load cases required to derive the component stress ranges for determining the combined stress ranges, see Appendix C/2.4.2.7, are given in Table B.4.1.

#### 4.3.2.4

Stresses induced by vertical and horizontal hull girder bending moments are not to be included in the stress range for fatigue assessment. Stress caused by the bending effect of the hull girder is to be calculated and deduced from the fatigue stress range result in accordance with the procedure described in 4.5.2.

**Table B.4.1<br>Load Cases for the Evaluation of Component Stress Range for Hopper Knuckle Joint**

| Load case | Component stress | Applied load | Parameters for calculation of loads |
| --- | --- | --- | --- |
| Full load condition |   |   |   |
| L1 | $s _{e1}$ | Dynamic wave pressure (full range) applies only to the side of the hull where the hopper knuckle is analysed. | Ship draught = midship draught from departure homogeneous full load condition in the ship loading manual, see Appendix C/1.3.2.<br>GM: see Sec 7/3.1.3.4<br>$r _{roll-gyr}$ : see Sec 7/3.1.3.4<br>Cargo density = 0.9 $\mathrm{t}/m ^{3}$ (minimum, see 4.3.1.2) |
| L2 | $s _{e2}$ | Dynamic wave pressure (full range) applies only to the side of the hull where the hopper knuckle is not analysed. | Ship draught = midship draught from departure homogeneous full load condition in the ship loading manual, see Appendix C/1.3.2.<br>GM: see Sec 7/3.1.3.4<br>$r _{roll-gyr}$ : see Sec 7/3.1.3.4<br>Cargo density = 0.9 $\mathrm{t}/m ^{3}$ (minimum, see 4.3.1.2) |
| L3 | $s _{ix}$ | Dynamic tank pressure (full range) due to longitudinal acceleration. | Ship draught = midship draught from departure homogeneous full load condition in the ship loading manual, see Appendix C/1.3.2.<br>GM: see Sec 7/3.1.3.4<br>$r _{roll-gyr}$ : see Sec 7/3.1.3.4<br>Cargo density = 0.9 $\mathrm{t}/m ^{3}$ (minimum, see 4.3.1.2) |
| L4 | $s _{iy}$ | Dynamic tank pressure (full range) due to transverse accelerations. | Ship draught = midship draught from departure homogeneous full load condition in the ship loading manual, see Appendix C/1.3.2.<br>GM: see Sec 7/3.1.3.4<br>$r _{roll-gyr}$ : see Sec 7/3.1.3.4<br>Cargo density = 0.9 $\mathrm{t}/m ^{3}$ (minimum, see 4.3.1.2) |
| L5 | $s _{iz}$ | Dynamic tank pressure (full range) due to vertical acceleration. | Ship draught = midship draught from departure homogeneous full load condition in the ship loading manual, see Appendix C/1.3.2.<br>GM: see Sec 7/3.1.3.4<br>$r _{roll-gyr}$ : see Sec 7/3.1.3.4<br>Cargo density = 0.9 $\mathrm{t}/m ^{3}$ (minimum, see 4.3.1.2) |
| Ballast condition |   |   |   |
| L6 | $s _{e1}$ | Dynamic wave pressure (full range) applies only to the side of the hull where the hopper knuckle is analysed. | Ship draught = midship draught from departure normal ballast condition in the ship loading manual. If normal ballast condition is not defined, then the midship draught from light ballast condition is to be used, see Appendix C/1.3.2 |
| L7 | $s _{e2}$ | Dynamic wave pressure (full range) applies only to the side of the hull where the hopper knuckle is not analysed. | Ship draught = midship draught from departure normal ballast condition in the ship loading manual. If normal ballast condition is not defined, then the midship draught from light ballast condition is to be used, see Appendix C/1.3.2 |
| Load cases for bending moment correction |   |   |   |
| C1 | $s _{VBM}$ | Unit vertical bending moment applies to ends of cargo tank model | No other loads are to be applied |
| C2 | $s _{HBM}$ | Unit horizontal bending moment applies to ends of cargo tank model | No other loads are to be applied |
| Where:<br>$s _{e1}$,$s _{e2}$,$s _{ix}$,$s _{iy}$,$s _{iz}$ component stresses (with proper sign convention used) before correction for bending moment effect <sup>(5)</sup><br>$s _{VBM}$ stress response due to the application of unit vertical bending moment at ends of cargo tank model<br>$s _{HBM}$ stress response due to the application of unit horizontal bending moment at ends of cargo tank models |   |   |   |
| #underline{Notes}<br>1. For dynamic wave pressure load cases, the pressure distribution is to be calculated at mid-ship and this distribution is to be applied along the full length of the cargo tank FE model.<br>2. For dynamic tank pressure load cases, vertical, transverse and longitudinal accelerations are calculated at the centre of gravity position of the midship cargo tanks. The accelerations calculated for each tank are to be applied to all corresponding cargo tanks along the length of the FE model.<br>3. Longitudinal, transverse and vertical accelerations at tank centre of gravity position are to be calculated in accordance with Sec 7/3.3. The dynamic tank pressure amplitudes due to accelerations are to be calculated in accordance with Sec 7/3.5.4.7. The dynamic tank pressure (full range) is to be obtained as two times the dynamic tank pressure amplitude and distributed in accordance with Fig 7.3.9. Note that these pressure distributions are different from those used for strength analysis.<br>4. The dynamic wave pressure amplitude is to be calculated according to Sec 7/3.5.2.3. The dynamic wave pressure (full range) is to be obtained as two times the dynamic wave pressure amplitude. Note that the dynamic wave pressure and distribution is different from that used for strength analysis.<br>5. Component stresses (with proper sign convention used) calculated from load cases L1 to L7 are to be corrected to deduct the component due to vertical and horizontal bending moment effect, see 4.5.2.2. |   |   |   |

#### 4.4 Boundary Conditions

- **4.4.1** Cargo tank model

#### 4.4.1.1

The boundary conditions to be applied to the ends of the cargo tank model are to be in accordance with 2.6. The application of unit vertical and horizontal bending moment at the model ends is to be in accordance with 2.5.4.5 or 2.5.4.6.

- **4.4.2** Local finite element models

#### 4.4.2.1

Where a separate local finite element model is used for evaluating the hot spot stress range, the nodal displacements or equivalent nodal forces from the cargo tank model are to be applied to the corresponding boundary nodes on the local model.

#### 4.4.2.2

Where there are nodes on the local model boundaries which are not coincident with the nodal points on the cargo tank model, it is acceptable to impose prescribed displacements on these nodes using multi-point constraints. The use of linear multi-point constraint equations connecting two neighbouring coincident nodes is considered sufficient.

#### 4.4.2.3

All local loads in way of the structure represented by the separate local finite element model are to be applied to the model.

#### 4.5 Result Evaluation

- **4.5.1** General

#### 4.5.1.1

The fatigue damage calculation is to be based on the hot spot stress range evaluated close to the potential crack location in a direction perpendicular to the potential direction of the crack.

#### 4.5.1.2

For welded structural details, the hot spot stress range is to be obtained as surface stress acting in a direction perpendicular to the weld at a distance of 0.5 *t_net50* from the weld toe location, where *t_net50* is the net thickness of the plate where the fatigue crack is likely to initiate, see Appendix C/2.4.2.6.

#### 4.5.1.3

For fatigue assessment of the free edge, a rod element is used to obtain stress at free edge. The stress range is to be based on the axial stress in the rod element.

#### 4.5.1.4

For fatigue damage calculation of hopper knuckle connection, see 4.5.2.

- **4.5.2** Hopper knuckle connection

#### 4.5.2.1

Hot spot stress ranges for fatigue assessment of welded hopper knuckle joints are to be based on element direct stress along a direction perpendicular to intersection of the inner bottom plate and hopper plate. The stress ranges are to be evaluated on the upper surface of the hopper and inner bottom plate at a distance of 0.5 *t_net50* + *x_wt* from the intersection line, where *t_net50* is the net thickness of the inner bottom plate and *x_wt* is weld toe distance, see Fig C.2.1. The stress at the required location can be obtained by linear interpolation based on the surface stresses evaluated at the centroid of the 1^st and 2^nd elements from the intersection of the hopper slope plate, and the inner bottom plate.

#### 4.5.2.2

The component stress ranges are to be obtained by eliminating the stress induced by hull girder vertical and horizontal bending moments from the component stress determined from load cases L1 to L7 in Table B.4.1 as follows:
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1039.png)
Where:
*S_c_i* *S_e1*, *S_e2*, *S_ix*, *S_iy* or *S_iz*, component stress range after correction for bending moment effects
*s_c_i* *s_e1*, *s_e2*, *s_ix*, *s_iy* or *s_iz*, component stress (with proper sign convention used) including vertical and horizontal bending moment effects obtained from load cases L1 to L7, see Table B.4.1
*M_V_i* is the vertical hull girder bending moment due to loads applied to the cargo tank FE model obtained from load case L1, L2, L3, L4, L5, L6 or L7. The bending moment is to be calculated at the longitudinal position where the centroid of shell element under evaluation is located
*M_H_i* is the horizontal hull girder bending moment due to loads applied to the cargo tank FE model obtained from load case L1, L2, L3, L4, L5, L6 or L7. The bending moment is to be calculated at the longitudinal position where the centroid of shell element under evaluation is located
*s_VBM* stress due to unit vertical bending moment obtained from load case C1, see Table B.4.1
*s_HBM* stress due to unit horizontal bending moment obtained from load case C2, see Table B.4.1

#### 4.5.2.3

The hull girder vertical and horizontal bending moments in 4.5.2.2 may be evaluated at the frame position where the hopper knuckle is under evaluation if the longitudinal distance from the element centroid to the frame position is less than 500 mm.

#### 4.5.2.4

The component stress range, *S_i*, due to dynamic tank pressure resulting from longitudinal, transverse and vertical accelerations for the full load condition is given by:
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1040.png)

#### 4.5.2.5

The combined hot spot stress ranges required for fatigue damage calculation are to be calculated in accordance with Appendix C/2.4.2.7.

#### 4.5.2.6

Fatigue damage and fatigue life calculation is to be in accordance with Appendix C/1.4.1.
