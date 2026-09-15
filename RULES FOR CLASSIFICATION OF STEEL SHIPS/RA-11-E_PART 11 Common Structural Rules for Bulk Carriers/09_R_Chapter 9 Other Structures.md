# PART 11 Common Structural Rules for Bulk Carriers

> RULES FOR CLASSIFICATION OF STEEL SHIPS / RA-11-E / 2025 / EN / Rules

## Chapter 9 Other Structures

### Section 1 - FORE PART

Symbols
For symbols not defined in this Section, refer to Ch 1, Sec 4.
*L*_2 : Rule length *L*, but to be taken not greater than 300 m
*T_B* : Minimum ballast draught, in m, for normal ballast conditions
*k* : Material factor, defined in Ch 3, Sec 1, [2.2]
*m* : Coefficient taken equal to:
m = 10 for vertical stiffeners, vertical primary supporting members
m = 12 for other stiffeners, other primary supporting members
$\tau _{a}$ : Allowable shear stress, in $\mathrm{N}/mm ^{2}$, taken equal to:
![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1256.png)
*s* : Spacing, in m, of ordinary stiffeners or primary supporting members, measured at mid-span along the chord
l : Span, in m, of ordinary stiffeners or primary supporting members, measured along the chord between the supporting members, see Ch 3, Sec 6, [4.2] or [5.3] respectively.
*c_a* : Aspect ratio of the plate panel, equal to:
![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1257.png), to be taken not greater than 1.0
*c_r* : Coefficient of curvature of the panel, equal to:
![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1258.png), to be taken not less than 0.4
*r* : Radius of curvature, in m.

#### 2. Arrangement

- **2.1** Structural arrangement principles
  - **2.1.1** General
    Scantlings of the shell envelope, upper deck and inner bottom, if any, are to be tapered towards the forward end. Special consideration is to be paid to the structural continuity of major longitudinal members in order to avoid abrupt changes in section.
    Structures within the fore peak, such as platforms, decks, horizontal ring frames or side stringers are to be scarphed into the structure aft into the cargo hold.
    Where inner hull structures terminate at the collision bulkhead, the structural continuity is to be ensured forward of the collision bulkhead by adequate structure with tapering brackets.
    Longitudinal stiffeners of deck, bottom and side shell are to be extended as far forward as practicable.
    All shell frames and tank boundary stiffeners are to be continuous, or are to be bracketed tat their ends.
    Where the brackets are provided to ensure the structural continuity from the forward end to 0.15 *L* behind fore perpendicular, flanged brackets have to be used.
  - **2.1.2** Structures in tanks
    Where peaks are used as tanks, stringer plates are to be flanged or face bars are to be fitted at their inner edges. Stringers are to be effectively fitted to the collision bulkhead so that the forces can be properly transmitted.
- **2.2** Tripping brackets
  - **2.2.1** For peaks or other tanks forward of the collision bulkhead transversely framed, tripping brackets vertically spaced not more than 2.6 m are to be fitted, according to Fig 1, between primary supporting members, decks and/or platforms
    The as-built thickness of the tripping brackets is to be not less than the as-built thickness of the side frame webs to which they are connected.
    ![Fig 1: Tripping brackets](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1259.png)
    Fig 1: Tripping brackets
- **2.3** Floors and bottom girders
  - **2.3.1** Where no centreline bulkhead is provided, a centre bottom girder is to be fitted.
    In general, the minimum depth of the floor at the centerline and center girders is to be not less than the required depth of the double bottom of the foremost cargo hold.
  - **2.3.2** Solid floors
    In case of transverse framing, solid floors are to be fitted at every frame.
    In case of the longitudinal framing, the spacing of solid floors is not to be greater than 3.5 m or four transverse frame spaces, whichever is the smaller. Larger spacing of solid floors may be accepted, provided that the structure is verified by means of FEA deemed appropriate by the Society.
  - **2.3.3** Bottom girder
    In case of transverse framing, the spacing of bottom girders is not to exceed 2.5 m
    In case of longitudinal framing, the spacing of bottom girders is not to exceed 3.5 m.
    Larger spacing of bottom girders may be accepted, provided that the structure is verified by means of FEA deemed appropriate by the Society.

#### 3. Load model

- **3.1** Load point
  - **3.1.1** Unless otherwise specified, lateral pressure is to be calculated at load points according to:
    • Ch 6, Sec 1, [1.5], for plating
    • Ch 6, Sec 2, [1.4], for stiffeners.
- **3.2** Pressure in bow area
  - **3.2.1** Lateral pressure in intact conditions
    The pressure in bow area, in $\mathrm{kN}/m ^{ 2}$, is to be taken equal to ($p _{S}$ *+* $p _{W}$).
    where:
    $p _{S}$, $p _{W}$ : Hydrostatic and hydrodynamic pressures according to Ch 4, Sec 5 or internal still water and inertial pressures according to Ch 4, Sec 6, [2] to be considered among load cases H, F, R and P.
  - **3.2.2** Lateral pressure in testing conditions
    The lateral pressure $p _{T}$ in testing conditions is taken equal to:
    • $p _{T}$ = $p _{ST}$ - $p _{S}$ for bottom shell plating and side shell plating
    • $p _{T}$ = $p _{ST}$ otherwise
    where:
    $p _{ST}$ : Testing pressure defined in Ch 4, Sec 6, [4]
    $p _{S}$ : Pressure taken equal to:
    • if the testing is carried out afloat: hydrostatic pressure defined in Ch 4, Sec 5, [1] for the draught $T _{1}$, defined by the Designer, at which the testing is carried out. If $T _{1}$ is not defined, the testing is considered as being not carried out afloat
    • if the testing is not carried out afloat: $p _{S}$ = 0
  - **3.2.3** Elements of the outer shell
    The still water and wave lateral pressures are to be calculated considering separately:
    • the still water and wave external sea pressures
    • the still water and wave internal pressure considering the compartment adjacent to the outer shell as being loaded. If the compartment adjacent to the outer shell is intended to carry liquids, this still water and wave internal pressures are to be reduced from the corresponding still water and wave external sea pressures.
  - **3.2.4** Elements other than those of the outer shell
    The still water and wave lateral pressures to be considered as acting on an element which separates two adjacent compartments are those obtained considering the two compartments individually loaded.
- **3.3** Bow flare area pressure
  - **3.3.1** The bow pressure $p _{FB}$, in $\mathrm{kN}/m ^{ 2}$, is to be obtained according to Ch 4, Sec 5, [4.1].
- **3.4** Bottom slamming pressure
  - **3.4.1** The bottom slamming pressure $p _{SL}$, in $\mathrm{kN}/m ^{ 2}$, in the flat bottom forward is to be obtained according to Ch 4, Sec 5, [4.2].

#### 4. Scantlings

- **4.1** Bow flare reinforcement
  - **4.1.1** The bow flare area to be reinforced is that extending forward of 0.9 *L* from the aft end and above the normal ballast waterline according to the applicable requirements in [4.2] to [4.4].
- **4.2** Plating
  - **4.2.1** The net thickness of plating are to be not less than those obtained from the formulae in Table 1 and Table 2.

    **Minimum net thickness, in mm**

    | Bottom, | 5.5 + 0.03 *L* |
    | --- | --- |
    | Side | 0.85 *L^1/2* |
    | Inner bottom | 5.5 + 0.03 *L* |
    | Strength deck | 4.5 + 0.02 *L* |
    | Transverse and longitudinal<br>watertight bulkheads | 0.6 *L^1/2* |

    **Net thickness, in mm**

    | Intact conditions | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1260.png) |
    | --- | --- |
    | Bow flare area | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1261.png) |
    | Testing conditions | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1262.png) |
- **4.3** Ordinary stiffeners
  - **4.3.1** General
    The requirements of this sub-article apply to ordinary stiffeners considered as clamped at both ends. For other boundary conditions, the yielding check is to be considered on a case by case basis.
  - **4.3.2** The net dimensions of ordinary stiffeners are to comply with the requirements in Ch 6, Sec 2, [2.3]
  - **4.3.3** The net thickness of the web of ordinary stiffeners, in mm, is to be not less than the greater of:
    • *t* = 3.0 + 0.015 *L*_2
    • 40 % of the net required thickness of the attached plating, to be determined according to [4.2] and [5.2].
    The net dimensions of ordinary stiffeners are to comply with the requirement in Ch 6 Sec 2, [2.2.2] and [2.3].
  - **4.3.4** The net scantlings of single-span ordinary stiffeners are to be not less than those obtained from the formulae in Table 3.

    | Stiffener type | Net section modulus $w$, in $\mathrm{cm} ^{3}$ | Net sectional shear area $A _{sh}$, in $\mathrm{cm} ^{2}$ |
    | --- | --- | --- |
    | Single span ordinary stiffeners subjected to lateral pressure | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1263.png) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1264.png) |
    | Single span ordinary stiffeners located in bow flare area | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1265.png) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1266.png) |
    | Single span ordinary stiffeners subjected to testing pressure | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1267.png) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1268.png) |
    | where:<br>$\phi$ : Angle, in deg, between the stiffener web and the shell plate, measured at the middle of the stiffener span; the correction is to be applied when $\phi$ is less than 75. |   |   |
  - **4.3.5** The maximum normal stress $\sigma$ and shear stress $\tau$ in a multi-span ordinary stiffener are to comply with the formulae in Table 4.
    The maximum normal stress $\sigma$ and shear stress $\tau$ in a multi-span ordinary stiffener are to be determined by a direct calculation taking into account:
    • the distribution of still water and wave pressure and forces, if any
    • the number and position of intermediate supports (decks, girders, etc.)
    • the condition of fixity at the ends of the stiffener and at intermediate supports
    • the geometrical characteristics of the stiffener on the intermediate spans.

    | Condition | Intact | Testing |
    | --- | --- | --- |
    | Normal stress | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1269.png) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1270.png) |
    | Shear stress | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1271.png) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1272.png) |
- **4.4** Primary supporting members
  - **4.4.1** Minimum thickness
    The net thickness of the web of primary supporting members, in mm, is to be not less than that obtained from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1273.png)
  - **4.4.2** Side transverses
    The net section modulus $w$, in $\mathrm{cm} ^{3}$, and the net shear sectional area $A _{sh}$, in $\mathrm{cm} ^{2}$, of side transverses are to be not less than the values obtained from the following formulae:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1274.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1275.png)
    In addition, the net section modulus $w$, in $\mathrm{cm} ^{3}$, and the net shear sectional area $A _{sh}$, in $\mathrm{cm} ^{2}$, of side transverses located within the bow flare area are to be not less than the values obtained from the following formulae:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1276.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1277.png)
  - **4.4.3** Side girders
    The net section modulus $w$, in $\mathrm{cm} ^{3}$, and the net shear sectional area $A _{sh}$, in $\mathrm{cm} ^{2}$, of side girders are to be not less than the values obtained from the following formulae:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1278.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1279.png)
    In addition, the net section modulus $w$, in $\mathrm{cm} ^{3}$, and the net shear sectional area $A _{sh}$, in $\mathrm{cm} ^{2}$, of side girders located within the bow flare area are to be not less than the values obtained from the following formulae:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1280.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1281.png)
  - **4.4.4** Deck primary supporting members
    The net scantlings of deck primary supporting members are to be not less than those obtained from the formulae in Table 5. The design pressures in the formulae are taken from intact conditions and testing conditions respectively as stated in [3.2]. For a complex deck structure, a calculation deemed appropriate by the Society may be carried out in lieu of the formulae.

    | Condition | Net section modulus<br>w, in $\mathrm{cm} ^{3}$ | Net sectional shear area<br>$A _{sh}$, in $\mathrm{cm} ^{2}$ |
    | --- | --- | --- |
    | Primary supporting<br>members subjected to lateral pressure in intact conditions | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1282.png) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1283.png) |
    | Primary supporting<br>members subjected to lateral pressure in testing conditions | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1284.png) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1285.png) |
    | Where,<br>$\phi$ : Angle, in deg, between the primary supporting member’s web and the shell plate, measured at the middle of the primary supporting member’s span; the correction is to be applied when $\phi$ is less than 75. |   |   |

#### 5. Strengthening of bottom forward area

- **5.1** Application
  - **5.1.1** The bottom forward area to be reinforced is the part of the ship's bottom extending forward of $0.2V \sqrt {L}$ from the fore perpendicular end, up to a height of 0.05$T _{B}$ or 0.3 m above base line, whichever is the smaller.
- **5.2** Bottom plating
  - **5.2.1** The net thickness, in mm, of the bottom forward area, is not to be less than:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1286.png)
    where:
    $C _{s}$ : Coefficient relating to load patch of impact pressure, taken equal to:
    $C _{s}$ = 1.0 where no intermediate longitudinals is provided between or dinary stiffeners
    $C _{s}$ = 1.3 where intermediate longitudinals are provided between ordinary stiffeners.
  - **5.2.2** For ships with a rise of floor the strengthened plating must at least extend to the bilge curvature.
- **5.3** Ordinary stiffeners
  - **5.3.1** The net section modulus, in $\mathrm{cm} ^{3}$, of transverse or longitudinal ordinary stiffeners of the bottom forward area is not to be less than:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1287.png)
    where:
    $C _{s}$ : Coefficient defined in [5.2.1].
  - **5.3.2** The net shear area, in $\mathrm{cm} ^{2}$, of transverse or longitudinal ordinary stiffeners of the bottom forward area is not to be less than:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1288.png)
    The area of the welded connection has to be at least twice this value.
- **5.4** Primary supporting members
  - **5.4.1** The net thickness of girders in double bottom forward area, in mm, is not to be less than the greatest of either of the value $t _{1}$ to $t _{3}$ specified in the followings according to each location:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1289.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1290.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1291.png)
    where:
    $c _{A}$ : Coefficient taken equal to:
    $c _{A} = 3/A$, with $0.3 \leq c _{A} \leq 1.0$
    $A$ : Loaded area, in $\mathrm{m}^{ 2}$, between the supports of the structure considered, obtained from the following formula:
    $A = S \ell$
    $p _{SL}$ : As defined in [3.4]
    $S$ : Spacing of centre or side girders under consideration, in m
    l : Span of centre or side girders between floors under consideration, in m
    $d _{0}$ : Depth of the centre or side girder under consideration, in m
    $d _{1}$ : Depth of the opening, if any, at the point under consideration, in m
    $H$ : Value obtained from the following formulae:
    $\phi$ : Major diameter of the openings, in m
    $\alpha$ : The greater of $a$ or $S _{1}$, in m.
    $a$ : Depth of girders at the point under consideration, in m, Where, however, if horizontal stiffeners are fitted on the girder, $a$ is the distance from the horizontal stiffener under consideration to the bottom shell plating or inner bottom plating, or the distance between the horizontal stiffeners under consideration.
    $S _{1}$ : Spacing, in m, of vertical ordinary stiffeners or floors
    $C _{1} ^{'}$ : Coefficient obtained from Table 6 depending on $S _{1} / a$. For intermediate values of $S _{1} / a$, $C _{1} ^{'}$ is to be determined by linear interpolation.
    $C _{1} ^{' '}$ : Coefficient obtained from Table 7 depending on $S _{1} / a$. For intermediate values of $S _{1} / a$, $C _{1} ^{' '}$ is to be obtained by linear interpolation.
    Table 6 Coefficient $C _{1} ^{'}$

    | $S _{1} / a$ | 0.3 and<br>under | 0.4 | 0.5 | 0.6 | 0.7 | 0.8 | 0.9 | 1.0 | 1.2 | 1.4 and<br>over |
    | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
    | $C _{1} ^{'}$ | 64 | 38 | 25 | 19 | 15 | 12 | 10 | 9 | 8 | 7 |

    Table 7 Coefficient $C _{1} ^{' '}$

    | $S _{1} / a$ |   | 0.3 and under | 0.4 | 0.5 | 0.6 | 0.7 | 0.8 | 0.9 | 1.0 | 1.2 | 1.4 | 1.6 and over |
    | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
    | $C _{1} ^{' '}$ | Centre girder | 4.4 | 5.4 | 6.3 | 7.1 | 7.7 | 8.2 | 8.6 | 8.9 | 9.3 | 9.6 | 9.7 |
    | $C _{1} ^{' '}$ | Side girder | 3.6 | 4.4 | 5.1 | 5.8 | 6.3 | 6.7 | 7.0 | 7.3 | 7.6 | 7.9 | 8.0 |
    - **(a)** Where the girder is provided with an unreinforced opening :![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1292.png)
    - **(b)** In other cases: ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1293.png)
  - **5.4.2** Floors
    The net thickness of floors in double bottom forward area, in mm, is not to be less than the greatest of either of the value $t _{1}$ to $t _{3}$ specified in the followings according to each location:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1294.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1295.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1296.png)
    where :
    $c _{A}$ : Coefficient taken equal to:
    $c _{A} = 3/A$, with $0.3 \leq c _{A} \leq 1.0$
    $A$ : Loaded area, in $\mathrm{m}^{ 2}$, between the supports of the structure considered, obtained from the following formula:
    $A = S \ell$
    $p _{SL}$ : As defined in [3.4]
    $S$ : Spacing of floors under consideration, in m
    l : Span of floors between centre girder and side girder or side girders under consideration, in m
    $d _{0}$ : Depth of the solid floor at the point under consideration in m
    $d _{1}$ : Depth of the opening, if any, at the point under consideration in m
    $H$ : Value obtained from the following formulae:
    1) Where slots without reinforcement are provided:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1297.png), without being taken less than 1.0
    2) Where slots with reinforcement are provided: ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1298.png)
    1) Where slots without reinforcement are provided:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1299.png), without being taken less than ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1300.png)
    2) Where slots with reinforcement are provided:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1301.png)
    $d _{2}$ : Depth of slots without reinforcement provided at the upper and lower parts of solid floors, in m, whichever is greater
    $S _{1}$ : Spacing, in m, of vertical ordinary stiffeners or girders
    $\phi$ : Major diameter of the openings, in m.
    $a$ : Depth of the solid floor at the point under consideration, in m, Where, however, if horizontal stiffeners are fitted on the floor, $a$ is the distance from the horizontal stiffener under consideration to the bottom shell plating or the inner bottom plating or the distance between the horizontal stiffeners under consideration
    $S _{2}$ : The smaller of $S _{1}$ or $a$, in m
    $C _{2} ^{' }$ : Coefficient given in Table 8 depending on $S _{1} /d _{0}$. For intermediate values of $S _{1} /d _{0}$, $C _{2} ^{' }$ is to be determined by linear interpolation.
    Table 8: Coefficient $C _{2} ^{' }$

    | $S _{1} /d _{0}$ | 0.3 and under | 0.4 | 0.5 | 0.6 | 0.7 | 0.8 | 0.9 | 1.0 | 1.2 | 1.4 and over |
    | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
    | $C _{2} ^{' }$ | 64 | 38 | 25 | 19 | 15 | 12 | 10 | 9 | 8 | 7 |
    - **a)** Where openings with reinforcement or no opening are provided on solid floors:
    - **b)** Where openings without reinforcement are provided on solid floors:

#### 6. Stem

- **6.1** Bar stem
  - **6.1.1** The gross cross sectional area, in $\mathrm{cm} ^{2}$, of a bar stem below the load waterline is not to be less than:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1302.png)
  - **6.1.2** Starting from the load waterline, the cross sectional area of the bar stem may be reduced towards the upper end to 0.75 *A_b*.
- **6.2** Plate stem and bulbous bows
  - **6.2.1** The gross thickness, in mm, is not to be less than the values obtained from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1303.png), without being taken greater than ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1304.png)
    where:
    $s _{B}$ : Spacing, in m, between horizontal stringers (partial or not), breasthooks, or equivalent horizontal stiffening members.
    The gross plate thickness is to be not less than the net thickness, obtained according to [4.2], plus the corrosion addition *t_C* as defined in Ch 3, Sec 3.
    Scantlings of the ordinary stiffeners are to be determined according to [4.3].
  - **6.2.2** Starting from 0.6 m above the load waterline up to *T+C*, the gross thickness may gradually be reduced to 0.8 *t*, where *t* is the gross thickness defined in [6.2.1].
  - **6.2.3** Plate stems and bulbous bows must be stiffened by breasthooks and/or frames.

#### 7. Forecastle

- **7.1** General
  - **7.1.1** An enclosed forecastle is to be fitted on the freeboard deck.
    The aft bulkhead of the enclosed forecastle is to be fitted in way or aft of the forward bulkhead of the foremost hold, as shown in Fig 2.
    However, if this requirement hinders hatch cover operation, the aft bulkhead of forecastle may be fitted forward of the forward bulkhead of the foremost cargo hold provided the forecastle length is not less than 7 % of ship length for freeboard as specified in Ch 1, Sec 4, [3.2] abaft the fore side of stem.
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1305.png)
    Figure 2: Forecastle
  - **7.1.2** The forecastle height *H_F* above the main deck is to be not less than the greater of the following values:
    • the standard height of a superstructure as specified in Ch 1, Sec 4, [3.18]
    • *H_C* *+* 0.5 m, where *H_C* is the height of the forward transverse hatch coaming of the foremost cargo hold, i.e. cargo hold No.1.
  - **7.1.3** All points of the aft edge of the forecastle deck are to be located at a distance less than or equal to l_F:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1306.png)
    from the hatch coaming plate in order to apply the reduced loading to the No.1 forward transverse hatch coaming and No.1 hatch cover in applying Ch 9, Sec 5, [6.2.2] and Ch 9, Sec 5, [7.3.8].
  - **7.1.4** A breakwater is not to be fitted on the forecastle deck with the purpose of protecting the hatch coaming or hatch covers. If fitted for other purposes, it is to be located such that its upper edge at centreline is not less than *H_B* /tan20° forward of the aft edge of the forecastle deck, where *H_B* is the height of the breakwater above the forecastle (see Fig 2).


### Section 2 - AFT PART

Symbols
For symbols not defined in this Section, refer to Ch 1, Sec 4.
*L*_1 : Rule length *L*, but to be taken not greater than 200 m
*L*_2 : Rule length *L*, but to be taken not greater than 300 m
*k* : Material factor, defined in Ch 3, Sec 1, [2.2]
*z_TOP* : *Z* co-ordinate, in m, of the top of the tank
*m* : Coefficient taken equal to:
*m* = 10 for vertical stiffeners, vertical primary supporting members
*m* = 12 for other stiffeners, other primary supporting members
$\tau _{a}$ : Allowable shear stress, in $\mathrm{N}/mm ^{2}$, taken equal to:
![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1307.png)
*s* : Spacing, in m, of ordinary stiffeners or primary supporting members, measured at mid-span along the chord
l : Span, in m, of ordinary stiffeners or primary supporting members, measured along the chord between the supporting members, see Ch 3, Sec 6, [4.2] or [5.3] respectively.
*c_a* : Aspect ratio of the plate panel, equal to:
![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1308.png), to be taken not greater than 1.0
*c_r* : Coefficient of curvature of the panel, equal to:
![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1309.png), to be taken not less than 0.4
*r* : Radius of curvature, in m.

#### 1. General

- **1.1** Introduction
  - **1.1.1** The requirements of this Section apply for the scantlings of structures located aft of the aft peak bulkhead and for the reinforcements of the flat bottom aft area.
  - **1.1.2** Aft peak structures which form the boundary of spaces not intended to carry liquids, and which do not belong to the outer shell, are to be subjected to lateral pressure in flooding conditions. Their scantlings are to be determined according to the relevant criteria in Ch 6.
- **1.2** Connections of the aft part with structures located fore of the aft peak bulkhead
  - **1.2.1** Tapering
    Adequate tapering is to be ensured between the scantlings in the aft part and those fore of the aft peak bulkhead. The tapering is to be such that the scantling requirements for both areas are fulfilled.
- **1.3** Net scantlings
  - **1.3.1** As specified in Ch 3, Sec 2, all thicknesses referred to in this Section are net, i.e. they do not include any corrosion addition. The gross thicknesses are to be obtained as specified in Ch 3, Sec 2, [3].

#### 2. Load model

- **2.1** Load point
  - **2.1.1** Unless otherwise specified, lateral pressure is to be calculated at load points according to:
    • Ch 6, Sec 1, [1.5], for plating
    • Ch 6, Sec 2, [1.4], for stiffeners.
- **2.2** Lateral pressures
  - **2.2.1** Lateral pressure in intact conditions
    The aft part lateral pressure in intact conditions, in $\mathrm{kN}/m ^{ 2}$, is to be taken equal to (*p_S* + *p_W*).
    where:
    *p_S*, *p_W* : Hydrostatic and hydrodynamic pressures according to Ch 4, Sec 5, or internal still water and inertial pressures according to Ch 4, Sec 6, [2], to be considered among load cases H, F, R and P.
  - **2.2.2** Lateral pressure in testing conditions
    The lateral pressure *p_T* in testing conditions is taken equal to:
    • *p_T* = *p_ST* – *p_S* for bottom shell plating and side shell plating
    • *p_T* = *p_ST* otherwise
    where:
    *p_ST* : Testing pressure defined in Ch 4, Sec 6, [4]
    *p_S* : Pressure taken equal to:
    • if the testing is carried out afloat: hydrostatic pressure defined in Ch 4, Sec 5, [1] for the draught $T _{1}$, defined by the Designer, at which the testing is carried out. If $T _{1}$ is not defined, the testing is considered as being not carried out afloat.
    • if the testing is not carried out afloat: *p_S* = 0
  - **2.2.3** Elements of the outer shell
    The still water and wave lateral pressures are to be calculated considering separately:
    • the still water and wave external sea pressures
    • the still water and wave internal pressure considering the compartment adjacent to the outer shell as being loaded. If the compartment adjacent to the outer shell is intended to carry liquids, this still water and wave internal pressures are to be reduced from the corresponding still water and wave external sea pressures.
  - **2.2.4** Elements other than those of the outer shell
    The still water and wave lateral pressures to be considered as acting on an element which separates two adjacent compartments are those obtained considering the two compartments individually loaded.

#### 3. Aft peak

- **3.1** Arrangement
  - **3.1.1** General
    The aft peak is, in general, to be transversely framed.
  - **3.1.2** Floors
    Solid floors are to be fitted at every frame spacing.
    The floor height is to be adequate in relation to the shape of the hull. Where a sterntube is fitted, the floor height is to extend at least above the sterntube. Where the hull lines do not allow such extension, plates of suitable height with upper and lower edges stiffened and securely fastened to the frames are to be fitted above the sterntube.
    In way of and near the rudder post, propeller post and rudder horn, floors are to be extended up to the peak tank top and are to be increased in thickness; the increase will be considered by the Society on a case by case basis, depending on the arrangement proposed.
    Floors are to be provided with stiffeners located at intervals not exceeding 800 mm.
  - **3.1.3** Side frames
    Side frames are to be extended up to a deck located above the full load waterline.
    Side frames are to be supported by one of the following types of structure:
    • non-tight platforms, to be fitted with openings having a total area not less than 10 % of the area of the platforms
    • side girders supported by side primary supporting members connected to deck transverses.
  - **3.1.4** Platforms and side girders
    Platforms and side girders within the peak are to be arranged in line with those located in the area immediately forward.
    Where this arrangement is not possible due to the shape of the hull and access needs, structural continuity between the peak and the structures of the area immediately forward is to be ensured by adopting wide tapering brackets.
    Where the aft peak is adjacent to a machinery space whose side is longitudinally framed, the side girders in the aft peak are to be fitted with tapering brackets.
  - **3.1.5** Longitudinal bulkheads
    A longitudinal non-tight bulkhead is to be fitted on the centreline of the ship, in general in the upper part of the peak, and stiffened at each frame spacing.
    Where either the stern overhang is very large or the maximum breadth of the space divided by watertight and wash bulkheads is greater than 20 m, additional longitudinal wash bulkheads may be required.

#### 4. Scantlings

- **4.1** Plating
  - **4.1.1** The net thickness of plating are to be not less than those obtained from the formulae in Table 1 and Table 2.

    **Minimum net thickness, in mm**

    | Bottom | 5.5 + 0.03 *L* |
    | --- | --- |
    | Side and transom | 0.85 *L^1/2* |
    | Inner bottom | 5.5 + 0.03 *L* |
    | Strength deck | 4.5 + 0.02 *L* |
    | Platform and wash bulkhead | 6.5 |
    | Transverse and longitudinal<br>watertight bulkheads | 0.6 *L^1/2* |

    **Net thickness, in mm**

    | Intact conditions | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1310.png) |
    | --- | --- |
    | Testing conditions | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1311.png) |
- **4.2** Ordinary stiffeners
  - **4.2.1** General
    The requirements of this sub-articleapply to ordinary stiffeners considered as clamped at both ends. For other boundary conditions, the yielding check is to be considered on a case by case basis.
  - **4.2.2** The net dimensions of ordinary stiffeners are to comply with the requirements in Ch 6, Sec 2, [2.3].
  - **4.2.3** The net thickness of the web of ordinary stiffeners, in mm, is to be not less than the greater of:
    • *t* = 3.0 + 0.015 *L*_2
    • 40 % of the net required thickness of the attached plating, to be determined according to [4.1].
    The net dimensions of ordinary stiffeners are to comply with the requirement in Ch 6, Sec 2, [2.2.2] and [2.3].
  - **4.2.4** The net scantlings of single-span ordinary stiffeners are to be not less than those obtained from the formulae in Table 3.

    | Stiffener type | Net section modulus $w$, in $\mathrm{cm} ^{3}$ | Net sectional shear area $A _{sh}$, in $\mathrm{cm} ^{2}$ |
    | --- | --- | --- |
    | Single span ordinary stiffeners subjected to lateral pressure | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1312.png) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1313.png) |
    | Single span ordinary stiffeners subjected to testing pressure | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1314.png) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1315.png) |
    | where:<br>$\phi$ : Angle, in deg, between the stiffener web and the shell plate, measured at the middle of the stiffener span; the correction is to be applied when $\phi$ is less than 75. |   |   |
  - **4.2.5** The maximum normal stress $\sigma$ and shear stress $\tau$ in a multi-span ordinary stiffener are to comply with the formulae in Table 4.
    The maximum normal stress $\sigma$ and shear stress $\tau$ in a multi-span ordinary stiffener are to be determined by a direct calculation taking into account:
    • the distribution of still water and wave pressure and forces, if any
    • the number and position of intermediate supports (decks, girders, etc.)
    • the condition of fixity at the ends of the stiffener and at intermediate supports
    • the geometrical characteristics of the stiffener on the intermediate spans.

    | Condition | Intact | Testing |
    | --- | --- | --- |
    | Normal stress | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1316.png) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1317.png) |
    | Shear stress | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1318.png) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1319.png) |
- **4.3** Primary supporting members
  - **4.3.1** Floors
    The net thickness of floors is to be not less than that obtained, in mm, from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1320.png)
  - **4.3.2** Side transverses
    The net section modulus $w$, in $\mathrm{cm} ^{3}$, and the net shear sectional area $A _{sh}$, in $\mathrm{cm} ^{2}$, of side transverses are to be not less than the values obtained from the following formulae:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1321.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1322.png)
  - **4.3.3** Side girders
    The net section modulus $w$, in $\mathrm{cm} ^{3}$, and the net shear sectional area $A _{sh}$, in $\mathrm{cm} ^{2}$, of side girders are to be not less than the values obtained from the following formulae:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1323.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1324.png)
  - **4.3.4** Deck primary supporting members
    The net scantlings of deck primary supporting members are to be not less than those obtained from the formulae in Table 5. The design pressures in the formulae are taken from intact conditions and testing conditions respectively as stated in [2.2]. For a complex deck structure, a direct strength calculation may be carried out in lieu of the formulae.

    | Condition | Net section modulus w, in $\mathrm{cm} ^{3}$ | Net sectional shear area<br>$A _{sh}$, in $\mathrm{cm} ^{2}$ |
    | --- | --- | --- |
    | Primary supporting members subjected to lateral pressure in intact conditions | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1325.png) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1326.png) |
    | Primary supporting members subjected to lateral pressure in testing conditions | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1327.png) | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1328.png) |
    | Where,<br>$\phi$ : Angle, in deg, between the primary supporting member’s web and the shell plate, measured at the middle of the primary supporting member’s span; the correction is to be applied when $\phi$ is less than 75. |   |   |

#### 5. Connection of hull structures with the rudder horn

- **5.1** Connection of aft peak structures with the rudder horn
  - **5.1.1** General
    The requirement of this sub-article apply to the connection between peak structure and rudder horn where the stern-frame is of an open type and is fitted with the rudder horn.
  - **5.1.2** Rudder horn
    Horn design is to be such as to enable sufficient access for welding and inspection.
    The scantlings of the rudder horn, which are to comply with Ch 10, Sec 1, [9.2], may be gradually tapered inside the hull.
    Connections by slot welds are not acceptable.
  - **5.1.3** Hull structures
    The vertical extension of hull structure to support the rudder horn between the horn intersection with the shell and the peak tank top is in accordance with the requirements of Ch 10, Sec 1, [9.2.6] and [9.2.7].
    The thickness ofthe structures adjacent to the rudder horn, such as shell plating, floors, platforms and side girders, the centreline bulkhead and any other structures, is to be adequately increased in relation to the horn scantlings.
- **5.2** Structural arrangement above the aft peak
  - **5.2.1** Side transverses
    Where a rudder horn is fitted, side transverses, connected to deck beams, are to be arranged between the platform forming the peak tank top and the weather deck.
    The side transverse spacing is to be not greater than:
    • 2 frame spacings in way of the horn
    • 4 frame spacings for and aft of the rudder horn
    • 6 frame spacings in the area close to the aft peak bulkhead.
    The side transverses are to be fitted with end brackets and located within the poop. Where there is no poop, the scantlings of side transverses below the weather deck are to be adequately increased with respect to those obtained from the formulae in [4.3.2].
  - **5.2.2** Side girders
    Where the depth from the peak tank top to the weather deck is greater than 2.6 m and the side is transversely framed, one or more side girders are to be fitted, preferably in line with similar structures existing forward.

#### 6. Sternframes

- **6.1** General
  - **6.1.1** Sternframes may be made of cast or forged steel, with a hollow section, or fabricated from plate.
  - **6.1.2** Cast steel and fabricated sternframes are to be strengthened by adequately spaced horizontal plates.
    Abrupt changes of section are to be avoided in castings; all sections are to have adequate tapering radius.
- **6.2** Connections
  - **6.2.1** Connection with hull structure
    Sternframes are to be effectively attached to the aft structure and the lower part of the sternframe is to be extended forward of the propeller post to a length not less than 1500 + 6 *L* mm, in order to provide an effective connection with the keel. However, the sternframe need not extend beyond the aft peak bulkhead.
    The net thickness of shell plating connected with the sternframe is to be not less than that obtained, in mm, from the following formula:
    *t* = 8.5 + 0.045 *L*
  - **6.2.2** Connection with the keel
    The thickness of the lower part of the sternframes is to be gradually tapered to that of the solid bar keel or keel plate.
    Where a keel plate is fitted, the lower part of the sternframe is to be so designed as to ensure an effective connection with the keel.
  - **6.2.3** Connection with transom floors
    Rudder posts and propeller posts are to be connected with transom floors having height not less than that of the double bottom and net thickness not less than that obtained, in mm, from the following formula:
    *t* = 9 + 0.023 *L_1*
  - **6.2.4** Connection with centre keelson
    Where the sternframe is made of cast steel, the lower part of the sternframe is to be fitted, as far as practicable, with a longitudinal web for connection with the centre keelson.
- **6.3** Propeller posts
  - **6.3.1** Gross scantlings
    With reference to Ch 3, Sec 2, all scantlings and dimensions referred to in [6.3.2] to [6.3.4] are gross, i.e. they include the margins for corrosion.
  - **6.3.2** Gross scantlings of propeller posts
    The gross scantlings of propeller posts are to be not less than those obtained from the formulae in Table 6 for single screw ships and Table 7 for twin screw ships.
    Scantlings and proportions of the propeller post which differ from those above may be considered acceptable provided that the section modulus of the propeller post section about its longitudinal axis is not less than that calculated with the propeller post scantlings in Table 6 or Table 7 as applicable.
  - **6.3.3** Section modulus below the propeller shaft bossing
    In the case of a propeller post without a sole piece, the section modulus of the propeller post may be gradually reduced below the propeller shaft bossing down to 85 % of the value calculated with the scantlings in Table 6 or Table 7 as applicable.
    In any case, the thicknesses of the propeller posts are to be not less than those obtained from the formulae in the tables.
  - **6.3.4** Welding of fabricated propeller post with the propeller shaft bossing
    Welding of a fabricated propeller post with the propeller shaft bossing is to be in accordance with Ch 11, Sec 2.
- **6.4** Propeller shaft bossing
  - **6.4.1** In single screw ships, the thickness of the propeller shaft bossing, included in the propeller post, is to be not less than 60 % of the dimension *b* required in [6.3.2] for bar propeller posts with a rectangular section.

    | Gross scantlings of propeller posts, in mm | Fabricated propeller post<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1329.png) | Cast propeller post<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1330.png) | Bar propeller post, cast or forged, having rectangular section<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1331.png) |
    | --- | --- | --- | --- |
    | *a* | 50 *L^1/2* | 33 *L^1/2* | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1332.png) |
    | *b* | 35 *L^1/2* | 23 *L^1/2* | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1333.png) |
    | *t_1*<sup>(1)</sup> | 2.5 *L^1/2* | 3.2 *L^1/2*<br>to be taken not less than<br>19 mm | - |
    | *t_2*<sup>(1)</sup> | - | 4.4 *L^1/2*<br>to be taken not less than<br>19 mm | - |
    | *t_D* | 1.3 *L^1/2* | 2.0 *L^1/2* | - |
    | *R* | - | 50 *L^1/2* | - |
    | <sup>(1)</sup> Propeller post thicknesses *t_1*, and *t_2* are, in any case, to be not less than (0.05 *L* + 9.5) mm. |   |   |   |

    | Gross scantlings of propeller posts, in mm | Fabricated propeller post<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1334.png) | Cast propeller post<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1335.png) | Bar propeller post, cast or forged, having rectangular section<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1336.png) |
    | --- | --- | --- | --- |
    | *a* | 25 *L^1/2* | 12.5 *L^1/2* | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1337.png) |
    | *b* | 25 *L^1/2* | 25 *L^1/2* | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1338.png) |
    | *t_1*<sup>(1)</sup> | 2.5 *L^1/2* | 2.5 *L^1/2* | - |
    | *t_2*<sup>(1)</sup> | 3.2 *L^1/2* | 3.2 *L^1/2* | - |
    | *t_3* | - | 4.4 *L^1/2* | - |
    | *t_D* | 1.3 *L^1/2* | 2.0 *L^1/2* | - |
    | <sup>(1)</sup> Propeller post thicknesses *t_1*, *t_2* and *t_3* are, in any case, to be not less than (0.05 *L* + 9.5) mm. |   |   |   |
- **6.5** Sterntubes
  - **6.5.1** Sterntubes
    The sterntube thickness is considered by the Society on a case by case basis. In no case, however, may it be less than the thickness of the side plating adjacent to the stern-frame.
    Where the materials adopted for the sterntube and the plating adjacent to the sternframe are different, the sterntube thickness is to be at least equivalent to that of the plating.


### Section 3 - MACHINERY SPACE

Symbols
For symbols not defined in this Section, refer to Ch 1, Sec 4.
*k* : Material factor, defined in Ch 3, Sec 1, [2.2]
*P* : Maximum continuous rating, in kW, of the engine
*n_r* : Number of revolutions per minute of the engine shaft at power equal to *P*
*L_E* : Effective length, in m, of the engine foundation plate required for bolting the engine to the seating, as specified by the engine manufacturer.

#### 1. General

- **1.1** Application
  - **1.1.1** The requirements of this Section apply for the arrangement and scantling of machinery space structures as regards general strength. It is no substitute to machinery manufacturer’s requirements that have to be dealt with at Shipyard diligence.
- **1.2** Scantlings
  - **1.2.1** Net scantlings
    As specified in Ch 3, Sec 2 all scantlings referred to in this Section are net, i.e. they do not include any margin for corrosion.
    The gross scantlings are obtained as specified in Ch 3, Sec 2, [3.1].
  - **1.2.2** General
    Unless otherwise specified in this Section, the scantlings of plating, ordinary stiffeners and primary supporting members in the machinery space are to be determined according to the relevant criteria in Ch 6.
    In addition, the minimum thickness requirements specified in this Section apply.
  - **1.2.3** Primary supporting members
    The Designer may propose arrangements and scantlings alternative to the requirements of this Section, on the basis of direct calculations which are to be submitted to the Society for examination on a case by case basis.
    The Society may also require such direct calculations to be carried out whenever deemed necessary.
- **1.3** Connections of the machinery space with structures located aft and forward
  - **1.3.1** Tapering
    Adequate tapering is to be ensured between the scantlings in the machinery space and those aft and forward. The tapering is to be such that the scantling requirements for all areas are fulfilled.
  - **1.3.2** Transition zone between engine room and cargo area
    In the transition zone between the engine room and the aftermost cargo hold due consideration is to be given to the proper tapering of major longitudinal members within the engine room such as flats, decks, horizontal rings or side stringers into the cargo hold, and for longitudinal bulkheads (inner skin, upper and lower wing tank) into the engine room.
    Where such structure is in line with longitudinal members aft or forward of the cargo hold bulkhead, adequate tapering is to be achieved by fitting large tapering brackets inside the wing tanks or engine room.
  - **1.3.3** Deck discontinuities
    Decks which are interrupted in the machinery space are to be tapered on the side by means of horizontal brackets.

#### 2. Double bottom

- **2.1** Arrangement
  - **2.1.1** General
    Where the machinery space is immediately forward of the after peak, the double bottom is to be transversely framed. In all other cases it may be transversely or longitudinally framed.
  - **2.1.2** Double bottom height
    The double bottom height at the centreline, irrespective of the location of the machinery space, is to be not less than the value defined in Ch 3, Sec 6, [6.1]. This depth may need to be considerably increased in relation to the type and depth of main machinery seatings.
    The above height is to be increased by the Shipyard where the machinery space is very large and where there is a considerable variation in draught between light ballast and full load conditions.
    Where the double bottom height in the machinery space differs from that in adjacent spaces, structural continuity of longitudinal members is to be ensured by sloping the inner bottom over an adequate longitudinal extent. The knuckles in the sloped inner bottom are to be located in way of floors.
  - **2.1.3** Centre bottom girder
    In general, the centre bottom girder may not be provided with holes. In any case, in way of any openings for manholes on the centre girder, permitted only where absolutely necessary for double bottom access and maintenance, local strengthening is to be arranged.
  - **2.1.4** Side bottom girders
    In the machinery space the number of side bottom girders is to be adequately increased, with respect to the adjacent areas, to ensure adequate rigidity of the structure. The side bottom girders are to be a continuation of any bottom longitudinals in the areas adjacent to the machinery space and are generally to have a spacing not greater than 3 times that of longitudinals and in no case greater than 3 m.
  - **2.1.5** Side bottom girders in way of machinery seatings
    Additional side bottom girders are to be fitted in way of machinery seatings.
    Side bottom girders arranged in way of main machinery seatings are to extend for the full length of the machinery space. Bottom girders are to extend as far aft as practicable in relation to the shape of the bottom and are to be supported by floors and side primary supporting members at the ends.
    Forward of the machinery space forward bulkhead, the bottom girders are to be generally tapered for at least three frame spaces and are to be effectively connected to the hull structure.
  - **2.1.6** Floors in longitudinally framed double bottom
    Where the double bottom is longitudinally framed, the floor spacing is to be not greater than:
    • 1 frame spacing in way of the main engine and thrust bearing
    • 2 frame spacings in other areas of the machinery space.
    Additional floors are to be fitted in way of other important machinery.
  - **2.1.7** Floors in transversely framed double bottom
    Where the double bottom in the machinery space is transversely framed, floors are to be arranged at every frame.
    Furthermore, additional floors are to be fitted in way of boiler foundations or other important machinery.
  - **2.1.8** Floors stiffeners
    In addition to the requirements in Ch 3, Sec 6, floors are to have web stiffeners sniped at the ends and spaced not more than approximately 1 m apart.
    The section modulus of web stiffeners is to be not less than 1.2 times that required in Ch 6, Sec 2, [4.1.2].
  - **2.1.9** Manholes and wells
    The number and size of manholes in floors located in way of seatings and adjacent areas are to be kept to the minimum necessary for double bottom access and maintenance.
    The depth of manholes is generally to be not greater than 40 % of the floor local depth, and in no case greater than 750 mm, and their width is to be equal to approximately 400 mm.
    In general, manhole edges are to be stiffened with flanges; failing this, the floor plate is to be adequately stiffened with flat bars at manhole sides.
    Manholes with perforated portable plates are to be fitted in the inner bottom in the vicinity of wells arranged close to the aft bulkhead of the engine room.
    Drainage of the tunnel is to be arranged through a well located at the aft end of the tunnel.
- **2.2** Minimum thicknesses
  - **2.2.1** The net thicknesses of inner bottom, floor and girder webs are to be not less than the values given in Table 1.

    | Element | Minimum net thickness, in mm |
    | --- | --- |
    | Inner bottom | 6.6 + 0.024 *L*<br>The Society may require the thickness of the inner bottom in way of the machinery seatings and on the main thrust blocks to be increased, on a case by case basis. |
    | Margin plate | 0.9 *L^1/2* + 1 |
    | Centre girder | 1.55 *L^1/2* + 3.5 |
    | Floors and side girders | 1.7 *L^1/2* + 1 |
    | Girder bounding a duct keel | 0.8 *L^1/2* + 2.5, to be taken not less than that required for the centre girder. |

#### 3. Side

- **3.1** Arrangement
  - **3.1.1** General
    The type of side framing in machinery spaces is generally to be the same as that adopted in the adjacent areas.
  - **3.1.2** Extension of the hull longitudinal structure within the machinery space
    In ships where the machinery space is located aft and where the side is longitudinally framed, the longitudinal structure is preferably to extend for the full length of the machinery space.
    In any event, the longitudinal structure is to be maintained for at least 0.3 times the length of the machinery space, calculated from the forward bulkhead of the latter, and abrupt structural discontinuities between longitudinally and transversely framed structures are to be avoided.
  - **3.1.3** Side transverses
    Side transverses are to be aligned with floors. One is preferably to be located in way of the forward end and another in way of the after end of the machinery casing.
    For a longitudinally framed side, the side transverse spacing is to be not greater than 4 frame spacings.
    For a transversely framed side, the side transverse spacing is to be not greater than 5 frame spaces. The web height is to be not less than twice that of adjacent frames and the section modulus is to be not less than four times that of adjacent frames.
    Side transverse spacing greater than that above may be accepted provided that the scantlings of ordinary frames are increased, according to the Society’s requirements to be defined on a case by case basis.

#### 4. Platforms

- **4.1** Arrangement
  - **4.1.1** General
    The location and extension of platforms in machinery spaces are to be arranged so as to be a continuation of the structure of side longitudinals, as well as of platforms and side girders located in the adjacent hull areas.
  - **4.1.2** Platform transverses
    In general, platform transverses are to be arranged in way of side or longitudinal bulkhead transverses.
    For longitudinally framed platforms, the spacing of platform transverses is to be not greater than 4 frame spacings.
- **4.2** Minimum thicknesses
  - **4.2.1** The net thickness of platforms is to be not less than 6.5 mm.

#### 5. Pillaring

- **5.1** Arrangement
  - **5.1.1** General
    The pillaring arrangement in machinery spaces is to account both for the concentrated loads transmitted by machinery and superstructures and for the position of main machinery and auxiliary engines.
  - **5.1.2** Pillars
    Pillars are to be arranged in the following positions:
    • in way of machinery casing corners and corners of large openings on platforms; alternatively, two pillars may be fitted on the centreline (one at each end of the opening)
    • in way of the intersection of platform transverses and girders
    • in way of transverse and longitudinal bulkheads of the superstructure.
    In general, pillars are to be fitted with brackets at their ends.
  - **5.1.3** Pillar bulkheads
    In general, pillar bulkheads, fitted in ‘tween decks below the upper deck, are to be located in way of load-bearing bulkheads in the superstructures.
    Longitudinal pillar bulkheads are to be a continuation of main longitudinal hull structures in the adjacent spaces forward and aft of the machinery space.
    Pillar bulkhead scantlings are to be not less than those required in [6.3] for machinery casing bulkheads.

#### 6. Machinery casing

- **6.1** Arrangement
  - **6.1.1** Ordinary stiffener spacing
    Ordinary stiffeners are to be located:
    • at each frame, in longitudinal bulkheads
    • at a distance of about 750 mm, in transverse bulkheads.
    The ordinary stiffener spacing in portions of casings that are particularly exposed to wave action is considered by the Society on a case by case basis.
- **6.2** Openings
  - **6.2.1** General
    All machinery space openings, which are to comply with the requirements in Sec 6, [6], are to be enclosed in a steel casing leading to the highest open deck. Casings are to be reinforced at the ends by deck beams and girders associated to pillars.
    In the case of large openings, the arrangement of cross-ties as a continuation of deck beams may be required.
    Skylights, where fitted with openings for light and air, are to have coamings of a height not less than:
    • 900 mm, if in position 1
    • 760 mm, if in position 2.
  - **6.2.2** Access doors
    Access doors to casings are to comply with Sec 6, [6.2].
- **6.3** Scantlings
  - **6.3.1** Plating and ordinary stiffeners
    The net scantlings of plating and ordinary stiffeners are to be not less than those obtained according to the applicable requirements in Ch 9, Sec 4.
  - **6.3.2** Minimum thicknesses
    The net thickness of bulkheads is to be not less than:
    • 5.5 mm for bulkheads in way of cargo holds
    • 4 mm for bulkheads in way of accommodation spaces.

#### 7. Main machinery seating

- **7.1** Arrangement
  - **7.1.1** General
    The scantlings of main machinery seatings and thrust bearings are to be adequate in relation to the weight and power of engines and the static and dynamic forces transmitted by the propulsive installation.
  - **7.1.2** Seating supporting structure
    Transverse and longitudinal members supporting the seatings are to be located in line with floors and double or single bottom girders, respectively.
    They are to be so arranged as to avoid discontinuity and ensure sufficient accessibility for welding of joints and for surveys and maintenance.
  - **7.1.3** Seatings included in the double bottom structure
    Where high-power internal combustion engines or turbines are fitted, seatings are to be integral with the double bottom structure. Girders supporting the bedplates in way of seatings are to be aligned with double bottom girders and are to be extended aft in order to form girders for thrust blocks.
    The girders in way of seatings are to be continuous from the bedplates to the bottom shell.
  - **7.1.4** Seatings above the double bottom plating
    Where the seatings are situated above the double bottom plating, the girders in way of seatings are to be fitted with flanged brackets, generally located at each frame and extending towards both the centre of the ship and the sides.
    The extension of the seatings above the double bottom plating is to be limited as far as practicable while ensuring adequate spaces for the fitting of bedplate bolts. Bolt holes are to be located such that they do not interfere with seating structures.
  - **7.1.5** Seatings in a single bottom structure
    For ships having a single bottom structure within the machinery space, seatings are to be located above the floors and to be adequately connected to the latter and to the girders located below.
  - **7.1.6** Number of girders in way of machinery seatings
    At least two girders are to be fitted in way of main machinery seatings.
    One girder may be fitted only where the following three formulae are complied with:
    *L* < 150 m
    *P* < 7100 kW
    *P* < 2.3 *n_rL_E*
- **7.2** Minimum scantlings
  - **7.2.1** The net scantlings of the structural elements in way of the internal combustion engine seatings are to be obtained from the formulae in Table 2. However, the net cross-sectional area of each bedplate of the seatings may be determined by the engine manufacturers, provided the information regarding permissible foundation stiffness considering the engine characteristics and engine room arrangement, etc.

    **Scantling minimum value**

    | Net cross-sectional area, in $\mathrm{cm} ^{2}$, of each bedplate of the seatings | $40+70 \frac{P}{n _{r} L _{E}}$ |
    | --- | --- |
    | Bedplate net thickness, in mm | Bedplates supported by two or more girders:<br>$\sqrt {240+175 \frac{P}{n _{r} L _{E}}}$<br>Bedplates supported by one girder:<br>$5+ \sqrt {240+175 \frac{P}{n _{r} L _{E}}}$ |
    | Total web net thickness, in mm, of girders fitted in way of machinery seatings | Bedplates supported by two or more girders:<br>$\sqrt {320+215 \frac{P}{n _{r} L _{E}}}$<br>Bedplates supported by one girder:<br>$\sqrt {95+65 \frac{P}{n _{r} L _{E}}}$ |
    | Web net thickness, in mm, of floors fitted in way of machinery seatings | $\sqrt {55+40 \frac{P}{n _{r} L _{E}}}$ |


### Section 4 - SUPERSTRUCTURES AND DECKHOUSES

Symbols
For symbols not defined in this Section, refer to Ch 1, Sec 4.
*L*_2 : Rule length *L*, but to be taken not greater than 300 m
$p _{D}$ : Lateral pressure for decks, in $\mathrm{kN}/m ^{ 2}$, as defined in [3.2.1]
$p _{SI}$ : Lateral pressure for sides of superstructures, in $\mathrm{kN}/m ^{ 2}$, as defined in [3.2.3]
*k* : Material factor, defined in Ch 3, Sec 1, [2.2]
*s* : Spacing, in m, of ordinary stiffeners, measured at mid-span along the chord
$\ell$ : Span, in m, of ordinary stiffeners, measured between the supporting members, see Ch 3, Sec 6, [4.2]
*c* : Coefficient taken equal to:
*c* = 0.75 for beams, girders and transverses which are simply supported on one or both ends
*c* = 0.55 in othe rcases
*m_a* : Coefficient taken equal to:
![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1339.png), with ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1340.png)

#### 1. General

- **1.1** Definitions
  - **1.1.1** Superstructure
    See Ch 1, Sec 4, [3.12.1]
  - **1.1.2** Deckhouse
    See Ch 1, Sec 4, [3.15.1]
  - **1.1.3** Long deckhouse
    A long deckhouse is a deckhouse the length of which within 0.4 *L* amidships exceeds 0.2 *L*. The strength of along deckhouse is to be specially considered.
  - **1.1.4** Short deckhouse
    A short deckhouse is a deckhouse not covered by the definition given in [1.1.3].
  - **1.1.5** Non-effective superstructure
    For the purpose of this section, all superstructures being located beyond 0.4 *L* amidships or having a length of less than 0.15 *L* are considered as non-effective superstructures.
  - **1.1.6** Insulated funnel
    Scantlings of insulated funnels are to be determined as for deckhouses.
  - **1.1.7** Effective superstructure
    Effective superstructure is a superstructure not covered by the definition given in [1.1.5]
- **1.2** Gross scantlings
  - **1.2.1** With reference to Ch 3, Sec 2, all scantlings and dimensions referred to in [4] and [5] are gross, i.e. they include the margins for corrosion.

#### 2. Arrangement

- **2.1** Strengthening at the ends of superstructures
  - **2.1.1** In way of end bulkheads of superstructures located within 0.4 *L* amidships, the thickness of the strength deck in a breadth of 0.1 *B* from the shell, the thickness of the sheerstrake, and the thickness of the superstructure side plating are to be increased by the percentage of strengthening specified in Table 1. The strengthening is to be extended over a region from 4 frame spacings abaft the end bulkhead to 4 frame spacings forward of the end bulkhead.

    | Type of superstructure | Strength deck and sheerstrake | Side plating of superstructure |
    | --- | --- | --- |
    | Effective | 30 % | 20 % |
    | Non-effective | 20 % | 10 % |
  - **2.1.2** Under strength decks in way of 0.6 *L* amidships, girders are to be fitted in alignment with longitudinal walls, which are to extend at least over three frame spacings beyond the end points of the longitudinal walls. The girders are to overlap with the longitudinal walls by at least two frame spacings.
- **2.2** Attachment of stiffening members
  - **2.2.1** Attachment of deck beams
    Transverse deck beams are to be connected to the frames by brackets according to Ch 3, Sec 6.
    Deck beams crossing longitudinal walls and girders may be attached to the stiffeners of longitudinal walls and the webs of girders respectively by welding without brackets.
  - **2.2.2** Attachment of deck girders and transverses
    End attachments of girders at bulkheads are to be so dimensioned that the bending moments and shear forces can be transferred. Bulkhead stiffeners under girders are to be sufficiently dimensioned to support the girders.
    Face plates are to be stiffened by tripping brackets according to Ch 3, Sec 6. At girders of symmetrical section, they are to be arranged alternately on both sides of the web.
  - **2.2.3** End attachment of superstructure frames
    Superstructure frames are to be connected to the main frames below, or to the deck. The end attachment may be carried out in accordance with Fig 1.
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1341.png)
    Fig 1: End attachment of superstructure frames
- **2.3** Transverse structure of superstructures and deckhouses
  - **2.3.1** The transverse structure of superstructures and deckhouses is to be sufficiently dimensioned by a suitable arrangement of end bulkheads, web frames, steel walls of cabins and casings, or by other measures.
- **2.4** Openings in enclosed superstructures
  - **2.4.1** *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 12(1))*
    All access openings in bulkheads at ends of enclosed superstructures are to be fitted with weathertight doors permanently attached to the bulkhead, and framed, stiffened and fitted so that the whole structure is of equivalent strength to the un-pierced bulkhead. The doors are to be so arranged that they can be operated from both sides of the bulkhead.
  - **2.4.2** *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 12(3))*
    The height of the sills of access openings in bulkheads at ends of enclosed superstructures shall be at least 380 mm above the deck.
  - **2.4.3** Any opening in a superstructure deck or in a deckhouse deck directly above the freeboard deck (deckhouse surrounding companionways), is to be protected by efficient weathertight closures.

#### 3. Load model

- **3.1** Load calculation point
  - **3.1.1** Unless otherwise specified, lateral pressure is to be calculated at load calculation points defined in:
    • Ch 6, Sec 1, [1.5], for plating
    • Ch 6, Sec2, [1.4] for ordinary stiffeners and primary supporting members.
- **3.2** Loads
  - **3.2.1** Lateral pressure for decks
    The lateral pressure for decks of superstructures and deckhouses, in $\mathrm{kN}/m ^{ 2}$, is to be taken equal to:
    • the external pressure $p _{D}$ defined in Ch 4, Sec 5, [2.1] for exposed decks,
    • 5 $\mathrm{kN}/m ^{ 2}$ for unexposed decks.
  - **3.2.2** Lateral pressure for exposed wheel house top
    The lateral pressure $p$ for exposed wheel house tops, in $\mathrm{kN}/m ^{ 2}$, is to be obtained according to Ch 4, Sec 5, [3.2].
  - **3.2.3** Lateral pressure for sides of superstructures
    The lateral pressure $p _{SI}$ for sides of superstructures, in $\mathrm{kN}/m ^{ 2}$, is to be obtained according to Ch 4, Sec 5, [3.3].

#### 4. Scantlings

- **4.1** Side plating of non-effective superstructures
  - **4.1.1** The gross thickness, in mm, of the side plating of non-effective superstructures is not to be less than the greater of the following values:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1342.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1343.png)
- **4.2** Deck plating of non-effective superstructures
  - **4.2.1** The gross thickness, in mm, of deck plating of non-effective superstructures is not to be less than the greater of the following values:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1344.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1345.png)
    where *L* is not to be taken greater than 200 m.
  - **4.2.2** Where additional superstructures are arranged on non-effective superstructures located on the freeboard deck, the gross thickness required by [4.2.1] may be reduced by 10 %.
  - **4.2.3** Where plated decks are protected by sheathing, the gross thickness of the deck plating according to [4.2.1] and [4.2.2] may be reduced by 1.5 mm. However, such deck plating is not to be less than 5 mm.
    Where a sheathing other than wood is used, attention is to be paid that the sheathing does not affect the steel. The sheathing is to be effectively fitted to the deck.
- **4.3** Deck beams and supporting deck structure
  - **4.3.1** Transverse deck beams and deck longitudinal ordinary stiffeners
    The section modulus $w$, in $\mathrm{cm} ^{3}$, and the shear area $A _{sh}$, in $\mathrm{cm} ^{2}$, of transverse deck beams and of deck longitudinal ordinary stiffeners are not to be less than the values obtained from the following formulae:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1346.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1347.png)
  - **4.3.2** Deck girders and transverses
    The section modulus $w$, in $\mathrm{cm} ^{3}$, and the shear area $A _{sh}$, in $\mathrm{cm} ^{2}$, of deck girders and transverses are not to be less than the values obtained from the following formulae:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1348.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1349.png)
    where:
    *e* : Width of loaded area, in m, of the unsupported adjacent plate fields, measured from each mid of plate field to mid of opposite plate filed.
    The girder depth is not to be less than $\ell /25$. The web depth of girders scalloped for continuous deck beams is to be at least 1.5 times the depth of the deck beams.
    Where a girder does not have the same section modulus throughout all girder fields, the greater scantlings are to be maintained above the supports and are to be reduced gradually to the smaller scantlings.
- **4.4** Superstructure frames
  - **4.4.1** Section modulus and shear area
    The section modulus $w$, in $\mathrm{cm} ^{3}$, and the shear area $A _{sh}$, in $\mathrm{cm} ^{2}$, of the superstructure frames are not to be less than the values obtained from the following formulae:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1350.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1351.png)
  - **4.4.2** Where frames are supported by a longitudinally framed deck, the frames fitted between web frames are to be connected to the adjacent longitudinal ordinary stiffeners by brackets. The scantlings of the brackets are to be determined in accordance with Ch 3, Sec 6 on the basis of the section modulus of the frames.
  - **4.4.3** Where further superstructures or deckhouses are arranged on the superstructures, strengthening of the frames of the space below may be required.
- **4.5** Decks of short deckhouses
  - **4.5.1** Plating
    The thickness, in mm, of weather deck of short deckhouses and is not to be less than:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1352.png)
    For weather decks of short deckhouses protected by sheathing and for decks within deckhouses, the gross thickness may be reduced by 1.5mm. However, such deck plating is not to be less than 5 mm.
  - **4.5.2** Deck beams
    The scantlings of deck beams and supporting deck structure are to be determined according to [4.3].

#### 5. End bulkheads of superstructure and deckhouse

- **5.1** Application
  - **5.1.1** The requirements in [5.2] and [5.3] apply to end bulkhead of superstructure and deckhouse forming the only protection for openings, as required by ILLC as amended, and for accommodations.
- **5.2** Loads
  - **5.2.1** The design load $p _{A}$, in $\mathrm{kN}/m ^{ 2}$, for determining the scantlings is to be obtained according to Ch 4, Sec 5, [3.4].
- **5.3** Scantlings
  - **5.3.1** Stiffeners
    The section modulus $w$, in $\mathrm{cm} ^{3}$, of the stiffeners is not to be less than the value obtained from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1353.png)
    This requirement assume the webs of lowest tier stiffeners to be efficiently welded to the decks. Scantlings for other types of end connections may be specially considered.
    The section modulus of deckhouse side stiffeners needs not to be greater than that of side frames on the deck situated directly below; taking account of spacing $s$ and span $\ell$.
  - **5.3.2** Plate thickness
    The gross thickness of the plating, in mm, is not to be less than the greater of the values obtained from the following formulae:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1354.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1355.png), for the lowest tier
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1356.png), for the upper tiers, without being less than 5.0 mm.


### Section 5 - HATCH COVERS

Symbols
For symbols not defined in this Section, refer to Ch 1, Sec 4.
*p_S* : Still water pressure, in $\mathrm{kN}/m ^{ 2}$, defined in [4.1]
*p_W* : Wave pressure, in $\mathrm{kN}/m ^{ 2}$, defined in [4.1]
*p_C* : Pressure acting on the hatch coaming, in $\mathrm{kN}/m ^{ 2}$, defined in [6.2]
*F_S, F_W* : Coefficients taken equal to:
*F_S* = 0 and *F_W* = 0.9 for ballast water loads on hatch covers of the ballast hold
*F_S* = 1.0 and *F_W* = 1.0 in other cases
*s* : Length, in m, of the shorter side of the elementary plate panel
$\ell$ : Length, in m, of the longer side of the elementary plate panel
*b_p* : Effective width, in m, of the plating attached to the ordinary stiffener or primary supporting member, defined in [3]
*w* : Net section modulus, in $\mathrm{cm} ^{3}$, of the ordinary stiffener or primary supporting member, with an attached plating of width *b_p*
*A_sh* : Net shear sectional area, in $\mathrm{cm} ^{2}$, of the ordinary stiffener or primary supporting member
*m* : Boundary coefficient for ordinary stiffeners and primary supporting members, taken equal to:
*m* = 8, in the case of ordinary stiffeners and primary supporting members simply supported at both ends or supported at one end and clamped at the other end
*m* = 12, in the case of ordinary stiffeners and primary supporting members clamped at both ends
*t_C* : Total corrosion addition, in mm, defined in [1.4]
*s_a* *,* *t_a* : Allowable stresses, in $\mathrm{N}/mm ^{2}$, defined in [1.5]

#### 1. General

- **1.1** Application
  - **1.1.1** The requirements in [1] to [8] apply to steel hatch covers in positions 1 and 2 on weather decks, defined in Ch 1, Sec 4, [3.20].
    The requirements in [9] apply to steel hatch covers of small hatches fitted on the exposed fore deck over the forward 0.25 *L*.
- **1.2** Materials
  - **1.2.1** Steel
    The formulae for scantlings given in [5] are applicable to steel hatch covers.
    Materials used for the construction of steel hatch covers are to comply with the applicable requirements of the Society.
  - **1.2.2** Other materials
    The use of materials other than steel is considered by the Society on a case by case basis, by checking that criteria adopted for scantlings are such as to ensure strength and stiffness equivalent to those of steel hatch covers.
- **1.3** Net scantlings
  - **1.3.1** All scantlings referred to in this Section, except otherwise specified, are net, i.e. they do not include any margin for corrosion.
    When calculating the stresses *s* and *t* in [5.3] and [5.4], the net scantlings are to be used.
    The gross scantlings are obtained as specified in Ch 3, Sec 2.
    The corrosion additions are given in [1.4].
- **1.4** Corrosion additions
  - **1.4.1** The total corrosion addition for both sides to be considered for the plating and internal members of hatch covers is equal to the value specified in Table 1.
    The corrosion addition for hatch coamings and coaming stays is defined according to Ch 3, Sec 3.

    **Corrosion addition *t_C*, in mm, for both sides**

    | Plating and stiffeners of single skin hatch cover | 2.0 |
    | --- | --- |
    | Top and bottom plating of double skin hatch cover | 2.0 |
    | Internal structures of double skin hatch cover | 1.5 |
  - **1.5.1** *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 15(6) and 16(5))*
    The allowable stresses *s_a* and *t_a*, in $\mathrm{N}/mm ^{2}$, are to be obtained from Table 2.
    Table 2: Allowable stresses, in $\mathrm{N}/mm ^{2}$

    | Members of | Subjected to | *s_a*, in $\mathrm{N}/mm ^{2}$ | *t_a*, in $\mathrm{N}/mm ^{2}$ |
    | --- | --- | --- | --- |
    | Weathertight hatch cover | External pressure, as defined in Ch 4, Sec 5, [5.2.1] | 0.80 *R_eH* | 0.46 *R_eH* |
    | Pontoon hatch cover | External pressure, as defined in Ch 4, Sec 5, [5.2.1] | 0.68 *R_eH* | 0.39 *R_eH* |
    | Weathertight hatch cover and pontoon hatch cover | Other loads, as defined in Ch 4, Sec 5, [5.1.1] and Ch 4, Sec 6, [2] | 0.90 *R_eH* | 0.51 *R_eH* |

#### 2. Arrangements

- **2.1** Height of hatch coamings
  - **2.1.1** *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 14 (1, 1))*
    *The height above the deck of hatch coamings is to be not less than:*
    *• 600 mm in position 1*
    *• 450 mm in position 2.*
  - **2.1.2** *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 14 (1, 2))*
    *The height of hatch coamings in positions 1 and 2 closed by steel covers provided with gaskets and securing devices may be reduced with respect to the above values or the coamings may be omitted entirely, on condition that the Administration is satisfied that the safety of the ship is not thereby impaired in any sea conditions.*
    *In such cases the scantlings of the covers, their gasketing, their securing arrangements and the drainage of recesses in the deck are considered by the Society on a case by case basis.*
  - **2.1.3** Regardless of the type of closing arrangement adopted, the coamings may have reduced height or be omitted in way of openings in closed superstructures.
- **2.2** Hatch covers
  - **2.2.1** Hatch covers on exposed decks are to be weathertight.
    Hatch covers in closed superstructures need not be weathertight.
    However, hatch covers fitted in way of ballast tanks, fuel oil tanks or other tanks are to be watertight.
  - **2.2.2** The ordinary stiffeners and primary supporting members of the hatch covers are to be continuous over the breadth and length of the hatch covers, as far as practical. When this is impractical, sniped end connections are not to be used and appropriate arrangements are to be adopted to ensure sufficient load carrying capacity.
  - **2.2.3** The spacing of primary supporting members parallel to the direction of ordinary stiffeners is to be not greater than 1/3 of the span of primary supporting members.
  - **2.2.4** The breadth of the primary supporting member face plate is to be not less than 40 % of their depth for laterally unsupported spans greater than 3 m. Tripping brackets attached to the face plate may be considered as a lateral support for primary supporting members.
    The face plate outstand is not to exceed 15 times the gross face plate thickness.
  - **2.2.5** Efficient retaining arrangements are to be provided to prevent translation of the hatch cover under the action of the longitudinal and transverse forces exerted by cargoes on the cover, if any. These retaining arrangements are to be located in way of the hatch coaming side brackets.
  - **2.2.6** The width of each bearing surface for hatch covers is to be at least 65 mm.
- **2.3** Hatch coamings
  - **2.3.1** Coamings, stiffeners and brackets are to be capable of withstanding the local forces in way of the clamping devices and handling facilities necessary for securing and moving the hatch covers as well as those due to cargo stowed on the latter.
  - **2.3.2** Special attention is to be paid to the strength of the fore transverse coaming of the forward hatch and to the scantlings of the closing devices of the hatch cover on this coaming.
  - **2.3.3** Longitudinal coamings are to be extended at least to the lower edge of deck beams.
    • where they are not part of continuous deck girders, the lower edge of longitudinal coamings are to extend for at least two frame spaces beyond the end of the openings.
    • where longitudinal coamings are part of deck girders, their scantlings are to be as required in Ch 6, Sec 4.
  - **2.3.4** A web frame or a similar structure is to be provided below the deck in line with the transverse coaming. Transverse coamings are to extend below the deck and to be connected with the web frames.
- **2.4** Small hatchways
  - **2.4.1** The height of small hatchway coamings is to be not less than 600 mm if located in position 1 and 450 mm if located in position 2.
    Where the closing appliances are in the form of hinged steel covers secured weathertight by gaskets and swing bolts, the height of the coamings may be reduced or the coamings may be omitted altogether.
  - **2.4.2** Small hatch covers are to have strength equivalent to that required for main hatchways and are to be of steel, weathertight and generally hinged.
    Securing arrangements and stiffening of hatch cover edges are to be such that weathertightness can be maintained in any sea condition.
    At least one securing device is to be fitted at each side. Circular hole hinges are considered equivalent to securing devices.
  - **2.4.3** Hold accesses located on the weather deck are to be provided with weathertight metallic hatch covers, unless they are protected by a closed superstructure. The same applies to accesses located on the forecastle deck and leading directly to a dry cargo hold through a trunk.
  - **2.4.4** Accesses to cofferdams and ballast tanks are to be manholes fitted with watertight covers fixed with bolts which are sufficiently closely spaced.
  - **2.4.5** Hatchways of special design are considered by the Society on a case by case basis.

#### 3. Width of attached plating

- **3.1** Ordinary stiffeners
  - **3.1.1** The width of the attached plating to be considered for the check of ordinary stiffeners is to be obtained, in m, from the following formulae:
    • where the attached plating extends on both sides of the stiffener:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1357.png)
    • where the attached plating extends on one side of the stiffener:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1358.png)
- **3.2** Primary supporting members
  - **3.2.1** The effective width of the attached plating to be considered for the yielding and buckling checks of primary supporting members analysed through isolated beam or grillage model is to be obtained, in m, from the following formulae:
    • where the plating extends on both sides of the primary supporting member:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1359.png)
    • where the plating extends on one side of the primary supporting member:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1360.png)
    where:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1361.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1362.png)
    l*_p* : Span, in m, of the considered primary supporting member
    *S_p*_,1*, S_p*_,2 : Half distance, in m, between the considered primary supporting member and the adjacent ones, *S_p*_,1 for one side, *S_p*_,2 for the other side.
    When a isolated beam or a grillage analysis is used, the areas of ordinary stiffeners are not to be included in the attached plating of the primary members.

#### 4. Load model

- **4.1** Lateral pressures and forces
  - **4.1.1** General
    The lateral pressures and forces to be considered as acting on hatch covers are indicated in [4.1.2] to [4.1.6]. When two or more panels are connected by hinges, each individual panel is to be considered separately.
    In any case, the sea pressures defined in [4.1.2] are to be considered for hatch covers located on exposed decks.
    Additionally, when the hatch cover is intended to carry uniform cargoes, special cargoes or containers, the pressures and forces defined in [4.1.3] to [4.1.6] are to be considered independently from the sea pressures.
  - **4.1.2** Sea pressures
    The still water and wave lateral pressures are to be considered and are to be taken equal to:
    • still water pressure: $p _{s} = 0$
    • wave pressure $p _{W}$, as defined in Ch 4, Sec 5 [5.2].
  - **4.1.3** Internal pressures due ballast water
    If applicable, the static and dynamic lateral pressures are to be considered and are defined in Ch 4, Sec 6, [2].
  - **4.1.4** Pressures due to uniform cargoes
    If applicable, the static and dynamic pressures are to be considered and are defined in Ch 4, Sec 5, [2.4.1]
  - **4.1.5** Pressures or forces due to special cargoes
    In the case of carriage on the hatch covers of special cargoes (e.g. pipes, etc.) which may temporarily retain water during navigation, the lateral pressures or forces to be applied are considered by the Society on a case by case basis.
  - **4.1.6** Forces due to containers
    In the case of carriage of containers on the hatch covers, the concentrated forces under the containers corners are to be determined in accordance with the applicable requirements of the Society.
- **4.2** Load point
  - **4.2.1** Sea pressures
    The wave lateral pressure to be considered as acting on each hatch cover is to be calculated at a point located longitudinally, at the hatch cover mid-length.
  - **4.2.2** Other pressures
    The lateral pressure is to be calculated:
    • in way of the geometrical centre of gravity of the plate panel, for plating
    • at mid-span, for ordinary stiffeners and primary supporting members.
    Internal dynamic lateral pressure to be considered as acting on the bottom of a hatch cover is to be calculated at a point located:
    • longitudinally, at the hatch cover mid-length
    • transversely, at hatchway side
    • Vertically, at the top of the hatch coaming for internal ballast water pressures

#### 5. Strength check

- **5.1** General
  - **5.1.1** Application
    The strength check is applicable to rectangular hatch covers subjected to a uniform pressure, designed with primary supporting members arranged in one direction or as a grillage of longitudinal and transverse primary supporting members.
    In the latter case, the stresses in the primary supporting members are to be determined by a grillage or a finite element analysis.
    It is to be checked that stresses induced by concentrated loads are in accordance with the criteria in [5.4.4].
  - **5.1.2** Hatch covers supporting containers
    The scantlings of hatch covers supporting containers are to comply with the applicable provisions of the Society.
  - **5.1.3** Hatch covers subjected to special cargoes
    For hatch covers supporting special cargoes, ordinary stiffeners and primary supporting members are generally to be checked by direct calculations, taking into account the stiffener arrangements and their relative inertia. It is to be checked that stresses induced by special cargoes are in accordance with the criteria in [5.4.4].
  - **5.1.4** Covers of small hatchways
    The gross thickness of covers is to be not less than 8 mm. This thickness is to be increased or an efficient stiffening fitted to the Society's satisfaction where the greatest horizontal dimension of the cover exceeds 0.6 m.
- **5.2** Plating
  - **5.2.1** Net thickness
    The net thickness of steel hatch cover top plating, in mm, is to be not less than the value obtained from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1363.png)
    where:
    $F _{p}$ : Factor for combined membrane and bending response, equal to:
    $F _{p} = 1.5$ in general
    $F _{p} =1.9 \sigma / \sigma _{a}$, for $\sigma \geq 0.8 \sigma _{a}$ for the attached plating of primary supporting members
    $\sigma$ : Normal stress, in $\mathrm{N}/mm ^{2}$, in the attached plating of primary supporting members, calculated according to [5.4.3] or determined through a grillage analysis or a finite element analysis, as the case may be.
  - **5.2.2** Minimum net thickness
    *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 16 (5, c))*
    In addition to [5.2.1], the net thickness, in mm, of the plating forming the top of the hatch cover is to be not less than the greater of the following values:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1364.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1365.png)
  - **5.2.3** Critical buckling stress check
    The compressive stress $\sigma$ in the hatch cover plating, induced by the bending of primary supporting members, parallel to the direction of ordinary stiffeners is to comply with the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1366.png)
    where:
    $S$ : Safety factor defined in Ch 6, Sec 3
    $\sigma _{C 1}$ : Critical buckling stress, in $\mathrm{N}/mm ^{2}$, taken equal to:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1367.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1368.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1369.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1370.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1371.png)
    *t* : Net thickness, in mm, of plate panel
    The compressive stress $\sigma$ in the hatch cover plating, induced by the bending of primary supporting members, perpendicular to the direction of ordinary stiffeners is to comply with the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1372.png)
    where:
    $S$ : Safety factor defined in Ch 6, Sec 3
    $\sigma _{C 2}$ : Critical buckling stress, in $\mathrm{N}/mm ^{2}$, taken equal to:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1373.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1374.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1375.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1376.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1377.png)
    $m$ : Coefficient taken equal to:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1378.png)
    *t* : Net thickness, in mm, of plate panel
    *s_s* : Length, in m, of the shorter side of the plate panel
    $\ell _{s}$ : Length, in m, of the longer side of the plate panel
    $\Psi$ : Ratio between smallest and largest compressive stress
    *c* : Coefficient taken equal to:
    *c* = 1.3 when plating is stiffened by primary supporting members
    *c* = 1.21 when plating is stiffened by ordinary stiffeners of angle or Ttype
    *c* = 1.1 when plating is stiffened by ordinary stiffeners of bulb type
    *c* = 1.05 when plating is stiffened by flat bar.
    *c =* 1.30 when plating is stiffened by ordinary stiffeners of U type. The higher c value but not greater than 2.0 may be taken if it is verified by buckling strength check of panel using non-linear FEA and deemed appropriate by the Society.
    An averaged value of c is to be used for plate panels having different edge stiffeners.
    The bi-axial compression stress in the hatch cover plating, when calculated by means of finite element analysis, is to comply with the requirements in Ch 6, Sec 3.
- **5.3** Ordinary stiffeners
  - **5.3.1** For flat bar ordinary stiffeners, the ratio $h _{w} /t _{w}$ is to comply with the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1379.png)
  - **5.3.2** Minimum net thickness of web
    The web net thickness of the ordinary stiffener, in mm, is to be not less than 4 mm.
  - **5.3.3** Net section modulus and net shear sectional area
    The net section modulus $w$, in $\mathrm{cm} ^{3}$, and the net shear sectional area $A _{sh}$, in $\mathrm{cm} ^{2}$, of an ordinary stiffener subject to lateral pressure are to be not less than the values obtained from the following formulae:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1380.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1381.png)
    where:
    l*_s* : Ordinary stiffener span, in m, to be taken as the spacing, in m, of primary supporting members or the distance between a primary supporting member and the edge support, as applicable. When brackets are fitted at both ends of all ordinary stiffener spans, the ordinary stiffener span may be reduced by an amount equal to 2/3 of the minimum brackets arm length, but not greater than 10 % of the gross span, for each bracket.
  - **5.3.4** Critical buckling stress check
    The compressive stress s in the face plate of ordinary stiffeners, induced by the bending of primary supporting members, parallel to the direction of ordinary stiffeners is to comply with the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1382.png)
    where:
    $S$ : Safety factor defined in Ch 6, Sec 3
    $\sigma _{C S}$ : Critical buckling stress, in $\mathrm{N}/mm ^{2}$, taken equal to:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1383.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1384.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1385.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1386.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1387.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1388.png)
    *I_a* : Moment of inertia, in $\mathrm{cm} ^{4}$, of the ordinary stiffener, including a face plate equal to spacing of ordinary stiffeners
    *A* : Cross-sectional area, in $\mathrm{cm} ^{2}$, of the ordinary stiffener, including a face plate equal to spacing of ordinary stiffeners
    $\ell$ : Span, in m, of the ordinary stiffener
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1389.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1390.png)
    $m$ : Number of half waves, given in Table 3.

    |   | 0 < *K* < 4 | 4 < *K* < 36 | 36 < *K* < 144 | $(m-1) ^{2} m ^{2}$ < *K* ≤ $m ^{2} (m+1) ^{2}$ |
    | --- | --- | --- | --- | --- |
    | $m$ | 1 | 2 | 3 | $m$ |

    *I_w* : Sectorial moment of inertia, in $\mathrm{cm} ^{6}$, of the ordinary stiffener about its connection with the plating, taken equal to:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1391.png) for flat bar ordinary stiffeners
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1392.png) for "Tee" ordinary stiffeners
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1393.png) for angles and bulb ordinary stiffeners
    *I_p* : Polar moment of inertia, in $\mathrm{cm} ^{4}$, of the ordinary stiffener about its connection with the plating, taken equal to:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1394.png) for flat bar ordinary stiffeners
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1395.png) for flanged ordinary stiffeners
    *I_t* : St Venant's moment of inertia, in $\mathrm{cm} ^{4}$, of the ordinary stiffener without face plate, taken equal to:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1396.png) for flat bar ordinary stiffeners
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1397.png) for flanged ordinary stiffeners
    *C* : Spring stiffness exerted by the hatch cover top plating, taken equal to:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1398.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1399.png), to be taken not less than zero; for flanged ordinary stiffeners, *k_p* need not be taken less than 0.1
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1400.png)
    $\sigma _{E 1}$ : As defined in [5.2.3]
    *t_p* : Net thickness, in mm, of the hatch cover plate panel.
- **5.4** Primary supporting members
  - **5.4.1** Application
    The requirements in [5.4.3] to [5.4.5] apply to primary supporting members which may be analysed through isolated beam models.
    Primary supporting members whose arrangement is of a grillage type and which cannot be analysed through isolated beam models are to be checked by direct calculations, using the checking criteria in [5.4.4].
  - **5.4.2** Minimum net thickness of web
    The web net thickness of primary supporting members, in mm, is to be not less than 6 mm.
  - **5.4.3** Normal and shear stress for isolated beam
    In case that grillage analysis or finite element analysis are not carried out, according to the requirements in [5.1.1], the maximum normal stress $\sigma$ and shear stress $\tau$ in the primary supporting members are to be obtained, in $\mathrm{N}/mm ^{2}$, from the following formulae:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1401.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1402.png)
    where:
    l*_m* : Span of the primary supporting member.
  - **5.4.4** Checking criteria
    The normal stress s and the shear stress $\tau$, calculated according to [5.4.3] or determined through a grillage analysis or finite element analysis, as the case may be, are to comply with the following formulae:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1403.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1404.png)
  - **5.4.5** Deflection limit
    *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 15 (6) and 16 (5, b))*
    The net moment of inertia of a primary supporting member, when loaded by sea pressure, is to be such that the deflection does not exceed $\mu \ell _{\max}$, where:
    $\mu$ : Coefficient taken equal to:
    $\mu$ = 0.0056 for weathertight hatch covers
    $\mu$ = 0.0044 for pontoon hatch covers
    $\ell _{\max}$ : Greatest span, in m, of primary supporting members.
  - **5.4.6** Critical buckling stress check of the web panels of the primary supporting members.
    The shear stress $\tau$ in the web panels of the primary supporting members, calculated according to [5.4.3] or determined through a grillage analysis or a finite element analysis, as the case may be, is to comply with the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1405.png)
    where:
    $S$ : Safety factor defined in Ch 6, Sec 3
    $\tau _{C}$ : Critical shear buckling stress, in $\mathrm{N}/mm ^{2}$, taken equal to:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1406.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1407.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1408.png) for ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1409.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1410.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1411.png)
    *t_pr,n* : Net thickness, in mm, of web of primary supporting member
    *a* : Greater dimension, in m, of web panel of primary supporting member
    *d* : Smaller dimension, in m, of web panel of primary supporting member.
    For primary supporting members parallel to the direction of ordinary stiffeners, $\tau _{C}$ is to be calculated by considering the actual dimensions of the panels.
    For primary supporting members perpendicular to the direction of ordinary stiffeners or for hatch covers built without ordinary stiffeners, a presumed square panel of dimension *d* is to be taken for the determination of the stress $\tau _{C}$, where *d* is the smaller dimension, in m, of web panel of the primary supporting member. the In such a case, the average shear stress $\tau$ between the values calculated at the ends of this panel is to be considered.
  - **5.4.7** For buckling stiffeners on webs of primary supporting members, the ratio $h _{w} /t _{w}$ is to comply with the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1412.png)
- **5.5** Ordinary stiffeners and primary supporting members of variable cross-section
  - **5.5.1** The net section modulus of ordinary stiffeners and primary supporting members with a variable cross-section is to be not less than the greater of the value obtained, in $\mathrm{cm} ^{3}$, from the following formulae:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1413.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1414.png)
    where:
    $w _{CS}$ : Net section modulus, in $\mathrm{cm} ^{3}$, for a constant cross-section, complying with the checking criteria in [5.4.4]
    $\alpha$ : Coefficient taken equal to:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1415.png)
    $\Psi$ : Coefficient taken equal to:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1416.png)
    $\ell _{1}$ : Length of the variable section part, in m (see Fig 1)
    $\ell _{0}$ : Span measured, in m, between end supports (see Fig 1)
    $w _{1}$ : Net section modulus at end, in $\mathrm{cm} ^{3}$ (see Fig 1)
    $w _{0}$ : Net section modulus at mid-span, in $\mathrm{cm} ^{3}$ (see Fig 1).
    Moreover, the net moment of inertia of ordinary stiffeners and primary supporting members with a variable cross-section is to be not less than the greater of the values obtained, in $\mathrm{cm} ^{4}$, from the following formulae:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1417.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1418.png)
    where:
    *I_CS* : Net moment of inertia with a constant cross-section, in $\mathrm{cm} ^{4}$, complying with [5.4.5]
    *j* : Coefficient taken equal to:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1419.png)
    $I _{1}$ : Net moment of inertia at end, in $\mathrm{cm} ^{4}$ (see Fig 1)
    $I _{0}$ : Net moment of inertia at mid-span, in $\mathrm{cm} ^{4}$ (see Fig 1).
    The use of these formulae is limited to the determination of the strength of ordinary stiffeners and primary supporting members in which abrupt changes in the cross-section do not occur along their length.
    ![Fig 1: Variable cross-section stiffener](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1420.png)
    Fig 1: Variable cross-section stiffener

#### 6. Hatch coamings

- **6.1** Stiffening
  - **6.1.1** The ordinary stiffeners of the hatch coamings are to be continuous over the breadth and length of the hatch coamings.
  - **6.1.2** Coamings are to be stiffened on their upper edges with a stiffener suitably shaped to fit the hatch cover closing appliances.
    Moreover, when covers are fitted with tarpaulins, an angle or a bulb section is to be fitted all around coamings of more than 3 m in length or 600 mm in height; this stiffener is to be fitted at approximately 250 mm below the upper edge. The width of the horizontal flange of the angle is not to be less than 180 mm.
  - **6.1.3** Where hatch covers are fitted with tarpaulins, coamings are to be strengthened by brackets or stays with a spacing not greater than 3 m.
    Where the height of the coaming exceeds 900 mm, additional strengthening may be required.
    However, reductions may be granted for transverse coamings in protected areas.
  - **6.1.4** When two hatches are close to each other, underdeck stiffeners are to be fitted to connect the longitudinal coamings with a view to maintaining the continuity of their strength.
    Similar stiffening is to be provided over 2 frame spacings at ends of hatches exceeding 9 frame spacings in length.
    In some cases, the Society may require the continuity of coamings to be maintained above the deck.
  - **6.1.5** Where watertight metallic hatch covers are fitted, other arrangements of equivalent strength may be adopted.
- **6.2** Load model
  - **6.2.1** The lateral pressure *p_C* to be considered as acting on the hatch coamings is defined in [6.2.2] and [6.2.3].
  - **6.2.2** The wave lateral pressure *p_C*, in $\mathrm{kN}/m ^{ 2}$, on the No 1 forward transverse hatch coaming is to be taken equal to:
    • *p_C* *=* 220, when a forecastle is fitted in accordance with Sec 1, [7.1]
    • *p_C* *=* 290, in the other cases.
  - **6.2.3** The wave lateral pressure *p_C*, in $\mathrm{kN}/m ^{ 2}$, on the hatch coamings other than the No 1 forward transverse hatch coaming is to be taken equal to:
    • *p_C* *=* 220
  - **6.2.4** For cargo holds intended for the carriage of liquid cargoes, the liquid internal pressures applied on hatch coaming is also to be determined according to Ch 4, Sec 6.
- **6.3** Scantlings
  - **6.3.1** Plating
    The net thickness of the hatch coaming plate is to be not less than the greater value obtained, in mm, from the following formulae:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1421.png)
    *t =* 9.5
  - **6.3.2** Ordinary stiffeners
    The net section modulus of the longitudinal or transverse ordinary stiffeners of hatch coamings is to be not less than the value obtained, in $\mathrm{cm} ^{3}$, from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1422.png)
    where:
    $m$ : Coefficient taken equal to:
    $m$ = 16 in general
    $m$ = 12 for the end span of stiffeners sniped at the coaming corners
    *c_p* : Ratio of the plastic section modulus to the elastic section modulus of the ordinary stiffeners with an attached plate breadth, in mm, equal to 40 *t*, where *t* is the plate net thickness.
    *c_p* *=* 1.16 in the absence of more precise evaluation.
  - **6.3.3** Coaming stays
    The net section modulus *w*, in $\mathrm{cm} ^{3}$, and the net thickness *t_w*, in mm, of the coaming stays designed as beams with flange connected to the deck or sniped and fitted with a bracket (examples shown in Fig 2 and Fig 3) are to be not less than the values obtained from the following formulae at the connection with deck:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1423.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1424.png)
    where:
    *H_C* : Stay height, in m
    *s_C* : Stay spacing, in m
    *h* : Stay depth, in mm, at the connection with deck.
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1425.png) ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1426.png)
    Fig 2: Coaming stay: example1 Fig 3: Coaming stay: example 2
    For calculating the section modulus of coaming stays, their face plate area may be taken into account only when it is welded with full penetration welds to the deck plating and adequate underdeck structure is fitted to support the stresses transmitted by it.
    For other designs of coaming stays, such as, for example, those shown in Fig 4 and Fig 5, the stress levels determined through a grillage analysis or finite element analysis, as the case may be, apply and are to be checked at the highest stressed locations. The stress levels are to comply with the following formulae:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1427.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1428.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1429.png) ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1430.png)
    Fig 4: Coaming stay: example 3 Fig 5: Coaming stay: example 4
  - **6.3.4** Local details
    The design of local details is to comply with the requirements in this section for the purpose of transferring the pressures on the hatch covers to the hatch coamings and, through them, to the deck structures below.
    Hatch coamings and supporting structures are to be adequately stiffened to accommodate the loading from hatch covers, in longitudinal, transverse and vertical directions.
    The normal stress $\sigma$ and the shear stress $\tau$, in $\mathrm{N}/mm ^{2}$, induced in the underdeck structures by the loads transmitted by stays are to comply with the following formulae:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1431.png)
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1432.png)
    Unless otherwise stated, weld connections and materials are to be dimensioned and selected in accordance with the Society’s requirements.
    Double continuous fillet welding is to be adopted for the connections of stay webs with deck plating and the weld throat thickness is to be not less than 0.44 *t_w*, where *t_w* is the gross thickness of the stay web.
    Toes of stay webs are to be connected to the deck plating with deep penetration double bevel welds extending over a distance not less than 15 % of the stay width.
  - **6.3.5** Coamings of small hatchways
    The gross thickness of coaming plate is to be not less than the lesser of the following values:
    • the gross thickness for the deck inside line of openings calculated for that position, assuming as spacing of stiffeners the lesser of the values of the height of the coaming and the distance between its stiffeners, if any, or
    • 10 mm.
    Coamings are to be suitably strengthened where their height exceeds 0.8 m or their greatest horizontal dimension exceeds 1.2 m, unless their shape ensures an adequate rigidity.

#### 7. Weathertightness, closing arrangement, securing devices and stoppers

- **7.1** Weathertightness
  - **7.1.1** *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 16 (1))*
    *Where the hatchway is exposed, the weathertightness is to be ensured by gaskets and clamping devices sufficient in number and quality.*
    *Weathertightness may also be ensured means of tarpaulins.*
  - **7.1.2** In general, a minimum of two securing devices or equivalent is to be provided on each side of the hatch cover.
- **7.2** Gaskets
  - **7.2.1** The weight of hatch covers and any cargo stowed thereon, together with inertia forces generated by ship motions, are to be transmitted to the ship’s structure through steel to steel contact.
    This may be achieved by continuous steel to steel contact of the hatch cover skirt plate with the ship’s structure or by means of defined bearing pads.
  - **7.2.2** The sealing is to be obtained by a continuous gasket of relatively soft elastic material compressed to achieve the necessary weathertightness. Similar sealing is to be arranged between cross-joint elements.
    Where fitted, compression flat bars or angles are to be well rounded where in contact with the gasket and to be made of a corrosion-resistant material.
  - **7.2.3** The gasket and the securing arrangements are to maintain their efficiency when subjected to large relative movements between the hatch cover and the ship’s structure or between hatch cover elements.
    If necessary, suitable devices are to be fitted to limit such movements.
  - **7.2.4** The gasket material is to be of a quality suitable for all environmental conditions likely to be encountered by the ship, and is to be compatible with the cargoes transported.
    The material and form of gasket selected are to be considered in conjunction with the type of hatch cover, the securing arrangement and the expected relative movement between the hatch cover and the ship’s structure.
    The gasket is to be effectively secured to the hatch cover.
  - **7.2.5** Coamings and steel parts of hatch covers in contact with gaskets are to have no sharp edges.
  - **7.2.6** Metallic contact is required for an earthing connection between the hatch cover and the hull structures. If necessary, this is to be achieved by means of a special connection for the purpose.
- **7.3** Closing arrangement, securing devices and stoppers
  - **7.3.1** General
    Panel hatch covers are to be secured by appropriate devices (bolts, wedges or similar) suitably spaced alongside the coamings and between cover elements.
    The securing and stop arrangements are to be fitted using appropriate means which cannot be easily removed.
    In addition to the requirements above, all hatch covers, and in particular those carrying deck cargo, are to be effectively secured against horizontal shifting due to the horizontal forces resulting from ship motions.
    Towards the ends of the ship, vertical acceleration forces may exceed the gravity force. The resulting lifting forces are to be considered when dimensioning the securing devices according to [7.3.5] to [7.3.7]. Lifting forces from cargo secured on the hatch cover during rolling are also to be taken into account.
    Hatch coamings and supporting structure are to be adequately stiffened to accommodate the loading from hatch covers.
    Hatch covers provided with special sealing devices, insulated hatch covers, flush hatch covers and those having coamings of a reduced height (see [2.1]) are considered by the Society on a case by case basis.
    In the case of hatch covers carrying containers, the scantlings of the closing devices are to take into account the possible upward vertical forces transmitted by the containers.
  - **7.3.2** Arrangements
    The securing and stopping devices are to be arranged so as to ensure sufficient compression on gaskets between hatch covers and coamings and between adjacent hatch covers.
    Arrangement and spacing are to be determined with due attention to the effectiveness for weathertightness, depending on the type and the size of the hatch cover, as well as on the stiffness of the hatch cover edges between the securing devices.
    At cross-joints of multipanel covers, (male/female) vertical guides are to be fitted to prevent excessive relative vertical deflections between loaded/unloaded panels.
    The location of stoppers is to be compatible with the relative movements between hatch covers and the ship’s structure in order to prevent damage to them. The number of stoppers is to be as small as possible.
  - **7.3.3** Spacing
    The spacing of the securing arrangements is to be generally not greater than 6 m.
  - **7.3.4** Construction
    Securing arrangements with reduced scantlings may be accepted provided it can be demonstrated that the possibility of water reaching the deck is negligible.
    Securing devices are to be of reliable construction and securely attached to the hatchway coamings, decks or hatch covers.
    Individual securing devices on each hatch cover are to have approximately the same stiffness characteristics.
  - **7.3.5** Area of securing devices
    The net cross area of each securing device is to be not less than the value obtained, in cm^2, from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1433.png)
    where:
    *S_S* : Spacing, in m, of securing devices
    $\alpha$ : Coefficient taken equal to:
    $\alpha$ = 0.75 for $R _{eH}$ > 235 $\mathrm{N}/mm ^{2}$
    $\alpha$ = 1.0 for $R _{eH}$ ≤ 235 $\mathrm{N}/mm ^{2}$
    In the above calculations, $R _{eH}$ may not be taken greater than 0.7 *R_m*.
    Between hatch cover and coaming and at cross-joints, a packing line pressure sufficient to obtain weathertightness is to be maintained by securing devices. For packing line pressures exceeding 5 N/mm, the net cross area *A* is to be increased in direct proportion. The packing line pressure is to be specified.
    In the case of securing arrangements which are particularly stressed due to the unusual width of the hatchway, the net cross area *A* of the above securing arrangements is to be determined through direct calculations.
  - **7.3.6** Inertia of edges elements
    The hatch cover edge stiffness is to be sufficient to maintain adequate sealing pressure between securing devices.
    The moment of inertia of edge elements is to be not less than the value obtained, in $\mathrm{cm} ^{4}$, from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1434.png)
    where:
    *p_L* : Packing line pressure, in N/mm, to be taken not less than 5
    *S_S* : Spacing, in m, of securing devices.
  - **7.3.7** Diameter of rods or bolts
    Rods or bolts are to have a gross diameter not less than 19 mm for hatchways exceeding 5 $\mathrm{m}^{ 2}$ in area.
  - **7.3.8** Stoppers
    Hatch covers are to be effectively secured, by means of stoppers, against the transverse forces arising from a pressure of 175 $\mathrm{kN}/m ^{ 2}$.
    With the exclusion of No 1 hatch cover, hatch covers are to be effectively secured, by means of stoppers, against the longitudinal forces acting on the forward end arising from a pressure of 175 $\mathrm{kN}/m ^{ 2}$.
    No 1 hatch cover is to be effectively secured, by means of stoppers, against the longitudinal forces acting on the forward end arising from a pressure of 230 $\mathrm{kN}/m ^{ 2}$. This pressure may be reduced to 175 $\mathrm{kN}/m ^{ 2}$ if a forecastle is fitted in accordance with Sec 1, [7.1].
    The equivalent stress in stoppers, their supporting structures and calculated in the throat of the stopper welds is to be equal to or less than the allowable value, equal to 0.8 $R _{eH}$.
- **7.4** Tarpaulins
  - **7.4.1** *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 15 (11))*
    *Where weathertightness of hatch covers is ensured by means of tarpaulins, at least two layers of tarpaulins are to be fitted.*
    Tarpaulins are to be free from jute and waterproof and are to have adequate characteristics of strength and resistance to atmospheric agents and high and low temperatures.
    The mass per unit surface of tarpaulins made of vegetable fibres, before the waterproofing treatment, is to be not less than:
    • 0.65 $\mathrm{kg}/m ^{2}$ for waterproofing by tarring
    • 0.60 $\mathrm{kg}/m ^{2}$ for waterproofing by chemical dressing
    • 0.55 $\mathrm{kg}/m ^{2}$ for waterproofing by dressing with black oil.
    In addition to tarpaulins made of vegetable fibres, those of synthetic fabrics or plastic laminates may be accepted by the Society provided their qualities, as regards strength, waterproofing and resistance to high and low temperatures, are equivalent to those of tarpaulins made of vegetable fibres.
- **7.5** Cleats
  - **7.5.1** Where rod cleats are fitted, resilient washers or cushions are to be incorporated.
  - **7.5.2** Where hydraulic cleating is adopted, a positive means is to be provided to ensure that it remains mechanically locked in the closed position in the event of failure of the hydraulic system.
- **7.6** Wedges
  - **7.6.1** Wedges
    *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 15 (10))*
    *Wedges are to be of tough wood, generally not more than 200 mm in length and 50 mm in width.*
    *They are generally to be tapered not more than 1 in 6 and their thickness is to be not less than 13 mm.*

#### 8. Drainage

- **8.1** Arrangement
  - **8.1.1** Drainage is to be arranged inside the line of gaskets by means of a gutter bar or vertical extension of the hatch side and end coaming.
  - **8.1.2** Drain openings are to be arranged at the ends of drain channels and are to be provided with efficient means for preventing ingress of water from outside, such as non-return valves or equivalent.
  - **8.1.3** Cross-joints of multi-panel hatch covers are to be arranged with drainage of water from the space above the gasket and a drainage channel below the gasket.
  - **8.1.4** If a continuous outer steel contact is arranged between the cover and the ship’s structure, drainage from the space between the steel contact and the gasket is also to be provided.

#### 9. Small hatches fitted on the exposed fore deck

- **9.1** Application
  - **9.1.1** The requirements of this article apply to steel covers of small hatches fitted on the exposed fore deck over the forward 0.25 *L*, where the height of the exposed deck in way of the hatch is less than 0.1 *L* or 22 m above the summer load waterline, whichever is the lesser.
    Small hatches are hatches designed for access to spaces below the deck and are capable to be closed weather-tight or watertight, as applicable. Their opening is generally equal to or less than 2.5 $\mathrm{m}^{ 2}$.
  - **9.1.2** Small hatches designed for use of emergency escape are to comply with the requirements of this article with exception of [9.4.1] a) and b), [9.4.3] and [9.5.1].
- **9.2** Strength
  - **9.2.1** For small rectangular steel hatch covers, the gross plate thickness, stiffener arrangement and scantlings are to be not less than those obtained, in mm, from Table 4 and Fig 6.
    Ordinary stiffeners, where fitted, are to be aligned with the metal-to-metal contact points, required in [9.3.1] (see also Fig 6).
    Primary stiffeners are to be continuous.
    All stiffeners are to be welded to the inner edge stiffener (see Fig 7).

    | Nominal size<br>(mm × mm) | Cover plate thickness (mm) | Primary stiffeners | Ordinary stiffeners |
    | --- | --- | --- | --- |
    | Nominal size<br>(mm × mm) | Cover plate thickness (mm) | Flat bar (mm × mm); number |   |
    | 630 × 630 | 8 | - | - |
    | 630 × 830 | 8 | 100 × 8 ; 1 | - |
    | 830 × 630 | 8 | 100 × 8 ; 1 | - |
    | 830 × 830 | 8 | 100 × 10 ; 1 | - |
    | 1030 × 1030 | 8 | 120 × 12 ; 1 | 80 × 8 ; 2 |
    | 1330 × 1330 | 8 | 150 × 12 ; 2 | 100 × 10 ; 2 |
  - **9.2.2** The upper edge of the hatchway coamings is to be suitably reinforced by a horizontal section, generally not more than 170 to 190 mm from the upper edge of the coamings.
  - **9.2.3** For small hatch covers of circular or similar shape, the cover plate thickness and reinforcement are to comply with [5.2].
  - **9.2.4** For small hatch covers constructed of materials other than steel, the required scantlings are to provide equivalent strength.
- **9.3** Weathertightness
  - **9.3.1** The hatch cover is to be fitted with a gasket of elastic material. This is to be designed to allow a metal to metal contact at a designed compression and to prevent over compression of the gasket by green sea forces that may cause the securing devices to be loosened or dislodged. The metal-to-metal contacts are to be arranged close to each securing device in accordance with Fig 6 and a sufficient capacity to withstand the bearing force.
- **9.4** Primary securing devices
  - **9.4.1** Small hatches located on exposed fore deck are to be fitted with primary securing devices such their hatch covers can be secured in place and weather-tight by means of a mechanism employing any one of the following methods:
    Dogs (twist tightening handles) with wedges are not acceptable.
    - **a)** butterfly nuts tightening onto forks (clamps)
    - **b)** quick acting cleats
    - **c)** central locking device.
  - **9.4.2** The primary securing method is to be designed and manufactured such that the designed compression pressure is achieved by one person without the need of any tools.
  - **9.4.3** For a primary securing method using butterfly nuts, the forks (clamps) are to be of robust design. They are to be designed to minimize the risk of butterfly nuts being dislodged while in use; by means of curving the forks upward, a raised surface on the free end, or a similar method. The plate thickness of unstiffened steel forks is to be not less than 16 mm. An example arrangement is shown in Fig 7.
  - **9.4.4** For small hatch covers located on the exposed deck forward of the fore-most cargo hatch, the hinges are to be fitted such that the predominant direction of green seas will cause the cover to close, which means that the hinges are normally to be located on the fore edge.
  - **9.4.5** On small hatches located between the main hatches, for example between Nos. 1 and 2, the hinges are to be placed on the fore edge or outboard edge, whichever is practicable for protection from green water in beam sea and bow quartering conditions.
- **9.5** Secondary securing devices
  - **9.5.1** Small hatches on the fore deck are to be fitted with an independent secondary securing device e.g. by means of a sliding bolt, a hasp or a backing bar of slack fit, which is capable of keeping the hatch cover in place, even in the event that the primary securing device became loosened or dislodged. It is to be fitted on the side opposite to the hatch cover hinges.
    ![Fig 6: Arrangement of stiffeners](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1435.png)
    Fig 6: Arrangement of stiffeners
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1436.png)
    1) Butterfly nut
    2) Bolt
    3) Pin
    4) Centre of pin
    5) Fork (clamp) plate
    6) Hatch cover
    7) Gasket
    8) Hatch coaming
    9) Bearing pad welded on the bracket of a toggle bolt for metal to metal contact
    10) Stiffener
    11) Inner edge stiffener.
    Fig 7: Example of a primary securing method


### Section 6 - ARRANGEMENT OF HULL AND SUPERSTRUCTURE OPENINGS

Symbols
For symbols not defined in this Section, refer to Ch 1, Sec 4.
*p* : Lateral pressure for glasses, in $\mathrm{kN}/m ^{ 2}$, defined in [3.3.2].

#### 1. General

- **1.1** Application
  - **1.1.1** The requirements of this Section apply to the arrangement of hull and superstructure openings excluding hatchways, for which the requirements in Ch 9, Sec 5 apply.
- **1.2** Definitions
  - **1.2.1** Standard height of superstructure
    The standard height of superstructure is that defined in Ch 1, Sec 4.
  - **1.2.2** Standard sheer
    The standard sheer is that defined according to the International Load Line Convention, as amended.
  - **1.2.3** Exposed zones
    Exposed zones are the boundaries of superstructures or deckhouses set in from the ship’s side at a distance equal to or less than 0.04 *B*.
  - **1.2.4** Unexposed zones
    Unexposed zones are the boundaries of deckhouses set in from the ship’s side at a distance greater than 0.04 *B*.

#### 2. External openings

- **2.1** General
  - **2.1.1** *Ref. SOLAS Reg.II-1/25-10.1*
    *All external openings leading to compartments assumed intact in the damage analysis, which are below the final damage waterline, are required to be watertight.*
  - **2.1.2** *Ref. SOLAS Reg.II-1/25-10.2*
    *External openings required to be watertight in accordance with [2.1.1] are to be of sufficient strength and, except for cargo hatch covers, are to be fitted with indicators on the bridge.*
  - **2.1.3** No openings, be they permanent openings or temporary openings such as shell doors, windows or ports, are allowed on the side shell between the embarkation station of the marine evacuation system and the waterline in the lightest seagoing condition. Windows and side scuttles of the non-opening type are allowed if the Society’s applicable criteria for fire integrity are complied with.
  - **2.1.4** *Ref. SOLAS Reg.II-1/25-10.5*
    *Other closing appliances which are kept permanently closed at sea to ensure the watertight integrity of external openings are to be provided with a notice affixed to each appliance to the effect that it is to be kept closed. Manholes fitted with closely bolted covers need not be so marked.*
- **2.2** Gangway, cargo and coaling ports
  - **2.2.1** *Ref. SOLAS Reg.II-1/17-1 & Reg.II-1/17.10.1 &.10.2 and ILLC, as amended (Resolution MSC.143(77) Reg. 21(2))*
    *Gangway, cargo and coaling ports fitted below the freeboard deck are to be of sufficient strength. They are to be effectively closed and secured watertight before the ship leaves port, and to be kept closed during navigation.*
    *Such ports are in no case to be so fitted as to have their lowest point below the deepest subdivision load line.*
    *Unless otherwise permitted by the Society, the lower edge of openings is not to be below a line drawn parallel to the freeboard deck at side, which is at its lowest point at least 230 mm above the upper edge of the uppermost load line.*

#### 3. Side scuttles, windows and skylights

- **3.1** General
  - **3.1.1** Application
    The requirements in [3.1] to [3.4] apply to side scuttles and rectangular windows providing light and air, located in positions which are exposed to the action of sea and/or bad weather.
  - **3.1.2** Side scuttle definition
    *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 23(2))*
    *Side scuttles are round or oval openings with an area not exceeding 0.16* $\mathrm{m}^{ 2}$*. Round or oval openings having areas exceeding 0.16* $\mathrm{m}^{ 2}$ *are to be treated as windows.*
  - **3.1.3** Window definition
    *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 23(3))*
    *Windows are rectangular openings generally, having a radius at each corner relative to the window size in accordance with recognised national or international standards, and round or oval openings with an area exceeding 0.16* $\mathrm{m}^{ 2}$*.*
  - **3.1.4** Number of openings in the shell plating
    *Ref. SOLAS Reg.II-1/17-1& Reg.II-1/17.1*
    *The number of openings in the shell plating are to be reduced to the minimum compatible with the design and proper working of the ship.*
  - **3.1.5** Material and scantlings
    *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 23(1))*
    *Side scuttles and windows together with their glasses, deadlights and storm covers, if fitted, are to be of approved design and substantial construction in accordance with, or equivalent to, recognised national or international standards.*
    *Non-metallic frames are not acceptable. The use of ordinary cast iron is prohibited for side scuttles below the freeboard deck.*
  - **3.1.6** Means of closing and opening
    *Ref. SOLAS Reg.II-1/17-1& Reg.II-1/17.2*
    *The arrangement and efficiency of the means for closing any opening in the shell plating are to be consistent with its intended purpose and the position in which it is fitted is to be generally to the satisfaction of the Society.*
  - **3.1.7** Opening of side scuttles
    *Ref. SOLAS Reg.II-1/17-1& Reg.II-1/17.3.2*
    *All side scuttles, the sills of which are below the freeboard deck, are to be of such construction as to prevent effectively any person opening them without the consent of the Master of the ship.*
- **3.2** Opening arrangement
  - **3.2.1** General
    *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 23(5))*
    *Side scuttles are not be fitted in such a position that their sills are below a line drawn parallel to the freeboard deck at side and having its lowest point 0.025 B or 0.5 m, whichever is the greater distance, above the summer load waterline (or timber summer load waterline if assigned).*
  - **3.2.2** Side scuttles below (1.4 + 0.025*B*) m above the water
    *Ref. SOLAS Reg.II-1/17-1& Reg.II-1/17.3.3.1 and.3.3.3*
    *Where in ‘tween decks the sills of any of the side scuttles are below a line drawn parallel to the freeboard deck at side and having its lowest point 1.4 + 0.025 B m above the water when the ship departs from any port, all the side scuttles in that ‘tween decks are to be closed watertight and locked before the ship leaves port, and they may not be opened before the ship arrives at the next port. In the application of this requirement, the appropriate allowance for fresh water may be made when applicable.*
    *For any ship that has one or more side scuttles so placed that the above requirements apply when it is floating at its deepest subdivision load line, the Society may indicate the limiting mean draught at which these side scuttles are to have their sills above the line drawn parallel to the freeboard deck at side, and having its lowest point 1.4 + 0.025 B above the waterline corresponding to the limiting mean draught, and at which it is therefore permissible to depart from port without previously closing and locking them and to open them at sea under the responsibility of the Master during the voyage to the next port. In tropical zones as defined in the International Convention on Load Lines in force, this limiting draught may be increased by 0.3 m.*
  - **3.2.3** Cargo spaces
    *Ref. SOLAS Reg.II-1/17-1& Reg.II-1/17.6.1 to.6.3*
    *No side scuttles may be fitted in any spaces which are appropriated exclusively for the carriage of cargo or coal.*
    *Side scuttles may, however, be fitted in spaces appropriated alternatively for the carriage of cargo or passengers, but they are to be of such construction as to prevent effectively any person opening them or their deadlights without the consent of the Master.*
    *If cargo is carried in such spaces, the side scuttles and their deadlights are to be closed watertight and locked before the cargo is shipped. The Society, at its discretion, may prescribe that the time of closing and locking is to be recorded in a log book.*
  - **3.2.4** Non-opening type side scuttles
    *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 23(6))*
    *Side scuttles are to be of the non-opening type where they become immersed by any intermediate stage of flooding or the final equilibrium waterline in any required damage case for ships subject to damage stability regulations.*
  - **3.2.5** Manholes and flush scuttles
    *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 18(1))*
    *Manholes and flush scuttles in positions 1 or 2, or within superstructures other than enclosed superstructures, are to be closed by substantial covers capable of being made watertight. Unless secured by closely spaced bolts, the covers are to be permanently attached.*
  - **3.2.6** Automatic ventilating scuttles
    *Ref. SOLAS Reg.II-1/17-1& Reg.II-1/17.7*
    *Automatic ventilating side scuttles, fitted in the shell plating below the freeboard deck, are considered by the Society on a case by case basis.*
  - **3.2.7** Window arrangement
    *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 23(7))*
    *Windows are not to be fitted below the freeboard deck, in first tier end bulkheads or sides of enclosed superstructures and in first tier deckhouses considered buoyant in the stability calculations or protecting openings leading below.*
  - **3.2.8** Skylights
    *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 23(12))*
    *Fixed or opening skylights are to have glass thickness appropriate to their size and position as required for side scuttles and windows. Skylight glasses in any position are to be protected from mechanical damage and, where fitted in positions 1 or 2, to be provided with permanently attached robust deadlights or storm covers.*
- **3.3** Glasses
  - **3.3.1** General
    In general, toughened glasses with frames of special type are to be used in compliance with, or equivalent to, recognised national or international standards. The use of clear plate glasses is considered by the Society on a case by case basis.
  - **3.3.2** Design loads
    The design load is to be determined in accordance with the applicable requirements of Ch 9, Sec 4.
  - **3.3.3** Materials
    Toughened glasses are to be in accordance with ISO 1095 for side scuttles and ISO 3254 for windows.
  - **3.3.4** Thickness of toughened glasses in side scuttles
    The thickness of toughened glasses in side scuttles is to be not less than that obtained, in mm, from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1437.png)
    where:
    *d* : Side scuttle diameter, in mm.
  - **3.3.5** Thickness of toughened glasses in rectangular windows
    The thickness of toughened glasses in rectangular windows is to be not less than that obtained, in mm, from the following formula:
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1438.png)
    where:
    $\beta$ : Coefficient defined in Table 1. $\beta$ is to be obtained by linear interpolation for intermediate values of *a/b*
    *a* : Length, in mm, of the longer side of the window
    *b* : Length, in mm, of the shorter side of the window.

    | *a/b* | $\beta$ |
    | --- | --- |
    | 1.0 | 0.284 |
    | 1.5 | 0.475 |
    | 2.0 | 0.608 |
    | 2.5 | 0.684 |
    | 3.0 | 0.716 |
    | 3.5 | 0.734 |
    | ≥ 4.0 | 0.750 |

    The Society may require both limitations on the size of rectangular windows and the use of glasses of increased thickness in way of front bulkheads which are particularly exposed to heavy sea.
- **3.4** Deadlight arrangement
  - **3.4.1** General
    *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 23(4))*
    *Side scuttles to the following spaces are to be fitted with hinged inside deadlights:*
    *• spaces below freeboard deck*
    *• spaces within the first tier of enclosed superstructures*
    *• first tier deckhouses on the freeboard deck protecting openings leading below or considered buoyant in stability calculations.*
    *Deadlights are to be capable of being closed and secured watertight if fitted below the freeboard deck and weathertight if fitted above.*
  - **3.4.2** Openings at the side shell in the second tier
    *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 23(8))*
    *Side scuttles and windows at the side shell in the second tier are to be provided with efficient, hinged inside deadlights capable of being closed and secured weathertight, if the superstructure protects direct access to an opening leading below or is considered buoyant in the stability calculations.*
  - **3.4.3** Openings set inboard in the second tier
    *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 23(9) and.23(10))*
    *Side scuttles and windows in side bulkheads set inboard from the side shell in the second tier which protect direct access below to spaces listed in [3.4.1], are to be provided with either hinged inside deadlights or, where they are accessible, permanently attached external storm covers of approved design and substantial constructioncapableofbeingclosedandsecuredweathertight.*
    *Cabin bulkheads and doors in the second tier and above separating side scuttles and windows from a direct access leading below or the second tier considered buoyant in the stability calculations may be accepted in place of deadlights or storm covers fitted to the side scuttles and windows.*
    Note 1: Deadlights in accordance with recognised standards are fitted to the inside of windows and side scuttles, while storm covers of comparable specifications to deadlights are fitted to the outside of windows, where accessible, and may be hinged or portable.
  - **3.4.4** Deckhouses on superstructures of less than standard height
    *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 23(11))*
    *Deckhouses situated on a raised quarter deck or on the deck of a superstructure of less than standard height may be regarded as being in the second tier as far as the requirements for deadlights are concerned, provided the height of the raised quarterdeck or superstructure is equal to or greater than the standard quarter deck height.*
  - **3.4.5** Openings protected by a deckhouse
    Where an opening in a superstructure deck or in the top of a deckhouse on the freeboard deck which gives access to a space below the freeboard deck or to a space within an enclosed superstructure is protected by a deckhouse, then it is considered that only those side scuttles fitted in spaces which give direct access to an open stairway need to be fitted with deadlights.

#### 4. Discharges

- **4.1** Arrangement of discharges
  - **4.1.1** Inlets and discharges
    *Ref. SOLAS Reg.II-1/17-1 & Reg.II-1/17.9.1*
    *All inlets and discharges in the shell plating are to be fitted with efficient and accessible arrangements for preventing the accidental admission of water into the ship.*
  - **4.1.2** Inboard opening of ash-shoot, rubbish-shoot, etc.
    *Ref. SOLAS Reg.II-1/17-1 & Reg.II-1/17.11.1 and.11.2*
    *The inboard opening of each ash-shoot, rubbish-shoot, etc. is to be fitted with an efficient cover.*
    *If the inboard opening is situated below the freeboard deck, the cover is to be watertight, and in addition an automatic non-return valve is to be fitted in the shoot in an easily accessible position above the deepest subdivision load line. When the shoot is not in use, both the cover and the valve are to be kept closed and secured.*
- **4.2** Arrangement of garbage chutes
  - **4.2.1** Inboard end above the waterline
    *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 22-1(1, b))*
    *The inboard end is to be located above the waterline formed by an 8.5° heel, to port or starboard, at a draft corresponding to the assigned summer freeboard, but not less than 1000 mm above the summer load waterline.*
    *Where the inboard end of the garbage chute exceeds 0.01 L above the summer load waterline, valve control from the freeboard deck is not required, provided the inboard gate valve is always accessible under service conditions.*
  - **4.2.2** Inboard end below the waterline
    *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 22-1(4))*
    *Where the inboard end of a garbage chute is below the waterline corresponding to the deepest draught after damage in a ship of more than 100 m in length, then:*
    *• the inboard end hinged cover/valve is to be watertight*
    *• the valve is to be a screw-down non-return valve fitted in an easily accessible position above the deepest subdivision load line*
    *• the screw-down non-return valve is to be controlled from a position above the freeboard deck and provided with open/shut indicators. The valve control is to be clearly marked: «Keep closed when not in use».*
  - **4.2.3** Gate valves
    *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 22-1(1, a))*
    *For garbage chutes, two gate valves controlled from the working deck of the chute may be accepted instead of a non-return valve with a positive means of closing it from a position above the freeboard deck. In addition, the lower gate valve is to be controlled from a position above the freeboard deck. An interlock system between the two valves is to be arranged.*
    *The distance between the two gate valves is to be adequate to allow the smooth operation of the interlock system.*
  - **4.2.4** Hinged cover and discharge flap
    *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 22-1(1, c))*
    *The upper and lower gate valves, as required in [4.2.3], may be replaced by a hinged weathertight cover at the inboard end of the chute together with a discharge flap.*
    *The cover and discharge flap are to be arranged with an interlock so that the flap cannot be operated until the hopper cover is closed.*
  - **4.2.5** Marking of valve and hinged cover
    *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 22-1(3))*
    *The controls for the gate valves and/or hinged covers are to be clearly marked: «Keep closed when not in use».*
- **4.3** Scantlings of garbage chutes
  - **4.3.1** Material
    The chute is to be constructed of steel. Other equivalent materials are considered by the Society on a case by case basis.
  - **4.3.2** Wall thickness
    The wall thickness of the chute up to and including the cover is to be not less than that obtained, in mm, from Table 2.

    | External diameter *d*, in mm | Thickness, in mm |
    | --- | --- |
    | *d* ≤ 80 | 7.0 |
    | 80 < *d* < 180 | 7.0 + 0.03(*d* - 80) |
    | 180 ≤ *d* ≤ 220 | 10.0 + 0.063(*d* - 180) |
    | *d* > 220 | 12.5 |

#### 5. Freeing ports

- **5.1** General provisions
  - **5.1.1** General
    *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 24 (1, a) and Reg.3 (15))*
    *Where bulwarks on the weather portions of freeboard or superstructure decks form wells, ample provision is to be made for rapidly freeing the decks of water and for draining them.*
    *A well is any area on the deck exposed to the weather, where water may be entrapped. Wells are considered to be deck areas bounded on four sides by deck structures; however, depending on their configuration, deck areas bounded on three or even two sides by deck structures may be deemed wells.*
  - **5.1.2** Freeing port areas
    *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 24)*
    *The minimum required freeing port areas in bulwarks on the freeboard deck are specified in Table 3.*

    | Ship types or ship particulars | Area $A$ of freeing ports, in $\mathrm{m}^{ 2}$ | Applicable requirement |
    | --- | --- | --- |
    | Type B-100 | 0.33 $\ell _{B} h _{B}$ | [5.5.2] |
    | Type B-60 | 0.25 $\ell _{B} h _{B}$ | [5.5.1] |
    | Ships fitted with a trunk included in freeboard calculation and/ or breadth ≥ 0.6 *B* | 0.33 $\ell _{B} h _{B}$ | [5.3.1] |
    | Ships fitted with a trunk not included in freeboard calculation and/or continuous or substantially continuous hatch coamings | $A _{2}$ | [5.3.1] |
    | Ships fitted with non-continuous trunk and/or hatch coamings | $A _{3}$ | [5.3.2] |
    | Ships fitted with open superstructure | $A _{S}$ for superstructures | [5.4.2] |
    | Ships fitted with open superstructure | $A _{W}$ for wells | [5.4.3] |
    | Other ships | $A _{1}$ | [5.2.1] |
    | where:<br>$\ell _{B}$ : Length, in m, of bulwark in a well at one side of the ship<br>$h _{B}$ : Mean height, in m, of bulwark in a well of length $\ell _{B}$. |   |   |
  - **5.1.3** Freeing port arrangement
    *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 24 (5))*
    *Where a sheer is provided, two thirds of the freeing port area required is to be provided in the half of the well nearer the lowest point of the sheer curve.*
    *One third of the freeing port area required is to be evenly spread along the remaining length of the well. With zero or little sheer on the exposed freeboard deck or an exposed superstructure deck the freeing port area is to be evenly spread along the length of the well.*
    *However, bulwarks may not have substantial openings or accesses near the breaks of superstructures, unless they are effectively detached from the superstructure sides.*
  - **5.1.4** Freeing port positioning
    *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 24 (5) and 24 (6))*
    *The lower edge of freeing ports is to be as near the deck as practicable.*
    *All the openings in the bulwark are to be protected by rails or bars spaced approximately 230 mm apart.*
  - **5.1.5** Freeing port closures
    *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 24 (6))*
    *If shutters or closures are fitted to freeing ports, ample clearance is to be provided to prevent jamming. Hinges are to have pins or bearings of non-corrodible material. If shutters are fitted with securing appliances, these appliances are to be of approved construction.*
- **5.2** Freeing port area in a well not adjacent to a trunk or hatchways
  - **5.2.1** Freeing port area
    *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 24 (1, b and c))*
    *Where the sheer in way of the well is standard or greater than the standard, the freeing port area on each side of the ship for each well is to be not less than that obtained, in* $\mathrm{m}^{ 2}$*, in Table 4.*
    *In ships with no sheer, the above area is to be increased by 50 %. Where the sheer is less than the standard, the percentage of increase is to be obtained by linear interpolation.*

    | Location | Area $A _{1}$ of freeing ports, in $\mathrm{m}^{ 2}$ |   |
    | --- | --- | --- |
    |   | $\ell _{B}$ ≤ 20 | $\ell _{B}$ > 20 |
    | Freeboard deck and raised quarterdecks | 0.7 + 0.035 $\ell _{B}$ + $A _{C}$ | 0.07 $\ell _{B}$ + $A _{C}$ |
    | Superstructure decks | 0.35 + 0.0175 $\ell _{B}$ + 0.5$A _{C}$ | 0.035 $\ell _{B}$ + 0.5$A _{C}$ |
    | where:<br>$\ell _{B}$ : Length, in m, of bulwark in the well, but need in no case to be taken as greater than 0.7 $L _{LL}$<br>$A _{C}$ : Area, in $\mathrm{m}^{ 2}$, to be taken, with its sign, equal to:<br>![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1439.png)<br>$h _{B}$ : Mean height, in m, of the bulwark in a well of length $\ell _{B}$. |   |   |
  - **5.2.2** Minimum freeing port area for a deckhouse having breadth not less than 0.8 *B*
    *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 24 (1, d))*
    *Where a flush deck ship is fitted amidships with a deckhouse having breadth not less than 0.8 B and the width of the passageways along the side of the ship less than 1.5 m, the freeing port area is to be calculated for two separate wells, before and abaft the deckhouse. For each of these wells, the freeing port area is to be obtained from Table 4, where* $\ell _{B}$ *is to be taken equal to the actual length of the well considered.*
  - **5.2.3** Minimum freeing port area for screen bulkhead
    *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 24 (1, e))*
    *Where a screen bulkhead is fitted across the full breadth of the ship at the fore end of a midship deckhouse, the weather deck is to be considered as divided into two wells, irrespective of the width of the deckhouse, and the freeing port area is to be obtained in accordance with [5.1.2].*
- **5.3** Freeing port area in a well contiguous to a trunk or hatchways
  - **5.3.1** Freeing area for continuous trunk or continuous hatchway coaming
    *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 24 (2))*
    *Where the ship is fitted with a continuous trunk not included in the calculation of freeboard or where continuous or substantially continuous hatchway side coamings are fitted between detached superstructures, the freeing port area is to be not less than that obtained, in* $\mathrm{m}^{ 2}$*, from Table 5.*

    | Breadth $B _{H}$, in m, of hatchway or trunk | Area $A _{2}$ of freeing ports, in $\mathrm{m}^{ 2}$ |
    | --- | --- |
    | $B _{H}$ ≤ 0.4 *B* | 0.2 $\ell _{B} h _{B}$ |
    | 0.4B < $B _{H}$ < 0.75 *B* | ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1440.png) |
    | $B _{H}$ ≥ 0.75 *B* | 0.1 $\ell _{B} h _{B}$ |
    | where:<br>$\ell _{B}$ : Length, in m, of bulwark in a well at one side of the ship<br>$h _{B}$ : Mean height, in m, of bulwark in a well of length $\ell _{B}$. |   |

    Where the ship is fitted with a continuous trunk having breadth not less than 0.6 *B*, included in the calculation of freeboard, and where open rails on the weather parts of the freeboard deck in way of the trunk for at least half the length of these exposed parts are not fitted, the freeing port area in the well contiguous to the trunk is to be not less than 33 % of the total area of the bulwarks.
  - **5.3.2** Freeing area for non-continuous trunk or hatchway coaming
    *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 24 (3))*
    *Where the free flow of water across the deck of the ship is impeded due to the presence of a non-continuous trunk, hatchway coaming or deckhouse in the whole length of the well considered, the freeing port area in the bulwark of this well is to be not less than that obtained, in* $\mathrm{m}^{ 2}$*, from Table 6.*

    | Free flow area $f _{P}$, in $\mathrm{m}^{ 2}$ | Freeing port area $A _{3}$, in $\mathrm{m}^{ 2}$ |
    | --- | --- |
    | $f _{P}$ ≤ $A _{1}$ | $A _{2}$ |
    | $A _{1}$ < $f _{P}$ < $A _{2}$ | $A _{1}$ + $A _{2}$ - $f _{P}$ |
    | $f _{P}$ ≥ $A _{2}$ | $A _{1}$ |
    | where:<br>$f _{P}$ : Free flow area on deck, equal to the net area of gaps between hatchways, and between hatchways and superstructures and deckhouses up to the actual height of the bulwark<br>$A _{1}$ : Area of freeing ports, in $\mathrm{m}^{ 2}$, to be obtained from Table 4<br>$A _{2}$ : Area of freeing ports, in $\mathrm{m}^{ 2}$, to be obtained from Table 5. |   |
- **5.4** Freeing port area in an open space within superstructures
  - **5.4.1** General
    *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 24 (4))*
    *In ships having superstructures on the freeboard or superstructure decks, which are open at either or both ends to wells formed by bulwarks on the open decks, adequate provision for freeing the open spaces within the superstructures is to be provided.*
  - **5.4.2** Freeing port area for open superstructures
    *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 24 (4))*
    *The freeing port area on each side of the ship for the open superstructure is to be not less than that obtained, in* $\mathrm{m}^{ 2}$*, from the following formula:*
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1441.png)
    *where:*
    $\ell _{T}$ *: Total well length, in m, to be taken equal to:*
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1442.png)
    $\ell _{W}$ *: Length, in m, of the open deck enclosed by bulwarks*
    $\ell _{S}$ *: Length, in m, of the common space within the open superstructures*
    $A _{1}$ *: Freeing port area, in* $\mathrm{m}^{ 2}$*, required for an open well of length* $\ell _{T}$*, in accordance with Table 4, where* $A _{C}$ *is to be taken equal to zero*
    $C _{SH}$ *: Coefficient which accounts for the absence of sheer, if applicable, to be taken equal to:*
    $C _{SH}$ *= 1.0 in the case of standard sheer or sheer greater than standard sheer*
    $C _{SH}$ *= 1.5 in the case of no sheer*
    $b _{0}$ *: Breadth, in m, of the openings in the end bulkhead of enclosed superstructures*
    $h _{S}$ *: Standard superstructure height, in m, defined in [1.2.1]*
    $h _{W}$ *: Distance, in m, of the well deck above the freeboard deck.*
  - **5.4.3** Freeing port area for open well
    *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 24 (4))*
    *The freeing port area on each side of the ship for the open well is to be not less than that obtained, in* $\mathrm{m}^{ 2}$*, from the following formula:*
    ![](https://kr-rule.krs.co.kr/Files/Document/RA-11-E/2014/image1443.png)
    $A _{1}$ : *Freeing port area, in* $\mathrm{m}^{ 2}$*, required for an open well of length* $\ell _{W}$*, in accordance with* *Table 4*
    *c_SH*, *h_S*, *h_W*, $\ell _{W}$ : *Defined in* *[5.4.2].*
    *The resulting freeing port areas for the open superstructure* $A _{S}$ *and for the open well* $A _{W}$ *are to be provided along each side of the open space covered by the open superstructure and each side of the open well, respectively.*
- **5.5** Freeing port area in bulwarks of the freeboard deck for ships of types B-100 and B-60
  - **5.5.1** Freeing arrangement for type B-60
    For type B-60 ships, the freeing port area in the lower part of the bulwarks of the freeboard deck is to be not less than 25 % of the total area of the bulwarks in the well considered.
    The upper edge of the sheer strake is to be kept as low as possible.
  - **5.5.2** Freeing arrangement for type B-100 ships with trunks
    For type B-100 ships, open rails are to be fitted on the weather parts of the freeboard deck in way of the trunk for at least half the length of these exposed parts.
    Alternatively, if a continuous bulwark is fitted, the freeing port area in the lower part of the bulwarks of the freeboard deck is to be not less than 33 % of the total area of the bulwarks in the well considered.

#### 6. Machinery space openings

- **6.1** Engine room skylights
  - **6.1.1** Engine room skylights in positions 1 or 2 are to be properly framed, securely attached to the deck and efficiently enclosed by steel casings of suitable strength. Where the casings are not protected by other structures, their strength will be considered by the Society on a case by case basis.
- **6.2** Closing devices
  - **6.2.1** Machinery casings
    *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 17 (1)and 12 (1))*
    *Openings in machinery space casings in positions 1 or 2 are to be fitted with doors of steel or other equivalent materials, permanently and strongly attached to the bulkhead, and framed, stiffened and fitted so that the whole structure is of equivalent strength to the unpierced bulkhead and weathertight when closed. The doors are to be capable of being operated from both sides and generally to open outwards to give additional protection against wave impact.*
    *Other openings in such casings are to be fitted with equivalent covers, permanently attached in their proper position.*
  - **6.2.2** Height of the sill of the door
    *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 17 (1 and 2))*
    *The height of the sill of the door is to be not less than:*
    *• 600 mm above the deck if in position 1*
    *• 380 mm above the deck if in position 2*
    *• 230 mm in all other cases.*
  - **6.2.3** Double doors
    *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 17 (1 and 2))*
    *Where casings are not protected by other structures, double doors (i.e. inner and outer doors) are required for ships assigned freeboard less than that based on Table B of the International Load Line Convention, as amended. An inner sill of 230 mm in conjunction with the outer sill of 600 mm is to be provided.*
  - **6.2.4** Fiddly openings
    *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 17 (5))*
    *Fiddly openings are to be fitted with strong covers of steel or other equivalent material permanently attached in their proper positions and capable of being secured weathertight.*
- **6.3** Coamings
  - **6.3.1** *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 17 (3))*
    *Coamings of any fiddly, funnel or machinery space ventilator in an exposed position on the freeboard deck or superstructure deck are to be as high above the deck as is reasonable and practicable.*
    *In general, ventilators necessary to continuously supply the machinery space and, on demand, the emergency generator room are to have coamings whose height is in compliance with [8.1.3], but need not be fitted with weathertight closing appliances.*
  - **6.3.2** *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 17 (4))*
    *Where, due to the ship’s size and arrangement, this is not practicable, lesser heights for machinery space and emergency generator room ventilator coamings, fitted with weathertight closing appliances in accordance with [8.1.2], may be permitted by the Society in combination with other suitable arrangements to ensure an uninterrupted, adequate supply of ventilation to these spaces.*

#### 7. Companionway

- **7.1** General
  - **7.1.1** Openings in freeboard deck
    *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 18 (2))*
    *Openings in freeboard deck other than hatchways, machinery space openings, manholes and flush scuttles are to be protected by an enclosed superstructure or by a deckhouse or companionway of equivalent strength and weathertightness.*
  - **7.1.2** Openings in superstructures
    *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 18 (2))*
    *Openings in an exposed superstructure deck or in the top of a deckhouse on the freeboard deck which give access to a space below the freeboard deck or a space within an enclosed superstructure are to be protected by an efficient deckhouse or companionway.*
  - **7.1.3** Openings in superstructures having height less than standard height
    *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 18 (3))*
    *Openings in the top of a deckhouse on a raised quarterdeck or superstructure of less than standard height, having a height equal to or greater than the standard quarterdeck height are to be provided with an acceptable means of closing but need not be protected by an efficient deckhouse or companionway provided the height of the deckhouse is at least the height of the superstructure. Openings in the top of the deckhouse on a deckhouse of less than a standard superstructure height may be treated in a similar manner.*
- **7.2** Scantlings
  - **7.2.1** Companionways on exposed decks protecting openings leading into enclosed spaces are to be of steel and strongly attached to the deck and are to have adequate scantlings.
- **7.3** Closing devices
  - **7.3.1** Doors
    *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 18 (2))*
    *Doorways in deckhouses or companionways leading to or giving access to spaces below the freeboard deck or to enclosed superstructures are to be fitted with weathertight doors. The doors are to be made of steel, to be capable of being operated from both sides and generally to open outwards to give additional protection against wave impact.*
    *Alternatively, if stairways within a deckhouse are enclosed within properly constructed companionways fitted with weathertight doors, the external door need not be weathertight.*
    *Where the closing appliances of access openings in superstructures and deckhouses are not weathertight, interior deck openings are to be considered exposed, i.e. situated in the open deck.*
  - **7.3.2** Height of sills
    *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 18 (4 to 6))*
    *The height above the deck of sills to the doorways in companionways is to be not less than:*
    *• 600 mm in position 1*
    *• 380 mm in position 2.*
    *Where access is provided from the deck above as an alternative to access from the freeboard deck, the height of the sills into the bridge or poop is to be 380 mm. This also applies to deckhouses on the freeboard deck.*
    *Where access is not provided from above, the height of the sills to doorways in deckhouses on the freeboard deck is to be 600 mm.*

#### 8. Ventilators

- **8.1** Closing appliances
  - **8.1.1** General
    *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 19 (4))*
    *Ventilator openings are to be provided with efficient weathertight closing appliances of steel or other equivalent material.*
  - **8.1.2** Closing appliance exemption
    *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 19 (3))*
    *Ventilators need not be fitted with closing appliances, unless specifically required by the Society, if the coamings extend for more than:*
    *• 4.5 m above the deck in position 1*
    *• 2.3 m above the deck in position 2.*
  - **8.1.3** Closing appliances for ships of not more than 100 m in length
    *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 19 (4))*
    *In ships of not more than 100 m in length, the closing appliances are to be permanently attached to the ventilator* *coamings.*
  - **8.1.4** Closing appliances for ships of more than 100 m in length
    *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 19 (4))*
    *Where, in ships of more than 100 m in length, the closing appliances are not permanently attached, they are to be conveniently stowed near the ventilators to which they are to be fitted.*
  - **8.1.5** Ventilation of machinery spaces and emergency generator room
    In order to satisfactorily ensure, in all weather conditions:
    • the continuous ventilation of machinery spaces,
    • and, when necessary, the immediate ventilation of the emergency generator room,
    the ventilators serving such spaces are to comply with [8.1.2], i.e. their openings are to be so located that they do not require closing appliances.
  - **8.1.6** Reduced height of ventilator coamings for machinery spaces and emergency generator room
    Where, due to the ship’s size and arrangement, the requirements in [8.1.5] are not practicable, lesser heights may be accepted for machinery space and emergency generator room ventilator coamings fitted with weathertight closing appliances in accordance with [8.1.1], [8.1.3] and [8.1.4] in combination with other suitable arrangements, such as separators fitted with drains, to ensure an uninterrupted, adequate supply of ventilation to these spaces.
  - **8.1.7** Closing arrangements of ventilators led overboard or through enclosed superstructures
    Closing arrangements of ventilators led overboard to the ship side or through enclosed superstructures are considered by the Society on a case by case basis. If such ventilators are led overboard more than 4.5 m above the freeboard deck, closing appliances may be omitted provided that satisfactory baffles and drainage arrangements are fitted.
- **8.2** Coamings
  - **8.2.1** General
    *Ref. ILLC, as amended (Resolution MSC.143(77) Reg. 19 (1 and 2))*
    *Ventilators in positions 1 or 2 to spaces below freeboard decks or decks of enclosed superstructures are to have coamings of steel or other equivalent material, substantially constructed and efficiently connected to the deck.*
    *Ventilators passing through superstructures other than enclosed superstructures are to have substantially constructed coamings of steel or other equivalent material at the freeboard deck.*
  - **8.2.2** Scantlings
    The scantlings of ventilator coamings exposed to the weather are to be not less than those obtained from Table 7.
    In exposed locations or for the purpose of compliance with buoyancy calculations, the height of coamings may be required to be increased to the satisfaction of the Society.

    | Feature | Scantlings |
    | --- | --- |
    | Height of the coaming, in mm, above the deck | *h* = 900 in position 1<br>*h* = 760 in position 2 |
    | Thickness of the coaming, in mm<sup>(1)</sup> | *t* = 5.5 + 0.01$d _{V}$<br>with 7.5 ≤ *t* ≤ 10 |
    | Support | If *h* > 900 mm, the coaming is to be suitably stiffened or supported by stays. |
    | where:<br>$d _{V}$ : External diameter of the ventilator, in mm.<br><sup>(1)</sup> Where the height of the ventilator exceeds the height h, the thickness of the coaming may be gradually reduced, above that height, to a minimum of 6.5 mm. |   |

#### 9. Tank cleaning openings

- **9.1** General
  - **9.1.1** Ullage plugs, sighting ports and tank cleaning openings may not be arranged in enclosed spaces. ![](images/image9.png)
