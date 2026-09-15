# PART 12 Common Structural Rules for Double Hull Oil Tankers

> RULES FOR CLASSIFICATION OF STEEL SHIPS / RA-12-E / 2025 / EN / Rules

## Chapter 9 Design Verification

### 1 Hull Girder Ultimate Strength

#### 1.1 General

- **1.1.1** Application

#### 1.1.1.1

The hull girder ultimate bending capacity in sagging is to be evaluated and checked to ensure it satisfies the following criteria. The criteria are applicable to intact ship structures, in extreme at sea conditions. They do not cover hogging, harbour or damaged conditions.

#### 1.1.1.2

The scantling requirements in this Sub-Section are to be applied to any cross section along the entire vessel’s length and are in addition to all other requirements within the rules.

#### 1.1.1.3

Outside the 0.4 *L* region of amidships the plate and stiffeners may be gradually reduced towards the local requirements at the ends.

#### 1.2 Rule Criteria

- **1.2.1** Vertical hull girder ultimate bending capacity

#### 1.2.1.1

The vertical hull girder ultimate bending capacity is to satisfy the following criteria:
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image646.png)
Where:
*M_sw* sagging still water bending moment, in kNm, to be taken as specified in Table 9.1.1.
*M_wv-sag* sagging vertical wave bending moment, in kNm, to be taken as the midship sagging value defined in Sec 7/3.4.1.1
*M_U* sagging vertical hull girder ultimate bending capacity, in kNm, as defined in Appendix A/1.1.1
$\gamma _{S}$ *,*$\gamma _{W}$ *,*$\gamma _{R}$ are the partial safety factors for the design load combinations given in 1.4

#### 1.3 Hull Girder Bending Moment Capacity

- **1.3.1** Calculation of capacity

#### 1.3.1.1

The hull girder ultimate bending capacity, *M_U*, in sagging is to be calculated according to Appendix A/1.1.1.

#### 1.3.1.2

The effective area for the hull girder ultimate strength capacity assessment is specified in Sec 8/1.2.1.

#### 1.3.1.3

The capacity is to be based on net scantlings using a corrosion addition, 0.5 *t_corr*, see Sec 6/3.2

#### 1.4 Partial Safety Factors

- **1.4.1** General

#### 1.4.1.1

The partial safety factors given in Table 9.1.1 apply when *M_U* is calculated according to the single step method in Appendix A/2.1 or the incremental method in A/2.2. The partial safety factors are given for two different design load combinations and both combinations are to be satisfied. Note that the definition of *M_sw* is different for each combination.

**Table 9.1.1<br>Partial Safety Factors**

| Design load combination | Definition of Still Water Bending Moment, *M_sw* | $\gamma _{S}$ | $\gamma _{W}$ | $\gamma _{R}$ |
| --- | --- | --- | --- | --- |
| a) | Permissible sagging still water bending moment, *M_sw-perm-sea*, in kNm, see Sec 7/2.1.1 | 1.0 | 1.2 | 1.1 |
| b) | Maximum sagging still water bending moment for operational seagoing homogeneous full load condition, *M_sw-full*, in kNm, see note1 | 1.0 | 1.3 | 1.1 |
| Where:<br>$\gamma _{S}$ partial safety factor for the sagging still water bending moment<br>$\gamma _{W}$ partial safety factor for the sagging vertical wave bending moment covering environmental and wave load prediction uncertainties<br>$\gamma _{R}$ partial safety factor for the sagging vertical hull girder bending capacity covering material, geometric and strength prediction uncertainties |   |   |   |   |
| Notes<br>1 The maximum sagging still water bending moment is to be taken from the departure condition with the ship homogeneously loaded at maximum draught and corresponding arrival and any mid-voyage conditions. |   |   |   |   |


### 2 Strength Assessment (FEM)

#### 2.1 General

- **2.1.1** Application

#### 2.1.1.1

A strength assessment of the hull structure using finite element analysis is mandatory.

#### 2.1.1.2

The finite element analysis consists of two parts:

- **(a)** cargo tank analysis to assess the strength of longitudinal hull girder structural members, primary supporting structural members and transverse bulkheads.
- **(b)** fine mesh analysis to assess detailed stress levels in local structural details.

#### 2.1.1.3

A flow diagram showing the minimum requirement of finite element analysis is shown in Fig 9.2.1.

#### 2.1.1.4

The structural assessment is to be carried out in accordance with the requirements given in Appendix B. The structural assessment is to verify that the acceptance criteria specified in 2.2.5 and 2.3.5 are complied with.

#### 2.1.1.5

The application of the scantlings verified by the structural assessment within the cargo tank region is to be in accordance with 2.4.

| Figure 9.2.1<br>Rule Minimum Requirement on Finite Element Analysis |
| --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image647.png) |
| #underline{Note}<br>1. The strength assessment of longitudinal hull girder shear structural members, as defined in 2.2.1.1 and Sec 4/Table 4.1.1, against hull girder vertical shear loads in way of transverse bulkheads may be based on the midship cargo tank finite element model with modification of plate and stiffener properties where appropriate, see Appendix B/1.1.1 and Appendix B/2.2.1 |

- **2.1.2** Submission of results

#### 2.1.2.1

A detailed report of the structural analysis is to be submitted to demonstrate compliance with the specified structural design criteria. This report shall include the following information:

- **(a)** list of plans used including dates and versions
- **(b)** detailed description of structural modelling including all modelling assumptions and any deviations in geometry and arrangement of structure compared with plans
- **(c)** plots to demonstrate correct structural modelling and assigned properties
- **(d)** details of material properties, plate thickness, beam properties used in the model
- **(e)** details of boundary conditions
- **(f)** details of all loading conditions reviewed with calculated hull girder shear force and bending moment distributions
- **(g)** details of applied loads and confirmation that individual and total applied loads are correct
- **(h)** plots and results that demonstrate the correct behaviour of the structural model under the applied loads
- **(i)** summaries and plots of global and local deflections
- **(j)** summaries and sufficient plots of stresses to demonstrate that the design criteria are not exceeded in any member
- **(k)** plate and stiffened panel buckling analysis and results
- **(l)** tabulated results showing compliance, or otherwise, with the design criteria
- **(m)** proposed amendments to structure where necessary, including revised assessment of stresses, buckling and fatigue properties showing compliance with design criteria.
- **2.1.3** Computer programs

#### 2.1.3.1

In general, any finite element computation program recognised by the Classification Society may be employed to determine the stress and deflection of the hull structure, provided that the combined effects of bending, shear, axial and torsional deformations are considered.

#### 2.1.3.2

The computer program used for the assessment of panel buckling capability is to take account of the combined interaction of bi-axial compressive stresses, shear stress and lateral pressure loads, as required by Sec 10/4.

#### 2.1.3.3

A computer program that has been demonstrated to produce reliable results to the satisfaction of the Classification Society is regarded as a recognised program. Where the computer programs employed are not supplied or recognised by the Classification Society, full particulars of the computer program, including calculation output, are to be submitted for approval. It is recommended that the designers consult the Classification Society on the suitability of the computer programs intended to be used prior to the commencement of any analysis work.

#### 2.2 Cargo Tank Structural Strength Analysis

- **2.2.1** Objective and scope

#### 2.2.1.1

The analysis is to cover at least the assessment of:

- **(a)** longitudinal hull girder structural members, primary supporting structural members and transverse bulkheads in the midship cargo tank region, and
- **(b)** longitudinal hull girder shear structural members in way of transverse bulkheads against hull girder vertical shear loads within the cargo area. These structural members include side shell, inner hull longitudinal bulkheads including upper sloped plate where fitted, hopper, longitudinal bulkheads and double bottom girders as defined in Sec 4/Table 4.1.1. The required strengthening in way of transverse bulkheads for hull girder shear loads in the forward, midship or aft cargo region may be based on the maximum hull girder shear force within the region considered. Alternatively assessment may be carried out to determine the strengthening requirement in way of individual transverse bulkhead position. The details are given in Appendix B/1.1.1.

#### 2.2.1.2

The required strengthening in way of transverse bulkheads for hull girder shear loads in the forward, midship or aft cargo region may be based on the maximum hull girder shear force within the region considered. Alternatively assessment may be carried out to determine the strengthening requirement in way of individual transverse bulkhead position. The details are given in Appendix B/1.1.1

#### 2.2.1.3

The analysis is to verify that the following are within the acceptance criteria under the applied static and dynamic loads:

- **(a)** stress level in the plating of longitudinal hull girder structural members, primary support structural members and transverse bulkheads, face plate of primary support members modelled by plate or rod elements.
- **(b)** buckling capability of plates and stiffened panels.
- **2.2.2** Structural modelling

#### 2.2.2.1

The modelling scantlings of the cargo tank finite element model are to be based on net scantlings as described in Sec 6/3.3.6.1 and Appendix B/2.2.1.5.

#### 2.2.2.2

The length of the cargo tank finite element model is to cover three cargo tank lengths. Where the tanks in the midship cargo region are of different lengths, the middle tank of the finite element model is to represent the cargo tank of the greatest length. All main longitudinal and transverse structural elements are to be represented in the finite element model. These include inner and outer shell, double bottom floor and girder system, transverse and vertical web frames, stringers, transverse and longitudinal bulkhead structures. All plating and stiffeners, including web stiffeners, on these structural elements are to be modelled.

#### 2.2.2.3

The mesh of the finite element model is to follow the stiffening system of the structure as far as practical, and is to represent the actual plate panels between stiffeners.

#### 2.2.2.4

The structure modelling is to be in accordance with the requirements given in Appendix B/2.2.

- **2.2.3** Loads and loading conditions

#### 2.2.3.1

The combinations of the ship static and dynamic loads which are likely to impose the most onerous load regimes on the hull structure are to be investigated in the structural analysis.

#### 2.2.3.2

The standard load cases to be used in the structural analysis are given in Appendix B/2.3.1. These load cases cover seagoing conditions (design load combination S+D) and harbour/tank testing conditions (design load combination S).

#### 2.2.3.3

Where the loading conditions specified by the designer are not covered by the standard load cases then these additional loading conditions are to be examined, see also Appendix B/2.3.1.

- **2.2.4** Load applications and boundary conditions

#### 2.2.4.1

All simultaneously acting hull girder and local loads are to be applied to the model. The application of local and hull girder loads to the finite element model is to be in accordance with the requirement given in Appendix B/2.4 and B/2.5.

#### 2.2.4.2

The boundary conditions to be applied are given in Appendix B/2.6.

- **2.2.5** Acceptance criteria

#### 2.2.5.1

Verification of results against the acceptance criteria is to be carried out in accordance with Appendix B/2.7.

#### 2.2.5.2

Verification of results against the acceptance criteria is to be carried out for all structural members within the longitudinal extent of the middle tanks of the three tank FE model, and the regions forward and aft of the middle tanks up to the extent of the transverse bulkhead stringer and buttress structure. For the assessment of shear strength in way of transverse bulkheads against hull girder shear loads, stress level and buckling capability of inner hull longitudinal bulkheads including upper sloped plate where fitted, side shell, longitudinal bulkheads, hopper and bottom longitudinal girders are to be verified against the acceptance criteria. See also Appendix B/2.7.1.

#### 2.2.5.3

The structural analysis is to demonstrate that the permissible von Mises stress criteria and utilisation factor against buckling for plate and stiffened panels specified in Tables 9.2.1 and 9.2.2 are not exceeded.

#### 2.2.5.4

Capacity models used for the assessment of local buckling capability of plate and stiffened panels are to be based on deduction of full corrosion addition thickness from the plate and stiffeners, as described in Sec 6/3.3.6.2 and Appendix B/2.7.3.

#### 2.2.5.5

Where a lower stool is not fitted to a transverse or longitudinal corrugated bulkhead, the maximum permissible stresses and buckling utilisation factors given in Tables 9.2.1 and 9.2.2 are to be reduced by 10 % for the corrugation and below supporting structure within the extent defined as follows:

**Table 9.2.1<br>Maximum Permissible Stresses**

| Structural component | Yield utilisation factor |
| --- | --- |
| Internal structure in tanks |   |
| Plating of all non-tight structural members including transverse web frame structure, wash bulkheads, internal web, horizontal stringers, floors and girders. Face plate of primary support members modelled using plate or rod elements | $\lambda _{y}$ ≤ 1.0 (load combination S + D)<br>$\lambda _{y}$ ≤ 0.8 (load combination S) |
| Structure on tank boundaries |   |
| Plating of deck, sides, inner sides, hopper plate, bilge plate, plane and corrugated cargo tank longitudinal bulkheads. Tight floors, girders and webs | $\lambda _{y}$ ≤ 0.9 (load combination S + D)<br>$\lambda _{y}$ ≤ 0.72 (load combination S) |
| Plating of inner bottom, bottom, plane transverse bulkheads and corrugated bulkheads. | $\lambda _{y}$ ≤ 0.8 (load combination S + D)<br>$\lambda _{y}$ ≤ 0.64 (load combination S) |
| Where:<br>$\lambda _{y}$ yield utilisation factor<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image648.png) for plate elements in general<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image649.png) for rod elements in general<br>$\sigma _{vm}$ von Mises stress calculated based on membrane stresses at element’s centroid, in $\mathrm{N}/mm ^{2}$<br>$\sigma _{rod}$ axial stress in rod element, in $\mathrm{N}/mm ^{2}$<br>$\sigma _{yd}$ specified minimum yield stress of the material, in $\mathrm{N}/mm ^{2}$, but not to be taken as greater than 315 $\mathrm{N}/mm ^{2}$ for load combination S+D in areas of stress concentration<sup>(2)</sup> |   |
| Note<br>1. Structural items given in the table are for guidance only. Stresses for all parts of the FE model specified in 2.2.5.2 are to be verified against the permissible stress criteria. See also Appendix B/2.7.1<br>2. Areas of stress concentration are corners of openings, knuckle joints, toes and heels of primary supporting structural members and stiffeners<br>3. Where a lower stool is not fitted to a transverse or longitudinal corrugated bulkhead, the maximum permissible stresses are to be reduced by 10 % in accordance with 2.2.5.5.<br>4. The yield utilisation factor for plane and corrugated longitudinal bulkheads between cargo tanks may be taken as for non-tight structural members for FE load cases where either both sides of the bulkhead are empty or both sides are loaded. The water-tight bottom girder under the longitudinal bulkhead is to be treated as a tight structural member. |   |

**Table 9.2.2<br>Maximum Permissible Utilisation Factor Against Buckling**

| Structural component | Buckling utilisation factor |
| --- | --- |
| Plate and stiffened panels<sup>(3)</sup> | $\eta$ ≤ 1.0 (load combination S + D)<br>$\eta$ ≤ 0.8 (load combination S) |
| Web plate in way of openings | $\eta$ ≤ 1.0 (load combination S + D)<br>$\eta$ ≤ 0.8 (load combination S) |
| Pillar buckling of cross tie structure | $\eta$ ≤ 0.75 (load combination S + D)<br>$\eta$ ≤ 0.65 (load combination S) |
| Corrugated bulkheads<br>- flange buckling<br>- column buckling | $\eta$ ≤ 0.9 (load combination S + D)<br>$\eta$ ≤ 0.72 (load combination S) |
| Where:<br>$\eta$ utilisation factor against buckling calculated in accordance with Appendix D/5 and Appendix B/2.7.3. Also see Sec 10/3.4.1 for web plate in way of openings and Sec 10/3.5.1 for cross tie structure |   |
| Note<br>1. Buckling capability of curved panels (e.g. bilge plate), face plate and tripping bracket of primary supporting members are not assessed based on finite element stress result<br>2. Where a lower stool is not fitted to a transverse or longitudinal corrugated bulkhead, the maximum permissible buckling utilisation factors are to be reduced by 10 % in accordance with 2.2.5.5<br>3. Permissible buckling utilisation factors specified in this table are applicable for the reference advanced buckling method given in Appendix D/1.1.2. If alternative buckling procedures are used the permissible utilisation factors are to be assessed and if required adjusted to meet acceptance criteria for equivalence specified in Appendix D/1.1.2. |   |

- **(a)** Full height of the corrugation
- **(b)** Supporting structure for a transverse corrugated bulkhead - longitudinally within half a web frame space forward and aft of the bulkhead
- **(c)** Supporting structure for a longitudinal corrugated bulkhead - transversely within three longitudinal stiffener spacings from each side of the bulkhead.

#### 2.3 Local Fine Mesh Structural Strength Analysis

- **2.3.1** Objective and scope

#### 2.3.1.1

For tankers of conventional arrangements, as a minimum requirement, the following areas in the midship cargo region are to be investigated:

- **(a)** main bracket toes and openings at critical locations and upper hopper knuckle joint of a typical transverse web frame located in the midship tank. Where a wash bulkhead is fitted, main bracket toes and openings at critical locations of transverse and vertical webs
- **(b)** main bracket toes and openings at critical locations on a typical transverse web frame adjacent to a transverse bulkhead in way of the transverse bulkhead horizontal stringers
- **(c)** main bracket toes, heels and openings at critical locations of horizontal stringers, connection of transverse bulkhead to double bottom girder or buttress of a typical transverse bulkhead
- **(d)** connections of transverse and longitudinal corrugated bulkheads to bottom stool or inner bottom and double bottom supporting structure if a lower stool is not fitted. If a gusset plate is fitted the connection between the corrugation and the upper corners of the gusset are to be assessed
- **(e)** end brackets and attached web stiffeners of typical longitudinal stiffeners of double bottom and deck, and adjoining vertical stiffener of transverse bulkhead. If longitudinal stiffeners are fitted above the deck then the connection in way of the transverse bulkhead are to be assessed.

#### 2.3.1.2

The selection of critical locations on the structural members described in 2.3.1.1 to perform fine mesh analysis is to be in accordance with Appendix B/3.1.

#### 2.3.1.3

Where the stress level in areas of stress concentration on structural members not specified in 2.3.1.1 exceeds the acceptance criteria of the cargo tank analysis, a fine mesh analysis is to be carried out to demonstrate satisfactory scantlings.

#### 2.3.1.4

Where the geometry can not be adequately represented in the cargo tank finite element model, a fine mesh analysis may be used to demonstrate satisfactory scantlings. In such cases the average stress within an area equivalent to that specified in the cargo tank analysis (typically s by s) is to comply with the requirement given in Table 9.2.1. See also Note 1 of Table 9.2.3.

- **2.3.2** Structural modelling

#### 2.3.2.1

The fine mesh structural models are to be in accordance with the requirements given in Appendix B/3.2.

#### 2.3.2.2

The fine mesh analysis may be carried out by means of a separate local finite element model with fine mesh zones, in conjunction with the boundary conditions obtained from the cargo tank model, or by incorporating fine mesh zones into the cargo tank model.

#### 2.3.2.3

The extent of the local finite element models is to be such that the calculated stresses at the areas of interest are not significantly affected by the imposed boundary conditions and application of loads. Detailed requirements on the extension of local finite element models are given in Appendix B/3.2.

#### 2.3.2.4

The fine mesh zone is to represent the localised area of high stress. The finite element mesh size within the fine mesh zones is to be not greater than 50 mm × 50 mm. The extent of the fine mesh zone is to be in accordance with Appendix B/3.2.

#### 2.3.2.5

The fine mesh models are to be based on the net scantlings in accordance with Sec 6/3.3.6.3 and Appendix B/3.2.

- **2.3.3** Loads and loading conditions

#### 2.3.3.1

Fine mesh detailed stress analysis is to be carried out for the standard load cases, and any other specifically specified load cases, required by 2.2.3.

- **2.3.4** Load applications and boundary conditions

#### 2.3.4.1

The application of loads and boundary conditions to the finite element model is to be in accordance with the requirements given in Appendix B/3.4.

- **2.3.5** Acceptance criteria

#### 2.3.5.1

Verification of stress results against the acceptance criteria is to be carried out in accordance with Appendix B/3.5.

#### 2.3.5.2

The structural assessment is to demonstrate that the von Mises stresses obtained from the fine mesh finite element analysis do not exceed the maximum permissible stress criteria specified in Table 9.2.3.

**Table 9.2.3<br>Maximum Permissible Membrane Stresses for Fine Mesh Analysis**

| Element stress | Yield utilisation factor |
| --- | --- |
| Element not adjacent to weld | $\lambda _{y}$ ≤ 1.7 (load combination S + D)<br>$\lambda _{y}$ ≤ 1.36 (load combination S) |
| Element adjacent to weld | $\lambda _{y}$ ≤ 1.5 (load combination S + D)<br>$\lambda _{y}$ ≤ 1.2 (load combination S) |
| Where:<br>$\lambda _{y}$ yield utilisation factor<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image650.png) for plate element<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image651.png) for rod or beam element<br>$\sigma _{vm}$ von Mises stress calculated based on membrane stress at element’s centroid, in $\mathrm{N}/mm ^{2}$<br>$\sigma _{rod}$ axial stress in rod element, in $\mathrm{N}/mm ^{2}$<br>$k$ higher strength steel factor, as defined in Sec 6/1.1.4 but not to be taken as less than 0.78 for load combination S+D |   |
| Note<br>1. Where the von Mises stress of the elements in the cargo tank FE model in way of the area under investigation by fine mesh exceeds its permissible value specified in Table 9.2.1, average von Mises stress, obtained from the fine mesh analysis, calculated over an area equivalent to the mesh size of the cargo tank finite element model is to be less than the permissible value specified in Table 9.2.1<br>2. The maximum permissible stresses are based on the mesh size of 50 mm × 50 mm. Where a smaller mesh size is used, an average von Mises stress calculated in accordance with Appendix B/3.5.1 over an area equal to the specified mesh size may be used to compare with the permissible stresses.<br>3. Average von Mises stress is to be calculated based on weighted average against element areas:<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image652.png)<br>where<br>$\sigma _{vm-av}$ is the average von Mises stress<br>$\sigma _{vm-i}$ is the von Mises stress of the *i^th* plate element within the area considered<br>$A _{i}$ is the area of the *i^th* plate element within the area considered<br>$n$ is the number of elements within the area considered<br>4. Stress averaging is not to be carried across structural discontinuities and abutting structure<br>5. Where a lower stool is not fitted to a transverse or longitudinal corrugated bulkhead, the maximum permissible stresses are to be reduced by 10 % for the areas under investigation by fine mesh analysis. |   |

#### 2.4 Application of Scantlings in Cargo Tank Region

- **2.4.1** General

#### 2.4.1.1

The application of the scantlings that comply with the requirements of the finite element strength assessment, to the structure within the cargo tank region, is to be in accordance with the requirements given in this sub-section.

#### 2.4.1.2

The application given in this sub-section assumes that the same material yield strength of the structure is maintained throughout the cargo tank region. Where steel having a different yield strength is applied, the required scantlings are to be assessed.

#### 2.4.1.3

The scaling procedure given in this sub-section is based on scantlings that satisfied the requirements given in Sec 9/2 and Appendix B.

#### 2.4.1.4

The net thickness and sectional properties for plating and local support members described in this sub-section are to be based on deduction of full corrosion addition, as specified in Sec 6/Table 6.3.2, from the gross scantlings. The gross thickness of plating, web and face plate of local support members are to be obtained by adding the full corrosion addition to the net thickness.

- **2.4.2** Application of scantlings to deck

#### 2.4.2.1

The scantlings of deck plating and deck longitudinal stiffeners are to be maintained longitudinally within 0.4 *L* amidships. The scantlings of deck plating and deck longitudinal stiffeners at a given transverse location within 0.4 *L* amidships are not to be taken as less than the maximum of that required for the corresponding transverse location along the length of the middle tanks of the cargo tank finite element model required by Appendix B/1.1.1.5.

#### 2.4.2.2

Outside 0.4 *L* amidships, the scantlings of the deck plating and deck longitudinal stiffeners may be tapered to that required by Sec 8 at the ends of the cargo tank region.

- **2.4.3** Application of scantlings to inner bottom

#### 2.4.3.1

The thickness of inner bottom plating may vary along the length and breadth of a tank.

#### 2.4.3.2

The scantlings of the inner bottom plating and longitudinal stiffeners of midship cargo tanks are not to be less than that required for the corresponding location of the middle tanks of the cargo tank finite element model required by Appendix B/1.1.1.5. These scantlings are to be maintained for all tanks within the cargo region, other than the fore-most and aft-mos tcargo tanks.

#### 2.4.3.3

For the fore-most and aft-most cargo tanks, the scantlings of the inner bottom longitudinal stiffeners are not to be less than the scantling requirements for the midship cargo tanks provided that the spacing of primary support members are not reduced in the forward and/or aft cargo tank. The minimum net thickness of the inner bottom plate, *t_ib-net*, is given by:
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image653.png) mm
where:
*t_ib-net-mid* required net thickness of the inner bottom plating for the corresponding location in the midship tank, in mm
*l_bdg* effective bending span, of floor at location under consideration, in accordance with Fig 4.2.7, in m
*l_bdg-mid* effective bending span, of floor at corresponding location in midship tank, defined in accordance with Fig 4.2.7, in m
*s_ib* spacing between longitudinal stiffeners at location under consideration, in mm
*s_ib-mid* spacing between longitudinal stiffeners at corresponding location in midship tank, in mm

- **2.4.4** Application of scantlings to bottom

#### 2.4.4.1

The scantlings of bottom longitudinal stiffeners are to be maintained longitudinally within 0.4 *L* amidships. The scantlings of the bottom longitudinal stiffener at a given transverse location within 0.4 *L* amidships are not to be less than the maximum of that required for the corresponding transverse location along the length of the middle tanks of the cargo tank finite element model required by Appendix B/1.1.1.5.

#### 2.4.4.2

Outside 0.4 *L* amidships, the scantlings of the bottom longitudinal stiffeners may be tapered to that required by Sec 8 at the ends of the cargo region.

#### 2.4.4.3

The thickness of the bottom plating may vary along the length and breadth of a tank. The bottom plate thicknesses of midship tanks are not to be less than that required for the corresponding location of the middle tanks of the cargo tank finite element model required by Appendix B/1.1.1.5. These thicknesses are to be maintained for all tanks within the cargo region, other than the fore-most and aft-most cargo tanks.

#### 2.4.4.4

For the fore-most and aft-most cargo tanks, the required minimum net thickness of the bottom plating, *t_btm-net,* is to be obtained as follows:
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image654.png) mm
where:
*t_btm-net-mid* required net thickness of the bottom plating for the corresponding location in the midship tank, in mm
*l_bdg* effective bending span, of floor at location under consideration, in accordance with Fig 4.2.7, in m
*l_bdg-mid* effective bending span, of floor at corresponding location in midship tank, defined in accordance with Fig 4.2.7, in m
*s_btm* spacing between longitudinal stiffeners at location under consideration, in mm
*s_btm-mid* spacing between longitudinal stiffeners at corresponding location in midship tank, in mm

- **2.4.5** Application of scantlings to side shell, longitudinal bulkheads and inner hull longitudinal bulkheads

#### 2.4.5.1

The scantlings of plating and longitudinal stiffeners of side shell, longitudinal bulkheads and inner longitudinal bulkheads within 0.15 *D* from the deck are to be maintained longitudinally within 0.4 *L* amidships. The scantlings of plating and longitudinal stiffener at a given height are not to be less than the maximum of that required for the corresponding vertical location along the length of the middle tanks of the cargo tank finite element model required by Appendix B/1.1.1.5*.* Outside 0.4 *L* amidships, the scantlings of the plating and stiffeners within 0.15 *D* from the deck may be tapered to that required by Sec 8 at the ends of the cargo tank region.

#### 2.4.5.2

The plate thickness of side shell, longitudinal bulkheads and inner hull longitudinal bulkheads, including hopper plating, outside 0.15 *D* from the deck may vary along the length and height of a tank. The plate thickness away from the transverse bulkheads is not to be less than that required for the corresponding location of the middle tanks of the cargo tank finite element model required by Appendix B/1.1.1.5. These scantlings are to be maintained for all tanks within the cargo region, other than the fore-most and aft-most cargo tanks. For the fore-most and aft-most cargo tanks, the minimum net thickness of the side shell, longitudinal bulkheads or inner hull longitudinal bulkheads (including hopper plating) plating outside 0.15 *D* from the deck is given by:
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image655.png) mm
Where:
*t_net-mid* required net thickness for corresponding location in the midship tank, in mm
*s* spacing between longitudinal stiffeners at location under consideration, in mm
*s_mid* spacing between longitudinal stiffeners at corresponding location in midship tank, in mm

#### 2.4.5.3

The plate thickness of side shell, longitudinal bulkheads and inner hull longitudinal bulkheads, including hopper plating, in way of transverse bulkheads required for strengthening against hull girder shear loads is not to be less than that required by Appendix B/1.1.1.6, B/1.1.1.7 and B/1.1.1.8. Within 0.15 *D* from the deck, the plate thicknesses in way of transverse bulkheads are not to be taken as less than that required by 2.4.5.1. Outside 0.15 *D* from the deck, the plate thicknesses in way of transverse bulkheads are not to be taken as less than that required by 2.4.5.2.

#### 2.4.5.4

The scantlings of longitudinal stiffeners of side shell, longitudinal bulkheads, inner longitudinal bulkheads and hopper plate at a given height, outside 0.15 D from the deck, are not to be less than that required for the corresponding vertical location of the middle tanks of the cargo tank finite element model as required by Appendix B/1.1.1.5. These scantlings are to be maintained for all tanks within the cargo region.

#### 2.4.5.5

The plate thickness required for strengthening against hull girder shear loads of the side shell, longitudinal bulkheads and inner hull longitudinal bulkheads in way of a transverse bulkhead is to be taken as the greater from the corresponding vertical location of the forward and aft transverse bulkhead of the middle tanks of the cargo tank finite element model as required by Appendix B/1.1.1.5. All relevant requirements in other sections of the Rules are also to be complied with.

- **2.4.6** Application of scantlings to transverse bulkheads

#### 2.4.6.1

The scantlings of transverse bulkhead plating, stiffeners and horizontal stringers may vary along the height and breadth of the bulkhead. The scantlings at a given location are not to be less than the maximum required at the corresponding location of both middle tank end transverse bulkheads of the cargo tank finite element model as required by Appendix B/1.1.1.5.

- **2.4.7** Application of scantlings to primary structural support members

#### 2.4.7.1

The web thickness of primary structural support members may vary along the length, breadth and height of a tank. The scantlings of the primary structural support members are not to be less than that required for the corresponding location of the middle tanks of the cargo tank finite element model required by Appendix B/1.1.1.5. These scantlings are to be maintained for all tanks within the cargo region, other than the fore-most and aft-most cargo tanks.

#### 2.4.7.2

Scantling requirements for primary support members in the fore-most and aft-most cargo tanks are to be determined by scaling the scantlings of the corresponding structural members in the midship tanks in accordance with Sec 8/2.6.9.

- **2.4.8** Structural details and openings

#### 2.4.8.1

Arrangement and scantlings of openings and structural details of primary structural members, complying with the requirements of Appendix B/3*,* are to be applied to the corresponding structural members in all tanks within the cargo tank region.


### 3 Fatigue Strength

#### 3.1 Fatigue Evaluation

- **3.1.1** General

#### 3.1.1.1

This Sub-Section, together with Appendix C, gives the minimum Rule requirements for design against fatigue failure for the structural details stipulated in these Rules. Structural details at other locations that are considered to be critical may require assessment using a procedure consistent with that contained in these Rules.

#### 3.1.1.2

The fatigue criteria, applicable to a broad range of structural details and arrangements, are to be used for the assessment of fatigue strength utilising numerical techniques.

#### 3.1.1.3

The fatigue analysis is to be carried out using either a ‘*nominal stress approach’* or a ‘*hot spot stress approach*’ depending on the structural details, as specified in 3.4. The procedure is illustrated in Fig 9.3.1.

#### 3.1.1.4

In a *nominal stress approach,* stresses in a structural component are calculated by using either analytical methods (e.g. a beam model) or using numerical methods (e.g. a coarse finite elementmesh), based on the applied loads and the structural properties of the component.

#### 3.1.1.5

In a *hot spot stress approach,* local stresses at a critical location (hotspot) where fatigue cracks may initiate are evaluated by numerical methods (e.g. a fine mesh finite element analysis). The analysis takes into account the influence of structural discontinuities due to the geometry of the connection but excludes the effects of welds.

#### 3.2 Fatigue Criteria

- **3.2.1** Corrosion model

#### 3.2.1.1

Net thicknesses in accordance with Sec 6/3.3.7 are to be used in the fatigue assessment.

- **3.2.2** Loads

#### 3.2.2.1

The loads specified in Sec 7/3, which are based on the North Atlantic wave environment, are to be used for the fatigue assessment. Other secondary cyclic loading, such as slamming, low cycle, or vibration induced fatigue, which may result in significant levels of stress range over the expected lifetime of the vessel, although not within the scope of these Rules, may need to be specially considered.

#### 3.2.2.2

These Rules assume a $10 ^{-4}$ probability level of exceedance for the purposes of load application and fatigue strength assessment.

- **3.2.3** Acceptance criteria

#### 3.2.3.1

The criteria stated in this sub-section and *Appendix C* are presented as a comparison of fatigue strength of the structure (capacity), and fatigue inducing loads (demands), in the form of a fatigue damage parameter, *DM*, see Appendix C/1.4.1.1. The calculated fatigue damage, *DM*, is to be less than or equal to 1 for the design life of the ship, which is not to be taken as less than 25 years.

| Fig 9.3.1<br>Schematic of Fatigue Assessment Process<br>(For Each Location or Structural Detail) |
| --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image656.png) |

#### 3.3 Locations to Apply

- **3.3.1** Longitudinal structure

#### 3.3.1.1

A fatigue strength assessment is to be carried out and submitted for the end connections of longitudinal stiffeners to transverse bulkheads, including wash bulkheads and web frames within the cargo tank region, located on the bottom shell, inner bottom, side shell, inner hull longitudinal bulkheads, longitudinal bulkheads and strength deck.

#### 3.3.1.2

A fatigue strength assessment is to be carried out for scallops in way of block joints on the strength deck within the cargo tank region.

- **3.3.2** Transverse structure

#### 3.3.2.1

A fatigue strength assessment is to be carried out and submitted for the knuckle between inner bottom and hopper plate for at least one transverse frame close to amidships. The total stress range for fatigue assessment is to be determined from a fine mesh finite element analysis.

#### 3.4 Fatigue Assessment Methods

- **3.4.1** Nominal stress approach

#### 3.4.1.1

The nominal stress approach, as described in Appendix C/1, is to be used for the fatigue evaluation of the following items:

- **(a)** longitudinal stiffener end connections to the transverse bulkheads, including wash bulkheads, and web frames on the bottom, inner bottom, side shell, inner hull longitudinal bulkheads, longitudinal bulkheads and strength deck.
- **(b)** scallops in way of block joints on the strength deck as described in Appendix C/1.6.
- **3.4.2** Hot spot stress approach

#### 3.4.2.1

The hot spot stress approach, as described in Appendix C/2, is to be used for the fatigue evaluation of the following items*:*

- **(a)** knuckle between inner bottom and hopper plate.
- **3.4.3** Alternative direct calculation approach

#### 3.4.3.1

Where it is considered necessary to carry out a fatigue assessment using an alternative direct calculation approach, not applying the loads specified in Sec 7/3, it is to be based on the individual Classification Society’s procedures. However, in no case are the scantlings to be lower than those which would be required by 3.4.1 and 3.4.2.
