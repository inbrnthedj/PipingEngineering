# Design Conditions and Criteria

According to ASME B31.1, a Power Piping System shall be designed for the most severe conditions of coincident pressure, temperature, and loading expected during service.

### Design Conditions to Consider
- Pressure
- Temperature
- Ambient influences (cooling/heating effects, atmospheric corrosion)
- Dynamic effects (impact, wind, earthquake, relief valve reaction)
- Weight effects (live loads, dead loads, snow, ice, fluid density)

### Design Criteria & Limits
1. Pressure-Temperature ratings for piping components
2. Allowable stress values ($S$)
3. Limits for sustained, displacement, and occasional stresses

### Wall Thickness Allowances
- Corrosion or erosion allowance
- Threading and grooving depth allowance
- Bending allowance (wall thinning during fabrication)
- Mechanical strength requirements

---

## Allowable Stress Values
For power piping, allowable stress values ($S$) are provided in **Appendix A** ("Allowable Stresses Tables") based on material specification and maximum design temperature.

### Design Temperature
The component design temperature is generally assumed to be the maximum temperature of the fluid. For uninsulated piping, the design temperature may be reduced below the fluid temperature based on testing or engineering calculations (typically taking into account ambient heat transfer and wall thickness).

---

## Pressure Design of Straight Pipe

Pressure design determines the minimum required wall thickness ($t_m$) for internal pressure.

### 1. Formula when Outside Diameter ($D_o$) is fixed:

![Fixed OD Formula](<tm_OD fixed.png>)

*Alternative LaTeX format:*
$$t_m = \frac{P \cdot D_o}{2(SE + P \cdot y)} + A$$

### 2. Formula when Inside Diameter ($d$) is fixed:

![Fixed ID Formula](<tm_ID fixed.png>)

*Alternative LaTeX format:*
$$t_m = \frac{P \cdot d + 2A(SE + P \cdot y)}{2[SE - P(1 - y)]} + A$$

### Parameter Definitions:
- **$t_m$** = Minimum required wall thickness (including allowances), in. (mm)
- **$A$** = Additional thickness allowances (corrosion/erosion depth + mechanical threading/grooving allowance), in. (mm)
- **$D_o$** = Outside diameter of pipe, in. (mm)
- **$d$** = Inside diameter of pipe, in. (mm)
- **$P$** = Internal design gage pressure, psig [kPa (gage)]
- **$S$** = Basic allowable stress for material at design temperature, psi (MPa)
- **$E$** = Longitudinal weld joint efficiency factor (or **$F$** for casting quality factor)
- **$y$** = Temperature coefficient (per ASME B31.1 Table 104.1.2(A))
- **$W$** = Weld joint strength reduction factor (for creep-range operating temperatures per Para. 102.4.7)

---

## Components and Joints
The ASME B31.1 Code imposes specific pressure, temperature, and mechanical limitations on components and joining methods.

### Components
- **Fittings and Bends:** Elbows, miters, tees, reducers
- **Valves:** Pressure-temperature ratings, bonnet closures
- **Flanges, Gaskets, and Bolting:** ASME B16.5 / B16.47 alignment

### Joints
- **Welded:** Butt welds, socket welds, fillet welds
- **Brazed and Soldered:** Temperature/fluid limitations
- **Expansion/Mechanical:** Flanged, threaded, flared, and expansion joints

---

## Flexibility Analysis
Flexibility is provided by adding layout changes, fittings, bends, offsets, and expansion loops to absorb thermal expansion.

Key analysis principles under ASME B31.1 (Para. 119):
- Based on nominal dimensions of pipe and fittings.
- Accounts for bending moments and torsional moments.
- **Cold Modulus of Elasticity ($E_c$):** Used for calculating expansion stress ranges.
- **Hot Modulus of Elasticity ($E_h$):** Used for calculating reactions (forces and moments) on equipment and supports.
- Incorporates **Flexibility Factors ($k$)** and **Stress Intensification Factors ($i$)** for components per Appendix D.