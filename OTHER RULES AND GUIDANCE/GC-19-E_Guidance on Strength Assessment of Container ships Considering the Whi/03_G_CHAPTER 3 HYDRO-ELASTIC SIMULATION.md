# Guidance on Strength Assessment of Container ships Considering the Whipping Effect

> OTHER RULES AND GUIDANCE / GC-19-E / 2025 / EN / Guidance

## CHAPTER 3 HYDRO-ELASTIC SIMULATION

### Section 1 General

#### 101. General

- **1.** The problem of hydro-elasticity of hull is solved by performing fluid-structure interaction analysis.
- **2.** The fluid domain assumes a three-dimensional potential flow and finds its solution by the boundary element method. Nonlinearity can be considered by using a weakly nonlinear approach that considers Froude-Krylov and hydrostatic forces (i.e. restoring forces) for the actual wetted area.
- **3.** When obtaining the hull response for whipping, it is sufficient to make the hydro-elastic simulation by idealizing the beam element which shows the two-dimensional characteristics of the cross section of hull. However, if the cross-sectional characteristics are susceptible to torsion, it should be idealized to allow for such consideration.
- **4.** The hydro-elastic simulation can be performed by direct integration method or mode superposition method.


### Section 2 Hydro-elastic simulation in time domain

#### 201. Simulation conditions

- **1.** **Wave incident angle**
  The contribution of whipping can be evaluated by performing an analysis based on an angle of 180° with respect to the wave. When directly calculating the long term analytical value considering the whipping, the calculation is performed at equidistant intervals of 30° or less considering all the encounter angles and long-term load analysis is performed. At this time, it is assumed that the probability of occurrence of each heading angle is the same. In order to reduce excessive nonlinear computation time, long-crested wave analysis may be performed without considering the short-crested wave effect.
- **2.** **Simulation time interval**
  The simulation time interval requires a sufficiently short time so that the impact pressure due to slamming, etc. can be appropriately reflected. The time interval is set to 0.025 second or less.
- **3.** **Simulation time duration**
  When applying the design wave method, the simulation time should include at least 35 wave periods. When the design sea state method is applied, the simulation requires long enough time to ensure the stability of the statistical analysis. It is recommended that the simulation time for short-term sea state is 3 hours or more.
- **4.** Regular waves constituting an irregular wave shall be at least four times longer than the length of the ship in case of long wavelength and in case of short wavelength, at least that frequency shall include the first vertical bending mode of the hull girder. There should be more than 150 regular waves between the minimum frequency and the maximum frequency.
- **5.** **Viscous roll damping**
  The viscous roll damping coefficient is recommended as a result of model testing or computational fluid dynamics, and a value of 5% can be used if there is no information.

#### 202. Fluid model

- **1.** The panels constituting the hull are to be of sufficient number of panels. In case of Rankine Source, more than 4,000 panels are recommended for semi-model as shown in **Fig. 3.1**, and the panel constituting the free surface of the fluid is appropriately created so that the radius of the free surface is more than three times the length of the ship.
  ![Fig 3.1 Rankine panel model for time domain analysis](https://kr-rule.krs.co.kr/Files/Document/GC-19-E/2024/image5.png)
  Fig 3.1 Rankine panel model for time domain analysis
- **2.** The panel model for nonlinear analysis models up to the height of the strength deck of ship.

#### 203. Structure model

- **1.** The three dimensional structural model of the ship should be able to express the entire ship, and the size of the elements constituting the model should be less than the minimum girder or floor spacing. For 1-D elements of secondary support members, beam elements with bending stiffness are to be used.
- **2.** Container loads should be applied considering the center of gravity of the stack as shown in **Fig3.2** and it is recommended to use elements that do not affect the stiffness of the structural model, e.g. Nastran RBE3 element. In case of 20ft container, it is possible to be applied by substituting with weight of 40ft container.
- **3.** Other loads should be applied properly considering the center of gravity.
- **4.** In the hydro-elastic analysis, the 3D structural model can be idealized as a one-dimensional beam theory model in order to save computation time when the structural response is calculated by direct integration method. In this case, a beam theory model which can consider torsional deformation should be used.
- **5.** The beam theory model should allow at least one beam element to be constructed for each bay of the container ship, and the beam element should take into consideration the central transverse section characteristics of each bay.
- **6.** In the case of container ships, it is difficult to idealize the beam element to reflect the torsional stiffness of the bulkhead. In this case, the torsional stiffness of the bulkhead can be considered by comparing the mode analysis results of the three-dimensional structure model and the mode analysis results of the beam element model as shown in **Fig 3.2** and then modifying the stiffness of the beam element model appropriately.
- **7.** The mode response frequency of the substituted one-dimensional beam theory model should be less than 5% for the first torsion and vertical bending modes compared to the results of the three-dimensional structure model.
- **8.** If there is no other data for structural damping, a 2% value of the critical damping can be used.
  ![Fig 3.2 Three-dimensional structural model of container ship](https://kr-rule.krs.co.kr/Files/Document/GC-19-E/2024/image6.png)
  Fig 3.2 Three-dimensional structural model of container ship

#### 204. Calculation of slamming load

- **1.** The slamming load can be calculated using the Generalized Wagner Model (GWM) or the two-dimensional wedge method. If other methods are used, sufficient data should be submitted to the Society for approval.
- **2.** The fore and aft sections where slamming loads may occur should be modeled with a sufficient number of sections to reflect the transition in slamming load over time. ![](images/image7.png)
