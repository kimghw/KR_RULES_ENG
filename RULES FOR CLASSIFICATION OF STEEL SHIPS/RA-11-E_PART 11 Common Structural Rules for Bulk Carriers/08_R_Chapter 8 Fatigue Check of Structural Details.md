# PART 11 Common Structural Rules for Bulk Carriers

> RULES FOR CLASSIFICATION OF STEEL SHIPS / RA-11-E / 2025 / EN / Rules

## Chapter 8 Fatigue Check of Structural Details

### Section 1 - GENERAL CONSIDERATION

#### 1. General

- **1.1** Application
  - **1.1.1** The requirements of this Chapter are to be applied to ships having length *L* of 150 m or above, with respect to 25 years operation life in North Atlantic.
  - **1.1.2** The requirements of this Chapter apply to fatigue cycles induced by wave loads. Fatigue induced by vibrations, low cycle loads or impact loads such as slamming, is out of the scope of this Chapter.
  - **1.1.3** The requirements of this Chapter are applicable where steel materials have a minimum yield stress less than 400 $\mathrm{N}/mm ^{2}$.
- **1.2** Net scantlings
  - **1.2.1** All scantlings and stresses referred to in this Chapter are net scantlings obtained in accordance with Ch 3, Sec 2.
- **1.3** Subject members
  - **1.3.1** Fatigue strength is to be assessed, in cargo hold area, for all the connected members at the considered locations described in Table 1.

    | Members | Details |
    | --- | --- |
    | Inner bottom plating | Connection with sloping and /or vertical plate of lower stool |
    | Inner bottom plating | Connection with sloping plate of hopper tank |
    | Inner side plating | Connection with sloping plate of hopper tank |
    | Transverse bulkhead | Connection with sloping plate of lower stool |
    | Transverse bulkhead | Connection with sloping plate of upper stool |
    | Hold frames of single side bulk carriers | Connection to the upper and lower wing tank |
    | Ordinary stiffeners in double side space | Connection of longitudinal stiffeners with web frames and transverse bulkhead |
    | Ordinary stiffeners in double side space | Connection of transverse stiffeners with stringer or similar |
    | Ordinary stiffeners in upper and lower wing tank | Connection of longitudinal stiffeners with web frames and transverse bulkhead |
    | Ordinary stiffeners in double bottom | Connection of longitudinal stiffeners with floors and floors in way of lower stool or transverse bulkhead |
    | Hatch corners | Free edges of hatch corners |

#### 2. Definitions

- **2.1** Hot spot
  - **2.1.1** Hot spot is the location where fatigue crack may initiate.
- **2.2** Nominal stress
  - **2.2.1** Nominal stress is the stress in a structural component taking into account macro-geometric effects but disregarding the stress concentration due to structural discontinuities and to the presence of welds.
    Nominal stresses are to be obtained either with the coarse mesh FE analysis specified in Ch 7, Sec 4, or with the simplified procedure specified in Sec 4.
- **2.3** Hot spot stress
  - **2.3.1** Hot spot stress is defined as the local stress at the hot spot. The hot spot stress takes into account the influence of structural discontinuities due to the geometry of the connection but excludes the effects of welds.
    Hot spot stresses are to be obtained either by fine mesh FE analysis specified in Ch 7, Sec 4, or by multiplying nominal stresses by stress concentration factors defined in Sec 4.
- **2.4** Notch stress
  - **2.4.1** Notch stress is defined as the peak stress at the weld toe taking into account stress concentrations due to the effects of structural geometry as well as the presence of welds.
    Notch stress is to be obtained by multiplying hot spot stress by fatigue notch factor defined in Sec 2, [2.3.1], Table 1.

#### 3. Loading

- **3.1** Loading condition
  - **3.1.1** The loading conditions to be considered are defined in Table 2 depending on the ship type. The standard loading conditions illustrated in Ch 4, App 3 are to be considered.

    | Ship type | Full load condition |   | Ballast condition |   |
    | --- | --- | --- | --- | --- |
    | Ship type | Homogeneous | Alternate | Normal ballast | Heavy ballast |
    | BC-A | √ | √ | √ | √ |
    | BC-B | √ | --- | √ | √ |
    | BC-C | √ | --- | √ | √ |
- **3.2** Load case
  - **3.2.1** Load cases
    For each loading condition, the load cases to be considered, defined in Ch 4, Sec 4, [2], are:
    - **(a)** “H1” and “H2” corresponding to the EDW “H” (head sea)
    - **(b)** “F1” and “F2” corresponding to the EDW “F” (following sea)
    - **(c)** “R1” and “R2” corresponding to the EDW “R” (beam sea)
    - **(d)** “P1” and “P2” corresponding to the EDW “P” (beam sea)
  - **3.2.2** In the case of fatigue assessment of hatch corners, only oblique sea is to be considered, taking into account the wave torsional moments defined in Ch 4, Sec 3, [3.4].
  - **3.2.3** Predominant load case
    From the above mentioned load cases and for each loading condition, the load case where the combined stress range is maximum, corresponds to the predominant load case.


### Section 2 - FATIGUE STRENGTH ASSESSMENT

Symbols
For symbols not defined in this Section, refer to Ch 1, Sec 4.
*i* : Suffix which denotes load case “H”, “F”, “R” or “P” specified in Ch 4, Sec 4
“*i*1” denotes load case “H1”, “F1”, “R1” or “P1” and “*i*2” denotes load case “H2”, “F2”, “R2” or “P2”
D*s_W*_,*_i*_(*_k*_) : Hot spot stress range, in $\mathrm{N}/mm ^{2}$, in load case “*i*” of loading condition “(*k*)”
*s_mean*_,*_i*_(*_k*_) : Structural hot spot mean stress, in $\mathrm{N}/mm ^{2}$, in load case “*i*” of loading condition “(*k*)”

#### 1. General

- **1.1** Application
  - **1.1.1** This Section gives the linear cumulative damage procedure for the fatigue strength assessment of this Chapter.
  - **1.1.2** Fatigue strength is assessed based on an equivalent notch stress range obtained by multiplying an equivalent hot spot stress range by a fatigue notch factor.
  - **1.1.3** Hot spot stress ranges and hot spot mean stresses of primary members, longitudinal stiffeners connections and hatch corners are to be assessed respectively by Sec 3, Sec 4 and Sec 5.
  - **1.1.4** Primary members and longitudinal stiffeners connections
    Predominant load cases and ‘condition 1’ are to be obtained respectively in [2.1] and [2.2]. The hot spot stress ranges calculated in Sec 3 or Sec 4, corresponding to the predominant load case for each loading condition, are to be used in [2.3.2] to calculate the equivalent hot spot stress range.
  - **1.1.5** Hatch corners
    The hot spot stress range calculated in Sec 5 is to be used in [2.3.2] to calculate the equivalent hot spot stress range.

#### 2. Equivalent notch stress range

- **2.1** Predominant load case
  - **2.1.1** The predominant load case “*I*” in fatigue assessment for each loading condition is the load case for which the combined stress range for the considered member is the maximum among the load cases “H”, “F”, “R” and “P” specified in Sec 1, [3.2.1].
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1052.png)
    where:
    D*s_W*_,*_i*_(*_k*_) : Combined hot spot stress range, in $\mathrm{N}/mm ^{2}$, defined either in Sec 3, [2.1.1], [2.2.1] or Sec 4, [2.3.1].
    *I* : Suffix which denotes the selected predominant load case of loading condition “(*k*)”.
- **2.2** Loading ‘condition 1’
  - **2.2.1** The ‘condition 1’ is the condition in which the maximum stress calculated by the equation below for the considered member is the largest on the tension side among the loading conditions “homogeneous”, “alternate”, “normal ballast” and “heavy ballast” specified in Sec 1, Table 2.
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1053.png)
    where:
    *s_mean*_,*_I*_(*_k*_) : Structural hot spot mean stress, in $\mathrm{N}/mm ^{2}$, in predominant load case of loading condition “(*k*)” defined in [2.1.1]
    D*s_W*_,*_I*_(*_k*_) : Hot spot stress range, in $\mathrm{N}/mm ^{2}$, in predominant load case of loading condition “(*k*)” defined in [2.1.1]
  - **2.2.2** Further to the determination of ‘condition 1’ according to [2.2.1], the corresponding loading condition is to be indexed with the suffix “*j*” equal1.
- **2.3** Equivalent notch stress range
  - **2.3.1** Equivalent notch stress range
    The equivalent notch stress range, in $\mathrm{N}/mm ^{2}$, for each loading condition is to be calculated with the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1054.png)
    where:
    D*s_equiv*_,*_j* : Equivalent hot spot stress range, in $\mathrm{N}/mm ^{2}$, in loading condition “*j*” obtained by [2.3.2].
    *K_f* : Fatigue notch factor defined in Table 1.

    | Subject | Without weld grinding | With weld grinding<br>(not applicable for ordinary stiffeners and boxing fillet welding^*1) |
    | --- | --- | --- |
    | Butt welded joint | 1.25 | 1.10 |
    | Fillet welded joint | 1.30 | 1.152 |
    | Non welded part | 1.00 | - |

    Note:
    *1 Boxing fillet welding is defined as a fillet weld around a corner of a member as an extension of the principal weld.
    *2 This is applicable for deep penetration welding, or full penetration welding only
    In case where grinding is performed, full details regarding grinding standards including the extent, smoothness particulars, final welding profiles and grinding workmanship as well as quality acceptance criteria are to be submitted to the Society for approval.
    It is preferred that any grinding is carried out by rotary burrs, is to extend below plate surfaces in order to remove any toe defects and ground areas are to have sufficient corrosion protection. Such treatments are to procedure smooth concave profiles at weld toes with the depth of these depressions penetrating into plate surfaces to at least 0.5 mm below the bottom of any visible undercuts.
    The depth of any grooves produced is to be kept to a minimum and, in general, kept to a maximum of 1 mm.
    Under no circumstances is grinding depth to exceed 2 mm or 7 % of plate growth thickness, whichever is smaller.
    Grinding has to extend to 0.5 longitudinal spacing or 0.5 frame spacing at the each side of hot spot locations.
  - **2.3.2** Equivalent hot spot stress range
    The equivalent hot spot stress range, in $\mathrm{N}/mm ^{2}$, is to be calculated for each loading condition with the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1055.png)
    where:
    *f_mean*_,*_j* : Correction factor for mean stress:
    • for hatch corners *f_mean*_,*_j* = 0.77
    • for primary members and longitudinal stiffeners connections, *f_mean*_,*_j* corresponding to the condition “*j*” taken equal to:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1056.png)
    *s_m*_,1 : Local hot spot mean stress, in $\mathrm{N}/mm ^{2}$, in the condition “1”, obtained from the following formulae:
    • if ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1057.png):
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1058.png)
    • if ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1059.png):
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1060.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1061.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1062.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1063.png)
    *s_m*_,*_j* : Local hot spot mean stress, in $\mathrm{N}/mm ^{2}$, in the condition “*j*”, obtained from the following formulae:
    • if ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1064.png):
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1065.png)
    • if ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1066.png):
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1067.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1068.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1069.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1070.png)
    *s_mean*_,*_j* : Structural hot spot mean stress, in $\mathrm{N}/mm ^{2}$, corresponding to the condition “*j*”
    *s_res* : Residual stress, in $\mathrm{N}/mm ^{2}$, taken equal to:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1071.png) for stiffener end connection
    *s_res* = 0 for non welded part and primary members (cruciform joint or butt weld)

#### 3. Calculation of fatigue damage

- **3.1** Correction of the equivalent notch stress range
  - **3.1.1** The equivalent notch stress range is to be corrected with the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1072.png)
    where:
    *f_coat* : Correction factor for corrosive environment, taken equal to:
    *f_coat* = 1.05 for water ballast tanks and fuel oil tank
    *f_coat* = 1.03 for dry bulk cargo holds and void space
    *f_material* : Correction factor for material, taken equal to:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1073.png)
    *f_thick* : Correction factor for plate thickness, taken equal to 1.0 for hatch corners, flat bar or bulb stiffeners, otherwise to be taken equal to:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1074.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1075.png) mm
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1076.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1077.png) mm
    *t* : Net thickness, in mm, of the considered member, taken as the flange in case of stiffeners
    D*s_eq*_,*_j* : Equivalent notch stress range, in $\mathrm{N}/mm ^{2}$, defined in [2.3.1].
- **3.2** Long-term distribution of stress range
  - **3.2.1** The cumulative probability density function of the long-term distribution of combined notch stress ranges is to be taken as a two-parameter Weibull distribution:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1078.png)
    where:
    *x* : Weibull shape parameter, taken equal to 1.0
    *N_R* : Number of cycles, taken equal to $10 ^{4}$.
- **3.3** Elementary fatigue damage
  - **3.3.1** The elementary fatigue damage for each loading condition is to be calculated with the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1079.png)
    where:
    *K* : S-N curve parameter, taken equal to $1.014 \times 10 ^{15}$
    *a_j* : Coefficient taken equal to 1.0 for the assessment of hatch corners and depending on the loading condition specified in Table 2 for primary members and longitudinal stiffeners connections.
    *N_L* : Total number of cycles for the design ship’s life, taken equal to:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1080.png)
    *T_L* : Design life, in seconds, corresponding to 25 years of ship’s life, taken equal to $7.884 \times 10 ^{8}$
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1081.png)
    $\Gamma$ : Type 2 incomplete gamma function
    $\gamma$ : Type 1 incomplete gamma function

    |   | Loading Conditions | BC-A | BC-B, BC-C |
    | --- | --- | --- | --- |
    | *L* < 200 m | Homogeneous | 0.6 | 0.7 |
    | *L* < 200 m | Alternate | 0.1 | --- |
    | *L* < 200 m | Normal ballast | 0.15 | 0.15 |
    | *L* < 200 m | Heavy ballast | 0.15 | 0.15 |
    | *L* ≥ 200 m | Homogeneous | 0.25 | 0.5 |
    | *L* ≥ 200 m | Alternate | 0.25 | --- |
    | *L* ≥ 200 m | Normal ballast | 0.2 | 0.2 |
    | *L* ≥ 200 m | Heavy ballast | 0.3 | 0.3 |

#### 4. Fatigue strength criteria

- **4.1** Cumulative fatigue damage
  - **4.1.1** The cumulative fatigue damage *D* calculated for the combined equivalent stress is to comply with the following criteria:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1082.png)
    where
    *D_j* : Elementary fatigue damage for each loading condition “*j*”.


### Section 3 - STRESS ASSESSMENT OF PRIMARY MEMBERS

Symbols
For symbols not defined in this Section, refer to Ch 1, Sec 4.
*i* : Suffix which denotes load case “H”, “F”, “R” or “P” specified in Ch 4, Sec 4
“*i*1” denotes load case “H1”, “F1”, “R1” or “P1” and “*i*2” denotes load case “H2”, “F2”, “R2” or “P2”
D*s_W*_,*_i*_(*_k*_) : Hot spot stress range, in $\mathrm{N}/mm ^{2}$, in load case “*i*” of loading condition “(*k*)”
*s_mean*_,*_i*_(*_k*_) : Structural hot spot mean stress, in $\mathrm{N}/mm ^{2}$, in load case “*i*” of loading condition “(*k*)”.

#### 1. General

- **1.1** Application
  - **1.1.1** Hot spot stress ranges and structural hot spot mean stresses of primary members are to be assessed according to the requirements of this Section, with the requirements given in Ch 7, Sec 4.

#### 2. Hot spot stress range

- **2.1** Stress range according to the direct method
  - **2.1.1** The hot spot stress range, in $\mathrm{N}/mm ^{2}$, in load case “*i*” of loading condition “(*k*)” is to be obtained from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1083.png)
    where:
    *s_W*_,*_i*_1(*_k*_), *s_W*_,*_i*_2(*_k*_) : Hot spot stress, in $\mathrm{N}/mm ^{2}$, in load case “*i*1” and “*i*2” of loading condition “(*k*)”, obtained by direct FEM analysis using fine mesh model specified in Ch 7, Sec 4.
- **2.2** Stress range according to the superimposition method
  - **2.2.1** Hot spot stress range
    The hot spot stress range, in $\mathrm{N}/mm ^{2}$, in load case “*i*” of loading condition “(*k*)” is to be obtained from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1084.png)
    where:
    *s_LW*_,*_i*_1(*_k*_), *s_LW*_,*_i*_2(*_k*_) : Hot spot stress, in $\mathrm{N}/mm ^{2}$, due to local loads in load cases “*i*1” and “*i*2” for loading condition “(*k*)” obtained by the direct analysis using fine mesh FE model specified in Ch 7, Sec 4
    *s_GW*_,*_i*_1(*_k*_), *s_GW*_,*_i*_2(*_k*_) : Hot spot stress, in $\mathrm{N}/mm ^{2}$, due to hull girder moments in load cases “*i*1” and “*i*2” for loading condition “(*k*)” obtained according to [2.2.2].
  - **2.2.2** Stress due to hull girder moments
    The hull girder hot spot stress, in $\mathrm{N}/mm ^{2}$, in load cases “*i*1” and “*i*2” for loading condition “(*k*)” is to be obtained from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1085.png)
    where:
    *C_WV*_,*_i*_1, *C_WV*_,*_i*_2, *C_WH*_,*_i*_1, *C_WH*_,*_i*_2 : Load combination factors for each load case defined in Ch 4, Sec 4, [2.2]
    *s_WV*_,*_i*_1 : Nominal hull girder stress, in $\mathrm{N}/mm ^{2}$, in sagging condition induced by vertical wave bending moment
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1086.png)
    *s_WV*_,*_i*_2 : Nominal hull girder stress, in $\mathrm{N}/mm ^{2}$, in hogging condition induced by vertical wave bending moment
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1087.png)
    *M_WV*_,*_H*, *M_WV*_,*_S* : Vertical wave bending moments, in kN.m, in hogging and sagging conditions defined in Ch 4, Sec 3, [3.1.1], with *f_p* = 0.5
    *N* : *Z* co-ordinate, in m, of the neutral axis, as defined in Ch 5, Sec 1
    *z* : *Z* co-ordinate, in m, of the point considered
    *s_WH*_,(*_k*_) : Nominal hull girder stress, in $\mathrm{N}/mm ^{2}$, induced by horizontal wave bending moment
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1088.png)
    *M_WH*_,(*_k*_) : Horizontal wave bending moment, in kN.m, in loading condition “(*k*)” defined in Ch 4, Sec 3, [3.3.1], with *f_p* = 0.5
    *y* : *Y* co-ordinate, in m, of the point considered, to be taken positive at port side and negative at starboard side
    *I_Y*, *I_Z* : Net moments of inertia of hull cross-section, in $\mathrm{m} ^{4}$, about transverse and vertical axis respectively, as defined in Ch 5, Sec 1.

#### 3. Hot spot mean stress

- **3.1** Mean stress according to the direct method
  - **3.1.1** The structural hot spot mean stress, in $\mathrm{N}/mm ^{2}$, in load case “*i*” for loading condition “(*k*)” is to be obtained from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1089.png)
- **3.2** Mean stress according to the superimposition method
  - **3.2.1** Hot spot mean stresses
    The structural hot spot mean stress, in $\mathrm{N}/mm ^{2}$, in load case “*i*” for loading condition “(*k*)” is to be obtained from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1090.png)
    where:
    *s_GS*_,(*_k*_) : Hot spot mean stress, in $\mathrm{N}/mm ^{2}$, due to still water hull girder moment in loading condition “(*k*)” obtained according to [3.2.2].
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1091.png),![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1092.png) : As defined in 2.2.1
  - **3.2.2** Stress due to still water hull girder moment
    The hot spot stress, in $\mathrm{N}/mm ^{2}$, due to still water bending moment in loading condition “(*k*)” is to be obtained from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1093.png)
    where:
    *M_S*_,(*_k*_) : Still water vertical bending moment, in kN.m, depending on the loading condition defined in Ch 4, Sec 3, [2.2]. If the design still water bending moments are not defined at a preliminary design stage, still water bending moment in each loading condition may be obtained from the following formulae:
    homogeneous condition ; ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1094.png)
    alternate condition ; ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1095.png)
    normal ballast condition ; ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1096.png)
    heavy ballast condition ; ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1097.png)
    *M_SW*_,*_H*, *M_SW*_,*_S* : Permissible still water bending moment, in kN.m, in hogging and sagging conditions
    *F_MS* : Distribution factor defined in Ch 4, Sec 3, Fig 2


### Section 4 - STRESS ASSESSMENT OF STIFFENERS

Symbols
For symbols not defined in this Section, refer to Ch 1, Sec 4.
*i* : Suffix which denotes load case “H”, “F”, “R” or “P” specified in Ch 4, Sec 4
“*i*1” denotes load case “H1”, “F1”, “R1” or “P1” and “*i*2” denotes load case “H2”, “F2”, “R2” or “P2”
D*s_W*_,*_i*_(*_k*_) : Hot spot stress range, in $\mathrm{N}/mm ^{2}$, in load case “*i*” of loading condition “(*k*)”
*s_mean*_,*_i*_(*_k*_) : Structural hot spot mean stress, in $\mathrm{N}/mm ^{2}$, in load case “*i*” of loading condition “(*k*)”

#### 1. General

- **1.1** Application
  - **1.1.1** Hot spot stress ranges and structural hot spot mean stresses of longitudinal stiffeners are to be assessed in line with the requirements of this Section.
  - **1.1.2** The hot spot stress ranges and structural hot spot mean stresses of longitudinal stiffeners are to be evaluated at the face plate of the longitudinal considering the type of longitudinal end connection and the following locations.
    (1) Transverse webs or floors other than those at transverse bulkhead of cargo hold or in way of stools, such that additional hot spot stress due to the relative displacement may not be considered. These longitudinal end connections are defined in Table 1. When transverse webs or floors are watertight, the coefficients *K_gl* and *K_gh* as defined in Table 2 are to be considered instead of those defined in Table 1.
    (2) Transverse webs or floors at transverse bulkhead of cargo hold in way of stools, such that additional hot spot stress due to the relative displacement should be considered. These longitudinal end connections are defined in Table 2. When transverse webs or floors at transverse bulkhead of cargo hold or in way of stools are not watertight, the coefficients *K_gl* and *K_gh* as defined in Table 1 are to be considered instead of those defined in Table 2.

#### 2. Hot spot stress range

- **2.1** Stress range obtained by the direct method
  - **2.1.1** Hot spot stress ranges, in $\mathrm{N}/mm ^{2}$, calculated with direct calculation for each load case “H”, “F”, “R” and “P” of each loading condition, are to be obtained according to Sec 3, [2.1].
- **2.2** Stress range according to the superimposition method
  - **2.2.1** The hot spot stress ranges, in $\mathrm{N}/mm ^{2}$, for each load case “H”, “F”, “R” and “P” of each loading condition according to the superimposition method are to be obtained according to Sec 3, [2.2].
- **2.3** Stress range according to the simplified procedure
  - **2.3.1** Hot spot stress ranges
    The hot spot stress range, in $\mathrm{N}/mm ^{2}$, due to dynamic loads in load case “*i*” of loading condition “(*k*)” is to be obtained from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1098.png)
    where
    *s_GW*_,*_i*_1(*_k*_), *s_GW*_,*_i*_2(*_k*_) : Stress due to hull girder moment, defined in [2.3.2]
    *s_W1,i1(k)*, *s_W1,i2(k)* : Stress *s_LW,ij(k)*, *s_CW,ij(k)* and *s_LCW,ij(k)* due to hydrodynamic or inertial pressure when the pressure is applied on the same side as the ordinary stiffener depending on the considered case
    *s_W2,i1(k)*, *s_W2,i2(k)* : Stress *s_LW,ij(k)*, *s_CW,ij(k)* and *s_LCW,ij(k)* due to hydrodynamic or inertial pressure when the pressure is applied on the side opposite to the stiffener depending on the considered case
    *s_LW*_,*_i*_1(*_k*_), *s_LW*_,*_i*_2(*_k*_) : Stresses due to wave pressure, defined in [2.3.3]
    *s_CW*_,*_i*_1(*_k*_), *s_CW*_,*_i*_2(*_k*_) : Stresses due to liquid pressure, defined in [2.3.4]
    *s_LCW*_,*_i*_1(*_k*_), *s_LCW*_,*_i*_2(*_k*_) : Stresses due to dry bulk cargo pressure, defined in [2.3.5]
    *s_d,i1(k)*, *s_d,i2(k)* : Stress due to relative displacement of transverse bulkhead, or floor in way of stools, defined in [2.3.6].
  - **2.3.2** Stress due to hull girder moments
    The hull girder hot spot stress, in $\mathrm{N}/mm ^{2}$, in load case “*i*1” and “*i*2” for loading condition “(*k*)” is to be obtained from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1099.png)
    where:
    *K_gh* : Geometrical stress concentration factor for nominal hull girder stress. *K_gh* is given in Table 1 and Table 2 for the longitudinal end connection specified in 1.1.2 and 1.1.2, respectively.
    The stress concentration factor can be evaluated directly by the FE analysis.
    *C_WV*_,*_i*_1, *C_WV*_,*_i*_2, *C_WH*_,*_i*_1, *C_WH*_,*_i*_2 : Load combination factors for each load case defined in Ch 4, Sec 4, [2.2]
    *s_WV*_,*_i*_1, *s_WV*_,*_i*_2, *s_WH*_,(*_k*_) : Nominal hull girder stresses, in $\mathrm{N}/mm ^{2}$, defined in Sec 3, [2.2.2]
  - **2.3.3** Stress due to wave pressure
    The hot spot stress, in $\mathrm{N}/mm ^{2}$, due to the wave pressure in load case “*i*1” and “*i*2” for loading condition “(*k*)” is to be obtained from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1100.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1101.png)![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1102.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1103.png)![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1104.png)
    where:
    *p_W*_,*_ij*_(*_k*_) : Hydrodynamic pressure, in $\mathrm{kN}/m ^{ 2}$, specified in Ch 4, Sec 5, 1.3], [1.4] and [1.5], with *f_p* = 0.5, in load case “*i*1” and “*i*2” for loading condition “(*k*)”. When the location of the considered member is above the waterline, the hydrodynamic pressure is to be taken as the pressure at waterline.
    *K_gl* : Geometrical stress concentration factor for stress due to lateral pressure. *K_gl* is given in Table 1 and Table 2 for the longitudinal end connection specified in [1.1.2 and 1.1.2, respectively. The stress concentration factor can be evaluated directly by the FE analysis.
    *K_s* : Geometrical stress concentration factor due to stiffener geometry
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1105.png)
    *a*, *b* : Eccentricity, in mm, of the face plate as defined in Fig 1. For angle profile, “*b”* is to be taken as half the net actual thickness of the web.
    *t_f,,* *b_f* : Thickness and breadth of face plate, in mm, respectively, as defined in Fig 1
    *w_a*, *w_b* : Net section modulus in A and B respectively (see Fig 1), in $\mathrm{cm} ^{3}$, of the stiffener about the neutral axis parallel to Z axis without attached plating.
    *C_NE*_,*_ij*_(*_k*_) : Correction factor for the non linearity of the wave pressure range in load case “*i*1” and “*i*2” of loading condition “(*k*)”
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1106.png)
    *T_LC*_(*_k*_) : Draught, in m, of the considered loading condition “(*k*)”
    *p_W*_,*_ij*_(*_k*_),*_WL* : Hydrodynamic pressure, in $\mathrm{kN}/m ^{ 2}$, at water line in load case “*i*1” and “*i*2” of loading condition “(*k*)*”*
    *z* : *Z* co-ordinate, in m, of the point considered
    *s* : Stiffener spacing, in m
    l : Span, in m, to be measured as shown in Fig 2. The ends of the span are to be taken at points where the depth of the end bracket, measured from the face plate of the stiffener is equal to half the depth of the stiffener
    *x_f* : Distance, in m, to the hot spot from the closest end of the span l (see Fig 2)
    *w* : Net section modulus, in $\mathrm{cm} ^{3}$, of the considered stiffener. The section modulus *w* is to be calculated considering an effective breadth *s_e*, in m, of attached plating obtained from the following formulae:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1107.png)
    ![Fig 1: Sectional parameters of a stiffener](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1108.png)
    Fig 1: Sectional parameters of a stiffener
    ![Fig 2: Span and hot spot of longitudinal stiffeners](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1109.png)
    Fig 2: Span and hot spot of longitudinal stiffeners
  - **2.3.4** Stress due to liquid pressure
    The hot spot stress, in $\mathrm{N}/mm ^{2}$, due to the liquid pressure in load case “*i*1” and “*i*2” for loading condition “(*k*)” is to be obtained from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1110.png)
    where:
    *p_BW*_,*_ij*_(*_k*_) : Inertial pressure, in $\mathrm{kN}/m ^{ 2}$, due to liquid specified in Ch 4, Sec 6, [2.2], with *f_p* = 0.5, in load case “*i*1” and “*i*2” for loading condition “(*k*)”. Where the considered location is located in fuel oil, other oil or fresh water tanks, no inertial pressure is considered for the tank top longitudinals and when the location of the considered member is above the liquid surface in static and upright condition, the inertial pressure is to be taken at the liquid surface line.
    *C_NI*_,*_ij*_(*_k*_) : Correction factor for the non linearity of the inertial pressure range due to liquid in load case “*i*1” and “*i*2” for loading condition “(*k*)”
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1111.png)
    *z_SF* : *Z* co-ordinate, in m, of the liquid surface. In general, it is taken equal to “Z*_TOP*” defined in Ch 4, Sec 6. If the considered location is located in fuel oil, other oil or fresh water tanks, it may be taken as the distance to the half height of the tank.
    *z* : *Z* co-ordinate, in m, of the point considered
    *p_BW*_,*_ij*_(*_k*_),*_SF*: Inertial pressure due to liquid, in $\mathrm{kN}/m ^{ 2}$, taken at the liquid surface in load case “*i*1” and “*i*2” for loading condition “(*k*)”. In calculating the inertial pressure according to Ch 4, Sec 6, [2.2.1], *x* and *y* coordinates of the reference point are to be taken as liquid surface instead of tank top.
    *K_ghK_s* : The stress concentration factor defined in [2.3.3]
  - **2.3.5** Stress due to dry bulk cargo pressure
    The hot spot stress, in $\mathrm{N}/mm ^{2}$, due to the dry bulk cargo pressure in load case “*i*1” and “*i*2” for loading condition “(*k*)” is to be obtained from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1112.png)
    Where,
    p_CW, ij(k) : Inertial pressure, in $\mathrm{kN}/m ^{ 2}$, due to dry bulk cargo specified in Ch 4, Sec 6 [1.3] for a cargo density p_C specified in Ch.4 Annex 3, and with fp = 0.5, in load case “i1” and “i2” for loading condition “(k)”
  - **2.3.6** Stress due to relative displacement of transverse bulkhead or floor in way of transverse bulkhead or stool
    For longitudinal end connection specified in 1.1.2, the additional hot spot stress, in $\mathrm{N}/mm ^{2}$, due to the relative displacement in the direction perpendicular to the attached plate between the transverse bulkhead or floor in way of stools and the adjacent transverse web or floor in load case “*i*1” and “*i*2” for loading condition “(*k*)” is to be obtained from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1113.png)
    where:
    *a*, *f* : Suffix which denotes the location considered as indicated in Table 2.
    *A*, *F* : Suffix which denotes the direction, forward (*F*) and after ward (*A*), of the transverse web or floor where the relative displacement is occurred as indicated in Table 2. (see Fig 3)
    *s_dF-a*_,*_ij*_(*_k*_), *s_dA-a*_,*_ij*_(*_k*_), *s_dF-f*_,*_ij*_(*_k*_), *s_dA-f*_,*_ij*_(*_k*_) : Additional stress at point “*a*” and “*f*”, in $\mathrm{N}/mm ^{2}$, due to the relative displacement between the transverse bulkhead or floors in way of stools and the forward (*F*) and after ward (*A*) transverse web or floor respectively in load case “*i*1” and “*i*2” for loading condition “(*k*)”
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1114.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1115.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1116.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1117.png)
    *d_F*_,*_ij*_(*_k*_), *d_A*_,*_ij*_(*_k*_) : Relative displacement, in mm, in the direction perpendicular to the attached plate between the transverse bulkhead or floor in way of stools and the forward (*F*) and afterward (*A*) transverse web or floor in load case “*i*1” and “*i*2” for loading condition “(*k*)” (see Fig 3)
    Relative displacement is defined as the displacement of the longitudinal in relation to the line passing through the stiffener end connection at the base of the stool measured at the first floor forward (*F*) or afterward (*A*) of the stool.
    Relative displacement is defined as the displacement of the longitudinal in relation to its original position measured at the first forward (*F*) or afterward (*A*) of the transverse bulkhead.
    Where the stress of the face of longitudinal at the assessment point due to relative displacement is tension, the sign of the relative displacement is positive.
    *I_F*, *I_A* : Net moment of inertia, in cm4, of forward (*F*) and afterward (*A*) longitudinal
    *K_dF-a*, *K_dA-a*, *K_dF-f*, *K_dA-f* : Stress concentration factor for stiffener end connection at point “*a*” and “*f*“ subject to relative displacement between the transverse bulkhead and the forward (*F*) and afterward (*A*) transverse web or floors in way of stool respectively as defined in Table 2. The stress concentration can be evaluated directly by the FE analysis when the detail of end connection is not defined in Table 2.
    l*_F*, l*_A* : Span, in m, of forward (*F*) and afterward (*A*) longitudinal to be measured as shown in Fig 2
    *x_fF*, *x_fA* : Distance, in m, to the hot spot from the closest end of l*_F* and l*_A* respectively (see Fig 2).
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1118.png)
    Fig 3: Definition of the relative displacement (Example of the side longitudinal)
    - **(a)** For longitudinals penetrating floors in way of stools
    - **(b)** For longitudinals other than (a)

#### 3. Hot spot mean stress

- **3.1** Mean stress according to the direct method
  - **3.1.1** The structural hot spot mean stress, in $\mathrm{N}/mm ^{2}$, in each loading condition calculated with the direct method is to be obtained according to Sec 3, [3.1].
- **3.2** Mean stress according to the superimposition method
  - **3.2.1** The structural hot spot mean stress, in $\mathrm{N}/mm ^{2}$, in each loading condition calculated with the superimposition method is to be obtained according to Sec 3, [3.2].
- **3.3** Mean stress according to the simplified procedure
  - **3.3.1** Hot spot mean stresses
    The structural hot spot mean stress, in $\mathrm{N}/mm ^{2}$, in loading condition “(*k*)” regardless of load case “*i*” is to be obtained from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1119.png)
    where
    *s_GS*_,(*_k*_) : Stress due to still water hull girder moment, defined in [3.3.2]
    *s_S*_1,(*_k*_) : Stress due to static pressure when the pressure is applied on the same side as the ordinary stiffener depending on the considered case, with consideration of the stresses defined in [3.3.3] to [3.3.5]
    *s_S*_2,(*_k*_) : Stress due to static pressure when the pressure is applied on the side opposite to the stiffener depending on the considered case
    *s_dS*_,(*_k*_) : Stress due to relative displacement of transverse bulkhead in still water, defined in [3.3.6].
  - **3.3.2** Stress due to still water hull girder moment
    The hot spot stress due to still water bending moment, in $\mathrm{N}/mm ^{2}$, in loading condition “(*k*)” is to be obtained with the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1120.png)
    where:
    *M_S*_,(*_k*_) : Still water vertical bending moment, in kN.m, defined in Sec 3, [3.2.2].
  - **3.3.3** Stress due to hydrostatic and hydrodynamic pressure
    The hot spot stress due to hydrostatic and hydrodynamic pressure, in $\mathrm{N}/mm ^{2}$, in loading condition “(*k*)” is to be obtained with the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1121.png)
    where:
    *p_S*_,(*_k*_) : Hydrostatic pressure, in $\mathrm{kN}/m ^{ 2}$, in loading condition “(*k*)” specified in Ch 4, Sec 5, [1.2].
    *p_CW,ij(k)* : Corrected hydrodynamic pressure, in $\mathrm{kN}/m ^{ 2}$, according to [2.3.3], with *f_p* = 0.5, in load case “*i*l” and “*i*2” for loading condition “(*k*)”
    *i* : Suffix which denotes the load case specified in Sec 2 [2.1.1], when calculating the mean stress, “*I*” is to be used.
  - **3.3.4** Stress due to liquid pressure in still water
    The structural hot spot mean stress due to liquid pressure in still water, in $\mathrm{N}/mm ^{2}$, in loading condition “(*k*)” is to be obtained with the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1122.png)
    where:
    *p_CS*_,(*_k*_) : Liquid pressure in still water, in $\mathrm{kN}/m ^{ 2}$, in loading condition “(*k*)” specified in Ch 4, Sec 6 [2.1]. Where the considered location is located in fuel oil, other oil or fresh water tanks, *d_AP* and *P_PV* defined in Ch 4, Sec 6 are to be taken equal to 0 and *z_TOP* specified in Ch 4, Sec 6, [2.1] is to be takene qual to *z_SF* specified in [2.3.4]
  - **3.3.5** Stress due to dry bulk cargo pressure in still water
    The structural hot spot mean stress due to dry bulk cargo pressure in still water, in $\mathrm{N}/mm ^{2}$, in loading condition “(*k*)” is to be obtained with the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1123.png)
    where:
    *p_CS*_,(*_k*_) : Dry bulk cargo pressure in still water, in $\mathrm{kN}/m ^{ 2}$, in loading condition “(*k*)” specified in Ch 4, Sec 6, [1.2]
  - **3.3.6** Stress due to relative displacement of transverse bulkhead in still water
    The additional hot spot mean stress, in $\mathrm{N}/mm ^{2}$, due to the relative displacement in the transverse direction between the transverse bulkhead and the adjacent transverse web or floor in loading condition “(*k*)”, is to be obtained with the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1124.png)
    where:
    *s_dSF-a*_,(*_k*_), *s_dSA-a*_,(*_k*_), *s_dSF-f*_,(*_k*_), *s_dSA-f*_,(*_k*_) : Additional stress at point “*a*” and “*f*“, in $\mathrm{N}/mm ^{2}$, due to the relative displacement between the transverse bulkhead and the forward (*F*) and afterward (*A*) transverse web or floor respectively in loading condition (*k*)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1125.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1126.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1127.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1128.png)
    *d_SF*_,(*_k*_), *d_SA*_,(*_k*_) : Relative displacement, in mm, in still water in the transverse direction between the transverse bulkhead and the forward (*F*) and afterward (*A*) transverse web or floor respectively in loading condition (*k*)

    | Bracket type | Assessed point | Bracket size | Stress concentration factors |   |
    | --- | --- | --- | --- | --- |
    | Bracket type | Assessed point | Bracket size | $K _{gl}$ | $K _{gh}$ |
    | 1<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1129.png) | $a$ | ----- | 1.65 | 1.1 |
    | 2<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1130.png) | $a$ | $dw \leq d<1.5 dw$ | 1.55 | 1.1 |
    |   | $a$ | $1.5 dw \leq d$ | 1.5 | 1.05 |
    | 3<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1131.png) | $a$ | $dw \leq d<1.5 dw$ | 1.5 | 1.1 |
    |   | $a$ | $1.5 dw \leq d$ | 1.45 | 1.05 |
    | 4<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1132.png) | $f$ | $dw \leq d<1.5 dw$ | 1.4 | 1.1 |
    |   | $f$ | $1.5 dw \leq d$ | 1.4 | 1.05 |
    | 5<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1133.png) | $f$ | $dw \leq d<1.5 dw$ | 1.35 | 1.1 |
    |   | $f$ | $1.5 dw \leq d$ | 1.35 | 1.05 |

    | Bracket type | Assessed point | Bracket size | Stress concentration factors |   |
    | --- | --- | --- | --- | --- |
    | Bracket type | Assessed point | Bracket size | $K _{gl}$ | $K _{gh}$ |
    | 6<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1134.png) | $a$ | $dw \leq d<1.5 dw$ | 1.15 | 1.05 |
    |   | $a$ | $1.5 dw \leq d$ | 1.1 | 1.05 |
    | 7<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1135.png) | $a$ | $dw \leq d<1.5 dw$ | 1.15 | 1.05 |
    |   | $a$ | $1.5 dw \leq d$ | 1.1 | 1.05 |
    | 8<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1136.png) | $a$ | $dw \leq d<1.5 dw$ | 1.1 | 1.1 |
    |   | $a$ | $1.5 dw \leq d$ | 1.05 | 1.05 |
    | 9<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1137.png) | $a$ | $d \leq 2 h$ | 1.45 | 1.1 |
    | 10<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1138.png) | $a$ | $d \leq 2.5 h$ | 1.35 | 1.1 |

    | Bracket type | Assessed point | Bracket size | Stress concentration factors |   |
    | --- | --- | --- | --- | --- |
    | Bracket type | Assessed point | Bracket size | $K _{gl}$ | $K _{gh}$ |
    | 11<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1139.png) | $a$ | $d _{1} \leq 2 h$<br>and<br>$h \leq d _{2}$ | 1.15 | 1.1 |
    |   | $f$ | $d _{1} \leq 2 h$<br>and<br>$h \leq d _{2}$ | 1.85 | 1.1 |
    | 12<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1140.png) | $a$ | $d _{1} \leq 2.5 h$<br>and<br>$h \leq d _{2}$ | 1.15 | 1.1 |
    |   | $f$ | $d _{1} \leq 2.5 h$<br>and<br>$h \leq d _{2}$ | 1.35 | 1.1 |
    | 13<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1141.png) | $a$ | $d _{1} \leq 2 h$<br>and<br>$h \leq d _{2}$ | 1.1 | 1.1 |
    |   | $f$ | $d _{1} \leq 2 h$<br>and<br>$h \leq d _{2}$ | 2.05 | 1.1 |
    | 14<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1142.png) | $a$ | $d _{1} \leq 2.5 h$<br>and<br>$h \leq d _{2}$ | 1.1 | 1.1 |
    |   | $f$ | $d _{1} \leq 2.5 h$<br>and<br>$h \leq d _{2}$ | 1.8 | 1.1 |

    | Bracket type | Assessed point | Bracket size | Stress concentration factors |   |   |   |
    | --- | --- | --- | --- | --- | --- | --- |
    | Bracket type | Assessed point | Bracket size | $K _{gl}$ | $K _{gh}$ | $K _{dF}$ | $K _{dA}$ |
    | 1<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1129.png) | $a$ | ----- | 1.5 | 1.1 | 1.15 | 1.5 |
    |   | $f$ | ----- | 1.1 | 1.05 | 1.55 | 1.05 |
    | 2<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1130.png) | $a$ | $dw \leq d<1.5 dw$ | 1.45 | 1.1 | 1.15 | 1.4 |
    |   | $a$ | $1.5 dw \leq d$ | 1.4 | 1.05 | 1.15 | 1.35 |
    |   | $f$ | $dw \leq d<1.5 dw$ | 1.1 | 1.05 | 1.15 | 1.1 |
    |   | $f$ | $1.5 dw \leq d$ | 1.05 | 1.05 | 1.1 | 1.05 |
    | 3<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1131.png) | $a$ | $dw \leq d<1.5 dw$ | 1.4 | 1.1 | 1.1 | 1.35 |
    |   | $a$ | $1.5 dw \leq d$ | 1.35 | 1.05 | 1.05 | 1.3 |
    |   | $f$ | $dw \leq d<1.5 dw$ | 1.05 | 1.05 | 1.1 | 1.05 |
    |   | $f$ | $1.5 dw \leq d$ | 1.05 | 1.05 | 1.05 | 1.05 |
    | 4<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1132.png) | $a$ | $dw \leq d<1.5 dw$ | 1.1 | 1.05 | 1.05 | 1.25 |
    |   | $a$ | $1.5 dw \leq d$ | 1.05 | 1.05 | 1.05 | 1.2 |
    |   | $f$ | $dw \leq d<1.5 dw$ | 1.3 | 1.1 | 1.35 | 1.05 |
    |   | $f$ | $1.5 dw \leq d$ | 1.3 | 1.05 | 1.3 | 1.05 |
    | 5<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1133.png) | $a$ | $dw \leq d<1.5 dw$ | 1.1 | 1.05 | 1.05 | 1.2 |
    |   | $a$ | $1.5 dw \leq d$ | 1.05 | 1.05 | 1.05 | 1.15 |
    |   | $f$ | $dw \leq d<1.5 dw$ | 1.3 | 1.1 | 1.55 | 1.1 |
    |   | $f$ | $1.5 dw \leq d$ | 1.3 | 1.05 | 1.5 | 1.05 |

    | Bracket type | Assessed point | Bracket size | Stress concentration factors |   |   |   |
    | --- | --- | --- | --- | --- | --- | --- |
    | Bracket type | Assessed point | Bracket size | $K _{gl}$ | $K _{gh}$ | $K _{dF}$ | $K _{dA}$ |
    | 6<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1134.png) | $a$ | $dw \leq d<1.5 dw$ | 1.1 | 1.05 | 1.05 | 1.1 |
    |   | $a$ | $1.5 dw \leq d$ | 1.05 | 1.05 | 1.05 | 1.05 |
    |   | $f$ | $dw \leq d<1.5 dw$ | 1.05 | 1.05 | 1.1 | 1.05 |
    |   | $f$ | $1.5 dw \leq d$ | 1.05 | 1.05 | 1.05 | 1.05 |
    | 7<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1135.png) | $a$ | $dw \leq d<1.5 dw$ | 1.1 | 1.05 | 1.05 | 1.2 |
    |   | $a$ | $1.5 dw \leq d$ | 1.05 | 1.05 | 1.05 | 1.15 |
    |   | $f$ | $dw \leq d<1.5 dw$ | 1.05 | 1.05 | 1.05 | 1.05 |
    |   | $f$ | $1.5 dw \leq d$ | 1.05 | 1.05 | 1.05 | 1.05 |
    | 8<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1136.png) | $a$ | $dw \leq d<1.5 dw$ | 1.1 | 1.1 | 1.05 | 1.15 |
    |   | $a$ | $1.5 dw \leq d$ | 1.05 | 1.05 | 1.05 | 1.1 |
    |   | $f$ | $dw \leq d<1.5 dw$ | 1.05 | 1.05 | 1.1 | 1.05 |
    |   | $f$ | $1.5 dw \leq d$ | 1.05 | 1.05 | 1.05 | 1.05 |
    | 9<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1137.png) | $a$ | $d \leq 2 h$ | 1.4 | 1.05 | 1.05 | 1.75 |
    |   | $f$ | $d \leq 2 h$ | 1.6 | 1.05 | 1.7 | 1.05 |
    | 10<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1138.png) | $a$ | $d \leq 2.5 h$ | 1.3 | 1.05 | 1.05 | 1.75 |
    |   | $f$ | $d \leq 2.5 h$ | 1.55 | 1.05 | 1.3 | 1.05 |

    | Bracket type | Assessed point | Bracket size | Stress concentration factors |   |   |   |
    | --- | --- | --- | --- | --- | --- | --- |
    | Bracket type | Assessed point | Bracket size | $K _{gl}$ | $K _{gh}$ | $K _{dF}$ | $K _{dA}$ |
    | 11<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1139.png) | $a$ | $d _{1} \leq 2 h$<br>and<br>$h \leq d _{2}$ | 1.1 | 1.05 | 1.05 | 1.2 |
    |   | $f$ | $d _{1} \leq 2 h$<br>and<br>$h \leq d _{2}$ | 1.75 | 1.05 | 1.4 | 1.05 |
    | 12<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1140.png) | $a$ | $d _{1} \leq 2.5 h$<br>and<br>$h \leq d _{2}$ | 1.1 | 1.05 | 1.05 | 1.2 |
    |   | $f$ | $d _{1} \leq 2.5 h$<br>and<br>$h \leq d _{2}$ | 1.3 | 1.05 | 1.05 | 1.05 |
    | 13<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1141.png) | $a$ | $d _{1} \leq 2 h$<br>and<br>$h \leq d _{2}$ | 1.05 | 1.05 | 1.05 | 1.15 |
    |   | $f$ | $d _{1} \leq 2 h$<br>and<br>$h \leq d _{2}$ | 1.95 | 1.05 | 1.55 | 1.05 |
    | 14<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1142.png) | $a$ | $d _{1} \leq 2.5 h$<br>and<br>$h \leq d _{2}$ | 1.05 | 1.05 | 1.05 | 1.15 |
    |   | $f$ | $d _{1} \leq 2.5 h$<br>and<br>$h \leq d _{2}$ | 1.7 | 1.05 | 1.15 | 1.05 |


### Section 5 - STRESS ASSESSMENT OF HATCH CORNERS

#### 1. General

- **1.1** Application
  - **1.1.1** Hot spot stress ranges and structural hot spot mean stresses of hatch corners based on the simplified procedure are to be assessed according to the requirements of this Section.

#### 2. Nominal stress range

- **2.1** Nominal stress range due to wave torsional moment
  - **2.1.1** The nominal stress range, in $\mathrm{N}/mm ^{2}$, due to cross deck bending induced by wave torsion moments is to be obtained from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1143.png)
    where:
    ![](images/image1144.png)
    *u* : Displacement of hatch corner in longitudinal direction, in m, taken equal to:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1145.png)
    *DOC* : Deck opening coefficient, taken equal to:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1146.png)
    *M_WT* : Maximum wave torsional moment, in kN.m, defined in Ch 4, Sec 3, [3.4.1], with *f_p* = 0.5
    *F_S* : Stress correction factor, taken equal to:
    $F _{s} = 5$
    *F_L* : Correction factor for longitudinal position of hatch corner, taken equal to:
    $F _{L} = 1.75 \frac{x}{L}$ for $0.57 \leq x/L \leq 0.85$
    $F _{L} = 1.0$ for $x/L<0.57 and x/L>0.85$
    *B_H* : Breadth of hatch opening, in m
    *W_Q* : Section modulus of the cross deck about *z*-axis, in $\mathrm{m} ^{3}$, including upper stool, near hatch corner (see Fig 2)
    *I_Q* : Moment of inertia of the cross deck about *z*-axis, in $\mathrm{m} ^{4}$, including upper stool, near the hatch corner (see Fig 2)
    *A_Q* : Effective shear area of the whole section of the cross deck, in $\mathrm{m}^{ 2}$, including upper stool, near the hatch corner (see Fig 2). For the determination of the effective shear area the consideration of only the plate elements is sufficient, and the stiffeners can be neglected.
    *b_S* : Breadth of remaining deck strip on one side, in m, beside the hatch opening
    *I_T* : Torsion moment of inertia of ships cross section, in $\mathrm{m} ^{4}$, calculated within cross deck area by neglecting upper and lower stool of the bulkhead (see Fig 1). It may be calculated according to App 1
    *ω* : Sector coordinate, in $\mathrm{m}^{ 2}$, calculated at the same cross section as *I_T* and at the *Y* and *Z* location of the hatch corner (see Fig 1) It may be calculated according to App 1
    *L_C* : Length of cargo area, in m, being the distance between engine room bulkhead and collision bulkhead
    *B_H,i* : Breadth of hatch opening of hatch *i*, in m
    *L_H,i* : Length of hatch opening of hatch *i*, in m
    *n* : Number of hatches.
    ![Fig 1: Cross section for determination of I_T and ω](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1147.png)
    Fig 1: Cross section for determination of *I_T* and *ω*
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1148.png)
    Fig 2: Elements to be considered for the determination of *A_Q*, *W_Q* and *I_Q*
- **2.2** Nominal mean stress
  - **2.2.1** The mean stress due to still water bending moment within the cross deck is set to 0.

#### 3. Hot spot stress

- **3.1** Hot spot stress range
  - **3.1.1** The hot spot stress range, in $\mathrm{N}/mm ^{2}$, is to be obtained from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1149.png)
    where:
    *K_gh* : Stress concentration factor for the hatch corner, taken equal to:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1150.png), to be taken not less than 1.0
    *r_a* : Radius, in m, in major axis
    *r_b* : Radius, in m, in minor axis (if the shape of corner is a circular arc, *r_b* is to be equal to *r_a*)
    l*_CD* : Length of cross deck, in m, in longitudinal direction
    *b* : Distance, in m, from the edge of hatch opening to the ship’s side.


### Appendix 1 - CROSS SECTIONAL PROPERTIES FOR TORSION

#### 1. Calculation Formulae

- **1.1** Torsion Function $\Phi$
  - **1.1.1** For any partial area of closed cells the following geometric figures and ratios have to be computed:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1151.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1152.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1153.png)
    ![Fig 1:](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1154.png)
    Fig 1:
    The following three versions of algorithms may be applied depending on the type of cross section:
    Version A: Asymmetric open cross sections as shown in Fig 2
    Version B: Symmetric cross sections with particular closed cells (closed cells without shared walls) as shown in Fig 3. In this case the torsion function can be calculated for each cell separately.
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1155.png) ; ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1156.png)
    Version C: Symmetric cross sections with multiple closed cells (closed cells with shared walls) as shown in Fig 4. In this case the torsion function for each cell *i* can be calculated by solving a linear system of equations considering the shared walls.
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1157.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1158.png)
    From this system of equations the torsion functions ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1159.png) and ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1160.png) can be derived.
- **1.2** Co-ordinate system, running coordinate s
  - **1.2.1** A 2-D cartesian co-ordinate system is to be used. The choice of the reference point O (origin of co-ordinate system) is free, but for symmetric cross sections it is advantageous to define the origin at the line of symmetry of the cross section. The running co-ordinate *s* starts within symmetric cross sections at the intersection of the line of symmetry with the cross section geometry, e.g. in hull cross sections at the intersection of centreline and bottom shell or double-bottom as indicated by ‘0’ in Fig 2 to Fig 4. The orientation of *s* as well as the direction of integration within closed cells is to be considered with respect to the algebraic signs and the assembly of the system of equations for the torsion function.
- **1.3** Computation of several properties for each part of the cross section
  - **1.3.1** ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1161.png) = ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1162.png) of the preceding partial area or of the preceding point of bifurcation. (to be set equal to zero at the beginning of the computation)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1163.png) = ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1164.png) , with ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1165.png) within closed cells
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1166.png) = ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1167.png)
    Summation
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1168.png) = ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1169.png) ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1170.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1171.png) = ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1172.png) ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1173.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1174.png) = ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1175.png) ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1176.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1177.png) = ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1178.png) ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1179.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1180.png) = ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1181.png) ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1182.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1183.png) = ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1184.png) ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1185.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1186.png) = ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1187.png) ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1188.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1189.png) = ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1190.png) ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1191.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1192.png) = ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1193.png) ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1194.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1195.png) = ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1196.png) ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1197.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1198.png) = ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1199.png) ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1200.png)
- **1.4** Computation of cross sectional properties for the entire cross section

  | Asymmetric cross section: | Symmetric cross section<br>(only half of the section is modeled) |
  | --- | --- |
  | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1201.png) = ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1202.png) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1203.png) = ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1204.png) |
  | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1205.png) = ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1206.png) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1207.png) = ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1208.png) |
  | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1209.png) = ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1210.png) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1211.png) = ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1212.png) |
  | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1213.png) = ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1214.png) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1215.png) = ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1216.png) |
  | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1217.png) = ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1218.png) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1219.png) = ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1220.png) |
  | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1221.png) = ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1222.png) |   |
  | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1223.png) = ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1224.png) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1225.png) = ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1226.png) |
  | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1227.png) = ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1228.png) |   |
  | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1229.png) = ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1230.png) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1231.png) = ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1232.png) |
  | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1233.png) = ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1234.png) |   |
  | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1235.png) = ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1236.png) |   |
  | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1237.png) = ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1238.png) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1239.png) = ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1240.png) |
  | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1241.png) = ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1242.png) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1243.png) = ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1244.png) |

  $I _{y}$, $I _{z}$, $I _{yz}$ are to be computed with relation to the centre of gravity.
  $S _{x}$, $S _{y}$, $S _{\omega }$, $I _{\omega }$, $I _{\omega y}$ and $I _{\omega z}$ are to be computed with relation to shear centre *M*
  The sector-coordinate $\omega$ has to be transformed with respect to the location of the shear centre *M*. For cross sections of type A, $\omega _{0}$ is to be added to each $\omega _{i}$ and $\omega _{k}$ as defined in [1.3]
  For cross sections of type B and C, $\Delta \omega$ can be calculated as follows:
  $\Delta \omega _{i} = z _{M} y _{i}$
  where:
  $\omega _{0}$ : Calculated sector co-ordinate with respect to the centre of the coordinate system (O) selected for the calculation according to the formulae for $\omega _{k}$ given in [1.3]
  $\omega$ : Transformed sector co-ordinate with respect to shear centre *M*
  $y _{M}$, $z _{M}$ : Distance between shear centre *M* and centre of the coordinate system B.
  The transformed values of $\omega$ can be obtained by adding $\Delta \omega$ to the values of $\omega _{0}$ obtained according to the formulae in [1.3].
  The transformed value for $\omega$ is to be equal to zero at intersections of the cross section with the line of symmetry (centreline for ship-sections).
  ![Fig 2: Cross sections of type A](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1245.png)
  Fig 2: Cross sections of type A
  ![Fig 3: Cross sections of type B](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1246.png)
  Fig 3: Cross sections of type B
  ![Fig 4: Cross section of type C](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1247.png)
  Fig 4: Cross section of type C
  Designation of line types (numbers at particular parts of cross sections) gives the order of the particular parts for the calculation and therefore the direction of the running coordinate *s*.

#### 2. Example calculation for a single side hull cross section

- **2.1** Cross section data
  - **2.1.1** The cross section is shown in Fig 5. The co-ordinates of the node-points marked by filled black circles in Fig 5 are given in the Table 1, where the plate thicknesses and the line segments (marked by circles in Fig 5) of the cross section are given in Table 2.

    | Node number | *Y* Coordinate | *Z* Coordinate |
    | --- | --- | --- |
    | 0 | 0.00 | 0.00 |
    | 1 | 14.42 | 0.00 |
    | 2 | 16.13 | 1.72 |
    | 3 | 16.13 | 6.11 |
    | 4 | 11.70 | 1.68 |
    | 5 | 0.00 | 1.68 |
    | 6 | 16.13 | 14.15 |
    | 7 | 16.13 | 19.6 |
    | 8 | 7.50 | 20.25 |
    | 9 | 7.50 | 19.63 |
    | 10 | 0.00 | 20.25 |
- **2.2** Determination of the torsion function $\Phi$
  - **2.2.1** The first step is to build a linear system of equation for the determination of the torsion function $\Phi$ of each closed cell. The cross section and the cells are shown in Fig 5.
    ![Fig 5: Single side hull cross section](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1248.png)
    Fig 5: Single side hull cross section

    | Line-No. | Node *i* | Node *k* | *y_i* | *z_i* | *y_k* | *z_k* | Length | Thickness |
    | --- | --- | --- | --- | --- | --- | --- | --- | --- |
    | 1 | 0 | 1 | 0.00 | 0.00 | 14.42 | 0.00 | 14.42 | 0.017 |
    | 2 | 1 | 2 | 14.42 | 0.00 | 16.13 | 1.72 | 2.43 | 0.017 |
    | 3 | 2 | 3 | 16.13 | 1.72 | 16.13 | 6.11 | 4.39 | 0.018 |
    | 4 | 3 | 4 | 16.13 | 6.11 | 11.70 | 1.68 | 6.26 | 0.019 |
    | 5 | 4 | 5 | 11.70 | 1.68 | 0.00 | 1.68 | 11.70 | 0.021 |
    | 6 | 3 | 6 | 16.13 | 6.11 | 16.13 | 14.15 | 8.04 | 0.018 |
    | 7 | 6 | 7 | 16.13 | 14.15 | 16.13 | 19.6 | 5.45 | 0.021 |
    | 8 | 7 | 8 | 16.13 | 19.60 | 7.50 | 20.25 | 8.65 | 0.024 |
    | 9 | 8 | 9 | 7.50 | 20.25 | 7.50 | 19.63 | 0.62 | 0.024 |
    | 10 | 9 | 6 | 7.50 | 19.63 | 16.13 | 14.15 | 10.22 | 0.015 |
    | 11 | 8 | 10 | 7.50 | 20.25 | 0.00 | 20.25 | 7.50 | 0.012 |

    Under consideration of the 4 cells (marked by rectangles in Fig 5) of the cross section, the following system of equation for the determination of the torsion function $\Phi$ can be developed. It should be noted that the direction of the rotation is to be considered (the rotation directions for the torsion functions $\Phi _{i}$should point in the same direction for all $\Phi _{i}$ to build up the system of equations).
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1249.png)
    The coefficients of the matrix can be calculated as follows:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1250.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1251.png)
    The areas of the cells can be calculated as follows:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1252.png)
    With these results the coefficient matrix will become:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1253.png)
    The solution of this system gives:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1254.png)
- **2.3** Determination of the line-segment properties
  - **2.3.1** The next step is the determination of $\omega _{k}$ according to the formulae given in [1.3]. ‘*s*’ starts at point 0 (Fig 5) with $\omega _{i}$ = 0 and follows the path from point 0 to point 1, 2, 3, 4 up to point 5. It is to be noted, that the term $\Phi \left( \ell _{i} /t _{i} \right)$ is for the line segments 1 to 3 (between points 0 and 3) calculated as $\Phi _{4} \left( \ell _{1...3} /t _{1...3} \right)$ where for the line segments 4 and 5 this term becomes $(\Phi _{4} - \Phi _{1} ) \left( \ell _{4...5} /t _{4...5} \right)$ because line segments 4 and 5 are shared walls of cell 4 and cell 1. The rotation direction for the torsion functions together with the direction of integration (direction of path, which one follows for the calculation) determines the algebraic sign within this term.
    For the line segment 6 $\omega _{i}$ has to be set to the value at point 3 and $\Phi \left( \ell _{i} /t _{i} \right) = \Phi _{1} \left( \ell _{6} /t _{6} \right)$. ‘*s*’ follows now the path from point 6 to point 7, 8, 9 back to point 6. The shared wall between cell 2 and cell 1 has to be considered for the terms which include the torsion function $\Phi$. For the line segment 11 between point 8 and 10, $\omega _{i}$ has to be set to the value at point 8.
    The other properties of the line segments can be calculated by the formulas given in [1.3].
- **2.4** Determination of cross-section properties
  - **2.4.1** After the summation of the line-segment properties, the cross section properties can be calculated as described in [1.4].
    The sector coordinate has to be transformed with respect to the shear centre as described in [1.4]
    The result of the calculations gives the sector co-ordinates, as indicated in Table 3.
    Table 3: Sector co-ordinates for the cross section of Fig 5

    | Point *i* | $\omega _{O,i}$ | $\Delta \omega _{i}$ | $\omega _{i}$ |
    | --- | --- | --- | --- |
    | 0 | 0.00 | 0.00 | 0.00 |
    | 1 | -135.97 | 84.99 | -50.98 |
    | 2 | -134.04 | 95.07 | -38.97 |
    | 3 | -102.32 | 95.07 | -7.25 |
    | 4 | -99.49 | 68.96 | -30.53 |
    | 5 | -0.06 | 0.00 | -0.06 |
    | 6 | -108.20 | 95.07 | -13.13 |
    | 7 | -72.30 | 95.07 | 22.77 |
    | 8 | 35.07 | 44.21 | 79.27 |
    | 9 | 33.08 | 44.21 | 77.28 |
    | 10 | -2.75 | 0.00 | -2.75 |
- **2.5** Notes
  - **2.5.1** For holds of single side skin construction, the hull cross section normally can be simplified in a section with four boxes (cell 1 cargo hold, cell 2 and 3 wing tanks and cell 4 hopper tanks and double bottom as shown in the calculation example) whereas the cross section of holds of double side skin construction, can be simplified to a cross section with two closed cells only (cell 1 cargo hold, cell 2 double hull). For the plate thickness of the line elements with variable thicknesses an equivalent plate thickness can be used calculated by the following formulae:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1255.png)
    Due to the simplifications, the value of the sector co-ordinate $\omega$ can differ from 0 at the intersections between the cross section and centreline. The difference between the value of the sector co-ordinate $\omega$ and the value of the torsional moment of inertia *I_T* for the simplified cross section is in normal cases less than 3 % compared to the values of the original cross section. ![](images/image9.png)
