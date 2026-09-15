# PART 12 Common Structural Rules for Double Hull Oil Tankers

> RULES FOR CLASSIFICATION OF STEEL SHIPS / RA-12-E / 2025 / EN / Rules

## Appendix D Buckling Strength Assessment

### 1 Advanced Buckling Analysis

#### 1.1 General

- **1.1.1** Scope

#### 1.1.1.1

This appendix describes the advanced buckling analysis method and its application as required by the Rules. The advanced buckling analysis method is to be based on nonlinear analysis techniques, or equivalent, which predict the complex behaviour of stiffened and un-stiffened panels.

- **1.1.2** Alternative procedures

#### 1.1.2.1

While this appendix describes the general purpose or direct calculation techniques to be employed, alternative advanced buckling and ultimate strength analysis procedures may be used provided they give comparable and consistent results to those obtained using the reference advanced buckling procedure given in the Background to Appendix D which is the basis for the permissible buckling utilisation factors in Sec 9/Table 9.2.2. See also 1.1.2.3.

#### 1.1.2.2

Where an alternative advanced procedure is used, documentation of the alternative advanced buckling analysis methodologies and detailed comparison of its results with those of the reference advanced buckling procedure given in Background to Appendix D and software tools are to be supplied for review and acceptance.

#### 1.1.2.3

Use of alternative buckling procedures to the reference advanced buckling procedure is acceptable provided that the alternative procedure is verified against the test cases specified in the *Background to* Appendix D and where the permissible utilisation buckling factor for the alternative method, #eqnID-2844_t, complies with:
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1148.png)
Where:
$\eta _{all}$ permissible utilisation factor against buckling for plate and stiffened panels as specified in Sec 9/Table 9.2.2
$\eta _{ref-i}$ utilisation factor for reference advanced buckling procedure for test case $i$ specified in Background to Appendix D
$\eta _{alt-i}$ utilisation factor for alternative buckling procedure for test case $i$ specified in Background to Appendix D

- **1.1.3** Definitions

#### 1.1.3.1

“Buckling” is used as a generic term to describe the strength of structures, generally under in-plane compressions and/or shear. The buckling strength or capacity can take into account the internal redistribution of loads depending on the situation.

#### 1.1.3.2

Buckling capacity accepting local elastic plate buckling with load redistribution is referred to as Method 1. The buckling capacity is the load that results in the first occurrence of membrane yield stress anywhere in the stiffened panel. Buckling capacity based on this principle gives a lower bound estimate of ultimate capacity, or the maximum load the panel can carry without suffering major permanent set. Method 1 buckling capacity assessment utilizes the positive elastic post-buckling effect for plates and accounts for load redistribution between the structural components, such as between plating and stiffeners. For slender structures the capacity calculated using this method is typically higher than the ideal elastic buckling stress (minimum Eigen-value). Accepting elastic buckling of structural components in slender stiffened panels implies that large elastic deflections and reduced in-plane stiffness will occur at higher buckling utilization levels.

#### 1.1.3.3

Method 2 buckling capacity does not accept load redistribution between structural components and refers to the minimum of value of the ideal elastic buckling stress and the Method 1 buckling capacity. Method 2 buckling capacity normally equals the same strength as Method 1 for stocky panels, while it is the ideal elastic buckling stress (minimum Eigen-value cut-off) for slender panels. By applying the ideal elastic buckling stress limitation, large elastic deflections and reduced in-plane stiffness will be avoided at higher buckling utilization levels.

#### 1.1.3.4

A “buckling failure mode” refers to a specific pattern of buckling failure. Typical failure modes of stiffened panels with open profiles are:

- **(a)** plate buckling
- **(b)** torsional stiffener buckling
- **(c)** stiffener web plate buckling
- **(d)** lateral stiffener buckling.


### 2 Advanced Buckling Analysis Method

#### 2.1 General

- **2.1.1** Effects to consider

#### 2.1.1.1

The advanced buckling assessment method is to be capable of considering the following effects:

- **(a)** non linear geometrical behaviour
- **(b)** inelastic material behaviour
- **(c)** initial deflections - geometrical imperfections/out-of flatness
- **(d)** welding residual stresses
- **(e)** interactions between buckling modes and structural elements; plates, stiffeners, girders etc.
- **(f)** simultaneous acting loads; bi-axial compression/tension, shear and lateral pressure
- **(g)** boundary conditions.

#### 2.1.1.2

Detailed requirements for items listed in 2.1.1.1 are given in 2.1.2 to 2.1.8. Additional requirements applicable to non-linear finite element models are given in 2.1.9 and 2.1.10.

- **2.1.2** Non linear geometrical behaviour

#### 2.1.2.1

The buckling method is to be based on non-linear large deflection plate theory or equivalent. Second order membrane strains due to geometrical non-linearity are to be accounted for.

#### 2.1.2.2

Non-linear plate theory according to von Karman and Marguerre is acceptable for assessing the strength beyond the ideal elastic buckling level.

- **2.1.3** Material behaviour and properties

#### 2.1.3.1

Inelastic material behaviour is to be considered. If the buckling method is not capable of handling non linear material and spread of plasticity, then the redistributed stress fields due to non-linear geometrical behaviour and geometrical imperfections are to be limited to below the von Mises yield criterion.

#### 2.1.3.2

Alternatively, if the buckling method is capable of handling non linear material, then a bi-linear material model is to be used with a conservative strain-hardening coefficient in the plastic region.

#### 2.1.3.3

The material property assumptions are to use the characteristic values of yield strength and Young’s Modulus. Where appropriate, a bi-linear isotropic elasto-plastic material model excluding strain rate effects is to be used or the Tangent Modulus is to be taken as a conservative value. A plastic tangent modulus of 1000 Mpa is acceptable for normal and higher strength steel.

- **2.1.4** Initial deflections - geometrical imperfections/out-of-flatness

#### 2.1.4.1

Initial deflections are to be included in the buckling assessment.

#### 2.1.4.2

For the deterministic strength assessment the geometrical imperfections are to be transformed to a regular model pattern.

#### 2.1.4.3

The imperfections may be divided into local imperfections (plate out-of-flatness and stiffener sideways out-of-straightness), and global imperfections of the stiffeners (stiffener lateral/vertical out-of-straightness).

#### 2.1.4.4

The shape of the initial deflections is to be such that the most critical failure modes are represented and triggered by the analysis. In general, a combination of the lowest buckling Eigen-modes will be appropriate. Consideration is to be given in the case of plates with high slenderness and in the case of simultaneously acting loads, where the critical failure mode may be different from the lowest Eigen-modes.

#### 2.1.4.5

The default maximum values of the imperfections are to be taken to be consistent with the IACS Shipbuilding and Quality Repair Standard. However, regular model imperfection amplitudes may generally be taken less than the maximum tolerance specified. The regular model imperfections may typically be case dependant (load ratio dependant) and are also to cover imperfections due to welding. The actual level of model imperfections will depend on the method of analysis, extension of model, etc. and is to be approved by the individual Classification Society.

- **2.1.5** Welding induced residual stress

#### 2.1.5.1

Residual stresses are not required to be explicitly included in the buckling assessment, see 2.1.4.5.

- **2.1.6** Interactions between buckling modes and structural elements

#### 2.1.6.1

The advanced buckling analysis method is to accurately model the interactions between the various structural components and hence between the different buckling modes.

#### 2.1.6.2

All the critical initial imperfection shapes are to be included, see 2.1.4.

- **2.1.7** Simultaneous acting loads

#### 2.1.7.1

The method is to be able to model any combination of biaxial in-plane compressive and shear membrane loads and lateral pressure.

#### 2.1.7.2

Any lateral pressure is to be applied first, in order to generate the deformed shape. The lateral pressure is then to be kept constant.

#### 2.1.7.3

The effect of lateral pressure enforcing deflections in different patterns than in-plane loads is to be included in such a way that the most critical buckling mode is developed.

- **2.1.8** Boundary conditions

#### 2.1.8.1

The boundary conditions are to represent the actual response of the plate or stiffened panel. In-plane and out-of-plane boundary conditions are to be considered.

#### 2.1.8.2

Where a panel is an integral part of a larger continuous area of stiffened plating, such as bottom or side panels, the edges may be taken as free to move in-plane, but forced to remain straight. Where a panel is not supported in-plane by adjacent structure, such as a stringer web panel or bottom girder web, then the edges are to be considered as completely free.

#### 2.1.8.3

Rotational restraint on the plate from the stiffeners is to be accounted for by direct analysis of the plate and stiffener interaction. Prescribed boundary conditions are, in general, not acceptable.

#### 2.1.8.4

The panels can be taken as supported in the lateral/vertical direction at the primary support members. The stiffeners may be taken as horizontally supported at the crossing of primary support members (preventing tilting at crossings). Geometrical rotational restraint of the plate from the primary support members is to be neglected.

- **2.1.9** Model extent

#### 2.1.9.1

The extent of the model used in the buckling assessment is to be sufficient to account for the structure that is surrounding the panel of interest, and to reduce the uncertainties introduced through the boundary conditions.

#### 2.1.9.2

In general, the model is to include more than one stiffener span in the stiffener direction and the portion between two primary support members in the direction normal to the stiffeners.

#### 2.1.10

Element size for non-linear finite element models

#### 2.1.10.1

The element size is to be small enough to describe the buckling deflections accurately.

#### 2.1.10.2

The mesh size will depend on the complexity of the geometry and loads and the type of element used, but a minimum of five elements across a half-buckling wave length is generally required.


### 3 Application and Structural Modelling Principles

#### 3.1 General

- **3.1.1** Scope

#### 3.1.1.1

The following specifies the standard assumptions to be applied for the application of the advanced buckling method. These assumptions may be refined when the advanced buckling method is capable of more accurate representation of the structure.

- **3.1.2** Boundary conditions

#### 3.1.2.1

The boundary conditions are to accurately account for the in-plane and rotational constraints imposed by the adjacent structures (such as stiffeners, primary support members and adjacent plates). The assumptions defined in 3.1.2.3 to 3.1.2.4 are to be applied.

#### 3.1.2.2

The boundary conditions are divided into two main groups being representative for “free edge plating” and “continuous plating”. The latter group represents large stiffened panels such as deck plating, bottom plating, ship sides, etc., while the other represents girders, floors, stringers, etc.

#### 3.1.2.3

The continuous plating condition is representative for elements having in-plane support conditions by the surrounding structure. The boundary conditions for stiffened panels are to be taken as:

- **(a)** panel edges perpendicular to stiffeners are to be considered simply supported
- **(b)** panel edges parallel to stiffeners are to be considered as having rotational support equivalent to that provided by stiffeners within the panel
- **(c)** the ends of stiffeners are to be considered as part of a continuous panel and supported sideways by the primary support members
- **(d)** all edges of the panel are to be constrained to remain straight but are free to displace inwards.

#### 3.1.2.4

Free edge plating conditions are representative for elements having weak in-plane support along one or more edges, e.g. vertically stiffened double bottom floors. The boundary conditions for stiffened panels are to be taken as:

- **(a)** panel edges perpendicular to stiffeners are to be considered simply supported
- **(b)** panel edges parallel to stiffeners are to be considered as having rotational support equivalent to that provided by stiffeners within the panel
- **(c)** the ends of stiffeners are to be considered as supported sideways when attached directly to adjacent structure, otherwise they are to be assumed simply supported
- **(d)** all free edges of the panel are free to displace inwards. Rotational restraints of the edge reinforcements on the free edges may be considered.

#### 3.1.2.5

The boundary conditions for un-stiffened panels are to be taken as:

- **(a)** panel edges are to be considered simply supported unless otherwise stated
- **(b)** free edges of the panel, if any, are free to displace inwards. The continuous edges are to be constrained to remain straight.
- **3.1.3** Structural idealisation

#### 3.1.3.1

The structural modelling and buckling assessment method applicable for free edge plating is to be taken as:

- **(a)** parallel to the stiffener direction: one frame bay is normally sufficient for structures having significant stress gradients. For uniformly compressed elements with the free edges parallel to the stiffener direction, such as longitudinal girders, multi-bay models are to be considered
- **(b)** normal to the stiffener direction: between primary support members, but may be limited to six stiffener spacings
- **(c)** assessment method: Method 2 - buckling capacity with no allowance for redistribution of load unless otherwise specified.

#### 3.1.3.2

The structural modelling and buckling assessment method applicable for continuous plating is to be taken as:

- **(a)** parallel to the stiffener direction: at least two frame bays, in order to model imperfections between adjacent panels
- **(b)** normal to the stiffener direction: between primary support members, but may be limited to six stiffener spacings
- **(c)** assessment method: Method 1 - buckling capacity with allowance for redistribution of load unless otherwise specified.


### 4 Assessment Criteria

#### 4.1 General

- **4.1.1** Buckling strength assessment methods

#### 4.1.1.1

The buckling capacity value is to be based on one of the following assessment methods:
The application of which assessment method to use is given in 3.1.3

- **(a)** Buckling Capacity with allowance for redistribution of load
- **(b)** Buckling Capacity with no allowance for redistribution of load
- **4.1.2** Method 1: Buckling capacity with allowance for redistribution of load

#### 4.1.2.1

The buckling capacity value is to be taken as the load that results in the first occurrence of membrane yield stress anywhere in the stiffened panel. This includes the redistribution of load as indicated in 1.1.3.2. In particular the following locations are to be checked for von Mises stresses equivalent to yield:

- **(a)** at the edges of the plate
- **(b)** along the line of intersection of the plate and stiffeners, especially at the ends of the stiffener and at the stiffener mid point
- **(c)** along the flanges of the stiffeners, especially at the ends of the stiffener and at the stiffener mid point.
- **4.1.3** Method 2: Buckling capacity with no allowance for redistribution of load

#### 4.1.3.1

The buckling capacity value or the load that results in the first occurrence of membrane yield stress anywhere in the stiffened panel, see 1.1.3.3.

#### 4.2 Utilisation Factors

- **4.2.1** General

#### 4.2.1.1

The utilisation factor, $\eta$, is used as a measure of safety margin against buckling strength failure. The utilisation factor is defined as the ratio between the applied loads and the corresponding ultimate capacity or buckling strength.

#### 4.2.1.2

A structure is considered to have an acceptable buckling strength if it satisfies the following criteria:
$\eta _{act} \leq \eta _{allow}$
Where:
$\eta _{allow}$ allowable buckling utilisation factor, as defined in Sec 9/2.2.5
$\eta _{act}$ actual buckling utilisation factor based on the applied design loads

#### 4.2.1.3

For combined loads, the utilisation factor, $\eta$, is to be taken as the ratio between the applied equivalent load and the corresponding buckling capacity, see Fig D.4.1, and is to be taken as:
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1149.png)
Where:
*W_act* applied equivalent load due to the combined membrane loads
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1150.png) $\mathrm{N}/mm ^{2}$
*W_u* equivalent load due to the combined membrane loads which results in the buckling capacity point, see Fig D.4.1
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1151.png) $\mathrm{N}/mm ^{2}$
Where the combined loads are all factored by the same ratio and the applied pressure load is to be kept constant
σ_dx applied axial stress in *x* direction, in $\mathrm{N}/mm ^{2}$
σ_dy applied axial stress in *y* direction, in $\mathrm{N}/mm ^{2}$
t_d applied shear stress, in $\mathrm{N}/mm ^{2}$
σ_cx buckling strength due to compression in *x* direction, in $\mathrm{N}/mm ^{2}$
σ_cy buckling strength due to compression in *y* direction, in $\mathrm{N}/mm ^{2}$
t_cr buckling strength in shear, in $\mathrm{N}/mm ^{2}$

| Fig D.4.1<br>Definition of Utilisation Factor Example Showing a Bi-Axial Loading Pattern |
| --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1152.png) |


### 5 Strength Assessment (FEM) - Buckling Procedure

#### 5.1 General

- **5.1.1** Scope

#### 5.1.1.1

The following procedure is to be used for the assessment of the buckling requirements for the Strength Assessment (FEM) as part of the Design Verification procedure, see Sec 9/2.

#### 5.1.1.2

All structural elements in the finite element analysis are to be assessed individually. Each stiffener with attached plate and all un-stiffened panels are to be assessed.

#### 5.1.1.3

The buckling performance of each member is considered acceptable if it satisfies the following criterion:
$\eta _{act} \leq \eta _{allow}$
Where
$\eta _{allow}$ allowable buckling utilisation factor, as defined in Sec 9/2.2.5
$\eta _{act}$ actual buckling utilisation factor based on the applied design loads, see 4.2.1

#### 5.2 Structural Modelling and Capacity Assessment Method

- **5.2.1** General

#### 5.2.1.1

The longitudinally effective structure of the hull girder is to be modelled as stiffened panels or un-stiffened panels as specified in Table D.5.1 and Fig D.5.1. These provide the standard assumptions to be used for the buckling capacity assessment method.

#### 5.2.1.2

The structural models are to be based on the net thickness obtained by deducting the full corrosion addition, i.e. -1.0 *t_corr*, and any owner’s extras from the proposed thickness. This thickness reduction applies to the plating and the stiffener web and face plate.

- **5.2.2** Stiffened panels

#### 5.2.2.1

Each stiffener with attached plate is to be represented as a stiffened panel of the extent defined in Table D.5.1 and hence is assumed to be part of a larger structural entity to correctly model the overall buckling behaviour.

#### 5.2.2.2

In general, the assessment method is to model changes in plate thickness, stiffener size and spacing. However where the advanced buckling method is unable to correctly model these changes, the calculations are to be performed separately for each stiffener and plate between the stiffeners. Plate thickness, stiffener properties and stiffener spacing at the considered location are to be assumed for the whole panel. If the plate thickness, stiffener properties and stiffener spacing varies within the stiffened panel, the calculations are to be performed for all configurations of the panel. Where the panel between stiffeners consists of several plate thickness the weighted average thickness may by used for the thickness of the plating for assessment of the corresponding stiffener/plating combination. Calculation of weighted average is to be in accordance with 5.2.3.3. See Fig D.5.6.

- **5.2.3** Un-stiffened panels

#### 5.2.3.1

The assessment method is to model changes in plate thickness and panel geometry.

#### 5.2.3.2

In way of web frames, stringers and brackets, the geometry of the panel (i.e. plate bounded by web stiffeners/face plate) may not have a rectangular shape. Where the advanced buckling method is unable to correctly model the panel geometry, then an equivalent rectangular panel is to be defined as shown in Fig D.5.5. Where web stiffeners are not connected to the intersecting stiffeners, then the panel may be defined as shown in Fig D.5.6. The FE analysis is to represent the actual structure in order to derive realistic stress values for application to the equivalent rectangular panel. The stresses of all elements whose centroids are within the equivalent plate panel are to be considered for stress average in accordance with 5.3.2.1.

#### 5.2.3.3

Where the advanced buckling method is unable to correctly model changes in net plate thickness across a panel, and the panel consists of a number of finite plate elements, then the average thickness is to be taken as:
$t _{avr} = \frac{\sum _{} ^{} A _{j} t _{j}}{\sum _{} ^{} A _{j}}$
Where:
$A _{j}$ area of the *j^th* plate element making up the panel
$t _{j}$ net thickness of the *j^th* plate element making up the panel

**Table D.5.1<br>Structural Elements for the Strength Assessment (FEM)**

| Structural elements | Idealisation | Assessment method<sup>(1)</sup> | Normal panel definition<sup>(2)</sup> |   |
| --- | --- | --- | --- | --- |
| Longitudinal structure, see Fig D.5.1 |   |   |   |   |
| Longitudinally stiffened panels<br>Shell envelope<br>Deck<br>Inner hull<br>Hopper tank side<br>Longitudinal bulkheads<br>Centreline bulkheads | Stiffened panel | Method 1 |   | Length: between web frames<br>Width : between primary support members (PSM)<sup>(2)</sup> |
| Double bottom longitudinal girders in line with longitudinal bulkhead or connected to hopper tank side | Stiffened panel | Method 1 |   | Length: between web frames<br>Width : full web depth |
| Web of horizontal girders in double side tank connected to hopper tank side | Stiffened panel | Method 1 |   | Length: between web frames<br>Width: full web depth |
| Web of double bottom longitudinal girders not in line with longitudinal bulkhead or not connected to hopper tank side | Stiffened panel | Method 2 |   | Length: between web frames<br>Width: full web depth |
| Web of horizontal girders in double side tank not connected to hopper tank side | Stiffened panel | Method 2 |   | Length: between web frames<br>Width: full web depth |
| Web of single skin longitudinal girders | Un-stiffened panel | Method 2 |   | Between local stiffeners/face plate/PSM |
| Transverse structure, see Fig D.5.2 |   |   |   |   |
| Web of transverse deck girders including brackets | Un-stiffened panel | Method 2 |   | Between local stiffeners/face plate/PSM |
| Vertical web in double side tank | Stiffened panel | Method 2 |   | Length: full web depth<br>Width: between primary support members |
| All irregularly stiffened panels, e.g.<br>Web panels in way of hopper tank and bilge | Un-stiffened panel | Method 2 |   | Between local stiffeners/face plate/PSM |
| Double bottom floors | Stiffened panel | Method 2 |   | Length: full web depth<br>Width: between primary support members |
| Vertical web frame including brackets | Un-stiffened panel | Method 2 |   | Between vertical web stiffeners/face plate/PSM |
| Cross tie web plate | Un-stiffened panel | Method 2 |   | Between vertical web stiffeners/face plate/PSM |
| Transverse oil-tight and watertight bulkheads, see Fig D.5.3 and transverse wash bulkheads, see Fig D.5.4 |   |   |   |   |
| All regularly stiffened bulkhead panels | Stiffened panel | Method 1 |   | Length: between primary support members<br>Width: between primary support members |
| Regularly stiffened bulkhead with secondary buckling stiffeners perpendicular to regular stiffeners<sup>(3)</sup> | Stiffened panel | Method 1 |   | Length: between primary support members<br>Width: between primary support members |
| All irregularly stiffened bulkhead panels, e.g. web panels in way of hopper tank and bilge | Un-stiffened panel | Method 2 |   | Between local stiffeners/face plate |
| Web plate of bulkhead stringers including brackets | Un-stiffened panel | Method 2 |   | Between web stiffeners/face plate |
| Transverse corrugated bulkheads |   |   |   |   |
| Upper/lower stool including stiffeners | Stiffened panel | Method 1 |   | Length: between internal web diaphragms<br>Width: length of stool side |
| Stool internal web diaphragm | Un-stiffened panel | Method 2 |   | Between local stiffeners/face plate/PSM |
| Note<br>1. The assessment method specifies which buckling strength assessment method is to be used, see 4.1<br>2. See structural idealisation, 3.1.3.<br>3. The secondary stiffener can be modelled as “sniped” or “continuous”. The stiffener is considered “sniped” unless rotational end supports are provided at both ends<br>An area stiffened by irregular buckling stiffeners only should be assessed by considering each plate in the panel as Unstiffened panel using Method 2. |   |   |   |   |

| Fig D.5.1<br>Advanced Buckling Assessment for longitudinal strength |
| --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1153.png) |
| #underline{Notes}<br>1. SP - M1 denotes stiffened panel - buckling strength assessed using Method 1<br>2. SP - M2 denotes stiffened panel - buckling strength assessed using Method 2 |

| Fig D.5.2<br>Transverse Web Frames |
| --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1154.png) |
| #underline{Notes}<br>SP - M1 denotes Stiffened Panel - buckling strength assessed using Method 1<br>UP - M2 denotes Un-stiffened Panel - buckling strength assessed using Method 2<br>SP - M2 denotes Stiffened Panel - buckling strength assessed using Method 2 |

| Fig D.5.3<br>Transverse Bulkhead |
| --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1155.png) |
| #underline{Notes}<br>SP - M1 denotes Stiffened Panel - buckling strength assessed using Method 1<br>UP - M2 denotes Un-stiffened Panel - buckling strength assessed using Method 2 |

| Fig D.5.4<br>Cross Tie |
| --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1156.png) |
| #underline{Notes}<br>SP - M1 denotes Stiffened Panel - buckling strength assessed using Method 1<br>UP - M2 denotes Un-stiffened Panel - buckling strength assessed using Method 2<br>SP - M2 denotes Stiffened Panel - buckling strength assessed using Method 2 |

| Fig D.5.5<br>Modelling of an Un-stiffened Panel with Irregular Geometry |
| --- |
| (a) The four corners closest to a right angle, 90 degrees, in the bounding polygon for the plate are identified.<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1157.png) |
| (b) The distances along the plate bounding polygon between the corners are calculated, i.e. the sum of all the straight line segments between the end points.<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1158.png) |
| (c) The pair of opposite edges with the smallest total length is identified, i.e. minimum of $d _{1} +d _{3}$ and $d _{2} +d _{4}$. |
| (d) A line is joined between the middle points of the chosen opposite edges (i.e. a mid point is defined as the point at half the distance from one end). This line defines the longitudinal direction, $x _{1}$, for the capacity model. The length of the line defines the length of the capacity model, $l _{1}$ or $d _{2}$ measured from one end point.<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1159.png) |
| (e) The width of the model, $l _{2}$, is to be taken as:<br>$l _{2} = A _{pl} / l _{1}$<br>Where:<br>$A _{pl}$ area of the plate<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1160.png) |
| (f) The stresses from the FE analysis are to be resolved into the local coordinate system of the equivalent rectangular panel. These stresses are to be used for the buckling assessment. |

| Fig D.5.6<br>Capacity Model for Web Plate |
| --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1161.png) |
| #underline{Note}<br>The correction of panel breadth is applicable also for other slot configurations provided that the web or collar plate is attached to at least one side of the passing stiffener. |

#### 5.3 Load Application

- **5.3.1** General

#### 5.3.1.1

The ultimate capacity or buckling strength is to be assessed for the effects of the combined bi-axial and shear membrane stresses acting on the structural panel.

#### 5.3.1.2

The axial compressive and shear stress distribution is to be taken from the FE analysis and applied to the buckling model. The stresses from the FE analysis are not to be adjusted for the required change in thickness for buckling, i.e. -0.5 *t_corr* used in the FE analysis and 1.0 *t_corr* used for the buckling assessment.

#### 5.3.1.3

The lateral pressure applied to the FE analysis is also to be applied to the buckling assessment.

#### 5.3.1.4

The stresses may be applied by means of enforced displacements obtained from the finite element analysis to the panel edges or by loads applied to the panel edges.

#### 5.3.1.5

Where the advanced buckling method is unable to correctly model changes in axial or shear stress across a panel, then the stresses and pressures may be averaged as defined in 5.3.2 and 5.3.3.

- **5.3.2** Average membrane stresses

#### 5.3.2.1

When the plate panel consists of a number of finite plate elements, the average membrane stress is to be calculated using a weighted average approach, as given by:
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1162.png) $\mathrm{N}/mm ^{2}$
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1163.png) $\mathrm{N}/mm ^{2}$
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1164.png) $\mathrm{N}/mm ^{2}$
Where:
*σ_xmi* membrane stress in *x*-direction at the centroid of the *i^th* plate element of the panel, in $\mathrm{N}/mm ^{2}$
*σ_ymi* membrane stress in *y*-direction at the centroid of the *i^th* plate element of the panel, in $\mathrm{N}/mm ^{2}$
*τ_xymi* membrane shear stress at the centroid of the *i^th* plate element of the panel, in $\mathrm{N}/mm ^{2}$
*A_i* area of the *i*thplateelementmakingupthepanel, in $\mathrm{mm} ^{2}$
*n* number of elements in the panel
When *σ_xmi* or *σ_ymi* are in tension, then the respective value is to be taken as zero.

- **5.3.3** Average lateral pressure

#### 5.3.3.1

Where the plate panel consists of a number of finite elements, the average pressure, *P_avr*, is to be calculated using a weighted average approach, as given by:
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1165.png) $\mathrm{kN}/m ^{ 2}$
Where:
*P_i* pressure acting on the *i^th* plate element making up the panel, in $\mathrm{kN}/m ^{ 2}$
*A_i* area of the *i^th* plate element making up the panel, in $\mathrm{mm} ^{2}$
*n* number of elements in the panel

#### 5.4 Limitations of the Advanced Buckling Assessment Method

- **5.4.1** General

#### 5.4.1.1

In the absence of a suitable advanced buckling method, then the following structural elements can be assessed according to Table D.5.2.

**Table D.5.2<br>Requirements for Structures Where There is no Advanced Buckling Method Available**

| Structural elements | Buckling mode | Rule reference |
| --- | --- | --- |
| bilge plate | transverse elastic buckling | Sec 8/2.2.3 |
| primary support members | global (overall) buckling and torsional buckling | Sec 10/2.3 |
| web plate of primary support members in way of openings | buckling of web plate | Sec 10/3.4 |
| cross ties | global (overall) buckling | Sec 10/3.5 |
| corrugated bulkheads | flange panel buckling | Sec 10/3.2 |
| corrugated bulkheads | global (overall) buckling | Sec 10/3.5 |


### 6 Ultimate Hull Girder Strength Assessment

#### 6.1 General

- **6.1.1** Scope

#### 6.1.1.1

This procedure is required for the assessment of the ultimate hull girder strength assessment as part of the Design Verification procedure, see Sec 9/1.

#### 6.1.1.2

All structural elements of the strength deck are to be assessed individually.

#### 6.2 Load Application

- **6.2.1** General

#### 6.2.1.1

The uni-axial compressive stress used for the ultimate capacity assessment of longitudinally stiffened deck panels is to be calculated at the stiffener/plate intersection point.

#### 6.2.1.2

The hull girder stresses are based on the section modulus properties using a deduction of half the corrosion addition, i.e. -0.5 *t_corr*, and owner’s extra from the proposed thickness.

#### 6.2.1.3

Lateral pressure is not to be included in the buckling assessment for hull girder ultimate strength.

#### 6.3 Structural Modelling and Buckling Assessment

- **6.3.1** General

#### 6.3.1.1

The longitudinally effective structure of the strength deck is to be modelled as stiffened panels using Method 1 to derive the ultimate capacity.

#### 6.3.1.2

Each deck stiffener with attached plate is to be represented as a stiffened panel with the transverse extent being between two adjacent primary support members.

#### 6.3.1.3

The buckling capacity models are to be based on the net thickness obtained by deducting half the corrosion addition, i.e. -0.5 *t_corr*, and any owner’s extras from the proposed thickness. This thickness reduction applies to the plating and the stiffener web and face plate.

#### 6.3.1.4

In general, the assessment method is to correctly model changes in plate thickness, stiffener size and spacing. However where the advanced buckling method is unable to correctly model these changes, the calculations are to be performed separately for each stiffener and plate between the stiffeners. Plate thickness, stiffener properties and stiffener spacing at the considered location are to be assumed for the whole panel. If the plate thickness, stiffener properties and stiffener spacing varies within the stiffened panel, the calculations are to be performed for all configurations of the panel.

| **Rules for the Classification of Steel Ships** |
| --- |
| **PART 12 COMMON STRUCTURAL RULES FOR DOUBLE HULL OIL TANKERS**<br>Published by<br>**KR**<br>36, Myeongji ocean city 9-ro, Gangseo-gu,<br>BUSAN, KOREA<br>TEL : +82 70 8799 7114<br>FAX : +82 70 8799 8999<br>Website : http://www.krs.co.kr |
|   |

| CopyrightⒸ 2014, KR<br>Reproduction of this Rules in whole or in parts is prohibited without permission of the publisher. |
| --- |
