# PART 12 Common Structural Rules for Double Hull Oil Tankers

> RULES FOR CLASSIFICATION OF STEEL SHIPS / RA-12-E / 2025 / EN / Rules

## Appendix C Fatigue Strength

### 1 Nominal Stress Approach

#### 1.1 General

- **1.1.1** Applicability

#### 1.1.1.1

This sub-section defines the procedure for a simplified fatigue assessment which is to be used to evaluate the fatigue strength of the ships structural details. The fatigue assessment uses a nominal stress approach based on beam theory.

#### 1.1.1.2

The fatigue assessment is to be applied to welded connections where the steel has a minimum yield strength of less than 400 $\mathrm{N}/mm ^{2}$.

- **1.1.2** Assumptions

#### 1.1.2.1

The following assumptions are made in the fatigue assessment:

- **(a)** a linear cumulative damage model, i.e. Palmgren-Miner’s Rule, has been used in connection with the S-N data in 1.4.5
- **(b)** for longitudinal stiffener end connections, nominal stresses obtained by empirical formulae, see 1.4.2 to 1.4.4, and Rule based loads, see 1.3, form the basis of the nominal stress based fatigue assessment
- **(c)** the long term stress ranges of a structural detail can be characterized using a modified Weibull probability distribution parameter, $\xi$, as described in 1.4.1.5 and 1.4.1.6
- **(d)** structural details are idealised and classified in 1.5.

#### 1.1.2.2

The structural detail classification in 1.5 is based on typical joint geometry under simple loadings. When a structural detail is considered different from those shown in 1.5, a suitable finite element (FE) analysis should be used to demonstrate the adequacy of the detail in terms of fatigue strength. See 2.1.1.3.

#### 1.1.2.3

Where the loading or geometry considered is too complex for a simple classification, a finite element (FE) analysis of the detail is to be carried out to determine the fatigue stress of that detail. Sub-sec 2 defines the procedure for a finite element based assessment to determine hot spot stresses that is to be used for weld toe locations that are typically found at welded hopper knuckle connections in way of transverse primary support members. For bent type knuckle connections, recommendation is given in 2.1.1.2.

#### 1.2 Corrosion Model

- **1.2.1** Net thickness

#### 1.2.1.1

The net thickness and corrosion additions, as indicated in Sec 6/3 are to be incorporated into the representation of the structural capacity models.

#### 1.3 Loads

- **1.3.1** General

#### 1.3.1.1

Ship structures are subjected to various types of loads, which include:

- **(a)** static loads including cargo and lightship weights
- **(b)** wave induced loads
- **(c)** impact loads, such as bottom slamming, bow flare impacts and sloshing in partially filled tanks
- **(d)** cyclic loads resulting from main engine or propeller induced vibratory forces
- **(e)** transient loads such as thermal loads
- **(f)** residual stresses.

#### 1.3.1.2

The fatigue strength analysis considers the following wave induced loads for calculation of the long term distribution of stresses:

- **(a)** hull girder loads (i.e. vertical and horizontal wave bending moments)
- **(b)** dynamic wave pressures
- **(c)** dynamic tank pressure loads resulting from ship motions.
- **1.3.2** Selection of loading conditions

#### 1.3.2.1

Fatigue analyses are to be carried out for representative loading conditions according to the intended ship’s operation. The following two loading conditions are to be examined:

- **(a)** full load condition at design draught at departure, *T_full*, see Sec 4/1.1.5.4
- **(b)** ballast condition at normal ballast draught at departure, *T_bal-n*, see Sec 4/1.1.5.3. If a normal ballast condition is not defined in the loading manual, minimum ballast draught, *T_bal*, see Sec 4/1.1.5.2, should be used.
- **1.3.3** Determination of loads

#### 1.3.3.1

Loads applied to the structure are to be calculated in order to determine the stress ranges for the relevant loading conditions.

#### 1.3.3.2

Combined stresses resulting from the action of global and local loads are to be calculated in accordance with 1.4.4*,* with consideration given to the probability level of $10 ^{-4}$.

- **1.3.4** Vertical wave bending moment

#### 1.3.4.1

The vertical wave bending moment is to be calculated based on Sec 7/3.4.1. The pseudo amplitude (half range) values of the vertical wave bending moment, *M_wv-v-amp*, for full load and ballast condition are to be taken as:
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1041.png) kNm
Where:
*M_wv-hog* hogging vertical wave bending moment, in kNm
*M_wv-sag* sagging vertical wave bending moment, in kNm

- **1.3.5** Horizontal wave bending moment

#### 1.3.5.1

The horizontal wave bending moment is to be calculated based on Sec 7/3.4.2. The pseudo amplitude (half range) values of the horizontal wave bending moment, *M_wv-h-amp*, for full load and ballast condition are to be taken as:
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1042.png) kNm
Where:
*M_wv-h-pos* positive horizontal wave bending moment, in kNm
= *M_wv-h*
*M_wv-h-neg* negative horizontal wave bending moment, in kNm
= -*M_wv-h*

- **1.3.6** Dynamic wave pressure

#### 1.3.6.1

The dynamic wave pressure is to be calculated according to Sec 7/3.5.2.

#### 1.3.6.2

Considering the stretching of the external pressure due to intermittent wet and dry area, a pseudo amplitude of external pressure (half pressure range), *P_ex-amp*, is defined in Sec 7/3.5.2.3 in detail and illustrated in Fig C.1.1.

| Fig C.1.1<br>Dynamic Pressure |
| --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1043.png) |

- **1.3.7** Dynamic tank pressure

#### 1.3.7.1

The dynamic tank pressure amplitude, *P_in-amp­*, is to be calculated according to Sec 7/3.5.4.5 and Sec 7/3.5.4.6. No dynamic internal pressure is considered for the deck.

#### 1.4 Fatigue Damage Calculation

- **1.4.1** Fatigue strength determination

#### 1.4.1.1

The fatigue assessment of the structure is based on the application of the Palmgren-Miner cumulative damage rule given below. When the cumulative fatigue damage ratio, *DM*, is greater than 1, the fatigue capability of the structure is not acceptable. *DM* is to be taken as:
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1044.png)
Where:
$n _{i}$ number of cycles of stress range $S _{i}$
$N _{i}$ number of cycles to failure at stress range $S _{i}$
$n _{tot}$ total number of stress range blocks

#### 1.4.1.2

Assessment of the fatigue strength of welded structural members includes the following three phases:

- **(a)** calculation of stress ranges
- **(b)** selection of the design S-N curve
- **(c)** calculation of the cumulative damage.

#### 1.4.1.3

The cumulative fatigue damage ratio, *DM*, is to be less than 1 for the design life of the ship. The design life is not to be less than 25 years. Unless other wise specified the resultant cumulative damage is to be taken as:
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1045.png)
Where:
*DM_i* cumulative fatigue damage ratio for the applicable loading condition
*i* = 1 for full load condition
= 2 for normal ballast condition

#### 1.4.1.4

Assuming the long term distribution of stress ranges fit a two-parameter Weibull probability distribution, the cumulative fatigue damage *DM_i* for each relevant condition is to be taken as:
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1046.png)
Where:
$N _{L}$ number of cycles for the expected design life. Unless stated otherwise, $N _{L}$ to be taken as:
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1047.png)
The value is generally between $0.6 \times 10 ^{8}$ and $0.8 \times 10 ^{8}$ cycles for a design life of 25 years
$f _{0}$ 0.85, factor taking into account non-sailing time for operations such as loading and unloading, repairs, etc.
$U$ design life, in seconds
= $0.788 \times 10 ^{9}$ for a design life of 25 years
$L$ rule length, in m, as defined in Sec 4/1.1.1.1
$m$ S-N curve parameter as defined in 1.4.5.5
$K _{2}$ S-N curve parameter as defined in 1.4.5.5
$\alpha _{i}$ proportion of the ship's life:
$\alpha _{1}$ = 0.5 for full load condition
$\alpha _{2}$ = 0.5 for ballast condition
$S _{Ri}$ stress range at the representative probability level of $10 ^{-4}$, in $\mathrm{N}/mm ^{2}$
$N _{R}$ 10,000, number of cycles corresponding to the probability level of $10 ^{-4}$
$\xi$ Weibull probability distribution parameter, as defined in 1.4.1.6
$\Gamma$ Gamma function
$\mu _{i}$ coefficient taking into account the change in slope of the S-N curve
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1048.png)
$v _{i}$ ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1049.png)
$S _{q}$ stress range at the intersection of the two segments of the S-N curve, see Table C.1.6, in $\mathrm{N}/mm ^{2}$
$\Delta m$ slope change of the upper-lower segment of the S-N curve
= 2
$\gamma (a,x)$ incomplete Gamma function, Legendre form

#### 1.4.1.5

The probability density function of the long term distribution of stress ranges (hull girder + local bending) is to be represented by a two-parameter Weibull distribution. This assumption enables the use of a closed form equation for calculation of the fatigue life when the two parameters of the Weibull distribution are determined. The probability density function, *f(S)*, is to be taken as:
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1050.png)
Where:
$S$ stress range, in $\mathrm{N}/mm ^{2}$
$\xi$ Weibull probability distribution parameter, as defined in 1.4.1.6
$f _{1}$ scale parameter
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1051.png)
$N _{R}$ number of cycles corresponding to the probability of exceedance of 1/$N _{R}$
$S _{R}$ stress range with probability of exceedance of 1/$N _{R}$, in $\mathrm{N}/mm ^{2}$

#### 1.4.1.6

For each structural detail considered, the Weibull shape parameter is to be selected with due consideration given to the load categories contributing to the cyclic stresses. $\xi$, is to be taken as:
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1052.png)
Where:
*L* rule length, in m, as defined in Sec 4/1.1.1.1
*D* moulded depth, in m, as defined in Sec 4/1.1.4.1
*f_Weibull* area dependent modification factor, as given in Table C.1.1 and Fig C.1.2

**Table C.1.1<br>Distribution of *f_Weibull* Factors**

| Plating area | *f_Weibull* (see note) |
| --- | --- |
| Bottom | 0.9 at centreline and 0.95 at side |
| Side and bilge | 1.1 at up to draught *T_LC* and 1.0 at deck |
| Deck | 1.0 |
| Inner bottom | 1.0 |
| Inner hull longitudinal bulkhead | 1.1 up to D/2 and 1.0 at deck |
| Inner longitudinal bulkhead | 1.1 up to D/2 and 1.0 at deck |
| Centreline longitudinal bulkhead | 1.1 up to D/2 and 1.0 at deck |
| Note: Intermediate values to be linearly interpolated |   |

| Fig C.1.2<br>Distribution of *f_Weibull* Factors |
| --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1053.png) |

#### 1.4.1.7

The cumulative fatigue damage ratio, *DM*, may be converted to a calculated fatigue life using the relationship given below. In this format, the calculated fatigue life is to be equal or greater than the design life of the ship.
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1054.png) years

- **1.4.2** Stresses to be used

#### 1.4.2.1

The nominal stresses are to be determined taking into account the overall geometric changes of the detail. The effect of stress concentrations due to structural discontinuities, presence of attachments and the weld profile is not considered.

- **1.4.3** Nominal stress calculation

#### 1.4.3.1

This Sub-Section outlines a simplified approach to determine the combination of global and local stress components of the stress response of the ship.

#### 1.4.3.2

Stress responses are to be calculated with varying levels of detail. The following approach has been adopted in this simplified procedure:

- **(a)** the hull girder is treated as a simple beam as a way of obtaining reasonable approximations to the nominal stress level in longitudinal hull girder elements. This is used for the evaluation of hull girder stress levels in way of critical details
- **(b)** the structural member with effective attached plating is used in determining the nominal stress response of longitudinal and transverse frames due to dynamic wave pressure and dynamic tank pressure loads. The member end restraints and moments are considered.
- **1.4.4** Definition of stress components

#### 1.4.4.1

Dynamic stress variations are referred to as either stress range, $S$, or stress amplitude, $\sigma$.

#### 1.4.4.2

The global dynamic stress components (primary stresses) considered in fatigue analysis are vertical wave hull girder bending stress, $\sigma _{v}$, and horizontal wave hull girder bending stress, $\sigma _{h}$.

#### 1.4.4.3

The local dynamic stress amplitudes considered are defined as the total local stress amplitude due to dynamic wave pressure loads or dynamic tank pressure loads, $\sigma _{e-i}$.

#### 1.4.4.4

The local stress components are defined as secondary stress resulting from bending of girder systems, $\sigma _{2}$, stress amplitude produced by bending of stiffeners between girder supports, $\sigma _{2A}$, and tertiary stress amplitude produced by bending of un-stiffened plate elements between longitudinals and transverse frames, $\sigma _{3}$. See Fig C.1.3.

#### 1.4.4.5

The total local stress due to dynamic wave or dynamic tank pressure loads, *σ_e-i,* is to be taken as:
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1055.png) $\mathrm{N}/mm ^{2}$
Where:
$\sigma _{2}$ local stress component, in $\mathrm{N}/mm ^{2}$, as defined in 1.4.4.4
$\sigma _{2A}$ local stress component, in $\mathrm{N}/mm ^{2}$, as defined in 1.4.4.4
$\sigma _{3}$ local stress component, in $\mathrm{N}/mm ^{2}$, as defined in 1.4.4.4

| Fig C.1.3<br>Definition of Local Stress Components |
| --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1056.png) |

#### 1.4.4.6

For the calculation of stress components, the vertical wave hull girder stress, $\sigma _{v}$, is given by:
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1057.png) $\mathrm{N}/mm ^{2}$
Where:
*Mwv-v-amp* pseudo amplitude (half range), in kNm, as defined in 1.3.4
*Z_v-net75* ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1058.png) $\mathrm{m} ^{3}$ see Sec 4/2.6.1
*Iv-net75* net vertical hull girder moment of inertia, of hull cross-section about transverse neutral axis, in $\mathrm{m} ^{4}$
*Iv-net75* is to be calculated based on gross thickness, minus the corrosion addition 0.25 *t_corr* of all effective structural elements, see Sec 4/2.6.1
*z* distance from baseline to the critical location of the considered member, i.e. top of flange of longitudinal stiffener, in m
*z_NA-net75* distance from baseline to horizontal neutral axis consistent with *I_v-net75*, in m

#### 1.4.4.7

The corresponding stress range due to vertical wave bending moment, $S _{v}$, is to be taken as:
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1059.png) $\mathrm{N}/mm ^{2}$
Where:
$\sigma _{v}$ vertical wave hull girder stress, in $\mathrm{N}/mm ^{2}$, as defined in 1.4.4.6

#### 1.4.4.8

The horizontal wave hull girder stress, $\sigma _{h}$, is to be taken as:
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1060.png) $\mathrm{N}/mm ^{2}$
Where:
*M_wv-h-amp* in kNm, as defined in 1.3.5
*Z_h-net75* ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1061.png) $\mathrm{m} ^{3}$ see Sec 4/2.6.2
*y* distance from vertical neutral axis of hull cross section to the critical location of the considered member, in m. i.e. top of face plate of longitudinal stiffener
*Ih-net75* net horizontal hull girder moment of inertia, of the hull cross-section about the vertical neutral axis, in $\mathrm{m} ^{4}$.
*Ih-net75* is to be calculated based on gross thickness, minus the corrosion addition 0.25 *t_corr* for all effective structural elements, see Sec 4/2.6.2

#### 1.4.4.9

The corresponding stress range due to horizontal wave bending moment, *S_h*, is to be taken as:
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1062.png) $\mathrm{N}/mm ^{2}$
Where:
$\sigma _{h}$ horizontal wave hull girder stress, in $\mathrm{N}/mm ^{2}$, as defined in 1.4.4.8

#### 1.4.4.10

The effect of secondary stress $\sigma _{2}$, as defined in 1.4.4.4, is in general small for double hull tankers and is therefore not taken into consideration.

#### 1.4.4.11

The stress amplitude produced by bending of stiffeners between girder supports (e.g. frames, bulkheads), $\sigma _{2A}$, is to be taken as:
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1063.png) $\mathrm{N}/mm ^{2}$
Where:
*K_n* stress factor for unsymmetrical profiles, as defined in 1.4.4.15
*K_d* stress factor for bending stress in longitudinal stiffeners caused by relative deformation between supports, may be determined by FE analysis of the cargo hold model where the actual relative deformation is taken into account or taken as follows:
1.0 at frame connections
1.15 for all longitudinals at transverse bulkhead connections including wash bulkheads except:
1.3 for side and bilge longitudinals at mid position between lowest side stringer and deck at side
1.15 for side and bilge longitudinals at lowest side stringer and deck at side
to be linearly interpolated between these two positions
1.5 for bottom longitudinals at mid position between longitudinal bulkhead, bottom girders or buttress structure
1.15 for bottom longitudinals at longitudinal bulkhead, bottom girders or buttress structure
to be linearly interpolated between these two positions
See Fig C.1.4
1.5 for bottom longitudinals in the mid position between longitudinal bulkhead, bottom girders or buttress structure
1.15 for bottom longitudinals at longitudinal bulkhead, bottom girders or buttress structure
to be linearly interpolated between these two positions
*M* moment at stiffener support adjusted to weld toe location at the stiffener (e.g. at bracket toe), in kNm:
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1064.png)
*s* stiffener spacing, in mm
*l_bdg* effective bending span, of longitudinal stiffener, as shown in Fig C.1.5, in m. See also Fig 4.2.1 and 4.2.2 in Sec 4 for soft toe brackets. Top stiffeners with a soft toe are to be treated the same as flat bars with a soft toe bracket. The span point is to be taken at the point where the depth of the end bracket, measured from the face of the member, is equal to half the depth of the member
*Z_-net50* section modulus of longitudinal stiffener with associated effective plate flange *b_eff*, in $\mathrm{cm} ^{3}$, calculated based on gross thickness minus the corrosion addition 0.5 *t_corr*.
*b_eff* as defined in Sec 4/2.3.3
*r_p* moment interpolation factor, for interpolation to weld toe location along the stiffener length:
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1065.png) where ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1066.png)
where *x* is the distance to the hot spot, in m. See Fig C.1.5.
*P* lateral dynamic pressure amplitude at the mid-span between the frame considered and the neighbouring frame, in $\mathrm{kN}/m ^{ 2}$.
*P_in-amp* for dynamic tank pressure, is to be taken as defined in 1.3.7
*Pex-amp* for dynamic wave pressure, is to be taken as defined in 1.3.6

| Fig C.1.4<br>Variation of Bulkhead Factor *K_d* in Full Load Condition for a Vessel with Two Longitudinal Bulkheads |
| --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1067.png) |

| Fig C.1.5<br>Definition of Effective Span Lengths |
| --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1068.png)<br>Supported by free flange transverses (1)<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1069.png)<br>Supported by free flange transverses (2)<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1070.png)<br>Supported by double skin / transverse bulkheads (1)<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1071.png)<br>Supported by double skin / transverse bulkheads (2) |

- **(a)** in full load condition:
- **(b)** in ballast condition:

#### 1.4.4.12

The stress range due to external wave or internal tank pressure, $S _{e}$ or $S _{i}$, is to be determined as:
$S _{e} = 2 \sigma _{2Ae}$ $\mathrm{N}/mm ^{2}$
$S _{i} = 2 \sigma _{2Ai}$ $\mathrm{N}/mm ^{2}$
Where:
$\sigma _{2Ae}$ stress amplitude, in $\mathrm{N}/mm ^{2}$, as defined in 1.4.4.11 when *P_ex-amp* is used
$\sigma _{2Ai}$ stress amplitude, in $\mathrm{N}/mm ^{2}$, as defined in 1.4.4.11 when *P_in-amp* is used

#### 1.4.4.13

Longitudinal local tertiary plate bending stress amplitude in the weld at the plate, transverse frame or bulkhead intersection, $\sigma _{3}$, is not relevant to the critical locations being considered and is to be neglected.

#### 1.4.4.14

The effective breadth of plate flanges of stiffeners (longitudinals) in bending (due to the shear lag effect), exposed to uniform lateral load for bending at ends, is defined in Sec 4/2.3.3.

#### 1.4.4.15

The stress concentration factors at the flange of un-symmetrical stiffeners on laterally loaded panels, $K _{n1}$ and $K _{n2}$, as shown in Fig C.1.6, are to be taken as:
$K _{n1} = \frac{1+ \lambda \beta}{1+ \lambda \beta ^{2} \psi _{z}}$ at the flange edge
$K _{n2} = \frac{1+ \lambda \beta ^{2}}{1+ \lambda \beta ^{2} \psi _{z}}$ at the web
$K _{n2}$ is typically used in the fatigue analysis of longitudinal end connections
Where:
$\beta$ $1- \frac{2b _{g}}{b _{f}}$ for built-up profiles
$1- \frac{t _{w-n et50}}{b _{f}}$ for rolled angle profiles
*b_g* breadth of flange from web centreline, in mm, see Fig C.1.7
*t_w-net50* net web thickness, in mm
*d_w* depth of stiffener web, see Fig C.1.7, in mm
$\lambda$ factor, as defined in 1.4.4.17
$\psi _{z}$ ratio between section modulus of the stiffener web with plate flange, as calculated at the flange and the section modulus of the complete panel stiffener
$\frac{d _{w} ^{2} t _{w-n et50}}{4Z _{n et50} 10 ^{3}}$ may be used as an approximate value
*Z_net50* section modulus of stiffener including the full width of the attached plate, *s*, with respect to a neutral axis normal to the stiffener web, in $\mathrm{cm} ^{3}$. It is to be calculated based on the gross thickness minus the corrosion addition 0.5 *t_corr*

| Fig C.1.6<br>Bending Stress in Symmetrical and Un-symmetrical Panel Stiffener with Same Web and Flange Areas |
| --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1072.png) |

| Fig C.1.7<br>Stiffener Geometry |
| --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1073.png) |

#### 1.4.4.16

The formulations are not directly applicable for bulb profiles. For these, the equivalent built-up profile is to be considered, see Fig C.1.8. The assumed built-up flange is to have the same properties as the bulb flange for cross-sectional area and moment of inertia about the vertical axis and neutral axis position. For HP bulb profiles, the equivalent built up profile dimensions are to be determined. Several examples are tabulated in Table C.1.2.

#### 1.4.4.17

For continuous stiffeners (fixed ends) the $\lambda$-factor at supports is to be taken as:
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1074.png)
Where:
$\eta$ ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1075.png)
*l_bdg* effective bending span, of longitudinal stiffener, in m
*bf* breadth of flange, in mm
*tf-net50* net flange thickness, in mm
*h_stf* stiffener height, including face plate, in mm
*tw-net50* net web thickness, in mm
*t_p-net50* net plate thickness, in mm
*s* plate width between stiffeners, in mm

| Fig C.1.8<br>Bulb Profile and Equivalent Built-up Flange |
| --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1076.png) |

**Table C.1.2<br>HP Equivalent Built-up Profile Dimensions**

| HP-bulb |   | Equivalent built-up flange |   |   |
| --- | --- | --- | --- | --- |
| Height<br>(mm) | Web thickness<br>$t _{w}$ (mm) | $b _{f}$<br>(mm) | $t _{f}$<br>(mm) | $b _{g}$<br>(mm) |
| 200 | 9 – 13 | $t _{w}$ + 24.5 | 22.9 | ($t _{w}$ + 0.9)/2 |
| 220 | 9 – 13 | $t _{w}$ + 27.6 | 25.4 | ($t _{w}$ + 1.0)/2 |
| 240 | 10 – 14 | $t _{w}$ + 30.3 | 28.0 | ($t _{w}$ + 1.1)/2 |
| 260 | 10 – 14 | $t _{w}$ + 33.0 | 30.6 | ($t _{w}$ + 1.3)/2 |
| 280 | 10 – 14 | $t _{w}$ + 35.4 | 33.3 | ($t _{w}$ + 1.4)/2 |
| 300 | 11 – 16 | $t _{w}$ + 38.4 | 35.9 | ($t _{w}$ + 1.5)/2 |
| 320 | 11 – 16 | $t _{w}$ + 41.0 | 38.5 | ($t _{w}$ + 1.6)/2 |
| 340 | 12 – 17 | $t _{w}$ + 43.3 | 41.3 | ($t _{w}$ + 1.7)/2 |
| 370 | 13 – 19 | $t _{w}$ + 47.5 | 45.2 | ($t _{w}$ + 1.9)/2 |
| 400 | 14 – 19 | $t _{w}$ + 51.7 | 49.1 | ($t _{w}$ + 2.1)/2 |
| 430 | 15 – 21 | $t _{w}$ + 55.8 | 53.1 | ($t _{w}$ + 2.3)/2 |

#### 1.4.4.18

For each loading condition, combined local stress components due to simultaneous dynamic tank and dynamic wave pressure loads are to be combined with global stress components induced by hull girder wave bending.

#### 1.4.4.19

Total combined stress range, *S*, is given by:
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1077.png) $\mathrm{N}/mm ^{2}$
Where:
f1, f2, f3and f4 stress range combination factors, representing the phase correlation between total stress range and each stress range component which is between 1.0 and -1.0, as defined in Tables C.1.3 to C.1.5. Where the factor is greater than 1.0 it is to be taken as 1.0. Where the factor is less than -1.0 it is to be taken as -1.0
*f_SN* 1.06, factor to account for joints in combined protected and unprotected environment*.*
*S_v* corresponding stress range due to vertical bending moment, in $\mathrm{N}/mm ^{2}$, as defined in 1.4.4.7
*S_h* corresponding stress range due to horizontal bending moment, in $\mathrm{N}/mm ^{2}$, as defined in 1.4.4.9
*S_e* stress range due to external wave or internal tank pressure, in $\mathrm{N}/mm ^{2}$, as defined in 1.4.4.12
*S_i* stress range due to external wave or internal tank pressure, in $\mathrm{N}/mm ^{2}$, as defined in 1.4.4.12

#### 1.4.4.20

The stress range combination factors, f1, f2, f3 and f4, which are to be applied to the following zones, are given in Tables C.1.3 to C.1.5:
#underline{Note}
Where ballast tanks, centre and wing cargo tanks do not have the same lengths e.g. if slop tank is present, the middle position is to be taken at the middle of the longer tank.

**Table C.1.3<br>Stress Range Combination Factors for Zone M**

|   | Stiffener location |   | $f _{1}$ | $f _{2}$ | $f _{3}$ | $f _{4}$ | $f _{i}$ |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Ballast | Bottom shell | $a _{i}$ | -0.49 | 0.49 | -1.04 | -0.13 | $a _{i} \left( \left\| y \right\| /B \right) +b _{i}$ |
| Ballast | Bottom shell | $b _{i}$ | 0.97 | 0.17 | 0.87 | 0.56 | $a _{i} \left( \left\| y \right\| /B \right) +b _{i}$ |
| Ballast | Side shell and bilge below D/2 | $a _{i}$ | -1.48 | 0.50 | -0.64 | 0.72 | $a _{i} \left( z/D \right) +b _{i}$ |
| Ballast | Side shell and bilge below D/2 | $b _{i}$ | 0.94 | 0.40 | 0.72 | 0.04 | $a _{i} \left( z/D \right) +b _{i}$ |
| Ballast | Side shell above D/2 | $a _{i}$ | 1.70 | -1.00 | -1.10 | -0.60 | $a _{i} \left( z/D \right) +b _{i}$ |
| Ballast | Side shell above D/2 | $b _{i}$ | -0.65 | 1.15 | 0.95 | 0.70 | $a _{i} \left( z/D \right) +b _{i}$ |
| Ballast | Inner bottom and lower stool | $a _{i}$ | -0.18 | 0.34 | 0.00 | -0.30 | $a _{i} \left( \left\| y \right\| /B \right) +b _{i}$ |
| Ballast | Inner bottom and lower stool | $b _{i}$ | 0.90 | 0.22 | 0.00 | 0.74 | $a _{i} \left( \left\| y \right\| /B \right) +b _{i}$ |
| Ballast | Inner hull below D/2<br>(including hopper plate) | $a _{i}$ | -1.70 | -0.90 | 0.00 | 1.04 | $a _{i} \left( z/D \right) +b _{i}$ |
| Ballast | Inner hull below D/2<br>(including hopper plate) | $b _{i}$ | 1.15 | 0.70 | 0.00 | 0.45 | $a _{i} \left( z/D \right) +b _{i}$ |
| Ballast | Inner hull above D/2 | $a _{i}$ | 1.40 | 0.50 | 0.00 | -1.94 | $a _{i} \left( z/D \right) +b _{i}$ |
| Ballast | Inner hull above D/2 | $b _{i}$ | -0.40 | 0.00 | 0.00 | 1.94 | $a _{i} \left( z/D \right) +b _{i}$ |
| Ballast | Deck and Upper stool | $a _{i}$ | -0.15 | 1.05 | 0.00 | 0.00 | $a _{i} \left( \left\| y \right\| /B \right) +b _{i}$ |
| Ballast | Deck and Upper stool | $b _{i}$ | 1.02 | -0.27 | 0.00 | 0.00 | $a _{i} \left( \left\| y \right\| /B \right) +b _{i}$ |
| Ballast | Centreline longitudinal bulkhead below D/2 | $a _{i}$ | 0.00 | 0.00 | 0.00 | 0.00 | $a _{i} \left( z/D \right) +b _{i}$ |
| Ballast | Centreline longitudinal bulkhead below D/2 | $b _{i}$ | 1.00 | 0.00 | 0.00 | 0.00 | $a _{i} \left( z/D \right) +b _{i}$ |
| Ballast | Centreline longitudinal bulkhead above D/2 | $a _{i}$ | 0.00 | 0.00 | 0.00 | 0.00 | $a _{i} \left( z/D \right) +b _{i}$ |
| Ballast | Centreline longitudinal bulkhead above D/2 | $b _{i}$ | 1.00 | 0.00 | 0.00 | 0.00 | $a _{i} \left( z/D \right) +b _{i}$ |
| Ballast | Longitudinal bulkhead below D/2 | $a _{i}$ | -0.20 | 1.30 | 0.00 | 0.00 | $a _{i} \left( z/D \right) +b _{i}$ |
| Ballast | Longitudinal bulkhead below D/2 | $b _{i}$ | 1.00 | 0.10 | 0.00 | 0.00 | $a _{i} \left( z/D \right) +b _{i}$ |
| Ballast | Longitudinal bulkhead above D/2 | $a _{i}$ | 0.20 | -1.30 | 0.00 | 0.00 | $a _{i} \left( z/D \right) +b _{i}$ |
| Ballast | Longitudinal bulkhead above D/2 | $b _{i}$ | 0.80 | 1.40 | 0.00 | 0.00 | $a _{i} \left( z/D \right) +b _{i}$ |
| Loaded | Bottom shell | $a _{i}$ | -0.43 | 0.78 | -0.77 | 0.00 | $a _{i} \left( \left\| y \right\| /B \right) +b _{i}$ |
| Loaded | Bottom shell | $b _{i}$ | 0.98 | 0.13 | 0.75 | 0.00 | $a _{i} \left( \left\| y \right\| /B \right) +b _{i}$ |
| Loaded | Side shell and bilge below D/2 | $a _{i}$ | -0.29 | -0.47 | 0.14 | 0.00 | $a _{i} \left( z/D \right) +b _{i}$ |
| Loaded | Side shell and bilge below D/2 | $b _{i}$ | 0.19 | 0.78 | 0.92 | 0.00 | $a _{i} \left( z/D \right) +b _{i}$ |
| Loaded | Side shell above D/2 | $a _{i}$ | 1.77 | -0.05 | -1.20 | 0.00 | $a _{i} \left( z/D \right) +b _{i}$ |
| Loaded | Side shell above D/2 | $b _{i}$ | -0.84 | 0.57 | 1.59 | 0.00 | $a _{i} \left( z/D \right) +b _{i}$ |
| Loaded | Inner bottom and Lower stool | $a _{i}$ | -0.71 | 1.13 | 0.00 | 0.55 | $a _{i} \left( \left\| y \right\| /B \right) +b _{i}$ |
| Loaded | Inner bottom and Lower stool | $b _{i}$ | 1.03 | 0.18 | 0.00 | -0.18 | $a _{i} \left( \left\| y \right\| /B \right) +b _{i}$ |
| Loaded | Inner hull below D/2<br>(including hopper plate) | $a _{i}$ | -0.80 | -1.70 | 0.00 | 2.60 | $a _{i} \left( z/D \right) +b _{i}$ |
| Loaded | Inner hull below D/2<br>(including hopper plate) | $b _{i}$ | 0.55 | 1.20 | 0.00 | -0.35 | $a _{i} \left( z/D \right) +b _{i}$ |
| Loaded | Inner hull above D/2 | $a _{i}$ | 1.90 | 0.30 | 0.00 | -1.70 | $a _{i} \left( z/D \right) +b _{i}$ |
| Loaded | Inner hull above D/2 | $b _{i}$ | -0.80 | 0.20 | 0.00 | 1.80 | $a _{i} \left( z/D \right) +b _{i}$ |
| Loaded | Deck and upper stool | $a _{i}$ | -0.26 | 1.40 | 0.00 | 0.00 | $a _{i} \left( \left\| y \right\| /B \right) +b _{i}$ |
| Loaded | Deck and upper stool | $b _{i}$ | 1.02 | -0.16 | 0.00 | 0.00 | $a _{i} \left( \left\| y \right\| /B \right) +b _{i}$ |
| Loaded | Centreline longitudinal bulkhead below D/2 | $a _{i}$ | -1.40 | 0.00 | 0.00 | 1.00 | $a _{i} \left( z/D \right) +b _{i}$ |
| Loaded | Centreline longitudinal bulkhead below D/2 | $b _{i}$ | 0.75 | 0.00 | 0.00 | 0.60 | $a _{i} \left( z/D \right) +b _{i}$ |
| Loaded | Centreline longitudinal bulkhead above D/2 | $a _{i}$ | 1.70 | 0.00 | 0.00 | -1.20 | $a _{i} \left( z/D \right) +b _{i}$ |
| Loaded | Centreline longitudinal bulkhead above D/2 | $b _{i}$ | -0.80 | 0.00 | 0.00 | 1.70 | $a _{i} \left( z/D \right) +b _{i}$ |
| Loaded | Longitudinal bulkhead below D/2 | $a _{i}$ | -0.60 | 0.40 | 0.00 | 1.10 | $a _{i} \left( z/D \right) +b _{i}$ |
| Loaded | Longitudinal bulkhead below D/2 | $b _{i}$ | 1.00 | 0.40 | 0.00 | 0.05 | $a _{i} \left( z/D \right) +b _{i}$ |
| Loaded | Longitudinal bulkhead above D/2 | $a _{i}$ | 0.60 | -0.84 | 0.00 | -0.84 | $a _{i} \left( z/D \right) +b _{i}$ |
| Loaded | Longitudinal bulkhead above D/2 | $b _{i}$ | 0.40 | 1.02 | 0.00 | 1.02 | $a _{i} \left( z/D \right) +b _{i}$ |

**Table C.1.4<br>Stress Range Combination Factors for Zone A**

|   | Stiffener location |   | $f _{1}$ | $f _{2}$ | $f _{3}$ | $f _{4}$ | $f _{i}$ |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Ballast | Bottom shell | $a _{i}$ | -0.20 | -0.80 | 1.20 | 1.50 | $a _{i} \left( \left\| y \right\| /B \right) +b _{i}$ |
| Ballast | Bottom shell | $b _{i}$ | 0.00 | 0.50 | -0.25 | 1.07 | $a _{i} \left( \left\| y \right\| /B \right) +b _{i}$ |
| Ballast | Side shell and bilge below D/2 | $a _{i}$ | -1.00 | 1.20 | -0.80 | 2.00 | $a _{i} \left( z/D \right) +b _{i}$ |
| Ballast | Side shell and bilge below D/2 | $b _{i}$ | 0.20 | 0.00 | 0.60 | -0.40 | $a _{i} \left( z/D \right) +b _{i}$ |
| Ballast | Side shell above D/2 | $a _{i}$ | 3.40 | -1.20 | -2.80 | 0.80 | $a _{i} \left( z/D \right) +b _{i}$ |
| Ballast | Side shell above D/2 | $b _{i}$ | -2.00 | 1.20 | 1.60 | 0.20 | $a _{i} \left( z/D \right) +b _{i}$ |
| Ballast | Inner bottom and lower stool | $a _{i}$ | -0.50 | -1.90 | 0.00 | 0.30 | $a _{i} \left( \left\| y \right\| /B \right) +b _{i}$ |
| Ballast | Inner bottom and lower stool | $b _{i}$ | -0.05 | 0.60 | 0.00 | 0.85 | $a _{i} \left( \left\| y \right\| /B \right) +b _{i}$ |
| Ballast | Inner hull below D/2 | $a _{i}$ | 8.20 | -2.80 | 0.00 | 0.20 | $a _{i} \left( z/D \right) +b _{i}$ |
| Ballast | Inner hull below D/2 | $b _{i}$ | -3.50 | 1.00 | 0.00 | 0.90 | $a _{i} \left( z/D \right) +b _{i}$ |
| Ballast | Inner hull above D/2 | $a _{i}$ | 0.60 | 2.80 | 0.00 | -0.50 | $a _{i} \left( z/D \right) +b _{i}$ |
| Ballast | Inner hull above D/2 | $b _{i}$ | 0.30 | -1.80 | 0.00 | 1.25 | $a _{i} \left( z/D \right) +b _{i}$ |
| Ballast | Deck and upper stool | $a _{i}$ | 0.00 | 0.70 | 0.00 | 0.00 | $a _{i} \left( \left\| y \right\| /B \right) +b _{i}$ |
| Ballast | Deck and upper stool | $b _{i}$ | 1.00 | 0.00 | 0.00 | 0.00 | $a _{i} \left( \left\| y \right\| /B \right) +b _{i}$ |
| Ballast | Inner longitudinal bulkhead below D/2 | $a _{i}$ | -1.20 | 2.00 | 0.00 | 0.00 | $a _{i} \left( z/D \right) +b _{i}$ |
| Ballast | Inner longitudinal bulkhead below D/2 | $b _{i}$ | 1.10 | 0.00 | 0.00 | 0.00 | $a _{i} \left( z/D \right) +b _{i}$ |
| Ballast | Inner longitudinal bulkhead above D/2 | $a _{i}$ | 1.50 | -2.70 | 0.00 | 0.00 | $a _{i} \left( z/D \right) +b _{i}$ |
| Ballast | Inner longitudinal bulkhead above D/2 | $b _{i}$ | -0.25 | 2.35 | 0.00 | 0.00 | $a _{i} \left( z/D \right) +b _{i}$ |
| Ballast | Centreline longitudinal bulkhead below D/2 | $a _{i}$ | 0.00 | 0.00 | 0.00 | 0.00 | $a _{i} \left( z/D \right) +b _{i}$ |
| Ballast | Centreline longitudinal bulkhead below D/2 | $b _{i}$ | 1.00 | 0.00 | 0.00 | 0.00 | $a _{i} \left( z/D \right) +b _{i}$ |
| Ballast | Centreline longitudinal bulkhead above D/2 | $a _{i}$ | 0.00 | 0.00 | 0.00 | 0.00 | $a _{i} \left( z/D \right) +b _{i}$ |
| Ballast | Centreline longitudinal bulkhead above D/2 | $b _{i}$ | 1.00 | 0.00 | 0.00 | 0.00 | $a _{i} \left( z/D \right) +b _{i}$ |
| Loaded | Bottom shell | $a _{i}$ | -2.20 | 1.50 | 2.60 | 0.00 | $a _{i} \left( \left\| y \right\| /B \right) +b _{i}$ |
| Loaded | Bottom shell | $b _{i}$ | 1.20 | -0.15 | -0.30 | 0.00 | $a _{i} \left( \left\| y \right\| /B \right) +b _{i}$ |
| Loaded | Side shell and bilge below D/2 | $a _{i}$ | -1.20 | -1.20 | 0.60 | 0.00 | $a _{i} \left( z/D \right) +b _{i}$ |
| Loaded | Side shell and bilge below D/2 | $b _{i}$ | 0.30 | 0.80 | 0.70 | 0.00 | $a _{i} \left( z/D \right) +b _{i}$ |
| Loaded | Side shell above D/2 | $a _{i}$ | 3.00 | -0.30 | -0.50 | 0.00 | $a _{i} \left( z/D \right) +b _{i}$ |
| Loaded | Side shell above D/2 | $b _{i}$ | -1.80 | 0.35 | 1.25 | 0.00 | $a _{i} \left( z/D \right) +b _{i}$ |
| Loaded | Inner bottom and lower stool | $a _{i}$ | -1.00 | 2.30 | 0.00 | -0.20 | $a _{i} \left( \left\| y \right\| /B \right) +b _{i}$ |
| Loaded | Inner bottom and lower stool | $b _{i}$ | 1.00 | -0.10 | 0.00 | 0.00 | $a _{i} \left( \left\| y \right\| /B \right) +b _{i}$ |
| Loaded | Inner hull below D/2 | $a _{i}$ | -0.80 | 1.00 | 0.00 | 1.00 | $a _{i} \left( z/D \right) +b _{i}$ |
| Loaded | Inner hull below D/2 | $b _{i}$ | 0.20 | 0.00 | 0.00 | 0.50 | $a _{i} \left( z/D \right) +b _{i}$ |
| Loaded | Inner hull above D/2 | $a _{i}$ | 3.20 | -1.00 | 0.00 | -0.80 | $a _{i} \left( z/D \right) +b _{i}$ |
| Loaded | Inner hull above D/2 | $b _{i}$ | -1.80 | 1.00 | 0.00 | 1.40 | $a _{i} \left( z/D \right) +b _{i}$ |
| Loaded | Deck and upper stool | $a _{i}$ | -0.10 | 1.50 | 0.00 | 0.00 | $a _{i} \left( \left\| y \right\| /B \right) +b _{i}$ |
| Loaded | Deck and upper stool | $b _{i}$ | 1.00 | -0.15 | 0.00 | 0.00 | $a _{i} \left( \left\| y \right\| /B \right) +b _{i}$ |
| Loaded | Inner longitudinal bulkhead below D/2 | $a _{i}$ | -0.80 | 0.30 | 0.00 | 1.00 | $a _{i} \left( z/D \right) +b _{i}$ |
| Loaded | Inner longitudinal bulkhead below D/2 | $b _{i}$ | 1.00 | 0.50 | 0.00 | 0.30 | $a _{i} \left( z/D \right) +b _{i}$ |
| Loaded | Inner longitudinal bulkhead above D/2 | $a _{i}$ | 0.20 | -0.90 | 0.00 | -0.08 | $a _{i} \left( z/D \right) +b _{i}$ |
| Loaded | Inner longitudinal bulkhead above D/2 | $b _{i}$ | 0.50 | 1.10 | 0.00 | 0.84 | $a _{i} \left( z/D \right) +b _{i}$ |
| Loaded | Centreline longitudinal bulkhead below D/2 | $a _{i}$ | -1.10 | 0.00 | 0.00 | 0.44 | $a _{i} \left( z/D \right) +b _{i}$ |
| Loaded | Centreline longitudinal bulkhead below D/2 | $b _{i}$ | 0.60 | 0.00 | 0.00 | 0.80 | $a _{i} \left( z/D \right) +b _{i}$ |
| Loaded | Centreline longitudinal bulkhead above D/2 | $a _{i}$ | 1.30 | 0.00 | 0.00 | -0.56 | $a _{i} \left( z/D \right) +b _{i}$ |
| Loaded | Centreline longitudinal bulkhead above D/2 | $b _{i}$ | -0.60 | 0.00 | 0.00 | 1.30 | $a _{i} \left( z/D \right) +b _{i}$ |

**Table C.1.5<br>Stress Range Combination Factors for Zone F**

|   | Stiffener location |   | $f _{1}$ | $f _{2}$ | $f _{3}$ | $f _{4}$ | $f _{i}$ |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Ballast | Bottom shell | $a _{i}$ | -0.90 | 1.00 | 2.40 | -1.20 | $a _{i} \left( \left\| y \right\| /B \right) +b _{i}$ |
| Ballast | Bottom shell | $b _{i}$ | 0.85 | -0.10 | -1.00 | 1.10 | $a _{i} \left( \left\| y \right\| /B \right) +b _{i}$ |
| Ballast | Side shell and bilge below D/2 | $a _{i}$ | -0.60 | -0.40 | 1.00 | -1.80 | $a _{i} \left( z/D \right) +b _{i}$ |
| Ballast | Side shell and bilge below D/2 | $b _{i}$ | 0.00 | 0.50 | -0.15 | 0.90 | $a _{i} \left( z/D \right) +b _{i}$ |
| Ballast | Side shell above D/2 | $a _{i}$ | 0.60 | -0.90 | -2.70 | 3.00 | $a _{i} \left( z/D \right) +b _{i}$ |
| Ballast | Side shell above D/2 | $b _{i}$ | -0.60 | 0.75 | 1.70 | -1.50 | $a _{i} \left( z/D \right) +b _{i}$ |
| Ballast | Inner bottom and ower stool | $a _{i}$ | -0.30 | -1.00 | 0.00 | 0.00 | $a _{i} \left( \left\| y \right\| /B \right) +b _{i}$ |
| Ballast | Inner bottom and ower stool | $b _{i}$ | 0.90 | 0.25 | 0.00 | 1.00 | $a _{i} \left( \left\| y \right\| /B \right) +b _{i}$ |
| Ballast | Inner hull below D/2 | $a _{i}$ | -12.00 | -2.40 | 0.00 | 1.20 | $a _{i} \left( z/D \right) +b _{i}$ |
| Ballast | Inner hull below D/2 | $b _{i}$ | 5.00 | 1.00 | 0.00 | 0.50 | $a _{i} \left( z/D \right) +b _{i}$ |
| Ballast | Inner hull above D/2 | $a _{i}$ | 3.00 | 1.40 | 0.00 | -0.90 | $a _{i} \left( z/D \right) +b _{i}$ |
| Ballast | Inner hull above D/2 | $b _{i}$ | -2.50 | -0.90 | 0.00 | 1.55 | $a _{i} \left( z/D \right) +b _{i}$ |
| Ballast | Deck and upper stool | $a _{i}$ | 0.00 | 1.00 | 0.00 | 0.00 | $a _{i} \left( \left\| y \right\| /B \right) +b _{i}$ |
| Ballast | Deck and upper stool | $b _{i}$ | 1.00 | -0.10 | 0.00 | 0.00 | $a _{i} \left( \left\| y \right\| /B \right) +b _{i}$ |
| Ballast | Inner longitudinal bulkhead below D/2 | $a _{i}$ | -1.80 | 1.90 | 0.00 | 0.00 | $a _{i} \left( z/D \right) +b _{i}$ |
| Ballast | Inner longitudinal bulkhead below D/2 | $b _{i}$ | 1.30 | 0.00 | 0.00 | 0.00 | $a _{i} \left( z/D \right) +b _{i}$ |
| Ballast | Inner longitudinal bulkhead above D/2 | $a _{i}$ | 1.80 | -2.50 | 0.00 | 0.00 | $a _{i} \left( z/D \right) +b _{i}$ |
| Ballast | Inner longitudinal bulkhead above D/2 | $b _{i}$ | -0.50 | 2.20 | 0.00 | 0.00 | $a _{i} \left( z/D \right) +b _{i}$ |
| Ballast | Centreline longitudinal bulkhead below D/2 | $a _{i}$ | 0.00 | 0.00 | 0.00 | 0.00 | $a _{i} \left( z/D \right) +b _{i}$ |
| Ballast | Centreline longitudinal bulkhead below D/2 | $b _{i}$ | 1.00 | 0.00 | 0.00 | 0.00 | $a _{i} \left( z/D \right) +b _{i}$ |
| Ballast | Centreline longitudinal bulkhead above D/2 | $a _{i}$ | 0.00 | 0.00 | 0.00 | 0.00 | $a _{i} \left( z/D \right) +b _{i}$ |
| Ballast | Centreline longitudinal bulkhead above D/2 | $b _{i}$ | 1.00 | 0.00 | 0.00 | 0.00 | $a _{i} \left( z/D \right) +b _{i}$ |
| Loaded | Bottom shell | $a _{i}$ | -0.60 | -0.15 | 0.00 | 0.00 | $a _{i} \left( \left\| y \right\| /B \right) +b _{i}$ |
| Loaded | Bottom shell | $b _{i}$ | -0.45 | 0.05 | 1.00 | 0.00 | $a _{i} \left( \left\| y \right\| /B \right) +b _{i}$ |
| Loaded | Side shell and bilge below D/2 | $a _{i}$ | -1.20 | 0.18 | 0.00 | 0.00 | $a _{i} \left( z/D \right) +b _{i}$ |
| Loaded | Side shell and bilge below D/2 | $b _{i}$ | 0.00 | -0.03 | 1.00 | 0.00 | $a _{i} \left( z/D \right) +b _{i}$ |
| Loaded | Side shell above D/2 | $a _{i}$ | 4.00 | 0.02 | 0.00 | 0.00 | $a _{i} \left( z/D \right) +b _{i}$ |
| Loaded | Side shell above D/2 | $b _{i}$ | -2.60 | 0.05 | 1.00 | 0.00 | $a _{i} \left( z/D \right) +b _{i}$ |
| Loaded | Inner bottom and lower stool | $a _{i}$ | 2.80 | 2.20 | 0.00 | -1.00 | $a _{i} \left( \left\| y \right\| /B \right) +b _{i}$ |
| Loaded | Inner bottom and lower stool | $b _{i}$ | -0.80 | -0.30 | 0.00 | 1.10 | $a _{i} \left( \left\| y \right\| /B \right) +b _{i}$ |
| Loaded | Inner hull below D/2 | $a _{i}$ | 10.20 | 1.60 | 0.00 | 0.00 | $a _{i} \left( z/D \right) +b _{i}$ |
| Loaded | Inner hull below D/2 | $b _{i}$ | -4.50 | -0.60 | 0.00 | 1.00 | $a _{i} \left( z/D \right) +b _{i}$ |
| Loaded | Inner hull above D/2 | $a _{i}$ | -0.80 | -0.90 | 0.00 | 0.00 | $a _{i} \left( z/D \right) +b _{i}$ |
| Loaded | Inner hull above D/2 | $b _{i}$ | 1.00 | 0.65 | 0.00 | 1.00 | $a _{i} \left( z/D \right) +b _{i}$ |
| Loaded | Deck and upper stool | $a _{i}$ | -0.24 | 1.80 | 0.00 | 0.00 | $a _{i} \left( \left\| y \right\| /B \right) +b _{i}$ |
| Loaded | Deck and upper stool | $b _{i}$ | 1.00 | 0.00 | 0.00 | 0.00 | $a _{i} \left( \left\| y \right\| /B \right) +b _{i}$ |
| Loaded | Inner longitudinal bulkhead below D/2 | $a _{i}$ | -2.10 | -1.00 | 0.00 | 1.50 | $a _{i} \left( z/D \right) +b _{i}$ |
| Loaded | Inner longitudinal bulkhead below D/2 | $b _{i}$ | 1.15 | 0.60 | 0.00 | 0.35 | $a _{i} \left( z/D \right) +b _{i}$ |
| Loaded | Inner longitudinal bulkhead above D/2 | $a _{i}$ | 0.40 | -0.30 | 0.00 | -0.40 | $a _{i} \left( z/D \right) +b _{i}$ |
| Loaded | Inner longitudinal bulkhead above D/2 | $b _{i}$ | -0.10 | 0.25 | 0.00 | 1.30 | $a _{i} \left( z/D \right) +b _{i}$ |
| Loaded | Centreline longitudinal bulkhead below D/2 | $a _{i}$ | -0.60 | 0.00 | 0.00 | 0.00 | $a _{i} \left( z/D \right) +b _{i}$ |
| Loaded | Centreline longitudinal bulkhead below D/2 | $b _{i}$ | 0.25 | 0.00 | 0.00 | 1.00 | $a _{i} \left( z/D \right) +b _{i}$ |
| Loaded | Centreline longitudinal bulkhead above D/2 | $a _{i}$ | 0.20 | 0.00 | 0.00 | 0.00 | $a _{i} \left( z/D \right) +b _{i}$ |
| Loaded | Centreline longitudinal bulkhead above D/2 | $b _{i}$ | -0.15 | 0.00 | 0.00 | 1.00 | $a _{i} \left( z/D \right) +b _{i}$ |

- **(a)** Zone M: Midship region. This zone extends over the full length of all tanks where the tank LCG lies between 0.35 L and 0.8 L from AP.
- **(b)** Zone A: Aft region. This zone starts at the middle of the tank immediately aft of Zone M and extends aftwards to include all the aftmost tanks.
- **(c)** Zone F: Forward region. This zone starts at the middle of the tank immediately forward of Zone M and extends forwards to include all the foremost tanks.
- **(d)** Zone AT: Aft transition region between Zone M and Zone A. The stress range combination factors are to be calculated by linear interpolation between the stress range combination factors for Zones M and A.
- **(e)** Zone FT: Forward transition region between Zone M and Zone F. The stress range combination factors are to be calculated by linear interpolation between the stress range combination factors for Zones M and F.
- **1.4.5** Selection of S-N curves

#### 1.4.5.1

The capacity of welded steel joints with respect to fatigue strength is characterized by S-N curves which give the relationship between the stress ranges applied to a given detail and the number of constant amplitude load cycles to failure.

#### 1.4.5.2

For ship structural details, S-N curves are represented by:
$S ^{m} N = K _{2}$
Where:
$S$ stress range, in $\mathrm{N}/mm ^{2}$, as defined in 1.4.4.19
$N$ predicted number of cycles to failure under stress range *S*
$m$ constant depending on material and weld type, type of loading, geometrical configuration and environmental conditions (air or sea water), as defined in 1.4.5.5.
$K _{2}$ constant depending on material and weld type, type of loading, geometrical configuration and environmental conditions (air or sea water), as defined in 1.4.5.5.

#### 1.4.5.3

Experimental S-N curves are defined by their mean fatigue life and standard deviation. The mean S-N curve gives the stress level $S$ at which the structural detail will fail with a probability level of 50 percent after $N$ loading cycles. S-N curves considered in the present Rules are based upon a statistical analysis of appropriate experimental data and represent two standard deviations below the mean lines.

#### 1.4.5.4

Unless direct experimental measurements are available, the S-N curves described in 1.4.5.5 to 1.4.5.16 are to be used for assessment of the fatigue strength of structural details.

#### 1.4.5.5

As shown in Fig C.1.9, the basic design curves consist of linear relationships between $\log(S)$ and $\log(N)$, which are to be expressed as follows. The S-N curves have a change of inverse slope from $m$ to $m$ + 2 at $N$ = $10 ^{7}$ cycles (which corresponds to stress range $S _{q}$).
$\log(N) = \log(K _{2} ) - m \log(S)$
Where:
$\log(K _{2} )$ = $\log(K _{1} )-2 \delta$
$N$ predicted number of cycles to failure under stress range $S$
$K _{1}$ constant relating to the mean S-N curve, as given in Table C.1.6
$\delta$ standard deviation of $\log(N)$
$m$ inverse slope of the S-N curve, as given in Table C.1.6
$S _{q}$ Stress range corresponding to $10 ^{7}$ cycles of the S-N curve, in $\mathrm{N}/mm ^{2}$, as given in Table C.1.6

**Table C.1.6<br>Basic S-N Curve Data, In-Air**

| Class | $K _{1}$ |   |   | $m$ | Standard Deviation |   | $K _{2}$ | $S _{q}$<br>$\mathrm{N}/mm ^{2}$ |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Class |   | $\log _{10}$ | $\log _{e}$ | $m$ | $\log _{10}$ | $\log _{e}$ | $K _{2}$ | $S _{q}$<br>$\mathrm{N}/mm ^{2}$ |
| B | 2.343 E15 | 15.3697 | 35.3900 | 4.0 | 0.1821 | 0.4194 | 1.01 E15 | 100.2 |
| C | 1.082 E14 | 14.0342 | 32.3153 | 3.5 | 0.2041 | 0.4700 | 4.23 E13 | 78.2 |
| D | 3.988 E12 | 12.6007 | 29.0144 | 3.0 | 0.2095 | 0.4824 | 1.52 E12 | 53.4 |
| E | 3.289 E12 | 12.5169 | 28.8216 | 3.0 | 0.2509 | 0.5777 | 1.04 E12 | 47.0 |
| F | 1.726 E12 | 12.2370 | 28.1770 | 3.0 | 0.2183 | 0.5027 | 0.63 E12 | 39.8 |
| F2 | 1.231 E12 | 12.0900 | 27.8387 | 3.0 | 0.2279 | 0.5248 | 0.43 E12 | 35.0 |
| G | 0.566 E12 | 11.7525 | 27.0614 | 3.0 | 0.1793 | 0.4129 | 0.25 E12 | 29.2 |
| W | 0.368 E12 | 11.5662 | 26.6324 | 3.0 | 0.1846 | 0.4251 | 0.16 E12 | 25.2 |

| Fig C.1.9<br>Basic Design S-N Curves, In-Air |
| --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1078.png) |

#### 1.4.5.6

The class of S-N curve selected for determination of the cumulative fatigue damage, *DM*, is to be consistent with the fatigue assessment methods used and the type of detail to be analyzed.

#### 1.4.5.7

Experimental S-N curves give the relationship between the nominal stress range and the number of cycles to failure. Therefore, when using these S-N curves, the calculated stresses are to correspond to the nominal stresses used in creating these curves.

#### 1.4.5.8

The basic S-N curves to be used in this Appendix for fatigue assessment of longitudinal stiffener end connections are given in 1.4.5.5, with the S-N curve parameters given in Table C.1.6.

#### 1.4.5.9

Generally, adjustments to the S-N curves to take into account the following can be made:

- **(a)** effect of mean stresses
- **(b)** effect of plate thickness
- **(c)** weld improvement
- **(d)** influence of the environment.

#### 1.4.5.10

The stress range may be reduced depending on whether the mean stress is tensile or compressive. In the event that it can be demonstrated that a compressive stress exists and can be quantified, the effect of mean stress may be considered by assuming a stress range equal to the tensile component plus 60 % of the compressive component. The actual still water bending moment (SWBM) and the applicable static sea and tank pressures for the full load condition or ballast condition as appropriate are to be used in determining the mean stress level.

#### 1.4.5.11

The total stress range considering the mean stress effect is to be taken as follows:
*S_Ri* = *σ_tensile*–0.6 *σ_compressive* if *σ_compressive* < 0 and *σ_tensile* > 0
*S_Ri* = *S* if *σ_compressive* ≥ 0
*S_Ri* = 0.6 *S* if *σ_tensile* ≤ 0
Where:
*σ_tensile* mean stress plus half stress range, in $\mathrm{N}/mm ^{2}$
= *σ_mean* + *S*/2
*σ_compressive* mean stress minus half stress range, in $\mathrm{N}/mm ^{2}$
= *σ_mean* - *S*/2
*σ_mean* mean stress due to static load components in the full load condition or ballast condition as appropriate, in $\mathrm{N}/mm ^{2}$, see 1.3.2
For the nominal stress approach, *S* and *σ_mean* are to be calculated as follows:
*S* total combined stress range, in $\mathrm{N}/mm ^{2}$, as defined in 1.4.4.19
*=* *σ_tensile* *-* *σ_compressive*
*σ_mean* *=* *σ_hg* *+* *σ_ex* *+* *σ_in*
*σ_hg* mean stress due to hull girder bending, to be derived using *σ_v* from 1.4.4.6 with *M_wv-v-amp* taken as the actual SWBM for the full load condition or ballast condition as appropriate, see 1.3.2.
*σ_ex* mean local bending stress due to external static sea pressure, if applicable. *σ_ex* is to be derived using *σ_2A* from 1.4.4.11 with *P* calculated based on the actual draught for the full load condition or ballast condition as appropriate, see 1.3.2, where *P = P_hys*, see Sec 7/2.2.2.1.
*σ_in* mean local bending stress due to internal static tank pressure, if applicable. *σ_in* is to be derived using *σ_2A* from 1.4.4.11 with *P* calculated based on the head to the top of tank and the tank contents for the full load condition or ballast condition as appropriate, see 1.3.2, where *P = P_in-tk*, see Sec 7/2.2.3.1.
Notes


### 3 It is to be assumed that water ballast and cargo tanks are 100 % full. The fluid density is to be taken in accordance with Sec 7/2.2.3.1, where cargo density is not to be less than 0.9 tonnes/

For the hot spot stress approach in Sub Sec 2, the mean stress, *σ_mean*, is to be calculated by applying the applicable static loads to the FE model for the full load condition or ballast condition as appropriate. Alternatively, in lieu of applying the static loads to the FE model, the total stress range is to be calculated in accordance with 2.4.2.8.

#### 1.5 Classification of Structural Details

- **1.5.1** General

#### 1.5.1.1

The joint classification of structural details is to be made using Table C.1.7 where the design of soft toes and backing brackets corresponds to those shown in Fig C.1.10. When alternative designs are proposed, the adequacy in terms of fatigue strength is to be demonstrated using a suitable finite element analysis. See 2.1.1.3.

#### 1.5.1.2

Where the primary support member web stiffeners are omitted or not connected to the longitudinals in way of bottom, side and inner hull, see Note 6 of Table C.1.7.

**Table C.1.7<br>Classification of Structural Details**

| #underline{Notes}<br>1. Where the attachment length is less than or equal to 150 mm, the S-N curve may be upgraded one class from those specified in the table. For example, if the class shown in the table is F2, upgrade to F. Attachment length is defined as the length of the weld attachment on the longitudinal stiffener face plate without deduction of scallop.<br>2. Where the longitudinal stiffener is a flat bar and there is a stiffener/bracket welded to the face, the S-N curve is to be downgraded by one class from those specified in the table. For example, if the class shown in the table is F, downgrade to F2; if the class shown in the table is F2, downgrade to G. This also applies to unsymmetrical profiles where there is less than 8 mm clearance between the edge of the stiffener flange and the face of the attachment, e.g. bulb or angle profiles where the stated clearance cannot be achieved.<br>3. Lapped connections (attachments welded to the web of the longitudinals) should not be adopted and therefore these are not covered by the table.<br>4. For connections fitted with a soft heel, class F may be used if it is predominantly subjected to axial loading. Stiffeners fitted on deck and within 0.1 D below deck at side are considered to satisfy this condition.<br>5. For connections fitted with a collar around the face plate (i.e., connection type ID25 through 30) or full collar (i.e., connection type ID31), class F may be used if subjected to axial loading. Stiffeners fitted on deck and within 0.1 D below deck at side are considered to satisfy this condition<br>6. ID31 and 32 show details where web stiffeners are omitted or are not connected to the longitudinal stiffener face plate. A full collar (i.e. connection type ID31 ) or alternatively a detail design for cut-outs as shown in Fig C.1.11 or equivalent is required in way of:<br>• Side below the highest point of the wave wetted zone or below 0.1 D from the deck at side, whichever is lower.<br>• Bottom<br>• Inner hull longitudinal bulkhead below 0.1 D from the deck at side<br>• Hopper<br>• Inner bottom<br>The highest point of the wave wetted zone is defined as the full load draft plus $h _{wl}$ as shown in Fig C.1.1. Equivalence to Fig C.1.11 is to be demonstrated through a satisfactory fatigue assessment by using comparative FEM based hot spot stress of the cut-out in the primary support member and the collar.<br>7. For connection type ID32 having no collar welded to the face plate, class F is to be used in way of longitudinals in the strength deck irrespective of slot configuration. In other areas class E may be used irrespective of slot configuration. |   |   |   |
| --- | --- | --- | --- |
| ID | Connection type | Critical locations notes (1), (2), (3) |   |
| ID | Connection type | A | B |
| 1 | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1080.png) | F2 | F2 |

**Table C.1.7 (Continued)<br>Classification of Structural Details**

| ID | Connection type | Critical locations notes (1), (2), (3) |   |
| --- | --- | --- | --- |
| ID | Connection type | A | B |
| 2 | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1081.png) | F2 | F2(4) |
| 3 | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1082.png) | F | F2 |
| 4 | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1083.png) | F | F2(4) |
| 5 | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1084.png) | F | F |

**Table C.1.7 (Continued)<br>Classification of Structural Details**

| ID | Connection type | Critical locations notes (1), (2), (3) |   |
| --- | --- | --- | --- |
| ID | Connection type | A | B |
| 6 | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1085.png) | F2 | F2(4) |
| 7 | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1086.png) | F2 | F2 |
| 8 | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1087.png) | F2 | F2 |
| 9 | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1088.png) | F2 | F |

**Table C.1.7 (Continued)<br>Classification of Structural Details**

| ID | Connection type | Critical locations notes (1), (2), (3) |   |
| --- | --- | --- | --- |
| ID | Connection type | A | B |
| 10 | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1089.png) | F2 | F2 |
| 11 | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1090.png) | F | F2 |
| 12 | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1091.png) | F2 | F |
| 13 | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1092.png) | F2 | F2 |

**Table C.1.7 (Continued)<br>Classification of Structural Details**

| ID | Connection type | Critical locations notes (1), (2), (3) |   |
| --- | --- | --- | --- |
| ID | Connection type | A | B |
| 14 | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1093.png) | F2 | F2(4) |
| 15 | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1094.png) | F2 | F2 |
| 16 | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1095.png) | F2 | F |
| 17 | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1096.png) | F | F2 |

**Table C.1.7 (Continued)<br>Classification of Structural Details**

| ID | Connection type | Critical locations notes (1), (2), (3) |   |
| --- | --- | --- | --- |
| ID | Connection type | A | B |
| 18 | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1097.png) | F | F2(4) |
| 19 | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1098.png) | F | F |
| 20 | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1099.png) | F | F2 |
| 21 | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1100.png) | F | F2 |

**Table C.1.7 (Continued)<br>Classification of Structural Details**

| ID | Connection type | Critical locations notes (1), (2), (3) |   |
| --- | --- | --- | --- |
| ID | Connection type | A | B |
| 22 | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1101.png) | F | F2(4) |
| 23 | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1102.png) | F | F |
| 24 | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1103.png) | F | F2 |
| 25 | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1104.png) | F2 | F2(5 only) |

**Table C.1.7 (Continued)<br>Classification of Structural Details**

| ID | Connection type | Critical locations notes (1), (2), (3) |   |
| --- | --- | --- | --- |
| ID | Connection type | A | B |
| 26 | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1105.png) | F | F2(5 only) |
| 27 | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1106.png) | F2 | F2(5 only) |
| 28 | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1107.png) | F2 | F2(5 only) |
| 29 | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1108.png) | F | F2(5 only) |

**Table C.1.7 (Continued)<br>Classification of Structural Details**

| ID | Connection type | Critical locations notes (1), (2), (3) |   |
| --- | --- | --- | --- |
| ID | Connection type | A | B |
| 30 | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1109.png) | F | F2(5 only) |
| 31 | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1110.png) | F2(5, 6 only) | F2(5, 6 only) |
| 32 | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1111.png) | F(6, 7 only) | N/A |

| Fig C.1.10<br>Detail Design for Soft Toes and Backing Brackets |
| --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1112.png)<br>Recommended Design of Soft Toes and Backing Bracket of Pillar Stiffeners<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1113.png)<br>Recommended Design of Soft Toes and Backing Bracket of Tripping Brackets<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1114.png)<br>Recommended Alternative Design of Soft Toes of Tripping Brackets |

**Fig C.1.11<br>Design for Cut Outs in cases where Web Stiffeners are Omitted**

| 1 | 2 |
| --- | --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1115.png) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1116.png) |
| 3 | 4 |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1117.png) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1118.png) |
| #underline{Notes}<br>1. Soft toes marked “*” are to be dimensioned to suit the weld leg length such that smooth transition from the weld to the radiused part can be achieved. Max. 15 mm.<br>2. Configurations 1 and 4 indicate acceptable lapped lug plate connections, alternatively, butted lug plates with similar shape may be adopted.<br>3. Designs that are different than shown in the above sketches are acceptable subject to a satisfactory fatigue assessment by using comparative FEM based hot spot stress. |   |

#### 1.6 Other Details

- **1.6.1** Scallops in way of block joints

#### 1.6.1.1

Scallops in way of block joints in the cargo tank region, located on the strength deck, and down to 0.1*D* from the deck at side are to be designed according to Fig C.1.12 unless the specification in Sec 8/1.5.1.3 for class F2 is satisfied.

| Fig C.1.12<br>Welding of Deck Stiffeners in way of Block Joints |
| --- |
| (I) Offset butt on stiffener |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1119.png) |
| (II) Elongated scallop on stiffener |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1120.png) |
| (III) Closing scallop with collar |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1121.png) |
| #underline{Notes}<br>Alternative scallop geometry to that shown in option II may be accepted subject to demonstration of satisfactory fatigue life based on hull girder loads taking into account additional stress concentration factor in way of weld, determined using fine mesh FEM and applying class D S-N curve. |


### 2 Hot Spot Stress (FE Based) Approach

#### 2.1 General

- **2.1.1** Applicability

#### 2.1.1.1

The procedure in this section applies to welded knuckles between inner bottom and hopper plate fatigue analysis using a finite element (FE) based hot spot stress approach. A similar application method as described in Sub-Sec 1 for the nominal stress approach is used except where indicated in the following sections.

#### 2.1.1.2

Where the hopper knuckle between inner bottom and hopper plate is of the bent type, hot spot stress fatigue assessment is not a requirement provided the detail design standard described in 2.5.1.2 is followed. When alternative design is proposed, a suitable finite element (FE) analysis should be used to demonstrate the equivalency of the detail in terms of fatigue strength.

#### 2.1.1.3

Where the hot spot stress approach is considered necessary for demonstration of the adequacy of longitudinal stiffener end connection in lieu of the nominal stress approach, the procedure described in Sub-Sec 1 is generally to be followed with the exception that $S _{v}$, $S _{h}$, $S _{i}$ and $S _{e}$are to be determined directly from the finite element analysis using the surface hot spot stress component perpendicular to the weld obtained by linear extrapolation to the centre-line of the attachment, and then to the weld toe position. The S-N curve according to 2.4.3 is applicable.

- **2.1.2** Assumptions

#### 2.1.2.1

The assumptions made are given in 1.1.2.

#### 2.2 Corrosion Model

- **2.2.1** Net thickness

#### 2.2.1.1

The net thickness and corrosion additions given in Sec 6/3 are to be incorporated into the representation of the FE structural capacity models as described in Appendix B/4.

#### 2.3 Loads

- **2.3.1** General

#### 2.3.1.1

Dynamic wave and tank pressures are to be considered for the FE based fatigue analysis of knuckles between inner bottom and hopper plates, see 1.3.6 and 1.3.7.

#### 2.4 Fatigue Damage Calculation

- **2.4.1** Fatigue strength determination

#### 2.4.1.1

The procedure outlined in 1.4 is to be applied.

#### 2.4.1.2

The Weibull probability distribution parameter applicable to welded knuckles between inner bottom and hopper plate, $\xi$, is to be taken as:
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1122.png)
Where:
*L* rule length, in m, as defined in Sec 4/1.1.1.1

- **2.4.2** Stresses to be used

#### 2.4.2.1

To determine hot spot stresses, local 2D or 3D very fine mesh stress analyses, in conjunction with a 3D coarse mesh analysis are to be used. In highly stressed areas, in particular in the vicinity of structural discontinuities, the level of stresses depends on the size of elements because of the high stress gradient. If the stress field is more complex than a uniaxial field, the stresses adjacent to the potential crack location are to be used. A uniform mesh is to be used with smooth transition and avoidance of abrupt changes in mesh size.

#### 2.4.2.2

The following defines a general basis for the modelling of local structures:

- **(a)** hot spot stresses are to be calculated using an idealized welded joint with no misalignments. The finite element mesh is to be fine enough near the hot spot such that stresses and stress gradients can be determined with sufficient accuracy
- **(b)** plating, webs and face plates of primary and secondary members are modelled by 4-node thin shell elements. In cases of steep stress gradients, 8-node thin shell elements are to be used.
- **(c)** when thin shell elements are used, the structure is to be modelled at the mid face of the plates. For practical purposes, adjoining plates of different thickness may be assumed to be median line aligned, i.e., no staggering in way of thickness change is required.
- **(d)** the aspect ratio of elements is not to be greater than three in the vicinity of the hot spot.
- **(e)** the size of elements located in the vicinity of the hot spot is to be comparative to the net thickness of the structural member
- **(f)** stresses are to be calculated at the surface of the plate with a view to taking into account the plate bending moment, where relevant.

#### 2.4.2.3

A detailed description of hot spot stress calculation using finite element modelling is given by Appendix B/4.

#### 2.4.2.4

Generally, the element stresses are derived at the Gaussian integration points. Depending on the element type, it may be necessary to perform several interpolations in order to determine the actual stress at the considered hot spot location.

#### 2.4.2.5

For critical structural details, hot spot stresses are generally highly dependent on the finite element model used for representation of the structure. Alternative procedures to those described here, for the derivation of the hot spot stress, are to be confirmed or documented by reference to available fatigue test results for similar structural details.

#### 2.4.2.6

The hot spot stress is defined as the surface stress at 0.5 *t* away from the weld toe location, as shown in Fig C.2.1. The hot spot stress is to be obtained by linear interpolation in the ship’s transverse direction using the respective stress at the 1^st and 2^nd element from the structure intersection.

| Fig C.2.1<br>Hot Spot Stress |
| --- |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1123.png) |

#### 2.4.2.7

Stress range components along the direction perpendicular to the weld, due to the loads defined in 2.3, are to be calculated based on Appendix B/4. The total combined stress range, *S*, is to be taken as:
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1124.png) for full load condition
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1125.png) for ballast load condition
Where:
$S _{e1}$ stress range due to dynamic wave pressure applied to FE-model on the side where the hopper knuckle is to be investigated, in $\mathrm{N}/mm ^{2}$, see Table B.4.1
$S _{e2}$ stress range due to dynamic wave pressure applied to FE-model on the side of the hull where the hopper knuckle is not analysed, in $\mathrm{N}/mm ^{2}$, see Table B.4.1
$S _{i}$ stress range due to dynamic tank pressure applied to FE-model, in $\mathrm{N}/mm ^{2}$, see Appendix B/4.5.2.4 and Table B.4.1
$f _{m odel}$ 1.0 if the FE model is made according to net thickness for fatigue, i.e. using corrosion addition of 0.25 *t_corr* for the FE model except in way of critical location (in way of a knuckle and within 500 mm in all directions), which uses corrosion addition of 0.5 *t_corr*
0.95 if the FE model for strength assessment is used. FE model for strength assessment applies a corrosion addition of 0.5 *t_corr* for the whole model including structure in way of critical location

#### 2.4.2.8

To account for the mean stress effect, in lieu of applying the static loads to the FE model, the total stress range may be taken as:
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1126.png) for full load condition
![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1127.png) for ballast load condition
Where:
*S* total combined stress range, in $\mathrm{N}/mm ^{2}$, as defined in 2.4.2.7

- **2.4.3** Selection of S-N curves

#### 2.4.3.1

The fatigue analysis is to be carried out applying the Class D S-N curve for welded details if the hot spot stress is calculated according to 2.4.2.8. The thickness effect according to 1.4.5.12 will be applicable.

#### 2.5 Detail Design Standard

- **2.5.1** Hopper knuckles

#### 2.5.1.1

Design details for the welded knuckle between hopper plating and inner bottom plating are to be as shown in Fig C.2.2.
#underline{Guidance Note:}
Fig C.2.3 may be used as an option to increase fatigue strength at the hopper connection.

#### 2.5.1.2

Design details for the bent knuckle between hopper plating and inner bottom plating are to be as shown in Fig C.2.4.

- **2.5.2** Transverse Bulkhead Horizontal Stringer Heel

#### 2.5.2.1

Detail design improvement given in Fig C.2.5 is recommended for reducing the stress level and increasing fatigue strength at the horizontal stringer heel location between transverse oil-tight and wash bulkhead plating and inner hull longitudinal bulkhead plating. This recommendation should be considered in association with fine mesh FE analysis as required in Appendix B/3.1.3.

**Fig C.2.2<br>Hopper Knuckle Connection Detail, Without Bracket**

| Connections of floors in double bottom tanks to hopper tanks<br>Hopper corner connections employing welded inner bottom and hopper sloping plating |   |   |   |
| --- | --- | --- | --- |
| Critical areas |   |   | Detail design standard A |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1128.png) |   | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1129.png) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1130.png)<br>#underline{Note:}<br>1. A root face with a maximum of 1/3 of the abutting plate thickness is acceptable for the partial penetration welding, see Sec 6/5.3.4.<br>2. Grinding need not be applied in the No.1 tank in which floor spans are reduced due to shape.<br>3. Grinding need not be applied for the knuckle joints at transverse bulkhead positions, or at the floor adjacent to the transverse bulkhead. |
| Critical locations |   |   |   |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1131.png) |   |   |   |
| Minimum requirement | As a minimum, detail design standard A or B is to be fitted. Further consideration will be given where the hopper angle exceeds 50 degrees. The ground surface is to be protected by a stripe coat, of suitable paint composition, where the lower hopper knuckle region of cargo tanks is not coated. |   |   |
| Critical location | Hopper sloping plating connections to inner bottom plating in way of floors. Floor connections to inner bottom plating and side girders in way of hopper corners. |   |   |
| Detail design standard | Elimination of scallops in way of hopper corners, extension of inner bottom plating to reduce level of resultant stresses arising from cyclic external hydrodynamic pressure, cargo inertia pressure and hull girder loads. Scarfing bracket thickness is to be close to that of the inner bottom in way of knuckle. |   |   |
| Building tolerances | Median line of hopper sloping plate is to be in line with the median line of the girder with an allowable tolerance of t/3 or 5 mm, whichever is less, where $t$ is the inner bottom thickness. The allowable tolerance is to be measured parallel to the inner bottom. |   |   |
| Welding requirements | Partial penetration welding (hopper sloping plating to inner bottom plating). Partial penetration weld (connection of floors to inner bottom plating and to side girders, connection of hopper transverse webs to sloping plating, to inner bottom plating, and to side girders in way of hopper corners). |   |   |

**Fig C.2.3<br>Option: Hopper Knuckle Connection Detail, With Bracket**

| Connections of floors in double bottom tanks to hopper tanks<br>Hopper corner connections employing welded inner bottom and hopper sloping plating |   |   |   |
| --- | --- | --- | --- |
| Critical areas |   |   | Detail design standards B |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1132.png) |   | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1133.png) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1134.png)<br>#underline{Note:}<br>1. Bracket to be fitted inside cargo tank<br>2. Bracket to extend approximately to the first longitudinal<br>3. The bracket toes are to have a soft nose design<br>4. Full penetration welding at bracket toes<br>5. Bracket material to be same as that of inner bottom<br>6. Buckling of bracket to be checked:<br>$\frac{d}{t _{bkt}} < 21 \sqrt {235/ \sigma _{yd}}$<br>where:<br>$d$ = bracket max depth, as defined in Table 10.2.3<br>$t _{bkt}$ = bracket thickness<br>$\sigma _{yd}$ = specified minimum yield stress of material |
| Critical locations |   |   |   |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1135.png) |   |   |   |
| Minimum requirement | As a minimum, detail design standard A or B is to be fitted. Further consideration will be given where hopper angle exceeds 50 degrees. |   |   |
| Critical location | Hopper sloping plating connections to inner bottom plating in way of floors. Floor connections to inner bottom plating and side girders in way of hopper corners. |   |   |
| Detail design standard | Elimination of scallops in way of hopper corners, extension of inner bottom plating to reduce level of resultant stresses arising from cyclic external hydrodynamic pressure, cargo inertia pressure and hull girder loads. Scarfing bracket thickness to be close to that of the inner bottom in way of knuckle. |   |   |
| Building tolerances | Median line of hopper sloping plate is to be in line with the median line of girder with an allowable tolerance of t/3 or 5 mm, whichever is less, where $t$ is the inner bottom thickness. |   |   |
| Welding requirements | Partial penetration welding (hopper sloping plating to inner bottom plating). Partial penetration weld (connection of floors to inner bottom plating and to side girders, connection of hopper transverse webs to sloping plating, to inner bottom plating, and to side girders in way of hopper corners). |   |   |

**Fig C.2.4<br>Hopper Knuckle Connection Detail, Bent Type**

| Connections of floors in double bottom tanks to hopper tanks<br>Hopper corner connections employing bent knuckle inner bottom and hopper sloping plating |   |   |
| --- | --- | --- |
| Critical areas |   | Detail design standard C |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1136.png) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1137.png) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1138.png)<br>#underline{Note:}<br>Longitudinal brackets may be omitted if it can be demonstrated that the girder provides sufficient support at the knuckle line. |
| Critical locations |   |   |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1139.png) |   |   |
| Minimum requirement | As a minimum, the detail design standard C is to be fitted. |   |
| Critical location | Side girder connections to inner bottom plating in way of floors. Floor and hopper transverse web connections to inner bottom plating and to side girders in way of hopper corners. |   |
| Detail design standard | Elimination of scallops in way of hopper corners and additional longitudinal brackets to reduce peak and range of resultant stresses arising from cyclic external hydrodynamic pressure, cargo inertia pressure, and hull girder global loading. |   |
| Building tolerances | Enhanced alignment standard. The nominal distance between the centres of thickness of the two abutting members (e.g. floor and hopper web plate and additional supporting brackets) should not exceed 1/3 of the table member thickness. |   |
| Welding requirements | Partial penetration welding with a maximum root face of 1/3 of the abutting plate thickness (Connection of side girders to inner bottom plating. Connection of floors to inner bottom plating and to side girders. Connection of hopper transverse webs to sloped inner bottom plating and to side girders in way of hopper corners). |   |

**Fig C.2.5<br>Option: Transverse Bulkhead Horizontal Stringer Heel**

| Connections of horizontal girder in double side tanks to transverse bulkheads<br>Connection of horizontal stringer on plane oiltight transverse or wash bulkheads to inner hull longitudinal bulkhead |   |   |   |
| --- | --- | --- | --- |
| Critical areas |   |   | Detail design improvement |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1140.png) |   | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1141.png) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1142.png)<br>#underline{Note:}<br>* Weld toe to be ground smooth, visible undercuts to be removed where brackets not fitted.<br>** Where a face plate is considered necessary, it is recommended that design features be adopted to reduce the stress concentration at the face plate termination (e.g., taper and soft nose). |
| Critical locations |   |   |   |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1143.png) |   |   |   |
| Critical location | Intersections of webs of transverse bulkhead horizontal stringer and double side tank horizontal girder forming square corners. |   |   |
| Detail design improvement | Elimination of scallops in way of cruciform joint and fitting a localized ‘D’ grade steel insert plate, with minimum thickness of 7 mm in addition to the Rule required thickness, to reduce the peak and range of resultant stresses arising from cyclic cargo inertia pressure and hull girder global loading. In addition, a soft toed backing bracket of suitable dimension is to be fitted. The following bracket sizes are recommended:<br>• VLCC: 800 × 800 × 30 R600 with soft toe as shown in Figure<br>• Suezmax and Aframax tankers: 800 × 600 × 25 R550 with soft toe as shown in Figure, where the longer arm length is in way of the inner skin.<br>The actual bracket design is to be verified by fine mesh finite element analysis in accordance with Appendix B/3.1.3. |   |   |
| Building tolerances | Enhanced alignment standard. The nominal distance between the centres of thickness of the two abutting members should not exceed 1/3 of the table member thickness. |   |   |
| Welding requirements | Fillet welding having minimum weld factor of 0.44, where backing bracket is fitted or partial penetration welding where backing bracket is not fitted. The extent of partial penetration should be of the order of longitudinal spacing. A small scallop of suitable shape, which is to be closed by welding after completion of the continuous welding of bulkhead, should be provided where scallop is eliminated. |   |   |

- **2.5.3** Transverse and longitudinal corrugated bulkhead connection to lower stool

#### 2.5.3.1

Detail design improvement given in Fig C.2.6 is recommended for reducing the stress level at the connection of transverse and longitudinal corrugated bulkhead to lower stool. This recommendation should be considered in association with fine mesh FE analysis as required in Appendix B/3.1.5.

**Fig C.2.6<br>Transverse and Longitudinal Bulkhead Connection to Lower Stool**

| Connections of side stringers in double side tanks to transverse bulkheads<br>Higher tensile stringers to horizontal girders on plane oiltight transverse or wash bulkheads |   |   |   |
| --- | --- | --- | --- |
| Critical areas |   |   | Detail design improvement |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1144.png) |   | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1145.png) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1146.png)<br>#underline{Note:}<br>* Full penetration weld is to be applied at the connection of the corrugated bulkhead and stool plate to the shelf plate of the lower stool.<br>** Where adjacent shedder plates cross, a bracket stiffener is to be provided at the crossing point. |
| Critical locations |   |   |   |
| ![](https://kr-rule.krs.co.kr/Files/Document/RA-12-E/2014/image1147.png) |   |   |   |
| Critical location | 1. Connections of corrugated bulkhead to lower stool and shelf plate<br>2. Connections of corrugated bulkhead to shedder plate if fitted without a gusset plate |   |   |
| Detail design improvement | 1. Gusset plate should be fitted to the shelf plate in line with the face of the corrugation to reduce stress concentrations at the corrugated corners. The minimum height of the gusset plate should be taken as half the corrugated bulkhead flange width.<br>2. To reduce stress concentration at the crossing of the shedder plates, shedder plates may be arranged in an alternate configuration as shown in figure. Alternatively, bracketed stiffener may be fitted at the crossing points underneath the shedder plates. |   |   |
| Building tolerances | Ensure good alignment between lower stool sloping plates and corrugation faces as far as possible. The nominal distance between the centres of thickness of the two abutting members should not exceed 1/3 of the table member thickness. |   |   |
| Welding requirements | Full penetration welding should be used at the connections of the bulkhead corrugations, gusset plates and the lower stool sloping plates to the lower stool shelf plate (Grade Z steel is recommended). Start and stop of welding should be as far away as practicable from the corners of the corrugations. |   |   |
