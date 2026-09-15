# Guidance for Fatigue Strength Assessment Including Springing

> OTHER RULES AND GUIDANCE / GC-35-E / 2025 / EN / Guidance

## CHAPTER 1 GENERAL

### Section 1 General

#### 101. Application

- **1.** This guidance is for assessing the fatigue strength of the hull structure taking into account the vibration response of the ship in waves and can be assessed in addition to **Pt.3, Annex 3-3** Guidance for the Fatigue Strength Assessment of Ship Structures of **Guidance relating to Rules for the Classification of Steel Ships** upon request by the applicant.
- **2.** The springing is caused by the wave load and the resonance of the hull girder. The effect of springing is important for a ship with large slenderness ratio with low hull girder natural frequency or large vessels. Whipping is a vibration response that occurs when impact load such as slamming is applied to a ship, and its effect is important for ships with characteristics such as high speed and large flare that can cause large slamming loads. Whipping is often evaluated in view of ultimate load, but this guidance evaluates the effect of whipping in terms of fatigue strength evaluation.
- **3.** Although this guidance cover vibration response analysis using computer simulation method and fatigue strength evaluation method by stress calculation, through a model test, the method of evaluating the fatigue strength of structural details by applying the stress concentration factor after measuring the vibration influence on the longitudinal bending moment and torsional moment can also be used.
- **4.** When evaluating the fatigue strength considering vibration response in waves other than those provided in this guidance, sufficient data on the applied theory and verification of program should be provided and be approved by the Society.

#### 102. Class Notations

“**SeaTrust(SPR1)**” or “**SeaTrust(SPR2)**” notation may be assigned upon request of the applicant(shipowner or shipbuilder), once review has been made in accordance with this guidance and is considered appropriate.


### Section 2 Assessment Procedure

#### 201. General

- **1.** The fatigue strength assessment procedure considering springing can be divided into a linear springing assessment procedure and a nonlinear springing assessment procedure taking into account whipping as shown in **Fig. 1.1**.
- **2.** The "**SeaTrust (SPR1)**" and "**SeaTrust (SPR2)**" notations are given for linear springing assessment procedure and nonlinear springing assessment procedure respectively.

#### 202. Linear springing assessment

- **1.** Based on the stress transfer function obtained from the results of linear hydro-elastic simulation, the effect of wave and hull resonance on the fatigue strength is evaluated in the frequency domain.
- **2.** Due to the linear approximation in ship motion, nonlinear springing and whipping can not be taken into account, but the simulation time can be shortened by calculation in the frequency domain.
  ![Fig. 1.1 Procedure for fatigue strength assessment including springing](images/image5.png)
  **Fig. 1.1 Procedure for fatigue strength assessment including springing****203. Nonlinear springing assessment**
- **1.** Effects of nonlinear springing and whipping on fatigue strength are considered and for this, the nonlinear hydro-elastic simulation in time domain is required.
- **2.** Nonlinear hydro-elastic simulation can be performed relatively similar to actual seagoing conditions, but it takes a long analysis time, therefore it is necessary to reduce analysis time through selection of dominant sea states on fatigue strength.

#### 204. Methods for calculating the fatigue damage

- **1.** For the linear springing and nonlinear springing assessment, the direct method or comparative method is used, respectively.
- **2.** The direct method is a method for calculating fatigue damage directly using stress results obtained from a hydro-elastic simulation. The procedure for analysis is similar to the linear spectral fatigue analysis method described in **Pt.3, Annex 3-3**, 6. of **Guidance relating to Rules for the Classification of Steel Ships**.
- **3.** The comparative method is a method for calculating fatigue damage by multiplying the fatigue damage for the rigid body by the springing correlation coefficient which is obtained by comparing the simulation result including the influence of hydro-elasticity with the result which not.


### Section 3 Assessment conditions

#### 301. Loading conditions

- **1.** For container ships, it is evaluated based on the loading condition which is expected to have the highest operation rate.
- **2.** When the loading conditions are clearly separated by full load and ballast condition, such as bulk carriers, ore carriers and tankers, the operating ratio of these two loading conditions should be taken into account.
- **3.** The ratio of periods during which the ship is not operated for loading, unloading and repair is excluded from the fatigue damage calculation.

#### 302. Speed

- **1.** The ship speed for fatigue assessment is to be taken as 2/3 of design speed.
- **2.** When there is speed information of the ship in accordance with significant wave height, relevant information can be used.

#### 303. Trading route and design fatigue life

The trading route and design fatigue life for evaluation follow the conditions in which the fatigue strength assessment were performed in accordance with the **Pt.3**, **Annex 3-3** of **Guidance relating to Rules for the Classification of Steel Ships**.


### Section 4 Hydro-elastic simulation

#### 401. General

- **1.** The hydro-elastic simulation is to be carried out based on fluid-structure interaction.
- **2.** The fluid domain assumes a three-dimensional potential flow and finds its solution by the boundary element method. Nonlinearity can be considered by using a weakly nonlinear approach that considers Froude-Krylov and hydrostatic forces (i.e. restoring forces) for the actual wetted area.

#### 402. Simulation conditions

- **1.** **Wave incident angle**
  Simulation is performed at equal intervals of 30° or less taking into account all wave headings. In this case, if there is route information of the ship, the probability of occurrence of the predicted wave incidence can be considered. Otherwise, it is assumed that the probability of occurrence of the wave incidence is the same.
- **2.** **Wave frequency**
  In the linear springing assessment, the number of wave frequencies should be large enough so that the frequency characteristic of the stress transfer function can be adequately expressed and at least 40 wave frequencies should be considered in the range where the high frequency includes at least the primary longitudinal bending mode of the hull. In the nonlinear springing assessment, there should be more than 150 regular waves between the minimum frequency and the maximum frequency.
- **3.** **Simulation time interval**
  The simulation time interval is recommended to be 0.025 second or less.
- **4.** **Simulation time duration**
  The hydro-elastic simulation for nonlinear springing assessment is recommended to be performed for more than 3 hours for each short-term sea state.
- **5.** **Viscous roll damping**
  The viscous roll damping coefficient is recommended as a result of model testing or computational fluid dynamics, and a value of 5% can be used if there is no information.

#### 403. Fluid model

- **1.** The panels constituting the hull are to be of sufficient number of panels. In case of Rankine Source, more than 4,000 panels are recommended for semi-model as shown in **Fig. 1.2**, and the panel constituting the free surface of the fluid is appropriately created so that the radius of the free surface is more than three times the length of the ship.
- **2.** The panel model for nonlinear analysis models up to the height of the strength deck of ship.

#### 404. Calculation of slamming load

- **1.** **1**. Slamming load calculation is performed in order to obtain the hull girder vibration responses caused by whipping.
- **2.** The slamming load can be estimated by including the three-dimensional effect, or a calculation method from two-dimensional sections using GWM(Generalized Wagner Model) can be used. Where it is limited to calculate the slamming load for all wave headings, it may be applied for head and stern seas only.

#### 405. Structural model for fatigue strength assessment

- **1.** **Structural model of ship**
  The three-dimensional structural model of the ship should be able to express the entire ship, and the size of the elements constituting the model should be less than the minimum girder or floor spacing. For secondary supporting members, beam elements with bending stiffness shall be used.
- **2.** **Model of fatigue strength assessment region**
  The finite element model of the structure is to consist of shell elements. At the hot spot region, the 4-noded quadrilateral shell elements of the size $t \times t$ are used, where $t$ is the plate thickness. The weld bead is not included in the finite element model. In order to determine the surface stress distribution of the shell element, fictitious beams without stiffness are put on the connection line of shell element and stress evaluation is to be performed by the structural analysis. Also, stress evaluation is to be obtained from the shell element by the structural analysis. In case, FE models are to be based on as built scantlings and the beam element stresses are calculated taking account of shear flexibility.
- **3.** **Mass modeling**
  It is recommended that cargo masses such as containers be modeled using elements that do not affect the stiffness(e.g. Nastran RBE3 element), taking into account the possible center of gravity.
- **4.** **Structural damping**
  In case of container ships, a 2% value of the critical damping can be used.For other vessels, relevant data should be submitted to the Society.
  ![Fig. 1.2 Rankine panel model for simulation](https://kr-rule.krs.co.kr/Files/Document/GC-35-E/2020/image6.png)
  **Fig. 1.2 Rankine panel model for simulation**

#### 406. Methods for calculating the stress

Since the hydro-elastic simulation, in the time domain, requires very large computational resource to accurately perform the structural analysis at every time interval for the global finite element model with considerable degrees of freedom, methods to reduce the computational resource required for structural analysis may be applied. This guidance adopts the modal superposition method and load conversion method, which are described follows.

- **1.** **Modal superposition method**
  - **(1)** The modal superposition method calculates structural stress responses by superposition of stress components obtained by modal response of ship hull vibration.
  - **(2)** Eigenmodes to be used in hydro-elastic simulation are selected on the basis of the ship hull vibration analysis.
  - **(3)** The stress transformation matrix with respect to selected eigenmodes for elements which will be performed of fatigue strength assessment is to be obtained.
  - **(4)** The stress time series is calculated by combining the time series of modal responses which are calculated from hydro-elastic simulation and the stress transformation matrix which is obtained from (3).
  - **(5)** In general, where the number of eigenmodes which are used in modal superposition is high, the accuracy of structural response can be improved. However, since a higher-mode including local deformation can make influence to structural response, the eigenmodes for modal superposition method are to be carefully chosen after verification.
- **2.** **Load conversion method**
  - **(1)** This method obtains ship hull vibration response by multiplying hull girder loads which are acting on cross section at ship longitudinal position obtained from hydro-elastic simulation to a stress transformation matrix of the global finite element model.
  - **(2)** The stress transformation matrix of finite element for which fatigue damage will be calculated is to be obtained by applying an unit hull girder load to the cross section where the finite element is.
  - **(3)** The magnitude of hull girder loads acting on cross section which is located in longitudinal position is to be calculated at every time interval in the time domain simulation. For cross sections at which hull girder loads are not calculated directly, the loads are to be estimated by interpolation.
  - **(4)** The stress of the target structural element is calculated by multiplying and superimposing the magnitude of each load component at the longitudinal position obtained in (3) to the stress transformation matrix for the unit load obtained in (2).
  - **(5)** The load conversion method is applicable conveniently to the hydro-elastic simulation of a simple structural model such as a beam model. However, since the accuracy of the application to an evaluation position where wave pressure or inertia force is dominant instead of hull girder loads may not be sufficient, particular attention is to be paid to application of the method.
- **3.** **Calculation of hot spot stress**
  The hot spot stress for the calculation of fatigue damage is to be estimated in accordance with **Pt.3, Annex 3-3**, 2. of **Guidance relating to Rules for the Classification of Steel Ships** using the analysis results obtained in **1**. or **2**. above. ![](images/image7.png)
