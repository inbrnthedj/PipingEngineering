# ASME B31.3 Material Categorization: Listed, Unlisted, and Reclaimed

This document outlines the operational differences, design constraints, and engineering burdens associated with **Listed**, **Unlisted**, and **Reclaimed** materials as governed by **ASME B31.3 (Chapter III, Materials)**.

---

## 1. Listed Materials

### Definition
A **Listed Material** is any piping material or component that is explicitly specified and accepted within the tables of **ASME B31.3 Appendix A** (for metallic materials) or Appendix B. These materials conform to trusted standardization bodies vetted by the ASME B31.3 committee (such as ASTM, ASME SA/SB, or API specifications).

### Engineering & Design Rules
* **Predefined Properties:** Basic allowable stress values ($S$) across various temperature configurations are precalculated and mapped directly in Appendix A.
* **Code Calculations:** Standard analytical wall-thickness formulas (e.g., $t = \frac{PD}{2(SEW + PY)}$) can be utilized immediately without secondary verification of mechanical limitations.
* **Traceability Requirement:** Verification requires matching the Mill Test Report (MTR) against the applicable listed ASTM/ASME specification numbers.

### Common Examples
* **Pipes:** ASTM A106 Grade B (Carbon Steel), ASTM A312 TP316 (Stainless Steel).
* **Forgings / Flanges:** ASTM A105 (Carbon Steel), ASTM A182 F11 (Alloy Steel).

---

## 2. Unlisted Materials

### Definition
An **Unlisted Material** is a material that is **not** indexed in the Appendix A tables, but conforms to a published, public engineering specification covering raw chemistry, heat-treatment requirements, physical minimum properties, and robust mechanical testing protocols.

### Engineering & Design Rules
* **Calculated Stresses:** Because the code does not provide an allowable stress value ($S$), the design engineer assumes full liability to calculate it manually per **Paragraph 302.3.2**.
* **Safety Factors:** Allowable stress must be derived by applying strict code design margins to the material's verified Minimum Tensile Strength ($S_T$) and Minimum Yield Strength ($S_Y$) at the design temperature.
* **Operational Alignment:** The engineer must verify that all additional criteria—such as impact testing rules, fluid compatibility restrictions, and pressure/temperature boundaries—are fully assessed and satisfied.

### Common Examples
* High-performance proprietary nickel or titanium alloys that have not yet been formally adopted into the Appendix A framework.
* International or foreign national standard materials (e.g., specific EN/DIN or JIS specifications) required for global fabrication or matching imported equipment modules.

---

## 3. Reclaimed Materials

### Definition
**Reclaimed Materials** are salvaged or used piping components (such as pipes, valves, fittings, or structural members) that are decommissioned from an existing facility or asset and plan to be reinstalled into a new, separate piping layout.

### Engineering & Design Rules
* **Paragraph 323.1.4 Requirements:** Reclaimed material is permissible *only* if its baseline specification can be positively identified and validated as a listed standard or qualified as an unlisted material.
* **Inspection Protocol:** The engineer must execute strict cleaning, visual inspection, and non-destructive examination (NDE) to guarantee freedom from internal/external structural cracks, pit depth damage, or wall thinning.
* **Historical Degradation Factors:** The engineer must formally account for service history degradation. This includes reviewing past exposure to corrosive fluid media, tracking thickness allowances already sacrificed, and assessing damage from long-term high-temperature operations (such as creep or hydrogen attack).

---
## Other Notes

### Impact Tests
- Requirements for impact testing are provided in Table 323.2.2.
- Impact testing is required to be performed in accordance with ASTM A370 which covers Charpy V-notch impact testing.
- Exemptions to impact testing including low stress exemptions are provided.

### 2014 Edition: Fig. 323.2.2b for CS without impact testing
In the 2014 edition, the use of carbon steels without impact testing is applicable for piping:
 - in elevated temperature service
 - that is expected to experience shock loading or thermal blowing
 - contains welds between dissimilar materials
 - the code warns that calculation of stresses due to cold springing or misalignment should be included as part of the stress ratio

---

## Summary Comparison Matrix

| Technical Attribute | Listed Materials | Unlisted Materials | Reclaimed Materials |
| :--- | :--- | :--- | :--- |
| **Code Table Status** | Found directly in Appendix A / Appendix B. | Absent from the Appendix A tables. | Can be listed or unlisted; however, salvaging adds historical variables. |
| **Allowable Stresses ($S$)**| Precalculated across target temperatures. | Must be manually calculated by the engineer using code safety margins. | Based on the baseline identified spec, but down-rated if creep/wear is discovered. |
| **Specification Basis** | Approved ASTM, ASME SA/SB, or API standards. | Published public specs (e.g., EN, JIS, or proprietary alloy data sheets). | Original specification must be verified via physical or chemical testing. |
| **Primary Risk Managed** | Standard material manufacturing variations. | Unverified material response to code stress calculations. | Past field degradation, hidden defects, and fatigue tracking. |
| **Engineering Burden** | **Low:** Routine code design calculations. | **Medium:** Mandatory specification checking and stress limits derivation. | **High:** Mandatory field NDE, cleaning, verification testing, and lifecycle analysis. |