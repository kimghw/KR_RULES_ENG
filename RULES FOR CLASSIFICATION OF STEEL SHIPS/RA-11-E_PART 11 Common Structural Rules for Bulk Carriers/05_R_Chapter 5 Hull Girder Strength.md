# PART 11 Common Structural Rules for Bulk Carriers

> RULES FOR CLASSIFICATION OF STEEL SHIPS / RA-11-E / 2025 / EN / Rules

## Chapter 5 Hull Girder Strength

### Section 1 - Yielding check

Symbols
For symbols not defined in this Section, refer to Ch 1, Sec 4.
$M _{SW}$ : Design still water bending moment in intact condition, in kN.m, at the hull transverse section considered, defined in Ch 4, Sec 3, [2.2]:
$M _{SW}$ = $M _{SW,H}$ in hogging conditions
$M _{SW}$ = $M _{SW,S}$ in sagging conditions
$M _{WV}$ : Vertical wave bending moment in intact condition, in kN.m, at the hull transverse section considered, defined in Ch 4, Sec 3, [3.1]
$M _{SW,F}$ : Still water bending moment, in kN.m, in flooded conditions, at the hull transverse section under consideration, to be calculated according to Ch 4, Sec 3
$M _{WV,F}$ : Vertical wave bending moment, in kN.m, in flooded conditions, at the hull transverse section under consideration, to be calculated according to Ch 4, Sec 3
$M _{WV,P}$ : Vertical wave bending moment, in kN.m, in harbour conditions, at the hull transverse section under consideration, to be calculated according to Ch 4, Sec 3
$M _{WH}$ : Horizontal wave bending moment, in kN.m, at the hull transverse section considered, defined in Ch 4, Sec 3, [3.3]
$Q _{SW}$ : Design still water shear force in intact condition, in kN, at the hull transverse section considered, defined in Ch 4, Sec 3, [2.3]
$Q _{WV}$ : Vertical wave shear force in intact condition, in kN, at the hull transverse section considered, defined in Ch 4, Sec 3, [3.2]
$Q _{SW,F}$ : Still water shear force, in kN, in flooded conditions, at the hull transverse section under consideration, to be calculated according to Ch 4, Sec 3
$Q _{WV,F}$ : Vertical wave shear force, in kN, in flooded conditions, at the hull transverse section under consideration, to be calculated according to Ch 4, Sec 3
$Q _{WV,P}$ : Vertical wave shear force, in kN, in harbour conditions, at the hull transverse section under consideration, to be calculated according to Ch 4, Sec 3
$k$ : Material factor, as defined in Ch 1, Sec 4, [2.2.1]
$x$ : *X* co-ordinate, in m, of the calculation point with respect to the reference co-ordinate system defined in Ch 1, Sec 4, [4]
$z$ : *Z* co-ordinate, in m, of the calculation point with respect to the reference co-ordinate system defined in Ch 1, Sec 4, [4]
$N$ : *Z* co-ordinate, in m, of the centre of gravity of the hull transverse section defined in [1.2], with respect to the reference co-ordinate system defined in Ch 1, Sec 4, [4]
$V _{D}$ : Vertical distance, in m, defined in [1.4.2]
$I _{Y}$ : Net moment of inertia, in $\mathrm{m} ^{4}$, of the hull transverse section about its horizontal neutral axis, to be calculated according to [1.5]
$I _{Z}$ : Net moment of inertia, in $\mathrm{m} ^{4}$, of the hull transverse section about its vertical neutral axis, to be calculated according to [1.5]
$S$ : Net first moment, in $\mathrm{m} ^{3}$, of the hull transverse section, to be calculated according to [1.6]
$Z _{A}$ : Net section modulus, in $\mathrm{m} ^{3}$,at any point of the hull transverse section, to be calculated according [1.4.1]
$Z _{AB} , Z _{AD}$: Net section moduli, in $\mathrm{m} ^{3}$, at bottom and deck, respectively, to be calculated according to [1.4.2]
$C$ : Wave parameter defined in Ch 1, Sec 4, [2.3.1]
$\sigma _{1,ALL}$ : Allowable normal stress, in $\mathrm{N}/mm ^{2}$, defined in [3.1.1]
$\tau _{1,ALL}$ : Allowable shear stress, in $\mathrm{N}/mm ^{2}$, defined in [3.2.1]
$\rho$ : Sea water density, taken equal to 1.025 $\mathrm{t}/m ^{3}$.

#### 1. Strength characteristics of the hull girder transverse sections

- **1.1** General
  - **1.1.1** This Article specifies the criteria for calculating the hull girder strength characteristics to be used for the checks in [2] to [5], in association with the hull girder loads specified in Ch 4, Sec 3.
- **1.2** Hull girder transverse sections
  - **1.2.1** General
    Hull girder transverse sections are to be considered as being constituted by the members contributing to the hull girder longitudinal strength, i.e. all continuous longitudinal members below and including the strength deck defined in [1.3], taking into account the requirements in [1.2.2] to [1.2.9].
    These members are to be considered as having (see also Ch 3, Sec 2) net offered scantlings based on gross offered thickness reduced by 0.5 *t_C*, when the hull girder strength characteristics are used for:
    • the hull girder yielding check according to [2] to [5]
    • the ultimate strength check in Ch 5, Sec 2
    • the calculation of the hull girder stresses for the strength checks of plating, ordinary stiffeners and primary supporting members according to Ch 6.
  - **1.2.2** Continuous trunks and continuous longitudinal hatch coamings
    Continuous trunks and continuous longitudinal hatch coamings may be included in the hull girder transverse sections, provided they are effectively supported by longitudinal bulkheads or primary supporting members.
  - **1.2.3** Longitudinal ordinary stiffeners or girders welded above the strength deck
    Longitudinal ordinary stiffeners or girders welded above the strength deck (including the deck of any trunk fitted as specified in [1.2.2]) are to be included in the hull girder transverse sections.
  - **1.2.4** Longitudinal girders between hatchways, supported by longitudinal bulkheads
    Where longitudinal girders, effectively supported by longitudinal bulkheads, are fitted between hatchways, the sectional area of these longitudinal girders are to be included in the hull girder transverse.
  - **1.2.5** Longitudinal bulkheads with vertical corrugations
    Longitudinal bulkheads with vertical corrugations are not to be included in the hull girder transverse sections.
  - **1.2.6** Members in materials other than steel
    Where a member contributing to the longitudinal strength is made in material other than steel with a Young’s modulus *E* equal to $2.06 \times 10 ^{5}$ $\mathrm{N}/mm ^{2}$, the steel equivalent sectional area that may be included in the hull girder transverse sections is obtained, in $\mathrm{m}^{ 2}$, from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image377.png)
    where:
    *A_M* : Sectional area, in $\mathrm{m}^{ 2}$, of the member under consideration.
  - **1.2.7** Large openings
    Large openings are:
    • elliptical openings exceeding 2.5 m in length or 1.2 m in breadth
    • circular openings exceeding 0.9 m in diameter.
    Large openings and scallops, where scallop welding is applied, are always to be deducted from the sectional areas included in the hull girder transverse sections.
  - **1.2.8** Small openings
    Smaller openings than those in [1.2.7] in one transverse section in the strength deck or bottom area need not be deducted from the sectional areas included in the hull girder transverse sections, provided that:
    $\Sigma b _{S} \leq 0.06 (B- \Sigma b)$
    where:
    $\Sigma b _{S}$ : Total breadth of small openings, in m, in the strength deck or bottom area at the transverse section considered, determined as indicated in Fig 1
    $\Sigma b$ : Total breadth of large openings, in m, at the transverse section considered, determined as indicated in Fig 1.
    Where the total breadth of small openings $\Sigma b _{S}$ does not fulfil the above criteria, only the excess of breadth is to be deducted from the sectional areas included in the hull girder transverse sections.
  - **1.2.9** Lightening holes, draining holes and single scallops
    Lightening holes, draining holes and single scallops in longitudinals need not be deducted if their height is less than 0.25 *h_w*, without being greater than 75 mm, where *h_w* is the web height, in mm.
    Otherwise, the excess is to be deducted from the sectional area or compensated.
    ![Fig 1: Calculation of #eqnID-831 and #eqnID-832](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image378.png)
    Fig 1: Calculation of #eqnID-831 and #eqnID-832
- **1.3** Strength deck
  - **1.3.1** The strength deck is, in general, the uppermost continuous deck.
    In the case of a superstructure or deckhouses contributing to the longitudinal strength, the strength deck is the deck of the superstructure or the deck of the uppermost deckhouse.
  - **1.3.2** A superstructure extending at least 0.15 *L* within 0.4 *L* amidships may generally be considered as contributing to the longitudinal strength.
    For other superstructures and for deckhouses, their contribution to the longitudinal strength is to be assessed on a case by case basis, to evaluate their percentage of participation to the longitudinal strength.
- **1.4** Section modulus
  - **1.4.1** The section modulus at any point of a hull transverse section is obtained, in $\mathrm{m} ^{3}$, from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image379.png)
  - **1.4.2** The section moduli at bottom and at deck are obtained, in $\mathrm{m} ^{3}$, from the following formulae:
    • at bottom:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image380.png)
    • at deck:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image381.png)
    where:
    *V_D* : Vertical distance, in m, taken equal to:
    • in general:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image382.png)
    where:
    *z_D* : Z co-ordinate, in m, of strength deck at side, defined in [1.3], with respect to the reference co-ordinate system defined in Ch 1, Sec 4, [4]
    • if continuous trunks or hatch coamings are taken into account in the calculation of *I_Y*, as specified in [1.2.2]:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image383.png)
    where:
    *y_T*,*z_T* : Y and Z co-ordinates, in m, of the top of continuous trunk or hatch coaming with respect to the reference co-ordinate system defined in Ch 1, Sec 4, [4]; *y_T* and *z_T* are to be measured for the point which maximises the value of *V_D*
    • if longitudinal ordinary stiffeners or girders welded above the strength deck are taken into account in the calculation of *I_Y*, as specified in [1.2.3], *V_D* is to be obtained from the formula given above for continuous trunks and hatch coamings. In this case, *y_T* and *z_T* are the Y and Z co-ordinates, in m, of the top of the longitudinal stiffeners or girders with respect to the reference co-ordinate system defined in Ch 1, Sec 4, [4].
- **1.5** Moments of inertia
  - **1.5.1** The moments of inertia *I_Y* and *I_Z*, in $\mathrm{m} ^{4}$, are those, calculated about the horizontal and vertical neutral axes, respectively, of the hull transverse sections defined in [1.2].
- **1.6** First moment
  - **1.6.1** The first moment *S,* in $\mathrm{m} ^{3}$, at a level *z* above the baseline is that, calculated with respect to the horizontal neutral axis, of the portion of the hull transverse sections defined in [1.2] located above the *z* level.

#### 2. Hull girder stresses

- **2.1** Normal stresses
  - **2.1.1** General
    The normal stresses in a member made in material other than steel with a Young’s modulus *E* equal to $2.06 \times 10 ^{5}$ $\mathrm{N}/mm ^{2}$, included in the hull girder transverse sections as specified in [1.2.6], are obtained from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image384.png)
    where:
    $\sigma _{1S}$ : Normal stress, in $\mathrm{N}/mm ^{2}$, in the member under consideration, calculated according to [2.1.2] and [2.1.3] considering this member as having the steel equivalent sectional area *A_SE* defined in [1.2.6].
  - **2.1.2** Normal stresses induced by vertical bending moments
    The normal stresses induced by vertical bending moments are obtained, in $\mathrm{N}/mm ^{2}$, from the following formulae:
    • at any point of the hull transverse section, located below *z_VD*, where *z_VD* *= V_D* *+ N*:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image385.png)
    • at bottom:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image386.png)
    • at deck:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image387.png)
  - **2.1.3** Normal stresses in flooded conditions of BC-A or BC-B ships
    This requirement applies to BC-A or BC-B ships, in addition to [2.1.2].
    The normal stresses, in the flooded conditions specified in Ch 4, Sec 3, are to be obtained at any point, in $\mathrm{N}/mm ^{2}$, from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image388.png)
- **2.2** Shear stresses
  - **2.2.1** General
    The shear stresses induced by vertical shear forces *Q_SW* and *Q_WV* in intact condition and, for BC-A and BC-B ships by vertical shear forces *Q_SW*_,*_F* and *Q_WV*_,*_F* in flooded condition are normally to be obtained through direct analyses.
    When they are combined, vertical shear forces *Q_SW* and *Q_WV* in intact condition are to be taken with the same sign. The same is to be applied also for combination of vertical shear forces *Q_SW*_,*_F* and *Q_WV*_,*_F* in flooded condition.
    The shear force correction $\Delta Q _{C}$ is to be taken into account, in accordance with [2.2.2]. The shear force correction need not to be considered at the fore end of foremost hold and aft end of aftermost hold.
    As an alternative to this procedure, the shear stresses induced by the vertical shear forces *Q_SW* and *Q_WV* in intact condition and, for BC-A and BC-B ships by the vertical shear forces *Q_SW*_,*_F* and *Q_WV*_,*_F* in flooded condition may be obtained through the simplified procedure in [2.2.2] and [2.2.3] respectively.
  - **2.2.2** Simplified calculation of shear stresses induced by vertical shear forces
    The shear stresses induced by the vertical shear forces in the calculation point are obtained, in $\mathrm{N}/mm ^{2}$, from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image389.png)
    where:
    *t* : Minimum net thickness, in mm, of side and inner side plating, as applicable according to Table 1
    $\delta$ : Shear distribution coefficient defined in Table 1
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image390.png)
    $\Delta Q _{C}$ : Shear force correction (see Fig 2) at the section considered. The shear force correction is to be considered independently forward and aft of the transverse bulkhead for the hold considered. The shear force correction takes into account, when applicable, the portion of loads transmitted by the double bottom girders to the transverse bulkheads:
    • for ships with any non-homogeneous loading conditions, such as alternate hold loading conditions and heavy ballast conditions carrying ballast in hold(s):
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image391.png) for each non-homogenous loading condition
    • for other ships and homogenous loading conditions:
    $\Delta Q _{C}$ = 0
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image392.png), to be taken not greater than 3.7
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image393.png)
    $\ell _{0}$, $b _{0}$ : Length and breadth, respectively, in m, of the flat portion of the double bottom in way of the hold considered; $b _{0}$ is to be measured on the hull transverse section at the middle of the hold
    $\ell _{H}$ : Length, in m, of the hold considered, measured between the middle of the transverse corrugated bulkheads depth
    *B_H* : Ship’s breadth, in m, measured at the level of inner bottom on the hull transverse section at the middle of the hold considered
    *M* : Mass, in t, in the considered section.
    • Adjacent cargo hold is loaded in a non homogenous loading condition for the condition under consideration
    *M* is to include the total mass in the hold and the mass of water ballast in double bottom tank, bounded by side girders in way of hopper tank plating or longitudinal bulkhead.
    • Other cases
    *M* is the total mass in the hold.
    *T_LC,mh* : Draught, in m, measured vertically on the hull transverse section at the middle of the hold considered, from the moulded baseline to the waterline in the loading condition considered.
    ![Fig 1: Shear force correction #eqnID-852](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image394.png)
    Fig 1: Shear force correction #eqnID-852

    | Ship typology | Location | $t$, in mm | $\delta$ |
    | --- | --- | --- | --- |
    | Single side skin construction | Sides | $t _{S}$ | 0,5 |
    | Double side skin construction | Sides | $t _{S}$ | 0.5(1-$\phi$) |
    | Double side skin construction | Inner sides | $t _{IS}$ | 0.5$\phi$ |
    | where:<br>$t _{S}$ , $t _{IS}$ : Minimum net thicknesses, in mm, of side and inner side, respectively<br>$t _{SM}$ , $t _{ISM}$ : Mean net thicknesses, in mm, over all the strakes of side and inner side, respectively. They are calculated as $\Sigma ( \ell _{i} t _{i} )$/$\Sigma \ell _{i}$, where $\ell _{i}$ and $t _{i}$ are the length, in m, and the net thickness, in mm, of the i^th strake of side and inner side.<br>$\phi$ : Coefficient taken equal to: $\phi = 0.275+0.25 \frac{t _{ISM}}{t _{SM}}$ |   |   |   |
  - **2.2.3** Shear stresses in flooded conditions of BC-A or BC-B ships
    This requirement applies to BC-A or BC-B ships, in addition to [2.2.1] and [2.2.2].
    The shear stresses, in the flooded conditions specified in Ch 4, Sec 3, are to be obtained at the calculation point, in $\mathrm{N}/mm ^{2}$, from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image395.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image396.png)
    $\Delta Q _{C}$ : Shear force correction, to be calculated according to [2.2.2], where the mass of the ingressed water is to be added to *M*, and where the draught $T _{LC,mh}$ is to be measured up to the equilibrium waterline.
    $t$ : Net thickness, in mm, of the side plating.

#### 3. Checking criteria

- **3.1** Normal stresses
  - **3.1.1** It is to be checked that the normal stresses s_1 calculated according to [2.1.2] and, when applicable, [2.1.3] are in compliance with the following formula:
    $\sigma _{1} \leq \sigma _{1, ALL}$
    where:
    $\sigma _{1, ALL}$ : Allowable normal stress, in $\mathrm{N}/mm ^{2}$, obtained from the following formulae:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image397.png)
- **3.2** Shear stresses
  - **3.2.1** It is to be checked that the shear stresses t_1 calculated according to [2.2.1] or [2.2.2] and, when applicable, [2.2.3] are in compliance with the following formula:
    $\tau _{1} \leq \tau _{1,ALL}$
    where:
    $\tau _{1,ALL}$ : Allowable shear stress, in $\mathrm{N}/mm ^{2}$:
    $\tau _{1,ALL}$ = 120/*k*

#### 4. Section modulus and moment of inertia

- **4.1** General
  - **4.1.1** The requirements in [4.2] to [4.5] provide the minimum hull net girder section modulus, complying with the checking criteria indicated in [3], and the midship net section moment of inertia required to ensure sufficient hull girder rigidity.
  - **4.1.2** The *k* material factors are to be defined with respect to the materials used for the bottom and deck members contributing to the longitudinal strength according to [1]. When material factors for higher strength steels are used, the requirements in [4.5] apply.
- **4.2** Section modulus within 0.4 *L* amidships
  - **4.2.1** The net section moduli *Z_AB* and *Z_AD* at the midship section are to be not less than the value obtained, in $\mathrm{m} ^{3}$, from the following formula:
    • ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image398.png)
  - **4.2.2** In addition, the net section moduli *Z_AB* and *Z_AD* within 0.4 *L* amidships are to be not less than the value obtained, in $\mathrm{m} ^{3}$, from the following formula:
    • ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image399.png)
    • in addition, for BC-A and BC-B ships:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image400.png)
  - **4.2.3** Where the total breadth $\Sigma b _{S}$ of small openings, as defined in [1.2.8], is deducted from the sectional areas included in the hull girder transverse sections, the values *Z_R,MIN* and *Z_R* defined in [4.2.1] or [4.2.2] may be reduced by 3 %.
  - **4.2.4** Scantlings of members contributing to the longitudinal strength (see [1]), based on the section modulus requirement in [4.2.1], are to be maintained within 0.4 *L* amidships.
- **4.3** Section modulus outside 0.4 *L* amidships
  - **4.3.1** The net section moduli *Z_AB* and *Z_AD* outside 0.4 *L* amidships are to be not less than the value obtained, in $\mathrm{m} ^{3}$, from the following formula:
    • ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image401.png)
    • in addition, for BC-A and BC-B ships:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image402.png)
  - **4.3.2** Scantlings of members contributing to the hull girder longitudinal strength (see [1]) may be gradually reduced, outside 0.4 *L* amidships, to the minimum required for local strength purposes at fore and aft parts, as specified in Ch 9, Sec 1 or Ch 9, Sec 2, respectively.
- **4.4** Midship section moment of inertia
  - **4.4.1** The net midship section moment of inertia about its horizontal neutral axis is to be not less than the value obtained, in $\mathrm{m} ^{4}$, from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image403.png)
    where *Z’_R,MIN* is the required net midship section modulus *Z_R,MIN*, in $\mathrm{m} ^{3}$, calculated as specified in [4.2.1] but assuming *k* = 1.
- **4.5** Extent of higher strength steel
  - **4.5.1** When a material factor for higher strength steel is used in calculating the required section modulus at bottom or deck according to [4.2] or [4.3], the relevant higher strength steel is to be adopted for all members contributing to the longitudinal strength (see [1]), at least up to a vertical distance, in m, obtained from the following formulae:
    • above the baseline (for section modulus at bottom):
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image404.png)
    • below a horizontal line located at a distance *V_D* (see [1.4.2]) above the neutral axis of the hull transverse section (for section modulus a tdeck):
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image405.png)
    where:
    $\sigma _{1B}$, $\sigma _{1D}$ : Normal stresses, in $\mathrm{N}/mm ^{2}$, at bottom and deck, respectively, calculated according to [2.1]
    *z_D* : Z co-ordinate, in m, of the strength deck defined in [1.3], with respect to the reference co-ordinate system defined in Ch 1, Sec 4, [4]
  - **4.5.2** The higher strength steel is to extend in length at least throughout 0.4 *L* amidships where it is required for strength purposes according to the provision of the present Rules.

#### 5. Permissible still water bending moment and shear force

- **5.1** Permissible still water bending moment and shear force in intact condition
  - **5.1.1** Permissible still water bending moment
    The permissible still water bending moment at any hull transverse section in intact condition, in hogging or sagging conditions, is the value *M_SW* considered in the hull girder section modulus calculation according to [4.2] and [4.3].
    In the case of structural discontinuities in the hull transverse sections, the distribution of permissible still water bending moments is considered on a case by case basis.
  - **5.1.2** Permissible still water shear force - Direct calculation
    Where the shear stresses are obtained through calculation analyses according to [2.2.1], the permissible positive or negative still water shear force in intact condition at any hull transverse section is obtained, in kN, from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image406.png)
    where:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image407.png)
    *Q_T* : Shear force, in kN, which produces a shear stress $\tau$ = 120/*k* $\mathrm{N}/mm ^{2}$ in the most stressed point of the hull net transverse section, taking into account the shear force correction $\Delta Q _{C}$ in accordance with [2.2.2].
    A lower value of the permissible still water shear force may be considered, if requested by the Shipbuilder.
  - **5.1.3** Permissible still water shear force - Simplified calculation
    Where the shear stresses are obtained through the simplified procedure in [2.2.2], the permissible positive or negative still water shear force in intact condition at any hull transverse section is obtained, in kN, from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image408.png)
    where:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image409.png)
    $\delta$ : Shear distribution coefficient defined in Table 1
    *t* : Minimum net thickness, in mm, of side and inner side plating, as applicable according to Table 1
    $\Delta Q _{C}$ : Shear force corrections defined in [2.2.2], to be considered independently forward and aft of the transverse bulkhead.
    A lower value of the permissible still water shear force may be considered, if requested by the Shipbuilder.
- **5.2** Permissible still water bending moment and shear force in harbour conditions
  - **5.2.1** Permissible still water bending moment
    The permissible still water bending moment at any hull transverse section in harbour conditions, in hogging or sagging conditions, is obtained, in kN.m, from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image410.png)
    A lower value of the permissible still water bending moment in harbour conditions may be considered, if requested by the Shipbuilder.
  - **5.2.2** Permissible still water shear force
    The permissible positive or negative still water shear force at any hull transverse section, in harbour conditions, is obtained, in kN, from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image411.png)
    where:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image412.png)
    *Q_P* : Permissible still water shear force during navigation, in kN, to be calculated according to [5.1.3].
    A lower value of the permissible still water shear force in harbour conditions may be considered, if requested by the Shipbuilder.
- **5.3** Permissible still water bending moment and shear force in flooded condition
  - **5.3.1** Permissible still water bending moment
    The permissible still water bending moment at any hull transverse section in flooded condition, in hogging or sagging conditions, is the value *M_SW*_,*_F* considered in the hull girder section modulus calculation according to [4.2] and [4.3].
    In the case of structural discontinuities in the hull transverse sections, the distribution of permissible still water bending moments is considered on a case by case basis.
  - **5.3.2** Permissible still water shear force - Direct calculation
    Where the shear stresses are obtained through calculation analyses according to [2.2.1], the permissible positive or negative still water shear force in flooded condition at any hull transverse section is obtained, in kN, from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image413.png)
    where:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image414.png)
    *Q_T* : Shear force, in kN, which produces a shear stress $\tau$ = 120/*k* $\mathrm{N}/mm ^{2}$ in the most stressed point of the hull net transverse section, taking into account the shear force correction $\Delta Q _{C}$ in accordance with [2.2.2].
  - **5.3.3** Permissible still water shear force - Simplified calculation
    Where the shear stresses are obtained through the simplified procedure in [2.2.2], the permissible positive or negative still water shear force in flooded condition at any hull transverse section is obtained, in kN, from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image415.png)
    where:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image416.png)
    $\delta$ : Shear distribution coefficient defined in Table 1
    *t* : Minimum net thickness, in mm, of side and inner side plating, as applicable according to Table 1
    $\Delta Q _{C}$ : Shear force correction, to be calculated according to [2.2.2], where the mass *M* is to include the mass of the ingressed water in the hold considered and the draught *T_LC* is to be measured up to the equilibrium waterline.


### Section 2 - ULTIMATE STRENGTH CHECK

#### 1. Application

- **1.1** General
  - **1.1.1** The requirements of this Section apply to ships equal to or greater than 150 m in length *L*.

#### 2. Hull girder ultimate strength check

- **2.1** Hull girder loads
  - **2.1.1** Bending moment
    The bending moment *M* in sagging and hogging conditions, to be considered in the ultimate strength check of the hull girder, is to be obtained, in kN.m, in intact, flooded and harbour conditions, from the following formula:
    *M = M_SW+g_W* *M_WV*
    where:
    *M_SW,M_SW*_,*_F,M_SW*_,*_P* : Design still water bending moment, in kN.m, in sagging and hogging conditions at the hull transverse section considered, to be calculated respectively in intact (*M_SW*), flooded (*M_SW*_,*_F*) and harbour (*M_SW*_,*_P*) conditions
    *M_WV,M_WV*_,*_F,M_WV*_,*_P* : Vertical wave bending moment, in kN.m, in sagging and hogging conditions at the hull transverse section considered, defined in Ch 4, Sec 3, respectively in intact (*M_WV*), flooded (*M_WV*_,*_F*) and harbour (*M_WV*_,*_P*) conditions
    g*_W* : Safety factor on wave hull girder bending moments, taken equal to:
    g*_W* = 1.20
- **2.2** Hull girder bending moment
  - **2.2.1** Curve $M - \chi$
    The ultimate bending moment capacities of a hull girder transverse section, in hogging and sagging conditions, are defined as the maximum values of the curve of bending moment capacity *M* versus the curvature $\chi$ of the transverse section considered (see Fig 1).
    The curvature $\chi$ is positive for hogging condition and negative for sagging condition.
    The curve $M - \chi$ is to be obtained through an incremental-iterative procedure, according to the criteria specified in App 1.
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image417.png)
    Fig 1: Curve bending moment capacity *M* versus curvature $\chi$
  - **2.2.2** Hull girder transverse sections
    The hull girder transverse sections are constituted by the elements contributing to the hull girder longitudinal strength, considered with their net offered scantlings according to Ch 3, Sec 2, [3.2.4].
- **2.3** Checking criteria
  - **2.3.1** It is to be checked that the hull girder ultimate bending capacity at any hull transverse section is in compliance with the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image418.png)
    where:
    *M_U* : Ultimate bending moment capacity of the hull transverse section considered, calculated with net offered scantlings based on gross offered thickness reduced by 0.5 *t_C*, in kN.m:
    *M_U* *= M_UH* in hogging conditions
    *M_U* *= M_US* in sagging conditions
    *M_UH* : Ultimate bending moment capacity in hogging conditions, in kN.m, defined in [2.2.1]
    *M_US* : Ultimate bending moment capacity in sagging conditions, in kN.m, defined in [2.2.1]
    *M* : Bending moment, in kN.m, defined in [2.1.1] for the ship in intact, flooded and harbour conditions
    *g_R* : Safety factor taken equal to 1.10


### Appendix 1 - HULL GIRDER ULTIMATE STRENGTH

Symbols
For symbols not defined in this Appendix, refer to Ch 1, Sec 4.
*I_Y* : Moment of inertia, in $\mathrm{m} ^{4}$, of the hull transverse section around its horizontal neutral axis, to be calculated according to Ch 5, Sec 1, [1.5.1]
*Z_AB* *,Z_AD* : Section moduli, in $\mathrm{m} ^{3}$, at bottom and deck, respectively, defined in Ch 5, Sec 1, [1.4.2].
*R_eHs* : Minimum yield stress, in $\mathrm{N}/mm ^{2}$, of the material of the considered stiffener.
*R_eHp* : Minimum yield stress, in $\mathrm{N}/mm ^{2}$, of the material of the considered plate.
*A_s* : Net sectional area, in $\mathrm{cm} ^{2}$, of stiffener, without attached plating
*A_p* : Net sectional area, in $\mathrm{cm} ^{2}$, of attached plating

#### 1. Hull girder ultimate strength check

- **1.1** Introduction
  - **1.1.1** This Appendix provides the criteria for obtaining the curve $M - \chi$ and the ultimate longitudinal bending moment capacity *M_U* that are to be calculated according to the simplified incremental-iterative approach, as specified in [2.1].

#### 2. Criteria for the calculation of the curve

- **2.1** Simplified method based on a incremental-iterative approach
  - **2.1.1** Procedure
    The curve $M - \chi$ is to be obtained by means of an incremental-iterative approach, summarised in the flow chart in Fig 1.
    In this approach, the ultimate hull girder bending moment capacity *M_U* is defined as the peak value of the curve with vertical bending moment *M* versus the curvature $\chi$ of the ship cross section as shown in Fig 1. The curve is to be obtained through an incremental-iterative approach.
    Each step of the incremental procedure is represented by the calculation of the bending moment *M_i* which acts on the hull transverse section as the effect of an imposed curvature $\chi _{i}$.
    For each step, the value $\chi _{i}$ is to be obtained by summing an increment of curvature $\Delta \chi$ to the value relevant to the previous step $\chi _{i-1}$. This increment of curvature corresponds to an increment of the rotation angle of the hull girder transverse section around its horizontal neutral axis.
    This rotation increment induces axial strains $\varepsilon$ in each hull structural element, whose value depends on the position of the element. In hogging condition, the structural elements above the neutral axis are lengthened, while the elements below the neutral axis are shortened. Vice-versa in sagging condition.
    The stress $\sigma$ induced in each structural element by the strain $\varepsilon$ is to be obtained from the load-end shortening curve $\sigma - \varepsilon$ of the element, which takes into account the behaviour of the element in the non-linear elasto-plastic domain.
    The distribution of the stresses induced in all the elements composing the hull transverse section determines, for each step, a variation of the neutral axis position, since the relationship $\sigma - \varepsilon$ is non-linear. The new position of the neutral axis relevant to the step considered is to be obtained by means of an iterative process, imposing the equilibrium among the stresses acting in all the hull elements.
    Once the position of the neutral axis is known and the relevant stress distribution in the section structural elements is obtained, the bending moment of the section *M_i* around the new position of the neutral axis, which corresponds to the curvature $\chi _{i}$ imposed in the step considered, is to be obtained by summing the contribution given by each element stress.
    The main steps of the incremental-iterative approach described above are summarised as follows (see also Fig 1):
    Step 1 Divide the transverse section of hull into stiffened plate elements.
    Step 2 Define stress-strain relationships for all elements as shown in Table 1
    Step 3 Initialize curvature $\chi _{1}$ and neutral axis for the first incremental step with the value of incremental curvature (curvature that induces a stress equal to 1 % of yield strength in strength deck) as:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image419.png)
    where:
    *z_D* : Z co-ordinate, in m, of strength deck at side, with respect to reference co-ordinate defined in Ch 1, Sec 4, [4]
    Step 4 Calculate for each element the corresponding strain $\varepsilon _{i} = \chi (z _{i} -z _{NA} )$ and the corresponding stress $\sigma _{i}$
    Step 5 Determine the neutral axis *z_NA_cur* at each incremental step by establishing force equilibrium over the whole transverse section as:
    $\Sigma A _{i} \sigma _{i} = \Sigma A _{j} \sigma _{j}$ (i-th element is under compression, j-th element under tension)
    Step 6 Calculate the corresponding moment by summing the contributions of all elements as:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image420.png)
    Step 7 Compare the moment in the current incremental step with the moment in the previous incremental step. If the slope in $M - \chi$ relationship is less than a negative fixed value, terminate the process and define the peak value of *M_U*. Otherwise, increase the curvature by the amount of $\Delta \chi$ and go to Step 4.
    ![Fig 1: Flow chart of the procedure for the evaluation of the curve #eqnID-931](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image421.png)
    Fig 1: Flow chart of the procedure for the evaluation of the curve #eqnID-931
  - **2.1.2** Assumption
    In applying the procedure described in [2.1.1], the following assumptions are generally to be made:
    • the ultimate strength is calculated at hull transverse sections between two adjacent transverse webs.
    • the hull girder transverse section remains plane during each curvature increment.
    • the hull material has an elasto-plastic behaviour.
    • the hull girder transverse section is divided into a set of elements, which are considered to act independently.
    These elements are:
    - transversely framed plating panels and/or ordinary stiffeners with attached plating, whose structural behaviour is described in [2.2.1]
    - hard corners, constituted by plating crossing, whose structural behaviour is described in [2.2.2].
    • according to the iterative procedure, the bending moment *M_i* acting on the transverse section at each curvature value $\chi _{i}$ is obtained by summing the contribution given by the stress $\sigma$ acting on each element. The stress $\sigma$, corresponding to the element strain $\varepsilon$, is to be obtained for each curvature increment from the non-linear load-end shortening curves $\sigma - \varepsilon$ of the element.
    These curves are to be calculated, for the failure mechanisms of the element, from the formulae specified in [2.2]. The stress $\sigma$ is selected as the lowest among the values obtained from each of the considered load-end shortening curves $\sigma - \varepsilon$.
    • The procedure is to be repeated until the value of the imposed curvature reaches the value $\chi _{F}$, in $\mathrm{m} ^{-1}$, in hogging and sagging condition, obtained from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image422.png)
    where:
    *M_Y* : the lesser of the values *M_Y*_1 and *M_Y*_2, in kN.m:
    *M_Y*_1 *=* 10^3*R_eHZ_AB*
    *M_Y*_2 *=* 10^3*R_eHZ_AD*
    If the value $\chi _{F}$ is not sufficient to evaluate the peaks of the curve $M - \chi$, the procedure is to be repeated until the value of the imposed curvature permits the calculation of the maximum bending moments of the curve.
  - **2.1.3** Modeling of the hull girder cross section
    Hull girder transverse sections are to be considered as being constituted by the members contributing to the hull girder ultimate strength.
    Sniped stiffeners are also to be modeled imaginarily, taking account that they doesn’t contribute to the hull girder strength.
    The structural members are categorized into an ordinary stiffener element, a stiffened plate element or a hard corner element.
    The plate panel including web plate of girder or side stringer is idealized into either a stiffened plate element, an attached plate of an ordinary stiffener element or a hard corner element.
    The plate panel is categorized into the following two kinds:
    - longitudinally stiffened panel of which the longer side is in the longitudinal direction, and
    - transversely stiffened panel of which the longer side is in the perpendicular direction to the longitudinal direction.
    • Hard corner element
    Hard corner elements are sturdier elements composing the hull girder transverse section, which collapse mainly according to an elasto-plastic mode of failure (material yielding); they are generally constituted by two plates not lying in the same plane.
    The extent of a hard corner element from the point of intersection of the plates is taken equal to 20 *t_p* on transversely stiffened panel and to 0.5 *s* on a longitudinally stiffened panel. (see Fig 6)
    where:
    *t_p* : Gross offered thickness of the plate, in mm
    *s* : Spacing of the adjacent longitudinal stiffener, in m
    Bilge, sheer strake-deck stringer elements, girder-deck connections and face plate-web connections on large girders are typical hard corners.
    • Ordinary stiffener element
    The ordinary stiffener constitutes an ordinary stiffener element together with the attached plate.
    The attached plate width is in principle:
    - equal to the mean spacing of the ordinary stiffener when the panels on both sides of the stiffener are longitudinally stiffened, or
    - equal to the width of the longitudinally stiffened panel when the panel on one side of the stiffener is longitudinally stiffened and the other panel is of the transversely stiffened. (See Fig 6)
    • Stiffened plate element
    The plate between ordinary stiffener elements, between an ordinary stiffener element and a hard corner element or between hard corner elements is to be treated as a stiffened plate element. (See Fig 6)
    ![Fig 6: Extension of the breadth of the attached plating and hard corner element](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image423.png)
    Fig 6: Extension of the breadth of the attached plating and hard corner element
    The typical examples of modeling of hull girder section are illustrated in Figs 7 and 8.
    Notwithstanding the foregoing principle these figures are to be applied to the modeling in the vicinity of upper deck, sheer strake and hatch side girder.
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image424.png)
    Fig 7: Extension of the breadth of the attached plating and hard corner element
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image425.png)
    Fig 8: Examples of the configuration of stiffened plate elements, ordinary stiffener elements and hard corner elements on a hull section
    (Note)
    (1) In case of the knuckle point as shown in Fig 9, the plating area adjacent to knuckles in the plating with an angle greater than 30 degrees is defined as a hard corner. The extent of one side of the corner is taken equal to 20 *t_p* on transversely framed panels and to 0.5 *s* on longitudinally framed panels from the knuckle point.
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image426.png)
    Fig 9: The case of plating with knuckle point
    (2) Where the plate members are stiffened by non-continuous longitudinal stiffeners, the non-continuous stiffeners are considered only as dividing a plate into various elementary plate panels.
    (3) Where the opening is provided in the stiffened plate element, the openings are to be considered in accordance with Ch 5, Sec 1, [1.2.7], [1.2.8] and [1.2.9].
    (4) Where attached plating is made of steels having different thicknesses and/or yield stresses, an average thickness and/or average yield stress obtained from the following formula are to be used for the calculation.
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image427.png)’ ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image428.png)
    Where,
    $R _{eHp1}$, $R _{eHp2}$, $t _{1}$, $t _{2}$, $s _{1}$, $s _{2}$ and $s$ are shown in Fig 10.
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image429.png)
    Fig 10: Element with different thickness and yield strength
- **2.2** Load-end shortening curves $\sigma - \varepsilon$
  - **2.2.1** Stiffened plate element and ordinary stiffener element
    Stiffened plate element and ordinary stiffener element composing the hull girder transverse sections may collapse following one of the modes of failure specified in Table 1.
    • Where the plate members are stiffened by non-continuous longitudinal stiffeners, the stress of the element is to be obtained in accordance with [2.2.3] to [2.2.7], taking into account the non-continuous longitudinal stiffener.
    In calculating the total forces for checking the hull girder ultimate strength, the area of non-continuous longitudinal stiffener is to be assumed as zero.
    • Where the opening is provided in the stiffened plate element, the considered area of the stiffened plate element is to be obtained by deducting the opening area from the plating in calculating the total forces for checking the hull girder ultimate strength. The consideration of the opening is in accordance with the requirement in Ch 5, Sec 1, [1.2.7] to [1.2.9].
    • For stiffened plate element, the effective breadth of plate for the load shortening portion of the stress-strain curve is to be taken as full plate breadth, i.e. to the intersection of other plate or longitudinal stiffener - not from the end of the hard corner element nor from the attached plating of ordinary stiffener element, if any. In calculating the total forces for checking the hull girder ultimate strength, the area of the stiffened plate element is to be taken between the hard corner element and the ordinary stiffener element or between the hard corner elements, as applicable.

    | Element | Mode of failure | Curve $\sigma - \varepsilon$ defined in |
    | --- | --- | --- |
    | Lengthened stiffened plate element or ordinary stiffener element | Elasto-plastic collapse | [2.2.3] |
    | Shortened ordinary stiffener element | Beam column buckling<br>Torsional buckling<br>Web local buckling of flanged profiles<br>Web local buckling of flat bars | [2.2.4]<br>[2.2.5]<br>[2.2.6]<br>[2.2.7] |
    | Shortened stiffened plate element | Plate buckling | [2.2.8] |
  - **2.2.2** Hard corner element
    The relevant load-end shortening curve $\sigma - \varepsilon$ is to be obtained for lengthened and shortened hard corners according to [2.2.3].
  - **2.2.3** Elasto-plastic collapse of structural elements
    The equation describing the load-end shortening curve $\sigma - \varepsilon$ for the elasto-plastic collapse of structural elements composing the hull girder transverse section is to be obtained from the following formula, valid for both positive (shortening) and negative (lengthening) strains (see Fig 2):
    $\sigma = \Phi R _{eHA}$
    where:
    $R _{eHA}$ : Equivalent minimum yield stress, in $\mathrm{N}/mm ^{2}$, of the considered element, obtained by the following formula
    $R _{eHA} = \frac{R _{eHp} A _{p} +R _{eHs} A _{s}}{A _{p} +A _{s}}$
    $\Phi$ : Edge function, equal to:
    $\Phi$ = -1 for $\varepsilon$ < -1
    $\Phi$ = $\varepsilon$ for -1 ≤ $\varepsilon$ ≤1
    $\Phi$ = 1 for $\varepsilon$ > 1
    $\varepsilon$ : Relative strain, equal to:
    $\varepsilon = \frac{\varepsilon _{E}}{\varepsilon _{Y}}$
    $\varepsilon _{E}$ : Element strain
    $\varepsilon _{Y}$ : Strain at yield stress in the element, equal to:
    $\varepsilon _{Y} = \frac{R _{eHA}}{E}$
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image430.png)
    Fig 2: Load-end curve $\sigma - \varepsilon$ for elasto plastic collapse
  - **2.2.4** Beam column buckling
    The equation describing the load-end shortening curve $\sigma _{CR1} - \varepsilon$ for the beam column buckling of ordinary stiffeners composing the hull girder transverse section is to be obtained from the following formula (see Fig 3):
    $\sigma _{CR1} = \Phi \sigma _{C1} \frac{A _{s} +A _{pE}}{A _{s} +A _{p}}$
    where:
    $\Phi$ : Edge function defined in [2.2.3]
    $\sigma _{C1}$ : Critical stress, in $\mathrm{N}/mm ^{2}$, equal to:
    $\sigma _{C1} = \frac{\sigma _{E1}}{\varepsilon}$ for $\sigma _{E1} \leq \frac{R _{eHB}}{2} \varepsilon$
    $\sigma _{C1} = R _{eHB} \left( 1- \frac{R _{eHB} \varepsilon}{4 \sigma _{E1}} \right)$ for $\sigma _{E1} > \frac{R _{eHB}}{2} \varepsilon$
    $R _{eHB}$ : Equivalent minimum yield stress, in $\mathrm{N}/mm ^{2}$, of the considered element, obtained by the following formula
    $R _{eHB} = \frac{R _{eHB} A _{pE1} l _{pE} +R _{eHs} A _{s} l _{sE}}{A _{pE1} l _{pE} +A _{s} l _{sE}}$
    $A _{pE1}$ : Effective area, in $\mathrm{cm} ^{2}$, equal to
    $A _{pE1} = 10 b _{E1} t _{p}$
    $l _{pE}$ : Distance, in mm, measured from the neutral axis of the stiffener with attached plate of width $b _{E1}$ to the bottom of the attached plate
    $l _{sE}$ : Distance, in mm, measured from the neutral axis of the stiffener with attached plating of width $b _{E1}$ to the top of the stiffener
    $\varepsilon$ : Relative strain defined in [2.2.3]
    $\sigma _{E1}$ : Euler column buckling stress, in $\mathrm{N}/mm ^{2}$, equal to:
    $\sigma _{E1} = \pi ^{2} E \frac{I _{E}}{A _{E} l ^{2}} 10 ^{-4}$
    $I _{E}$ : Net moment of inertia of ordinary stiffeners, in $\mathrm{cm} ^{4}$, with attached shell plating of width $b _{E1}$
    $b _{E1}$ : Effective width, in m, of the attached shell plating, equal to:
    $b _{E1} = \frac{s}{\beta _{E}}$ for $\beta _{E} > 1.0$
    $b _{E1} = s$ for $\beta _{E} \leq 1.0$
    $\beta _{E} = 10 ^{3} \frac{s}{t _{p}} \sqrt {\frac{\varepsilon R _{eHP}}{E}}$
    $A _{pE}$ : Net sectional area, in $\mathrm{cm} ^{2}$, of attached shell plating of width $b _{E}$, equal to:
    $A _{pE} = 10 b _{E} t _{p}$
    $b _{E}$ : Effective width, in m, of the attached shell plating, equal to:
    $b _{E} = \left( \frac{2.25}{\beta _{E}} - \frac{1.25}{\beta _{E} ^{2}} \right) s$ for $\beta _{E} > 1.25$
    $b _{E} = s$ for $\beta _{E} \leq 1.25$
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image431.png)
    Fig 3: Load-end shortening curve $\sigma _{CR1} - \varepsilon$ for beam column buckling
  - **2.2.5** Torsional buckling
    The equation describing the load-end shortening curve $\sigma _{CR2} - \varepsilon$ for the flexural-torsional buckling of ordinary stiffeners composing the hull girder transverse section is to be obtained according to the following formula (see Fig 4).
    $\sigma _{CR2} = \Phi \frac{A _{s} \sigma _{C2} +A _{p} \sigma _{CP}}{A _{s} +A _{p}}$
    where:
    $\Phi$ : Edge function defined in [2.2.3]
    $\sigma _{C2}$ : Critical stress, in $\mathrm{N}/mm ^{2}$, equal to:
    $\sigma _{C2} = \frac{\sigma _{E2}}{\varepsilon}$ for $\sigma _{E 2} \leq \frac{R _{eHs}}{2} \varepsilon$
    $\sigma _{C2} = R _{eHs} \left( 1- \frac{R _{eHs} \varepsilon}{4 \sigma _{E2}} \right)$ for $\sigma _{E 2} > \frac{R _{eHs}}{2} \varepsilon$
    $\sigma _{E2}$ : Euler torsional buckling stress, in $\mathrm{N}/mm ^{2}$, defined in Ch 6, Sec 3, [4.3]
    $\varepsilon$ : Relative strain defined in [2.2.3]
    $\sigma _{CP}$ : Buckling stress of the attached plating, in $\mathrm{N}/mm ^{2}$, equal to:
    $\sigma _{CP} = \left( \frac{2.25}{\beta _{E}} - \frac{1.25}{\beta _{E} ^{2}} \right) R _{eHp}$ for $\beta _{E} > 1.25$
    $\sigma _{CP} = R _{eHp}$ for $\beta _{E} \leq 1.25$
    $\beta _{E}$ : Coefficient defined in [2.2.4]
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image432.png)
    Fig 4: Load-end shortening curve $\sigma _{CR2} - \varepsilon$ for flexural-torsional buckling
  - **2.2.6** Web local buckling of ordinary stiffeners made of flanged profiles
    The equation describing the load-end shortening curve $\sigma _{CR3} - \varepsilon$ for the web local buckling of flanged ordinary stiffeners composing the hull girder transverse section is to be obtained from the following formula:
    $\sigma _{CR3} = \Phi \frac{10 ^{3} b _{E} t _{p} R _{eHp} +(h _{we} t _{w} +b _{f} t _{f} )R _{eHs}}{10 ^{3} st _{p} +h _{w} t _{w} +b _{f} t _{f}}$
    where
    $\Phi$ : Edge function defined in [2.2.3]
    $b _{E}$ : Effective width, in m, of the attached shell plating, defined in [2.2.4]
    $h _{we}$ : Effective height, in mm, of the web, equal to:
    $h _{we} = \left( \frac{2.25}{\beta _{w}} - \frac{1.25}{\beta _{w} ^{2}} \right) h _{w}$ for $\beta _{w} > 1.25$
    $h _{we} = h _{w}$ for $\beta _{w} \leq 1.25$
    $\beta _{w} = \frac{h _{w}}{t _{w}} \sqrt {\frac{\varepsilon R _{eHs}}{E}}$
    $\varepsilon$ : Relative strain defined in [2.2.3]
  - **2.2.7** Web local buckling of ordinary stiffeners made of flat bars
    The equation describing the load-end shortening curve $\sigma _{CR4} - \varepsilon$ for the web local buckling of flat bar ordinary stiffeners composing the hull girder transverse section is to be obtained from the following formula (see Fig 5):
    $\sigma _{CR4} = \Phi \frac{A _{P} \sigma _{CP} +A _{s} \sigma _{C 4}}{A _{p} +A _{s}}$
    where:
    $\Phi$ : Edge function defined in [2.2.3]
    $\sigma _{CP}$ : Buckling stress of the attached plating, in $\mathrm{N}/mm ^{2}$, defined in [2.2.5]
    $\sigma _{C4}$ : Critical stress, in $\mathrm{N}/mm ^{2}$, equal to:
    $\sigma _{C 4} = \frac{\sigma _{E 4}}{\varepsilon}$ for $\sigma _{E 4} \leq \frac{R _{eHs}}{2} \varepsilon$
    $\sigma _{C 4} = R _{eHs} \left( 1- \frac{R _{eHs} \varepsilon}{4 \sigma _{E 4}} \right)$ for $\sigma _{E 4} > \frac{R _{eHs}}{2} \varepsilon$
    $\sigma _{E4}$ : Local Euler buckling stress, in $\mathrm{N}/mm ^{2}$, equal to:
    $\sigma _{E 4} = 160,000 \left( \frac{t _{w}}{h _{w}} \right) ^{2}$
    $\varepsilon$ : Relative strain defined in [2.2.3].
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image433.png)
    Fig 5: Load-end shortening curve $\sigma _{CR4} - \varepsilon$ for web local buckling
  - **2.2.8** Plate buckling
    The equation describing the load-end shortening curve $\sigma _{CR5} - \varepsilon$ for the buckling of transversely stiffened panels composing the hull girder transverse section is to be obtained from the following formula:
    $sigma _{CR`5} ``=`min {cases{R _{eHp} ` PHI PHI R _{eHp} LEFT [ {s} over {ELL } LEFT ( {2.25} over {beta _{E}} - {1.25} over {beta _{E} ^{2}} RIGHT ) +0.1 LEFT ( 1- {s} over {ELL } RIGHT ) LEFT ( 1+ {1} over {beta _{E} ^{2}} RIGHT ) ^{2} RIGHT ]&}}$
    where:
    $\Phi$ : Edge function defined in [2.2.3].
    $\beta _{E} = 10 ^{3} \frac{s}{t _{p}} \sqrt {\frac{\varepsilon R _{eHp}}{E}}$
    $s$ : plate breadth, in m, taken as the spacing between the ordinary stiffeners.
    $\ell$ : longer side of the plate, in m. ![](images/image9.png)
