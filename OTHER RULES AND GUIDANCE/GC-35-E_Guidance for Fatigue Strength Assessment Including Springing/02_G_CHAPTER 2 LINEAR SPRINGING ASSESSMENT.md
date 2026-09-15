# Guidance for Fatigue Strength Assessment Including Springing

> OTHER RULES AND GUIDANCE / GC-35-E / 2025 / EN / Guidance

## CHAPTER 2 LINEAR SPRINGING ASSESSMENT

### Section 1 Calculation of stress transfer function and response spectrum

#### 101. Stress transfer function

- **1.** The stress transfer function for wave heading, $\theta$, and wave frequency, $\omega$, is expressed as $H( \omega | \theta )$.
- **2.** When the hydro-elastic simulation for the calculation of the stress transfer function is carried out in the time domain, the stress transfer function of the regular wave can be calculated by using the Fourier transform on the time series stress data obtained in the irregular wave condition.

#### 102. Wave spectrum

The Modified Pierson-Moskowitz wave spectrum is recommended, which is defined in the following equation:
$S _{\eta } ( \omega | H _{s} ,T _{z} ) = \frac{H _{s}^{2}}{4 \pi} \left( \frac{2 \pi}{T _{z}} \right) ^{4} \omega ^{-5} \exp \left[ - \frac{1}{\pi} \left( \frac{2 \pi}{T _{z}} \right) ^{4} \omega ^{-4} \right]$
$\omega$ = wave frequency, in $\mathrm{rad}/s$.
$H _{s}$ = significant wave height, in $\mathrm{m}$.
$T _{z}$ = average Zero up-crossing wave period, in seconds.

#### 103. Response spectrum

- **1.** The response spectrum, $S ( \omega | H _{s} ,T _{z} , \theta )$, of the short-term sea state in the wave frequency domain can be estimated as follows using the wave spectrum and stress transfer function taking into account the thickness effect:
  $S ( \omega | H _{s} ,T _{z} , \theta ) = \left( f _{thick} \left| H ( \omega | \theta ) \right| \right) ^{2} S _{\eta } ( \omega | H _{s} ,T _{z} )$
  $f _{thick}$ = correction factor to consider the thickness effect is calculated as follows:
  $f _{thick} = \left( \frac{t}{22} \right) ^{n}$, (for $t>22$)
  $f _{thick} =1$, (for $t \leq 22$)
  $t$ = thickness of the member in way of the hot spot for welded joints or base material free edge, in $\mathrm{mm}$.
  $n$ = thickness exponents according to the **Table 1** of **Pt 13, Ch 9, Sec 3** of **the Rules for the Classification of Steel Ships**.
- **2.** The moments of the response spectrum taking into account the influence of short-crested waves in the encounter frequency domain are calculated as follows:
  $m _{n} = \int _{\omega } ^{} { \sum _{\theta _{0} -90 {}^{\circ} } ^{\theta _{0} +90 {}^{\circ} } f _{s} ( \theta ) \left| \omega - \frac{\omega ^{2} V}{g} \cos \theta \right| ^{n} S( \omega | H _{s} ,T _{z} , \theta )}$
  using a spreading function usually defined as $f _{s} ( \theta )=kcos ^{2} ( \theta )$
  where $k$ is selected such that:  
  $\sum _{\theta _{0} -90 {}^{\circ} } ^{\theta _{0} +90 {}^{\circ} } f _{s} ( \theta )=1$
  where,
  $\theta _{0}$ = main wave heading.
  $\theta$ = relative spreading around the main wave heading.
  $V$ = speed, in $\mathrm{m}/s$.
  $g$ = gravity acceleration, taken equal to 9.81 $\mathrm{m}/s ^{2}$.


### Section 2 Linear springing assessment by direct method

#### 201. Procedure for linear springing assessment by direct method

- **1.** **1**. Fig. 2.1 provides an illustration of the linear springing assessment procedure by direct method.
- **2.** **2**. Using the response spectrum obtained from 103., the short-term fatigue damage is calculated in terms of the narrow-band approximation according to 20
- **3.** **3**. The short-term fatigue damage is obtained by multiplying a wide-band correction factor to the short-term fatigue damage obtained from 2. above.
- **4.** **4**. The long-term fatigue damage obtained by accumulating the short-term fatigue damage obtained from 3. is defined as the fatigue damage including linear springing.
  ![Fig. 2.1 Procedure for linear springing assessment by direct method](images/image8.png)
  **Fig. 2.1 Procedure for linear springing assessment by direct method****202. Short-term fatigue damage in terms of narrow-band approximation**
  The fatigue damage using the short-term closed-form method described in **Pt.3, Annex 3-3**, 6. of **Guidance relating to Rules for the Classification of Steel Ships** is as follows:
  $D _{ij} =2 ^{\frac{3m}{2}} \frac{n _{T}}{K _{2}} \Gamma ( \frac{m}{2} +1) \mu _{ij} r _{ij} p _{ij} m _{0ij} ^{\frac{m}{2}}$
  Where $(i, j)$ is the short-term sea state number defined by the significant wave, $H _{s}$, and the wave period, $T _{z}$, of the wave scatter diagram.
  $K _{2}$, $m$ = intercept and negative inverse slope of the S-N curve as specified in **Table 1** of **Pt.3, Annex 3-3** of **Guidance relating to Rules for the Classification of Steel Ships**, respectively.
  $n _{T}$ = total stress cycles for a life time of a ship given by the following formula:
  $n _{T} =f T$
  $f$ = average frequency given by the following formula:
  $f= \sum _{i} ^{} \sum _{j} ^{} p _{ij} f _{ij}$
  $p _{ij}$ = probability of occurrence of $H _{si}$ and $T _{zj}$.
  $f _{ij}$ = zero up-crossing frequency of stress response in the sea state.
  $f _{ij} = \frac{1}{2 \pi} \sqrt {\frac{m _{2ij}}{m _{0ij}}}$
  $m _{n ij}$ = moments of the response spectrum in the $(i, j)$ short-term sea state, as specified in **103. 2.**
  $T$ = design fatigue life, in seconds.
  $\Gamma \left( x \right)$ = complete Gamma function.
  $\mu _{ij}$ = coefficient taking into account the change of inverse slope of the S-N curve is as follows:
  $\mu _{ij} =1- \frac{\gamma \left( \frac{m}{2} +1, t _{ij} \right) - \frac{1}{t _{ij}} \gamma \left( \frac{m+2}{2} +1, t _{ij} \right)}{\Gamma \left( \frac{m}{2} +1 \right)}$
  $\gamma \left( a, x \right)$ = Incomplete Gamma function.
  $t _{ij} = \frac{s _{7}^{2}}{8m _{0 ij}}$
  $s _{7}$ = the stress range of the design S-N curve at $N=10 ^{7}$ cycles.
  $r _{ij}$ = ratio of the response zero up-crossing frequency in a given sea state to the average crossing frequency given by the following formula:
  $r _{ij} = \frac{f _{ij}}{f}$

#### 203. Short-term fatigue damage with wide-band model

- **1.** In the hydro-elastic simulation including springing, the response in the high frequency region is included, and the stress response spectrum shows a wide-band distribution. To take this into account, this guidance applies the wide-band model proposed by Benasciutti-Tovo. Where a different wide-band model is required, relevant data is to be submitted for approval.
- **2.** The fatigue damage, $D _{SPR1, ij}$, obtained by applying the wide-band correction factor, $\rho _{ij}$, to the fatigue damage, $D _{ij}$, obtained assuming the narrow-band response spectrum according to **201.** is as follows:
  $D _{L-SPR, ij} = \rho _{ij} D _{ij}$
  $\rho _{ij}$ = wide-band correction factor for the $\left( i, j \right)$ short-term sea state can be calculated as follows:
  $\rho _{ij} =b _{ij} +(1-b _{ij} ) \alpha _{2 ij}^{m-1}$
  $\alpha _{1 ij}$, $\alpha _{2 ij}$ = bandwidth parameters of the stress response spectrum are as follows:
  $\alpha _{1 ij} = \frac{m _{1 ij}}{\sqrt {m _{0 ij} m _{2 ij}}}$, $\alpha _{2 ij} = \frac{m _{2 ij}}{\sqrt {m _{0 ij} m _{4 ij}}}$ $0 \leq \alpha _{1ij}$, $\alpha _{2ij} \leq 1$
  $b _{ij}$ = weighting factor can be calculated as follows using the bandwidth parameters:
  $b _{ij} = \frac{( \alpha _{1 ij} - \alpha _{2 ij} ) \left[ 1.112(1+ \alpha _{1 ij} \alpha _{2 ij} -( \alpha _{1 ij} + \alpha _{2 ij} ))e ^{2.11 \alpha _{2 ij}} +( \alpha _{1 ij} - \alpha _{2 ij} ) \right]}{( \alpha _{2 ij} -1) ^{2}}$

#### 204. Long-term fatigue damage with wide-band model

- **1.** Taking account of all heading directions and loading conditions, the long-term cumulative fatigue damage ratio in air is calculated as follows:
  $D _{L-SPR, air} =2 ^{\frac{3m}{2}} \frac{n _{T}}{K _{2}} \Gamma \left( \frac{m}{2} +1 \right) \sum _{i} ^{} \sum _{j} ^{} \sum _{k} ^{} \sum _{l} ^{} \rho _{ijkl} \mu _{ijkl} r _{ijkl} p _{ijkl} m _{0 ijkl} ^{\frac{m}{2}}$
  $K _{2}$, $m$ = intercept and negative inverse slope of the S-N curve as specified in **Table 1 (a)** of **Pt.3, Annex 3-3** of **Guidance relating to Rules for the Classification of Steel Ships**, respectively.
  $p _{ijkl}$ = combined probability given by the following formula:
  $p _{ijkl} =p _{ij} p _{k} p _{l}$
  $p _{k}$, $p _{l}$ = probability for the heading angle and the loading condition, respectively.
- **2.** For unprotected joints exposed to sea water, the fatigue damage ratio, $D _{SPR1, cor}$, is given by:
  $D _{L-SPR, cor} =2 ^{\frac{3m}{2}} \frac{n _{T}}{K _{2}} \Gamma \left( \frac{m}{2} +1 \right) \sum _{i} ^{} \sum _{j} ^{} \sum _{k} ^{} \sum _{l} ^{} \rho _{ijkl} r _{ijkl} p _{ijkl} m _{0 ijkl} ^{\frac{m}{2}}$
  $K _{2}$, $m$ = intercept and negative inverse slope of the S-N curve as specified in **Table 1 (b)** of **Pt.3, Annex 3-3** of **Guidance relating to Rules for the Classification of Steel Ships**, respectively.
  For the structural members protected by effective means in ballast tanks, the fatigue damage ratio, $D _{L-SPR}$, is to be calculated as follows:
  $D _{L-SPR} =0.5D _{L-SPR, air} +0.5D _{L-SPR, cor}$
  Cumulative fatigue damage, $D _{L-SPR}$, is defined as the fatigue damage including linear springing, $D _{SPR1}$.
- **3.** The fatigue life,$T _{F, SPR1}$, considering linear springing for the members subject to fatigue strength assessment is calculated according to the following formula:
  $T _{F, SPR1} = \frac{T _{D}}{D _{SPR1}}$
  $T _{D}$ = design fatigue life, in years.


### Section 3 Linear springing assessment by comparative method

#### 301. Procedure for linear springing assessment by comparative method

- **1.** **1**. Fig. 2.2 provides an illustration of the linear springing assessment procedure by comparative method.
- **2.** **2**. Long-term fatigue damage, $D _{L-SPR}$, with wide-band model is to be obtained from **204**.
- **3.** **3**. The long-term fatigue damage, $D _{L-RGD}$, for rigid body is to be calculated using the stress transfer function in which hydro-elastic effect is excluded as illustrated in Fig. 2.2.
- **4.** **4**. The linear springing coefficient, $f _{SPR1}$, is to be defined as a ratio of $D _{L-SPR}$ and $D _{L-RGD}$ which are long-term fatigue damage obtained from **2**. and **3**. above.
- **5.** **5**. The fatigue damage, $D _{SPR1}$, including linear springing is to be obtained by multiplying a fatigue damage, $D$, calculated in accordance with **Pt.3, Annex 3-3, 6. (5)** of **Guidance relating to Rules for the Classification of Steel Ships** by the linear springing coefficient, $f _{SPR1}$.
  ![Fig. 2.2 Procedure for linear springing assessment by comparative method](images/image9.png)
  **Fig. 2.2 Procedure for linear springing assessment by comparative method**

#### 302. Long-term fatigue damage excluding hydro-elastic effect

- **1.** **1**. Long-term fatigue damage excluding hydro-elastic effect is calculated in accordance with **Pt.3, Annex 3-3, 6.** of **Guidance relating to Rules for the Classification of Steel Ships**. The stress transfer function used in the calculation of fatigue damage is obtained by simulation with a rigid body model, and the calculation of the stress transfer function is in accordance with **101**.
- **2.** **2**. Instead of performing a separate simulation with the rigid body to calculate the stress transfer function excluding the elastic effect as **1**. above, it may be obtained by removing the high frequency range from the stress transfer function calculated according to **101**. The range which is to be removed from the original stress transfer function is an area over 90% of the first natural frequency for ship hull.
- **3.** **3**. The fatigue damage, $D _{L-RGD}$, for the rigid body is defined as long-term fatigue damage obtained from 1. or 2. above.

#### 303. Calculation of the linear springing coefficient and long-term fatigue damage

- **1.** **1**. Linear springing coefficient, $f _{SPR1}$, is defined as follows:
  $f _{SPR1} = \frac{D _{L-SPR}}{D _{L-RGD}}$
- **2.** **2**. The long-term fatigue damage, $D _{SPR1}$, including linear springing by comparative method is derived as follows:
  $D _{SPR1} =f _{SPR1} D$
  $D$ = damage by spectral fatigue analysis, see **Pt.3, Annex 3-3**, 6. (5) **(B)** of **Guidance relating to Rules for the Classification of Steel Ships**.
- **3.** The fatigue life,$T _{F, SPR1}$, considering linear springing for the members subject to fatigue strength assessment is calculated according to the following formula:
  $T _{F, SPR1} = \frac{T _{D}}{D _{SPR1}}$
  $T _{D}$ = design fatigue life, in years. ![](images/image10.png)
