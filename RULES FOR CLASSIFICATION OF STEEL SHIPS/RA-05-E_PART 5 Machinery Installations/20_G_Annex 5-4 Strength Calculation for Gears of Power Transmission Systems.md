# PART 5 Machinery Installations

> RULES FOR CLASSIFICATION OF STEEL SHIPS / RA-05-E / 2025 / EN / Guidance

## Annex 5-4 Strength Calculation for Gears of Power Transmission Systems

### 1. General

#### (1) Application

This Guidance is to apply to enclosed gear used for transmission system which transmit power from main propulsion machinery and prime movers driving generators and essential auxiliaries(excluding auxiliary machinery for specific use etc.).

#### (2) Basic principles

- **(A)** The methods for calculation of strength of gears specified in this Guidance deal with surface durability(pitting) and tooth root bending strength.
- **(B)** All influence factors related to strength are defined regarding their physical interpretation. Some of the influence factors are determined by the gear geometry or have been established by conventions. Other factors, which are approximations, can be calculated according to methods acceptable to the Society.


### 5. General influence factors

#### (1) Application factor, _s2

The application factor accounts for dynamic overloads from sources external to the gearing, and is defined as the ratio between the maximum repetitive cyclic torque applied to the gear set and the nominal rated torque, and is in accordance with the **Table 1**. However, where the calculation sheets or data are submitted or the factor is measured actually, the value may be applied according to the discretion of the Society. The factor mainly depends on:
- characteristics of driving and driven machines
- ratio of masses
- type of couplings
- operating conditions (overspeeds, changes in propeller load conditions, etc.)

#### (2) Load sharing factor, _s2

The load sharing factor which accounts for the maldistribution of load in multiple path transmissions (dual tandem, epicycle, double helix, etc.), is defined as the ratio between the maximum load through an actual path and the evenly shared load, and is in accordance with the **Table 2**. However, where the calculation sheets or data are submitted or the factor is measured actually, the value may be applied according to the discretion of the Society.

| Driving engine | Construction or method of connection | $K _{A}$ |
| --- | --- | --- |
| Main propulsion | Reciprocating internal combustion engine with hydraulic or electromagnetic slip coupling | 1.00 |
| Main propulsion | Reciprocating internal combustion engine with high elasticity coupling | 1.30 |
| Main propulsion | Reciprocating internal combustion engine with other couplings | 1.50 |
| Auxiliary | Electric motor, reciprocating internal combustion engine with hydraulic or electromagnetic slip coupling | 1.00 |
| Auxiliary | Reciprocating internal combustion engine with high elasticity coupling | 1.20 |
| Auxiliary | Reciprocating internal combustion engine with other couplings | 1.40 |

| Planetary gears | $K _{\gamma }$ |
| --- | --- |
| up to 3 | 1.0 |
| 4 | 1.2 |
| 5 | 1.3 |
| 6 and over | 1.4 |

#### (3) Internal Dynamic factor, _s2

The dynamic factor which accounts for internally generated dynamic loads due to vibrations of pinion and wheel against each other, is defined as the ratio between the maximum load which dynamically acts on the tooth flanks and the maximum externally applied load ($F _{t} K _{A} K _{\gamma }$). The factor mainly depends on followings.
- transmission errors (depending on pitch and profile errors)
- masses of pinion and wheel
- gear mesh stiffness variation as the gear teeth pass through the meshing cycle
- transmitted load including application factor
- pitch line velocity
- dynamic unbalance of gears and shaft
- shaft and bearing stiffness
- damping characteristics of the gear system

- **(A)** Application
  - **(a)** In case of all the following conditions are satisfied.
  - **(i)** running velocity in the subcritical range:
    $\frac{v \cdot z _{1}}{100} \sqrt {\frac{u ^{2}}{1+u ^{2}}} <10 \mathrm{m}/s$
    - **(ii)** spur gears ($\beta =0 {}^{\circ}$) and helical gears with $\beta \leq 30 {}^{\circ}$
    - **(iii)** pinion with relatively low number of teeth, $z _{1} <50$
    - **(iv)** solid disc wheels or heavy steel gear rim
  - **(b)** all types of gears if $\frac{v \cdot z _{1}}{100} \sqrt {\frac{u ^{2}}{1+u ^{2}}} <3\mathrm{m}/s$ as well as to helical gears where $\beta >30 {}^{\circ}$.
  - **(c)** For gears other than (a), (b), reference is to be made to Method B outlined in the reference standard ISO 6336-1:2019.
- **(B)** Calculation formula
  - **(a)** For spur gears and for helical gears with overlap ratio $\varepsilon _{\beta } \geq 1$
    $K _{V} =1+ \left( \frac{K _{1}}{K _{A} \frac{F _{t}}{b}} +K _{2} \right) \cdot \frac{v \cdot z _{1}}{100} K _{3} \sqrt {\frac{u ^{2}}{1+u ^{2}}}$
    If $K _{A} \frac{F _{t}}{b} <100$ (N/mm), this value is assumed to $K _{A} \frac{F _{t}}{b} =100$ (N/mm).
    Numerical values for the factor $K _{1}$ are to be as specified in the **Table 3**.

    | Kind of gear | $K _{1}$ (ISO grades of accuracy*) |   |   |   |   |   |
    | --- | --- | --- | --- | --- | --- | --- |
    | Kind of gear | 3 | 4 | 5 | 6 | 7 | 8 |
    | Spur gear | 2.1 | 3.9 | 7.5 | 14.9 | 26.8 | 39.1 |
    | Helical gear | 1.9 | 3.5 | 6.7 | 13.3 | 23.9 | 34.8 |
    | NOTE<br>* ISO grades of accuracy according to ISO 1328-1:2013. In case of mating gears with different grades of accuracy the grade corresponding to the lower accuracy is to be used. |   |   |   |   |   |   |

    For all accuracy grades the factor $K _{2}$ is to be in accordance with the following.
    For spur gears, $K _{2} =0.0193$
    For helical gears, $K _{2} =0.0087$
    Factor $K _{3}$ is to be in accordance with the following.
    If $\frac{v \cdot z _{1}}{100} \sqrt {\frac{u ^{2}}{1+u ^{2}}} \leq 0.2$ then $K _{3} =2.0$
    If $\frac{v \cdot z _{1}}{100} \sqrt {\frac{u ^{2}}{1+u ^{2}}} >0.2$ then $K _{3} =2.071-0.357 \cdot \frac{v \cdot z _{1}}{100} \sqrt {\frac{u ^{2}}{1+u ^{2}}}$
  - **(b)** For helical gears with overlap ratio $\varepsilon _{\beta } <1$ the value $K _{V}$ is determined by linear interpolation between values determined for spur gears ($K _{V \alpha }$) and helical gears ($K _{V \beta }$) in accordance with:
    $K _{V} =K _{V \alpha } - \varepsilon _{\beta } (K _{V \alpha } -K _{V \beta } )$
    Where,
    $K _{V \alpha }$ is the $K _{V}$ value for spur gears, in accordance with (a).
    $K _{V \beta }$ is the $K _{V}$ value for helical gears, in accordance with (a).

#### (4) Face load distribution factors _s2

The face load distribution factors, $K _{H \beta } ,$ for contact stress, $K _{F \beta } ,$ for tooth root bending stress, account for the effect of non-uniform distribution of load across the facewidth. $K _{H \beta }$ and $K _{F \beta }$ are defined as follows:
$K _{H \beta } = \frac{Maximum load per unit face width}{Mean load per unit face width}$
$K _{F \beta } = \frac{Maximum bending stress at t ooth roo t per unit face width}{Mean bending stress at t ooth roo t per unit face width}$
The mean bending stress at tooth root relates to the considered face width. $K_F _\beta$ can be expressed as a function of the factor $K_H _\beta$. The factors $K_H _\beta$ and $K_F _\beta$ mainly depend on:
- gear tooth manufacturing accuracy
- errors in mounting due to bore errors
- bearing clearances
- wheel and pinion shaft alignment errors
- elastic deflections of gear elements, shafts, bearings, housing and foundations which support the gear elements
- thermal expansion and distortion due to operating temperature
- compensating design elements (tooth crowning, end relief, etc.)
The face load distribution factors, $K _{H \beta } ,$ for contact stress, and $K _{F \beta }$ for tooth root bending stress, are to be determined according to the Method *C* outlined in the ISO 6336-1:2019 standard. However, where the calculation sheets or data are submitted or the factors are measured actually, the values may be applied according to the discretion of the Society.

- **(A)** In case the hardest contact is at the end of the face width $K _{F \beta }$ is given by the following equations.
  $K _{F \beta } =K _{H \beta } ^{} ^{N}$
  $N= \frac{(b/h) ^{2}}{1+(b/h)+(b/h) ^{2}}$
  $b/h$ : face width/tooth height ratio, the minimum of $b _{1} /h _{1}$ or $b _{2} /h _{2}$.
  (For double helical gears, the face width of only one helix is to be used.
  When $b/h$<3 the value $b/h$=3 is to be used.)
- **(B)** In case of gears where the ends of the face width are lightly loaded or unloaded (end relief or crowning).
  $K_{F \beta} = K_{H \beta}$

#### (5) Transverse load distribution factors for surface durability and bending strength, _s2, _s2

The transverse load distribution factors, $K _{H \alpha }$ for contact stress and $K _{F \alpha }$ for tooth root bending stress, account for the effects of pitch and profile errors on the transversal load distribution between two or more pairs of teeth in mesh, and are to be determined according to Method B outlined in ISO 6336-1:2019. However, where the calculation sheets or data are submitted or the factors are measured actually, the values may be applied according to the discretion of the Society. The factors $K _{H \alpha }$ and $K _{F \alpha }$ mainly depend on followings.
- total mesh stiffness
- total tangential load $F _{t}$, $K _{A}$, $K _{\gamma }$, $K _{V}$, $K _{H \beta }$
- base pitch error
- tip relief
- running-in allowances


### 6. Surface durability

The criterion for surface durability is based on the Hertz pressure on the operating pitch point or at the inner point of single pair contact. The contact stress $\sigma _{H}$ is to be equal to or less than the permissible contact stress $\sigma _{HP}$.

#### (1) Basic equations

- **(A)** Contact stress, $\sigma_H$
  $\sigma _{H} = \sigma _{H0} \sqrt {K _{A} K _{\gamma } K _{V} K _{H \alpha } K _{H \beta }} \leq \sigma _{HP}$
  $\sigma _{H0} =Z _{B} Z _{H} Z _{E} Z _{\varepsilon } Z _{\beta } \sqrt {\frac{F _{t}}{d _{1} b} \frac{u+1}{u}}$: Pinion
  $\sigma_H0 = Z_D Z_H Z_E Z_\varepsilon Z_\beta \sqrt{F_\frac{t}{d_1 b} u+\frac{1}{u}$: Wheel
  $\sigma _{Ho}$ : Basic value of contact stress for pinion and wheel
  $Z _{B}$ : Single pair tooth contact factor for pinion
  $Z _{D}$ : Single pair tooth contact factor for wheel
  $Z _{H}$ : Zone factor
  $Z _{E}$ : Elasticity factor
  $Z _{\varepsilon }$ : Contact ratio factor
  $Z _{\beta }$ : Contact ratio factor
  $F _{t}$ : Nominal tangential load
- **(B)** Allowable contact stress, $\sigma _{HP}$
  $\sigma _{HP} =( \sigma _{Hlim} Z _{N} /S _{H} )Z _{L} Z _{V} Z _{R} Z _{W} Z _{X}$
  $\sigma _{Hlim}$ : Endurance limit for contact stress
  $Z _{N}$ : Life factor for contact stress
  $Z _{L}$ : Lubrication factor
  $Z _{V}$ : Velocity factor
  $Z _{R}$ : Roughness factor
  $Z _{W}$ : Hardness ratio factor
  $Z _{X}$ : Size factor for contact stress
  $S _{H}$ : Safety factor for contact stress

#### (2) Single pair tooth contact factor, _s2, _s2

Single pair tooth contact factors, $Z _{B}$ for pinion and $Z _{D}$ for wheel account for the influence of the tooth flank curvature on contact stresses at the inner point of single pair contact in relation to zone factor, $Z _{H}$ and are to be determined as follows.

- **(A)** For spur gears
  $Z _{B}$ = $M _{1}$ or 1, whichever is the larger value
  $Z _{D}$ = $M _{2}$ or 1, whichever is the larger value
  $M <sub>1</sub> = \frac{\tan \alpha <sub>tw</sub>}{\sqrt {\left[ \sqrt {\left( \frac{d <sub>a1</sub>}{d <sub>b1</sub>} \right) <sup>2</sup> -1} - \left( \frac{2 \pi}{z <sub>1</sub>} \right) \right] \left[ \sqrt {\left( \frac{d <sub>a2</sub>}{d <sub>b2</sub>} \right) <sup>2</sup> -1} -( \epsilon <sub>\alpha</sub> -1) \left( \frac{2 \pi}{z <sub>2</sub>} \right) \right]}}\#
  \#
  M <sub>2</sub> = \frac{\tan \alpha <sub>tw</sub>}{\sqrt {\left[ \sqrt {\left( \frac{d <sub>a2</sub>}{d <sub>b2</sub>} \right) <sup>2</sup> -1} - \left( \frac{2 \pi}{z <sub>2</sub>} \right) \right] \left[ \sqrt {\left( \frac{d <sub>a1</sub>}{d <sub>b1</sub>} \right) <sup>2</sup> -1} -( \epsilon <sub>\alpha</sub> -1) \left( \frac{2 \pi}{z <sub>1</sub>} \right) \right]}}$
- **(B)** For helical gears
  - **(a)** When $\varepsilon _{\beta }$ ≥ 1
    $Z _{B}$ = $Z _{D}$ = 1
  - **(b)** When $\varepsilon _{\beta }$＜ 1, $Z _{B}$ and $Z _{D}$ can be determined as follows;
    $Z _{B} =M _{1} - \varepsilon _{\beta } (M _{1} -1), Z _{B} \geq 1$
    $Z _{D} =M _{2} - \varepsilon _{\beta } (M _{2} -1), Z _{D} \geq 1$
    $M _{1}$ and $M _{2}$ : same as (A)
  - **(c)** For internal gears, $Z _{D} =1$

#### (3) Zone factor, _s2

The zone factor, $Z _{H}$ accounts for the influence on the Hertzian pressure of tooth flank curvature at pitch point and transforms the tangential load at the reference cylinder to the normal load at the pitch cylinder, and is to be determined as follows.
$Z _{H} = \sqrt {\frac{2 \cos \beta _{b}}{\cos ^{2} \alpha _{t} \tan \alpha _{tw}}}$

#### (4) Elasticity factor, _s2

The elasticity factor is the value haven relevance with the material properties affected contact stress, and is to be determined as follows.

- **(A)** For steel pinions and wheels ($E$ = 206,000 $\mathrm{N}/mm ^{2}$, $\nu$ = 0.3)
  $Z _{E} =189.8( \sqrt {\mathrm{N}/mm ^{2}} )$
  $E$ : Modulus of elasticity ($\mathrm{N}/mm ^{2}$)
  $\nu$ : Poisson's ratio
- **(B)** In other cases, reference is to be made to the reference standard ISO 6336-2:2019.

#### (5) Contact ratio factor, _s2

The contact ratio factor, $Z _{s}$, account for the influence of transverse contact ratio and the overlap ratio on the specified surface load of gears, and is to be determined as follows.

- **(A)** For spur gear
  $Z _{\varepsilon } = \sqrt {\frac{4- \varepsilon _{\alpha }}{3}}$
- **(B)** For helical gears
  For $\varepsilon _{\beta }$ < 1, $Z _{\varepsilon} = \sqrt {\frac{4- \varepsilon _{\alpha }}{3} (1- \varepsilon _{\beta } )+ \frac{\varepsilon _{\beta }}{\varepsilon _{\alpha }}}$
  For $\varepsilon _{\beta }$≥ 1, $Z _{\varepsilon } = \sqrt {\frac{1}{\varepsilon _{\alpha }}}$

#### (6) Helix angle factor, _s2

The helix angle factor, $Z _{\beta }$, account for the influence of helix angle on surface durability, allowing for such variable as the distribution of load along the lines of contact, $Z _{\beta }$ is dependent only on the helix angle and is to be determined as follows.
$Z _{\beta } = \sqrt {\frac{1}{\cos \beta}}$

#### (7) Endurance limit for contact stress, _s2

For a given material, $\sigma _{Hlim}$ is the limit of repeated contact stress which can be permanently endured. The value of $\sigma _{Hlim}$ can be regarded as the level of contact stress which the material will endure without pitting for at least $5 \times 10 ^{7}$ load cycles. The endurance limit mainly depends on followings.
- material composition, cleanliness and defects
- mechanical properties
- residual stresses
- hardening process, depth of hardened zone, hardness gradient
- material structure (forged, rolled bar, cast)
The endurance limit for contact stress $\sigma _{Hlim}$, is to be determined, in general, making reference to values indicated in the standard ISO 6336-5:2016, for material quality MQ.

- **(A)** Pitting is defined by followings.
  - **(a)** For not surface hardened gears,
    Pitted area > 2 % of total active flank area
  - **(b)** For surface hardened gears,
    Pitted area > 0.5 % of total active flank area, or > 4 % of one particular tooth flank area.
- **(B)** The $\sigma _{Hlim}$ values are to correspond to a failure probability of 1% or less.

#### (8) Life factor, _s2

The life factor $Z _{N}$, accounts for the higher permissible contact stress in case a limited life (number of cycles) is required. The factor mainly depends on followings.
- material and heat treatment
- number of cycles
- influence factors ($Z_R$, $Z_V$, $Z_L$, $Z_W$, $Z_X$)
The life factor, $Z _{n}$, can is to be determined according to Method B outlined in the reference standard ISO 6336-2:2019.

#### (9) Influence factor of lubrication film on contact stress, _s2, _s2, _s2

The lubricant factor, $Z _{L}$, accounts for the influence of the type of lubricant and its viscosity. The velocity factor, $Z _{V}$, accounts for the influence of the pitch line velocity. The roughness factor, $Z _{R}$, accounts for the influence of the surface roughness on the surface endurance capacity. The factors may be determined for the softer material where gear pairs are of different hardness. The factors mainly depend on followings.
- viscosity of lubricant in the contact zone
- the sum of the instantaneous velocities of the tooth surfaces
- load
- relative radius of curvature at the pitch point
- surface roughness of teeth flanks
- hardness of pinion and gear

- **(A)** Lubricant factor, $Z _{L}$
  The lubricant factor, $Z _{L}$, is to be determined as follows.
  $Z _{L} =C _{ZL} + \frac{4(1-C _{ZL} )}{(1.2+ \frac{134}{v _{40}} ) ^{2}}$
  $C _{ZL}$ : The values specified in the following.
  For 850 ≤ $\sigma_Hlim$ ≤ 1200 $\mathrm{N}/mm ^{2}$
  $C_ZL = \frac{0.08(\sigma_Hlim -850 )}{350} + 0.83$
  For $\sigma_Hlim$ < 850 $\mathrm{N}/mm ^{2}$, $C _{ZL}$ = 0.83
  For $\sigma_Hlim$ > 1,200 $\mathrm{N}/mm ^{2}$, $C _{ZL}$ = 0.91
  $v _{40}$ : nominal kinematic viscosity of the oil at 40 ${}^{\circ}\mathrm{C}$ ($\mathrm{mm} ^{2} /s$)
- **(B)** Velocity factor, $Z _{V}$
  The velocity factor, $Z _{V}$, is to be calculated from the following equations.
  $Z _{V} =C _{ZV} + \frac{2(1-C _{ZV} )}{\sqrt {0.8+ \frac{32}{v}}}$
  $C _{ZV}$ : The values specified in the following.
  $C _{ZV} =C _{ZL} +0.02$
- **(C)** Roughness factor, $Z _{R}$
  The roughness facto, $Z _{R}$, is to be calculated from the following equations;
  $Z _{R} = \left( \frac{3}{R _{z10}} \right) ^{C _{ZR}}$
  Where,
  $R _{z10} =R _{z} root {3} of {\frac{10}{\rho _{red}}}$
  The peak-to-valley roughness determined for the pinion $R _{z1}$ and for the wheel $R _{z2}$ are mean values for the peak-to-valley roughness $R _{z}$ measured on several tooth flanks ($R _{z}$ as defined in the reference standard ISO 6336-2:2019)
  $R _{z} = \frac{R _{z1} +R _{z2}}{2}$
  If the roughness stated is an arithmetic mean roughness, i.e. Ra value(=CLA value)
  (=AA value) the following approximate relationship can be applied:
  $R _{a} =CLA=AA=R _{z} /6$
  $\rho_red = \frac{\rho_1 \rho_2}{\rho_1 + \rho_2}$ (relative radius of curvature)
  $\rho 1,2=0.5d _{b 1, 2} \tan \alpha _{tw}$ (also for internal gears, $d _{b}$ negative sign)
  $C _{ZR}$ : The values specified in the following.
  a) For 850 ≤ $\sigma_Hlim$ ≤ 1,200 $\mathrm{N}/mm ^{2}$, $C _{ZR}$ = 0.32 - 0.0002 $\sigma _{Hlim}$
  b) For $\sigma_Hlim$ < 850 $\mathrm{N}/mm ^{2}$, $C _{ZR}$ = 0.150
  c) For $\sigma_Hlim$ > 1200 $\mathrm{N}/mm ^{2}$, $C _{ZR}$ = 0.080

#### (10) Hardness ratio factor, _s2

The hardness ratio factor, $Z _{W}$, accounts for the increase of surface durability of a soft steel gear meshing with a significantly harder gear with a smooth surface, in the following cases.

- **(A)** Surface-hardened pinion with through-hardened wheel
  - **(a)** For $HB <130$,
    $Z _{W} =1.2 \cdot \left( \frac{3}{R _{zH}} \right) ^{0.15}$
  - **(b)** For $130 \leq HB \leq 470$,
    $Z _{W} = \left( 1.2- \frac{HB-130}{1700} \right) \cdot \left( \frac{3}{R _{zH}} \right) ^{0.15}$
  - **(c)** For $HB >470$,
    $Z _{W} = \left( \frac{3}{R _{zH}} \right) ^{0.15}$
    Where,
    $HB$ : Brinell hardness of the tooth flanks of the softer gear of the pair
    $R _{zH}$ : equivalent roughness ($\mathrm{\mu} m$)
    $R _{zH} = \frac{R _{z1} \cdot (10/ \rho _{red} ) ^{0.33} \cdot (R _{z1} /R _{z2} ) ^{0.66}}{(v \cdot \nu _{40} /1500) ^{0.33}}$
    $v _{40}$ : nominal kinematic viscosity of the oil at 40 ${}^{\circ}\mathrm{C}$ ($\mathrm{mm} ^{2} /s$)
    $\rho _{red}$ : relative radius of curvature (refer to (9), (C))
- **(B)** Through-hardened pinion and wheel
  When the pinion is substantially harder than the wheel, the work hardening effect increases the load capacity of the wheel flanks. $Z _{W}$ applies to the wheel only, not to the pinion.
  - **(a)** For $HB _{1} /HB _{2} <1.2$,
    $Z _{W} =1$
  - **(b)** For $1.2 \leq HB _{1} /HB _{2} \leq 1.7$,
    $Z _{W} =1+ \left( 0.00898 \frac{HB _{1}}{HB _{2}} -0.00829 \right) \cdot (u-1)$
  - **(c)** For $HB _{1} /HB _{2} >1.7$,
    $Z _{W} =1+0.00698 \cdot (u-1)$
  - **(d)** For gear ratio $u>20$, $u=20$
  - **(e)** In any case, if calculated $Z _{W} <1$, $Z _{W} =1$

#### (11) Size factor, _s2

The size factor, $Z_X$, accounts for the influence of tooth dimensions on permissible contact stress and reflects the non-uniformity of material properties. The factor mainly depends on followings.
- material and heat treatment
- tooth and gear dimensions
- ratio of case depth to tooth size
- ratio of case depth to equivalent radius of curvature
For through-hardened gears and for surface-hardened gears with adequate casedepth relative to tooth size and radius of relative curvature $Z_X$ = 1. When the casedepth is relatively shallow then a smaller value of $Z_X$ should be chosen.

#### (12) Safety factor for contact stress, _s2

The safety factor for contact stress, $S _{H}$, is the values specified in the follows. However, where the calculation sheets or data are submitted or the factor is measured actually, the value may be applied according to the discretion of the Society.

- **(A)** Main propulsion gears : 1.20
- **(B)** Auxiliary gears : 1.15


### 7. Bending strength

The criterion for tooth root bending strength is the permissible limit of local tensile strength in the root fillet. The root stress, $\sigma _{F}$ and the permissible root stress, $\sigma _{FP}$ is to be calculated separately for the pinion and the wheel. $\sigma _{F}$ must not exceed $\sigma _{FP}$. The following formulae and definitions apply to gears having rim thickness greater than 3.5 $m _{n}$. The result of rating calculations made by following this method are acceptable for normal pressure angles up to 25 ° and reference helix angles up to 30°. For larger pressure angles and large helix angles, the calculated results should be confirmed by experience as by Method A of the reference standard ISO 6336-3:2019.

#### (1) Basic equations

- **(A)** Tooth root bending stress for pinion and wheel, $\sigma _{F}$ ($\mathrm{N}/mm ^{2}$)
  $\sigma _{F} = \frac{F _{t}}{bm _{n}} Y _{F} Y _{S} Y _{\beta } Y _{B} Y _{DT} K _{A} K _{\gamma } K _{V} K _{F \alpha } K _{F \beta } \leq \sigma _{FP}$
  $Y _{F}$ : Tooth form factor
  $Y _{S}$ : Stress correction factor
  $Y _{\beta }$ : Helix angle factor
  $Y _{B}$ : Rim thickness factor
  $Y _{DT}$ : Deep tooth factor
  $F _{t}$*,* $K_A$, $K_\gamma$, $K _{V}$, $K_{F \alpha}$, $K_{F \beta}$ : refer to **Par 4**, **Par 5**
- **(B)** Permissible tooth root bending stress for pinion and wheel, $\sigma _{FP}$ ($\mathrm{N}/mm ^{2}$)
  $\sigma _{FP} = \frac{\sigma _{FE} Y _{d} Y _{N}}{S _{F}} Y _{\delta re \ell T} Y _{R re \ell T} Y _{X}$
  $\sigma _{FE}$ : Bending endurance limit
  $Y _{d}$ : Design factor
  $Y _{N}$ : Life factor
  $Y _{\delta re \ell T}$ : Relative notch sensitivity factor
  $Y _{R re \ell T}$ : Relative surface factor
  $Y _{X}$ : Size factor
  $S _{F}$ : Safety factor for tooth root bending stress

#### (2) Tooth form factor, _s2

The tooth form factor, $Y _{F}$, is the values calculated by the following formula. (refer to **Fig 1**)
$Y _{F} = \frac{6 \frac{h _{F}}{m _{n}} \cos \alpha _{Fen}}{\left( \frac{s _{Fn}}{m _{n}} \right) ^{2} \cos \alpha _{n}}$
![](images/image75.png)
**Fig 1 For the Calculation of** $h _{F}$**,** $s _{Fn}$ **and** $\alpha _{Fen}$
For the calculation of $h _{F}$, $s _{Fn}$ and $\alpha _{Fen}$, the procedure outlined in the reference standard IISO 6336-3:2019 (Method B) is to be used.

#### (3) Stress correction factor, _s2

The stress correction factor, $Y _{S}$, is used to convert the nominal bending, and is the values calculated by the following formula. (having range of validity: 1 ≤ $q _{s}$ < 8)
$Y _{S} =(1.2+0.13L)q _{s} ^{\frac{1}{\left( 1.21+ \frac{2.3}{L} \right)}}$
$q _{s} = \frac{s _{Fn}}{2 \rho _{F}}$
$L= \frac{s _{Fn}}{h _{F}}$

#### (4) Helix angle factor, _s2

The helix angle factor, $Y _{B}$, account for the influence of helix angle on bending stress, and is the values calculated by the following formula. However, 1.0 is substituted for $\varepsilon _{\beta }$ when $\varepsilon _{\beta }$ > 1, 30° is substituted for $\beta$ when $\varepsilon _{\beta }$ > 30°.
$Y _{\beta } =1- \varepsilon _{\beta } \frac{\beta}{120}$

#### (5) Rim thickness factor, _s2

The rim thickness factor, $Y _{B}$, is a simplified factor used to de-rate thin rimmed gears. For critically loaded applications, this method should be replaced by a more comprehensive analysis. Factor $Y _{B}$ is to be determined as follows.

- **(A)** For external gears,
  In case of $s _{R} /h \geq 1.2$, $Y _{B} =1$
  In case of $0.5Where,
  \(s _{R}$ : rim thickness of external gears, (mm)
  The case of $s _{R} /h \leq 0.5$ is to be avoided.
- **(B)** For internal gears,
  In case of $s _{R} /m _{n} \geq 3.5$, $Y _{B} =1$
  In case of $1.75Where,
  \(s _{R}$ : rim thickness of internal gears (mm)
  The case of $s _{R} /m _{n} \leq 1.75$ is to be avoided.

#### (6) Deep tooth factor, _s2

The deep tooth factor, $Y _{DT}$, adjusts the tooth root stress to take into account high precision gears and contact ratios within the range of virtual contact ratio $2.05 \leq \varepsilon _{\alpha n} \leq 2.5$.
Where,
$\varepsilon _{\alpha n} = \frac{\varepsilon _{\alpha }}{\cos ^{2} \beta _{b}}$
Factor $Y _{DT}$ is to be determined as follows.
In case of ISO accuracy grade ≤ 4 and $\varepsilon _{\alpha n} >2.5$,
$Y _{DT} =0.7$
In case of ISO accuracy grade ≤ 4 and $2.05< \varepsilon _{\alpha n} \leq 2.5$,
$Y _{DT} =2.366-0.666 \cdot \varepsilon _{\alpha n}$
In all other cases, $Y _{DT} =1.0$

#### (7) Bending endurance limit, _s2

For a given material, $\sigma _{FE}$ is the local tooth root stress which can be permanently endured. According to the reference standard ISO 6336-5:2016 the number of $3 \times 10 ^{6}$ cycles is regarded as the beginning of the endurance limit. $\sigma _{FE}$ is defined as the unidirectional pulsating stress with a minimum stress of zero(disregarding residual stresses due to heat treatment). Other conditions such as alternating stress or prestressing etc. are covered by the design factor $Y_d$. The $\sigma _{FE}$ values are to correspond to a failure probability 1% or less. The endurance limit mainly depends on followings.
- material composition, cleanliness and defects
- mechanical properties
- residual stresses
- hardening process, depth of hardened zone, hardness gradient
- material structure (forged, rolled bar, cast)
The bending endurance limit, $\sigma _{FE}$ is to be determined, in general, making reference to values indicated in the reference standard ISO 6336-5:2016, for material quality MQ.

#### (8) Design factor, _s2

The design factor, $Y _{d}$, takes into account the influence of load reversing and shrinkfit prestressing on the tooth root strength. The design factor, $Y _{d}$, for load reversing, can be determined as follows. However, for shrinkfit, The design factor is the value according to the calculation sheets or data submitted to the Society and recognized appropriateness by the Society.
$Y _{d}$ = 1 : In general (For gears with uniformed load direction and not shrinkfit)
$Y _{d}$ = 0.9 : For gears with occasional part load in reverse direction, such as main wheel in
reversing
$Y _{d}$ = 0.7 : For idler gears

#### (9) Life factor, _s2

The life factor, $Y _{N}$, accounts for the higher tooth root bending stress permissible in case a limited life (number of cycles) is required. The factor mainly depends on followings.
- material and heat treatment
- number of load cycles (service life)
- influence factors ($Y _{\delta re \ell T}$, $Y _{R re \ell T}$, $Y _{X}$)
The life factor, $Y _{N}$, is to be determined according to Method B outlined in the reference standard ISO 6336-3:2019.

#### (10) Relative notch sensitivity factor, _s2

The relative notch sensitivity factor, $Y _{\delta re \ell T}$, indicates the extent to which the theoretically concentrated stress lies above the fatigue endurance limit. The factor mainly depends on material and relative stress gradient and is to be determined as follows.
$Y _{\delta re \ell T} = \frac{1+ \sqrt {0.2 \rho '(1+2q _{s} )}}{1+ \sqrt {1.2 \rho '}}$
Where,
$\rho '$ : slip-layer thickness according to **Table 4** (mm)

| Material |   | $\rho '$ (mm) |
| --- | --- | --- |
| Case hardened steels, flame or induction hardened steels |   | 0.0030 |
| Through-hardened steels<sup>(1)</sup>, yield point $R _{e}$ | 500 N/mm2 | 0.0281 |
| Through-hardened steels<sup>(1)</sup>, yield point $R _{e}$ | 600 N/mm2 | 0.0194 |
| Through-hardened steels<sup>(1)</sup>, yield point $R _{e}$ | 800 N/mm2 | 0.0064 |
| Through-hardened steels<sup>(1)</sup>, yield point $R _{e}$ | 1000 N/mm2 | 0.0014 |
| Nitrided steels |   | 0.1005 |
| (Note)<br>(1) The given values of $\rho '$ can be interpolated for values of $R _{e}$ not stated above |   |   |

#### (11) Relative surface factor, _s2

The relative surface factor, $Y _{Re lT}$, takes into account the dependence of the root strength on the surface condition in the tooth root fillet, and is the values specified in the **Table 5**. The method applied here is only valid when scratches or similar defects deeper than $2R _{z}$ are not present. If the roughness stated is an arithmetic mean roughness, i.e. $R _{a}$ value (=CLA value) (=AA value), the following approximate relationship can be applied.
$R _{a} =CLA=AA=R _{z} /6$

| $Y _{R re \ell T}$ |   | Remarks |
| --- | --- | --- |
| $R _{z}$ < 1 | 1 ≤ $R _{z}$ ≤ 40 | Remarks |
| 1.120 | 1.674 - 0.529($R_z$ + 1)^0.1 | Case hardened steels, through - hardened steels ($\sigma _{b}$ ≥ 800$\mathrm{N}/mm ^{2}$) |
| 1.070 | 5.306 - 4.203($R_z$ + 1)^0.01 | Normalized steels ($\sigma _{b}$ < 800$\mathrm{N}/mm ^{2}$) |
| 1.025 | 4.299 - 3.259($R_z$ + 1)^0.0058 | Nitrided steels |
| NOTE<br>$R _{z}$ : same as Par 6 (9) (C) |   |   |

#### (12) Size factor, _s2

The size factor, $Y _{X}$, takes into account the decrease of strength with increasing size. The factor mainly depends on followings.
- material and heat treatment
- tooth and gear dimensions
- ratio of case depth to tooth size
The Size factor, $Y _{X}$, is the values calculated in accordance with the **Table 6**.

| Remarks | Range | $Y _{X}$ |
| --- | --- | --- |
| Generally | $m _{n}$ ≤ 5 | 1 |
| Normalized and through-hardened steels | 5 < $m _{n}$ < 30 | 1.03 - 0.06 $m _{n}$ |
| Normalized and through-hardened steels | $m _{n}$ ≥ 30 | 0.85 |
| Surface hardened steels | 5 < $m _{n}$ < 25 | 1.05 - 0.010 $m _{n}$ |
| Surface hardened steels | $m _{n}$ ≥ 25 | 0.8 |

#### (13) Safety factor for tooth root bending stress, _s2

The safety factor for tooth root bending stress, $S _{F}$, is the values specified in the following. However, the safety factor for tooth root bending stress is the value according to the calculation sheets or data submitted to the Society and recognized appropriateness by the Society.

- **(A)** Main propulsion gears : 1.55
- **(B)** Auxiliary gears : 1.40
