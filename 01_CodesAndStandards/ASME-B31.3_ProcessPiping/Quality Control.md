# Inspection and Examination
An Inspector is responsible to ensure that the requirements of the code for inspection, examination and testing are met.
Rights and Qualifications of the Inspector are provided in ASME B31.3

## EXAMINATION
Examination is the quality control functions performed by the manufacturer (for components), fabricator or erector.
The Code requires that each piping installation (components and workmanship) be examined prior to initial operation.
The extent of required examination depends on the fluid service. Examination requirements are provided for the following fluid services:
- Normal Fluid Service
- Category D 
- Elevated Temperature
- High Pressure 
- High Purity
- Category M
- Severe Cyclic Conditions

In the examination, the code requires:
- any item with a defect be repaired or replaced
- new work be reexamined by the same methods, to the same extent, and by the same acceptance criteria as required for the original work

### Types of Examinations in ASME B31.3 Chapter VI:
- Visual
- Magnetic Particle
- Liquid Penetrant
- Radiographic
- Ultrasonic
- In-process
- Weld coupon

#### Visual Examination (VT)
*   **Description:** The primary, baseline inspection method using the naked eye (sometimes aided by mirrors, magnifiers, or weld gauges). It checks for surface defects, alignment, weld profiles, and signs of leakage.
*   **Fluid Service Application:** **All Fluid Services.** ASME B31.3 requires a minimum percentage of visual examination for every piping category (Category D, Normal, Severe Cyclic, High Pressure, and Category M). For example, it requires 100% VT for Severe Cyclic and Category M fluid services.


#### Magnetic Particle Examination (MT)
*   **Description:** A method used to detect surface and slightly subsurface discontinuities in **ferromagnetic** materials (like carbon steel). Magnetic particles are applied to the material while it is magnetized; defects distort the magnetic field and trap the particles.
*   **Fluid Service Application:** **Severe Cyclic, High Pressure, and Category M Services.** It is often used to inspect structural attachments, branch connections, and socket welds where volumetric inspection (like Radiography) is difficult to perform due to the geometry.
*   **Notes:**
    - Examination of Castings is covered in Par. 302.3.3
    - Examination of welds and of components other than castings are to be performed in accordance with ASME BPVC, Sec. V, Art. 7

#### Liquid Penetrant Examination (PT)
*   **Description:** A dye-penetrant method used to find surface-breaking defects (cracks, porosity, laps) in **non-magnetic** materials (like Austenitic Stainless Steel or copper alloys), though it can be used on carbon steel as well. The dye seeps into cracks and is drawn out by a developer.
*   **Fluid Service Application:** **Severe Cyclic, High Pressure, and Category M Services.** It is standard practice for checking root passes and completed welds on stainless steel piping networks where MT cannot be used.
*   **Notes:**
    - Examination of Castings is covered in Par. 302.3.3
    - Examination of welds and of components other than castings are to be performed in accordance with ASME BPVC, Sec. V, Art. 6

#### Radiographic Examination (RT)
*   **Description:** A volumetric examination method that uses X-rays or Gamma rays to view the internal structure of a weld. The radiation passes through the weld onto a film or digital sensor, creating a shadowgraph that reveals internal flaws like slag inclusions, lack of fusion, or porosity.
*   **Fluid Service Application:** **Normal, Severe Cyclic, and High Pressure Services.** Random radiography (typically 5%) is required for Normal Fluid Service butt welds. For Severe Cyclic and High Pressure services, the code increases this requirement drastically (often up to 100% full radiography depending on the design configuration).

#### Ultrasonic Examination (UT)
*   **Description:** A volumetric method that uses high-frequency sound waves sent into the material via a transducer. The waves bounce back when they hit an internal defect or the back wall of the material. Advanced methods like **PAUT (Phased Array Ultrasonic Testing)** are widely used as an alternative to RT (Appendix R ).
*   **Fluid Service Application:** **Severe Cyclic and High Pressure Services.** Like RT, it is used when full volumetric integrity is required for critical lines. It is preferred over RT when dealing with thick-walled piping or when radiation safety on a tight job site is a constraint.
*   **Notes:**
    - Appendix R was added in 2016 to provide alternative ultrasonic examination acceptance criteria based on fracture mechanics. It provides criteria for Ultrasonic Techniques that size the identified defects (not the amplitude of the reflected signal)

#### In-process Examination
*   **Description:** An examination that happens *during* the fabrication process rather than after completion. It involves visually checking fit-up, cleaning, preheat temperatures, the root pass, subsequent weld layers, and post-weld slag removal before the final weld cap is laid down.
*   **Fluid Service Application:** **Normal and Category M Services.** It is frequently used as an acceptable alternative to volumetric NDE (RT/UT) when the joint geometry makes standard volumetric testing impossible or impractical (e.g., certain branch connections), provided the owner/designer approves it.

#### Weld Coupon Examination
*   **Description:** This refers to production weld testing or the evaluation of specific sample coupons welded under the same conditions as the actual piping system. It is used to verify mechanical properties, impact toughness (Charpy V-notch), or hardness limits.
*   **Fluid Service Application:** **Low-Temperature, High Pressure, and Sour/Corrosive Services (e.g., NACE applications).** While not a "non-destructive" method applied to the finished pipe itself, coupon testing is critical when the fluid service operates at sub-zero temperatures requiring low-temperature impact testing, or when the chemistry must resist specific degradation mechanisms like hydrogen-induced cracking.

### Examination Personnel
Personnel performing NDT shall be qualified and certified for the method to be utilized as described in ASME BPVC Sec. V, Article 1, T-120(e) or (f)

The qualifications shall be documented by the employer's written practice in accordance with one of the following documents:
- The SNT-TC-1A, Personnel Qualification, and Certification in Nondestructive Testing
- The ANSI/ASNT CP-189, ASNT Standard for Qualification and Certification of Nondestructive Testing Personnel
- The national or international central certification programs, such as the ASNT Central Certification Program (ACCP) or ISO 9712:2012-based programs

## Testing
Leak Testing is required for every piping system before initial operation and after completion of applicable examination to ensure tightness
The 2016 edition added the ff. special leak test provisions:
- exempt threaded joints and tubing joints used to connect instruments to previously leak tested piping
- allow use of vaccuum leak testing as alternative to internal pressure leak testing of vacuum systems
- permit the owner to allow joints be covered by insulation during leak testing of Cat. D fluid service
- recommend consideration be given to performing additional leak test for assembled piping system prior to initial operation

### Types of Testing in ASME B31.3:
- Hydrostatic
- Pneumatic
- Hydrostatic-pneumatic
- Alternative
- Sensitive
- Helium Mass Spectrometer

#### Hydrostatic Leak Testing
*   **Description:** The standard and most widely used leak testing method. The piping system is completely filled with a liquid (**usually water**, unless there is a risk of freezing or process contamination) and pressurized to a minimum of 1.5 times the design pressure, adjusted for temperature.
*   **Fluid Service Application:** **Normal, Category D, and Category M Services.** It is the default, preferred baseline safety test for most process piping systems because water is virtually incompressible, making it significantly safer than pneumatic testing if a catastrophic rupture occurs.
*   **Notes:**
    - The hydrostatic test pressure at every point in a metallic piping system shall be as follows:
        - not less than 1.5 times the design pressure
        - when design temp > test temp, the min test pressure, at the point under consideration, shall be calculated as: **($P_T$)=1.5P($S_T$)/S**

#### Pneumatic Leak Testing
*   **Description:** A leak test performed using a gas (**typically dry compressed air or nitrogen**) instead of a liquid. Because compressed gas stores a tremendous amount of potential energy, this test carries a **high risk of explosive failure**. The pressure is strictly raised in gradual stages up to 1.1 times the design pressure, and a preliminary check is performed at the lower of 170 kPa (25 psi) or 50% of the test pressure.
*   **Fluid Service Application:** **Normal and Category M Services.** It is only used when hydrostatic testing is impractical—such as when the piping system cannot support the weight of water, when traces of moisture would ruin the catalyst/process fluid, or in cryogenic applications where water would freeze.

#### Hydrostatic-Pneumatic Leak Testing
*   **Description:** A hybrid testing method where the piping system is **partially filled with a liquid, and the remaining overhead vapor space is pressurized with a gas**. The test pressure limits follow the strict safety guidelines of a standard pneumatic test.
*   **Fluid Service Application:** **Normal Fluid Service.** This method is typically utilized for massive, large-diameter lines or complex vertical columns where filling the entire system with water would exceed the structural weight limits of the pipe racks or foundations, but a small liquid volume is still desired to reduce the total volume of compressed gas for safety.

#### Alternative Leak Testing
*   **Description:** A highly specialized testing alternative allowed only when both hydrostatic and pneumatic testing are deemed structurally impossible, damaging to the internals, or inherently dangerous. It requires a rigorous combination of 100% volumetric NDE (RT or UT) on all butt welds, surface NDE (PT or MT) on all other welds, and a final sensitive leak test.
*   **Fluid Service Application:** **Normal and High Pressure Services (with Owner Approval).** It is rarely used and serves as a last resort for critical process lines where neither water nor gas can be safely introduced prior to commissioning.

#### Sensitive Leak Testing
*   **Description:** A low-pressure gas test used to identify minuscule paths of leakage. The system is pressurized to at least the lesser of 105 kPa (15 psi) or 25% of the design pressure. A bubble-forming solution (like soapy water) is then applied to all joints, welds, and connections to look for forming bubbles.
*   **Fluid Service Application:** **Category M Fluid Service.** ASME B31.3 specifically mandates a sensitive leak test for Category M (highly toxic) fluid services to ensure absolute tight-integrity against minor gas escapes, often executed in tandem with other required tests.

#### Helium Mass Spectrometer Testing
*   **Description:** The most advanced and precise volumetric leak detection method, capable of spotting micro-leaks invisible to bubble testing. The piping system is evacuated or pressurized with helium gas, and a mass spectrometer "sniffer" probe detects the exact rate of helium atoms escaping the boundaries.
*   **Fluid Service Application:** **High Vacuum, Ultra-Pure Gas, and Highly Toxic/Hazardous Services.** While not explicitly listed as a standalone default category in the primary B31.3 test list, it is widely specified under the "Sensitive/Alternative" testing umbrellas for high-tech, semiconductor, or severe Category M piping systems where even a microscopic molecule of gas escape is unacceptable.

## Summary of Types

### Summary of Examination Types (ASME B31.3)

| Examination Type | Brief Description | Fluid Service Application |
| :--- | :--- | :--- |
| **Visual (VT)** | Baseline inspection using the naked eye, mirrors, or weld gauges to check alignment, surface defects, and weld profiles. | **All Fluid Services** (Minimum percentage required for all; 100% for Severe Cyclic and Category M). |
| **Magnetic Particle (MT)** | Detects surface and shallow subsurface defects in ferromagnetic materials using magnetic fields and particles. | **Severe Cyclic, High Pressure, and Category M** (Great for socket welds and branch connections). |
| **Liquid Penetrant (PT)** | Uses a color dye and developer to reveal surface-breaking cracks in non-magnetic materials (e.g., Stainless Steel). | **Severe Cyclic, High Pressure, and Category M** (Standard for stainless steel root and final passes). |
| **Radiographic (RT)** | Volumetric inspection using X-rays or Gamma rays to produce a shadowgraph of internal weld defects (e.g., slag, porosity). | **Normal, Severe Cyclic, and High Pressure** (Random 5% for Normal; up to 100% for critical/Severe Cyclic). |
| **Ultrasonic (UT)** | Volumetric inspection using high-frequency sound waves (or PAUT) to detect internal flaws and wall thickness. | **Severe Cyclic and High Pressure** (Preferred for thick-walled pipes or when radiation safety is a concern). |
| **In-process** | Step-by-step visual checks during fabrication (fit-up, preheat, root pass, slag removal) instead of just after completion. | **Normal and Category M** (Used with owner approval when joint geometry prevents RT/UT volumetric testing). |
| **Weld Coupon** | Destructive testing of separate sample production coupons to verify mechanical properties, toughness, and hardness. | **Low-Temperature, High Pressure, and Sour/Corrosive Services** (e.g., NACE applications). |

---

### Summary of Testing Types (ASME B31.3)

| Testing Type | Brief Description | Fluid Service Application |
| :--- | :--- | :--- |
| **Hydrostatic** | System is filled with liquid (typically water) and pressurized to a minimum of 1.5× design pressure. Safe baseline test. | **Normal, Category D, and Category M Services** (The default and preferred test method). |
| **Pneumatic** | System is pressurized gradually with gas (air/nitrogen) to 1.1× design pressure. High stored energy requires strict safety stages. | **Normal and Category M Services** (Only when moisture ruins process or piping weight limits prevent water filling). |
| **Hydrostatic-Pneumatic** | A hybrid test where the line is partially filled with liquid and the remaining vapor space is pressurized with gas. | **Normal Fluid Service** (Used for massive, large-diameter, or tall vertical lines to manage weight restrictions). |
| **Alternative** | Last-resort test combining 100% volumetric NDE (RT/UT), surface NDE (PT/MT), and a final sensitive leak test. | **Normal and High Pressure Services** (Requires Owner Approval; used only when hydrostatic/pneumatic tests are impossible). |
| **Sensitive** | Low-pressure gas test (lesser of 15 psi or 25% design pressure) using a bubble-forming solution applied to joints and welds. | **Category M Fluid Service** (Mandated to catch tiny micro-leaks of highly toxic fluids). |
| **Helium Mass Spectrometer** | Advanced volumetric method utilizing helium gas and a sniffer probe to detect atomic-level micro-leaks. | **High Vacuum, Ultra-Pure Gas, and Highly Hazardous Services** (Applied under Sensitive/Alternative criteria). |