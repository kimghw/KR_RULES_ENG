# Guidance for Fatigue Strength Assessment Including Springing

> OTHER RULES AND GUIDANCE / GC-35-E / 2025 / EN / Guidance

## CHAPTER 3 NONLINEAR SPRINGING ASSESSMENT

### Section 1 Nonlinear springing assessment by direct method

#### 101. Procedure for nonlinear springing assessment by direct method

- **1.** **1**. Fig. 3.1 provides an illustration of the nonlinear springing assessment procedure by direct method.
- **2.** **2**. Dominant sea states for fatigue damage evaluated in accordance with **Pt.3, Annex 3-3, 6.** of **Guidance relating to Rules for the Classification of Steel Ships** is to be selected.
- **3.** **3**. Stress time series are to be obtained from nonlinear hydro-elastic simulation including slamming in dominant sea states which are selected in 2. above.
- **4.** **4**. Short-term fatigue damage is to be evaluated by applying a linear cumulative damage summation(Palmgren-Miner's rule) and S-N curves to the stress range distribution, which is calculated by applying the rainflow-counting method to the stress time series obtained from **2**.
- **5.** **5**. The fatigue damage including nonlinear springing is to be obtained by applying correction factors for entire sea states and short-crested wave effect to the fatigue damage calculated from 4. above.

#### 102. Selection of dominant sea states for the fatigue damage

- **1.** Simulation in the time domain is required to evaluate the effect of springing and slamming due to nonlinearity of ship motion on fatigue strength.
- **2.** Because of the long process time required for nonlinear simulation in the time domain, it is difficult to simulate all short-term sea states directly. This guidance adopts a method for evaluating fatigue damage including nonlinear springing from the results of short-term sea states which contribute large influence on fatigue damage in **Pt.3, Annex 3-3**, 6. of **Guidance relating to Rules for the Classification of Steel Ships**.
- **3.** The spectral fatigue damage for short-term sea state is defined by $D _{ ijkl}$ taking into consideration ship-to-wave heading, $k$, and loading condition, $l$, in addition to the fatigue damage, $D _{ ij}$, which is defined in **Pt.3, Annex 3-3**, 6. (4) **(B)** of **Guidance relating to Rules for the Classification of Steel Ships**. The fatigue damage contribution, $d _{ijkl}$, for each short-term sea state is to be calculated by dividing the calculated short-term sea state fatigue damage, $D _{ ijkl}$, by the long-term fatigue damage, $D _{l}$, under a given loading condition.
  $d _{ijkl} = \frac{D _{ijkl}}{D _{l}}$
- **4.** The number of short-term sea states for which the cumulated fatigue damage exceeds the cumulative contribution, $C _{d}$, is to be calculated. The value of cumulative contribution value is to be determined in consultation with the Society, and a value of 0.5 or higher is recommended. For efficient calculation, the number of short-term sea states, $n$, may be obtained by sorting from the short-term sea state with a large contribution to fatigue damage as shown in the following equation. These $n$ short-term sea states are defined as the dominant sea states.
  $n$ = number of sea states is to be obtained as follows:
  $\sum _{r=1} ^{n} d _{r} >C _{d}$
  $d _{r}$ = fatigue damage contribution of the r-th short-term sea state when sorting from short-term sea state with high fatigue damage contribution.
  $C _{d}$ = the cumulative contribution.
  ![Fig. 3.1 Procedure for nonlinear springing assessment by direct method](images/image11.png)
  **Fig. 3.1 Procedure for nonlinear springing assessment by direct method**

#### 103. Calculation of fatigue damage by the rainflow-counting method

- **1.** **1**. The number of cycles of the reference stress range can be obtained using the rainflow-counting method to the stress time series of short-term sea states including vibration response due to springing and whipping.
- **2.** **2**. Short-term fatigue damage, $D _{NL-SPR, r}$, is calculated by applying the following Palmgren-Miner's linear cumulative damage law and the probability of occurrence of each short-term sea state to the reference stress range and its number of cycles.
  $D _{NL-SPR, r} =p _{r} \frac{T}{T _{r}} \sum _{} ^{} \frac{n _{i}}{N _{i}}$
  $p _{r}$ = probability of occurrence of $r$-th short-term sea state.
  $T$ = design fatigue life of the ship as defined in **Ch. 2,** **202.** of this guidance.
  $T _{r}$ = simulation time of $r$-th short-term sea state, in seconds.
  $n _{\Delta \sigma i}$ = estimated number of cycles at the reference stress range by the rainflow-counting method.
  $N _{\Delta \sigma i}$ = number of constant amplitude load cycles to failure according to the design S-N curve at the reference stress range.
- **3.** **3**. Cumulative fatigue damage, $D _{NL-SPR}$, in the dominant sea states is derived by summation of short-term fatigue damage as follows:
  $D _{NL-SPR} = \sum _{r=1} ^{n} D _{NL-SPR, r}$
  $n$ = number of the dominant sea states defined in 102. 4.

#### 104. Correction factor for entire sea states

A correction factor, $f _{AS}$, to take into consideration entire sea states is defined as following expression, which is a ratio of fatigue damage in the dominant sea states and entire sea states from spectral fatigue analysis results.
$f _{AS} = \frac{\sum _{r=1} ^{n} D _{l, r}}{D _{l}}$
$D _{l, r}$ = spectral fatigue damage in $r$-th dominant sea state under the loading condition $l$.
$D _{l}$ = cumulative spectral fatigue damage in entire sea states under the loading condition $l$.

#### 105. Correction factor for effect of short-crested wave

When the hydro-elastic simulation for nonlinear springing and whipping is carried out under long-crested wave condition, a correction factor can be used to consider the effect of short-crested wave. In this case, the correction factor, $f _{SC}$, can be estimated from the results of spectral fatigue analysis as the following expression.
$f _{SC} = \frac{D _{l}}{D _{l- LC}}$
The fatigue damage, $D _{l-LC}$, under long-crested wave condition is to be calculated with spectral moments which is obtained by excluding terms of spreading function from the moments defined in **Pt.3, Annex 3-3**, 6. (3) (C) of **Guidance relating to Rules for the Classification of Steel Ships** as follows:
$m _{0- LC} = \int _{\omega } ^{} {S \left( \omega |H _{s} , T _{z} , \theta \right)}$
$m _{2-LC} = \int _{\omega } ^{} { \left| \omega - \frac{\omega ^{2} V}{g} \cos \theta \right| ^{2} S( \omega | H _{s} ,T _{z} , \theta )}$

#### 106. Calculation of fatigue damage including nonlinear springing

- **1.** Fatigue damage, $D _{SPR2}$, including nonlinear springing is derived by applying correction factors obtained from 104. and 105 to fatigue damage which is calculated in dominant sea states according to 103 as the following expression.:
  $D _{SPR2} =f _{SC} \frac{1}{f _{AS}} D _{NL-SPR}$
- **2.** **2**. Fatigue life, $T _{F, SPR2}$, including nonlinear springing is obtained as follows:
  $T _{F, SPR2} = \frac{T _{D}}{D _{SPR2}}$


### Section 2 Nonlinear springing assessment by comparative method

#### 201. Procedure for nonlinear springing assessment by comparative method

- **1.** **1**. Fig. 3.2 provides an illustration of the nonlinear springing assessment procedure by comparative method.
- **2.** **2**. Dominant sea states for fatigue damage which is evaluated in accordance with **Pt.3, Annex 3-3, 6.** of **Guidance relating to Rules for the Classification of Steel Ships** is to be selected.
- **3.** **3**. Time series of stress are to be obtained from nonlinear hydro-elastic simulation including slamming in dominant sea states which are selected in 2. above.
- **4.** **4**. Short-term fatigue damage is to be evaluated by applying a linear cumulative damage summation(Palmgren-Miner's rule) and S-N curves to the stress range distribution, which is calculated by applying the rainflow-counting method to the stress time series obtained from **2**.
- **5.** **5**. The fatigue damage, $D _{NL-SPR}$, including nonlinear springing is to be obtained by applying correction factors for entire sea states and short-crested wave effect to the fatigue damage calculated from **4**. above.
- **6.** **6**. The fatigue damage, $D _{NL-RGD}$, for rigid body is to be obtained by applying 4. and 5. with time series not including hydro-elasticity.
- **7.** **7**. The nonlinear springing coefficient, $f _{SPR2}$, is to be defined as a ratio of $D _{NL-SPR}$ and $D _{NL-RGD}$ which are long-term fatigue damage obtained from 5. and 6.
- **8.** **8**. The fatigue damage, $D _{SPR2}$, including nonlinear springing is to be obtained by multiplying a fatigue damage, $D$, calculated in accordance with **Pt.3, Annex 3-3, 6. (5)** of **Guidance relating to Rules for the Classification of Steel Ships** by the nonlinear springing coefficient, $f _{SPR2}$.
  ![Fig. 3.2 Procedure for nonlinear springing assessment by comparative method](images/image12.png)
  **Fig. 3.2 Procedure for nonlinear springing assessment by comparative method**

#### 202. Long-term fatigue damage excluding hydro-elastic effect

- **1.** **1**. Time series of stress are to be obtained from simulation for the rigid body in dominant sea states which are defined in 102. The time series of wave elevation used in the simulation should be the same as the time series used in hydro-elastic simulation including nonlinear springing at this stage.
- **2.** **2**. Instead of performing a separate simulation with the rigid body to calculate the time series of stress excluding the elastic effect as 1. above, it may be obtained by applying low-pass filter to the time series calculated from hydro-elastic simulation.
- **3.** **3**. The fatigue damage, $D _{NL-RGD}$, excluding hydro-elastic effect is defined as the damage evaluated using the time series of stress obtained from 1. or 2. above.

#### 203. Calculation of the nonlinear springing coefficient and long-term fatigue damage

- **1.** **1**. The nonlinear springing coefficient, $f _{SPR2}$, is defined as follows:
  $f _{SPR2} = \frac{D _{NL-SPR}}{D _{NL-RGD}}$
- **2.** **2**. The fatigue damage, $D _{SPR2}$, including nonlinear springing by comparative method is derived as follows:
  $D _{SPR2} =f _{SPR2} D$
  where:
  $D$ = long-term fatigue damage by spectral fatigue analysis, see **Pt.3, Annex 3-3**, 6. (5) (B) of **Guidance relating to Rules for the Classification of Steel Ships**
- **3.** **3**. Fatigue life, $T _{F, SPR2}$, including nonlinear springing is obtained as follows:
  $T _{F, SPR2} = \frac{T _{D}}{D _{SPR2}}$
  where:
  $T _{D}$ = fatigue life, in years


### Section 3 Nonlinear springing assessment for low-speed blunt ships where vertical bending moment is significant

#### 301. Application

- **1.** **1**. Nonlinear springing assessment may be performed in head seas conditions for ships where stress ranges by vertical bending moment are significant to fatigue damage, e.g. very large ore carrier, to simplify the assessment, then the comparative method described in Sec. 2 is to be applied for the assessment.
- **2.** **2**. Since low-speed blunt ships have comparatively high stiffness, natural frequencies of ship hull are high and a vertical mode is the lowest eigenmode in general. Where natural frequencies are high, the effect on fatigue damage by linear springing is comparatively low, and it is essential that due consideration is given to the ship hull vibration response including whipping.

#### 302. Selection of dominant sea states for the fatigue damage

- **1.** **1**. The procedure described in **102**. is to be applied for selection of dominant sea states, but ship-to-wave headings are confined only to head seas condition.
- **2.** **2**. The fatigue damage contribution, $d _{180 ijl}$, under head seas condition is to be obtained as follows:
  $d _{180 ijl} = \frac{D _{180 ijl}}{D _{180 l}}$
  where:
  $D _{180 ijl}$ = fatigue damage in a short-term sea state under head seas condition
  $D _{180 l}$ = long-term fatigue damage under head seas condition
- **3.** **3**. Dominant sea states are selected according to **102**. **4**.

#### 303. Calculation of concentrated stress and fatigue damage

- **1.** **1**. Where the effect of vertical bending moment on fatigue damage is significant, the concentrated stress for fatigue strength assessment may be obtained from simplified stress analysis which is using nominal stresses and stress concentration factors instead of the procedure according to **Sec. 1** **406**.
- **2.** **2**. Time series of hull girder loads may be calculated with global 1-D finite element model consists of beam elements which properly represent for stiffness and weight distribution of a ship. Time series of stress for the fatigue strength assessment is to be obtained by multiplying the time series of nominal stress by stress concentration factors in accordance with **Pt.3, Annex 3-3, 4. (2)** and **(3)** of **Guidance relating to Rules for the Classification of Steel Ships**.
- **3.** **3**. Instead of performing a separate simulation with the rigid body to calculate the time series of stress excluding the elastic effect, it may be obtained by applying low-pass filter to the time series obtained from **2**. above.
- **4.** **4**. The fatigue damage $D _{NL-SPR}$ and $D _{NL-RGD}$, with and without the springing effect on fatigue damage, are to be obtained from by applying the rainflow-counting method described in 103. to the time series of stress obtained from 2. and 3. above.

#### 304. Calculation of the nonlinear springing coefficient and long-term fatigue damage

- **1.** **1**. The nonlinear springing coefficient, $f _{SPR2}$, is defined as follows:
  $f _{SPR2} = \frac{D _{NL-SPR}}{D _{NL-RGD}}$
- **2.** **2**. The fatigue damage, $D _{SPR2}$, including nonlinear springing by comparative method is derived as follows:
  $D _{SPR2} =f _{SPR2} D _{RGD}$
  where:
  $D _{RGD}$ = long-term fatigue damage according to **Pt.3, Annex 3-3** of **Guidance relating to Rules for the Classification of Steel Ships**
- **3.** **3**. Fatigue life, $T _{F, SPR2}$, including nonlinear springing is obtained as follows:
  $T _{F, SPR2} = \frac{T _{D}}{D _{SPR2}}$
  where:
  $T _{D}$ = fatigue life, in years. ![](images/image13.png)

  |   |
  | --- |
  | **Guidelines for Fatigue Strength Assessment Including Springing**<br>Published by<br>**KR**<br>36, Myeongji ocean city 9-ro, Gangseo-gu,<br>BUSAN, KOREA<br>TEL : +82 70 8799 7114<br>FAX : +82 70 8799 8999<br>Website : http://www.krs.co.kr |
  |   |

  | CopyrightⒸ 2020, **KR**<br>Reproduction of this Guidance in whole or in parts is<br>prohibited without permission of the publisher. |
  | --- |
