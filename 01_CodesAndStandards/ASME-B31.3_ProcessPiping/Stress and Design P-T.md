### Design Pressure
The pressure at the most severe condition of coincident internal or external pressure and temperature (minimum or maximum) expected during service, except as provided in para. 302.2.4.

Par. 302.2.4 - Allowances for Pressure and Temperature ð20Þ Variations:
 "Occasional variations of pressure, temperature, or both may occur in a piping system."

Pressure design is covered for the following components:
 - straight pipe
 - branch Connections
 - bends
 additional:
 - miter bends
 - closures
 - flanges
 - blanks
 - reducers

### Design Temperature
It is the temperature at which, under the coincident pressure, the greatest thickness or highgest component rating is required in accordance with Paragraph 301.2

#### Par. 301.2.1 - Design Pressure - General
1. The design pressure of each component shall not be less than the pressure at the most severe condition of coincident internal or external pressure and temperature (min or max) **except during service as provided in par. 302.2.4**.
2. The most severe condition is that which results in the greatest required component thickness and the highest component rating.
3. When more than one set of pressure-temp conditions exist for a piping system, the conditions governing the rating of components conforming to listed standards may differ from the conditions governing the rating of components designed in accordance with **par. 304**.
4. When a pipe is separated into individual pressure-containing chambers (including jacketed piping, blanks, etc.), the partition wall shall be designed on the basis of the most severe coincident temperature (min or max) and differential pressure between the adjoining chambers expected during service, **except as provided in par. 302.2.4**.

#### Impact Test Requirements
The **Design Minimum Temperature** may establish special design and material qualification requirements. 

See Table 323.2.2 "Requirements for Low Temperature Toughness Tests for Metals"

### Stress Values

#### Allowable Stress Values
The specified tensile and yield strength values are the minimum required in the materials specifications

For Metallic piping materials covered under B31.3, allowable stress values are provided. The values are the lowest of:
- 1/3 of the specified min tensile strength (at room temp)
- 1/3 tensile strenght at temperature
- 2/3 specified min yield strenght (at room temp)
- 2/3 min yield strength at temperature
- average stress for a minimum creep rate of 0.01% / 1000h
- 2/3 avg. stress for creep rupture in 100,000h
- 80% minimum stress creep rupture in 100,000h

#### Allowable Displacement Stress Range
S_A = allowable displacement stress range in accordance with eq. (1a and 1b), MPa (psi)
SL = stress due to sustained loads in systems where supports may be active in someconditions and inactive in others
 - in the 2014 edition, the max value of SL is required to be used in calculating allowable stress range for ALL conditions


#### ASME B31.3 Stress Range Limitation Note

In the ASME B31.3 2012 edition, the maximum basic allowable stresses ($S_c$ and $S_h$) used to calculate the displacement stress range were limited to **20,000 psi (138 MPa)** because high-strength steels have fatigue strengths similar to more common steels.

As a result of this cap, the absolute maximum allowable displacement stress range ($S_A$) under ideal conditions became limited to **60,000 psi (414 MPa)**.

#### NOTE: Mathematical Context
The maximum "liberal" allowable displacement stress range is calculated using the equation:

$$S_A = f \cdot [1.25 \cdot (S_c + S_h) - S_L]$$

Under ideal conditions where the stress range reduction factor $f = 1.2$ and sustained longitudinal stress $S_L = 0$, capping $S_c$ and $S_h$ at $20,000 \text{ psi}$ sets the absolute upper ceiling:

$$S_A = 1.2 \cdot [1.25 \cdot (20,000 + 20,000) - 0] = 60,000 \text{ psi} \ (414 \text{ MPa})$$
