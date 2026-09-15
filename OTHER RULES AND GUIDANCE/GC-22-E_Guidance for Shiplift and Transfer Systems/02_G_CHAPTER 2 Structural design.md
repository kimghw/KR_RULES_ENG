# Guidance for Shiplift and Transfer Systems

> OTHER RULES AND GUIDANCE / GC-22-E / 2025 / EN / Guidance

## CHAPTER 2 Structural design

### Section 1 Structural design criteria

#### 101. Loading

- **1.** The design is to be based on the maximum distributed load per metre applied as a keel block loading along the centreline of the platform, see also **Ch 1, 103. 6**.
- **2.** The above loading is to be applied over the docking length of the platform and to the shore end of the platform where transfer takes place.
- **3.** The access and decked-in areas of the platform are also to be designed for:
  - **(1)** a superimposed load of 5.0 kN/m^2, uniformly distributed; and
  - **(2)** a point load of 10 kN at any one point;
    but higher values may be required to meet operational or equipment criteria. These loadings will not, normally, influence the lifting capacity specified in **Ch 1, 103. 1** nor the design loading given in **1** and **2**.
- **4.** Consideration is to be given to the horizontal forces arising from wind loading and transfer operations. The horizontal strength of the platform is to be capable of resisting the following forces:
  - **(1)** During transfer operations: a total horizontal force of 250 N/m^2 on the projected area of the docked vessel, plus the effects of the forces required to overcome friction in the transfer system. The friction force is to be taken as 1.5 percent of the cradle wheel loads when roller bearings are fitted to the wheels, and 4 percent when plain or bushed bearings are fitted.
  - **(2)** Where a vessel is supported on the platform and transfer operations are not being carried out: a total horizontal force calculated from a wind loading of 2.5 kN/m^2 (corresponding to a wind speed of 64 m/s) on the projected area of the docked vessel.
- **5.** Resistance to these forces may be provided by one or more of the following methods:
  - **(1)** A horizontal bracing system.
  - **(2)** A horizontal rigid platform.
  - **(3)** An adequate decking acting as a horizontal girder.

#### 102. Load combinations

- **1.** Shiplift platforms and transfer systems are to be considered for the design loadings resulting from the following load cases:
  - **(1)** Case 1(Operational): docking and transfer with no wind
    The shiplift and transfer system are to be considered with respect to its self-weight plus the applied vertical load from the docked ship and transfer system, together with the horizontal loads resulting from the traction/friction loads during transfer operations.
  - **(2)** Case 2(Operational): docking and transfer with wind
    The shiplift and transfer system are to be considered with respect to its self-weight plus the applied vertical load from the docked ship and transfer system, together with the horizontal loads resulting from the in-operation wind speed (actual data to be provided or 20 m/s will be used) applied to both the ship and the platform, and also to traction/friction loads during transfer operations.
  - **(3)** Case 3(Survival): ship on transfer system on land during extreme wind conditions
    he transfer system is to be considered with respect to its self-weight plus the applied vertical load from the docked ship, together with the horizontal load resulting from the extreme wind condition (actual data to be provided or 63 m/s will be used) applied to both the ship and the platform.
- **2.** In way of platform bilge blocks, the platform structure is to be designed for the maximum loads resulting from load case 2. This load is to be not less than 20 percent of the maximum distributed load per metre.

#### 103. Allowable stresses

- **1.** The allowable stress, $\sigma _{a}$, is to be taken as the failure stress of the component concerned, multiplied by a stress factor, $F$, which depends on the load case considered. The allowable stress is given by the general expression:
  $\sigma _{a} = F \sigma$ or $\tau _{a} = F \tau$
  $\sigma _{a}$ = allowable direct stress (N/mm^2)
  $\tau _{a}$ = allowable shear stress (N/mm^2)
  $F$ = stress factor
  $\sigma , \tau$ = failure stress (N/mm^2)
- **2.** The stress factors, F, for steels in which $\sigma _{y} /\sigma _{u} \leq 0.85$, are given in **Table 2.1.**
  $\sigma _{y}$ = yield stress of material (N/mm^2)
  $\sigma _{u}$ = ultimate tensile stress of the material (N/mm^2)

  | Load case | 1 | 2 | 3 |
  | --- | --- | --- | --- |
  | Stress factor, $F$ | 0.67 | 0.75 | 0.85 |
- **3.** For steel with $\sigma _{y} / \sigma _{u} > 0.85$, the allowable stress is to be derived from the following expression:
  $\sigma _{a} = 0.459 ( \sigma _{u} + \sigma _{y} )$
  $\tau _{a} = 0.266 ( \sigma _{u} + \sigma _{y} )$
- **4.** Steels with $\sigma _{y} / \sigma _{u} > 0.94$, are not generally acceptable and shall be specially considered.
- **5.** The failure stresses for the elastic modes of failure are given in **Table 2.2** Failure stress.

  | Mode of failure | Symbol | Symbol Failure stress |
  | --- | --- | --- |
  | Tension | $\sigma _{t}$ | 1.0 $\sigma _{y}$ |
  | Compression | $\sigma _{c}$ | 1.0 $\sigma _{y}$ |
  | Shear | $\tau$ | 0.58 $\sigma _{y}$ |
  | Bearing | $\sigma _{br}$ | 1.0 $\sigma _{y}$ |
- **6.** For components subjected to combined stresses, the following allowable stress criteria are to be used:
  - **(1)** $\sigma _{xx} \leq \sigma _{a}$
  - **(2)** $\sigma _{yy} \leq \sigma _{a}$
  - **(3)** $\tau _{o} < \tau _{a}$
  - **(4)** $\sigma _{e} = \sqrt {\sigma _{xx} ^{ 2} - \sigma _{xx} \sigma _{yy} + \sigma _{yy} ^{ 2} +3 \tau _{o} ^{ 2}} \leq 1.1 \sigma _{a}$
    $\sigma _{xx}$ = applied stress in x direction (N/mm^2)
    $\sigma _{yy}$ = applied stress in y direction (N/mm^2)
    $\tau _{o}$ = applied shear stress (N/mm^2)
- **7.** The allowable stresses may be reduced in areas where openings in the structure may lead to the creation of stress concentrations.
- **8.** The safety factor in sheaves, shackles and other loose items are to comply with the requirements of **Pt 9, Ch 2** of the Rules.
- **9.** Items of structure which are subjected to wind forces only, irrespective of load combination, may be determined on the basis of a stress factor of $F =0.85$.

#### 104. Rope and chain factors of safety

- **1.** The safety factor required for ropes used to raise and lower the platform is to be not less than 3 to 1 based upon the certified breaking strength of the rope and the maximum rope tension. The maximum rope tension is to be calculated from the rated capacity of the hoists with an allowance for the cumulative effect of sheave friction and wire rope stiffness of 1.5 percent for ball or roller bearings and 5 percent for plain or bushed bearings.
- **2.** The safety factor required for chains used to raise and lower the platform is to be not less than 3.0 to 1.0 based upon the certified breaking strength of the chain and the maximum chain tension. The maximum chain tension is to be based upon the rated capacity of the hoist. In view of the possibility of stress corrosion cracking, grade 80 or similar type, alloy chain should not be used.
- **3.** Increased safety factors may be required where:
  - **(1)** The hoisting speed of the platform exceeds 0.5 m/mm.
  - **(2)** The mode of operation of the hoist system may produce significant shock loading.
  - **(3)** A less onerous inspection replacement programme than the Society's is envisaged in the case of installations certified but not classed.

#### 105. Materials

- **1.** Materials are to comply with the requirements of **Pt 2, Ch 1** and **Pt 9, Ch 2, 103.** of the Rules. Steel for the primary strength members is to comply with **Table 2.3**.

  | Design temperature<br>$T$ (°C) | Thickness $t$ (mm) | Steel grade |
  | --- | --- | --- |
  | \(10 t ≤ 40 A/AH |   |   |
  | \(10 t ≤ 40 A/AH | 40 < t ≤ 80 | D/DH |
  | \(10 t ≤ 40 A/AH | t > 80 | E/EH |
  | \(0 t ≤ 20 A/AH |   |   |
  | \(0 t ≤ 20 A/AH | 20 < t ≤ 25 | B/AH |
  | \(0 t ≤ 20 A/AH | 25 < t ≤ 40 | D/DH |
  | \(0 t ≤ 20 A/AH | t > 40 | E/EH |
  | \(-10 t ≤ 12.5 B/AH |   |   |
  | \(-10 t ≤ 12.5 B/AH | 12.5 < t ≤ 25.5 | D/DH |
  | \(-10 t ≤ 12.5 B/AH | t > 25.5 | E/EH |
  | \(-25 t ≤ 40 D/DH |   |   |
- **2.** Consideration may, however, be given to steel complying with an appropriate national standard, but tests to the satisfaction of the Society will be required to demonstrate the suitability of the steel.
- **3.** Alternative proposals in respect of the notch tough characteristics of the material will be considered when the service location of the particular installation is such that low temperatures are not climatically probable. ![](images/image4.png)
