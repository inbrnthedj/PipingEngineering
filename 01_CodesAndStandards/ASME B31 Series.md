# Comprehensive List of the ASME B31 Pressure Piping Series

*⚠️ **Disclaimer:** This repository contains personal study notes compiled as I learn the ASME engineering codes. These summaries are prone to errors and omissions and should **not** be used as a substitute for official engineering standards or professional calculations in real-world industrial plant design. Independent verification is highly encouraged, and constructive corrections are always welcome.*

## Introduction to the ASME B31 Series
The **ASME B31 Code for Pressure Piping** establishes minimum requirements for the design, materials, fabrication, erection, examination, inspection, testing, operation, and maintenance of piping systems. Rather than focusing on individual plant units or pressure vessels (which fall under the ASME BPVC), the B31 series governs the transport lines connecting equipment throughout various industrial facility types.

---

## 1. Active Primary Piping Codes

### ASME B31.1 - Power Piping
* **Scope:** Prescribes rules for piping systems typically found in electric power generating stations, industrial and institutional plants, geothermal heating systems, and central and district heating and cooling systems.
* **Core Fluids:** High-energy steam, boiler feedwater, condensate, and high-pressure water loops.

### ASME B31.3 - Process Piping
* **Scope:** The standard for piping found in petroleum refineries, chemical, pharmaceutical, textile, paper, semiconductor, and cryogenic plants.
* **Core Fluids:** A massive variety of process chemicals, raw materials, corrosive acids, hydrocarbons, and industrial gases.

### ASME B31.4 - Pipeline Transportation Systems for Liquids and Slurries
* **Scope:** Governs piping transporting liquids between plants, terminals, pumping stations, and distribution points.
* **Core Fluids:** Crude oil, liquid petroleum products, natural gas liquids, liquefied petroleum gas, carbon dioxide, liquid alcohol, and nonhazardous aqueous slurries (such as coal or ore mixed with water).

### ASME B31.5 - Refrigeration Piping and Heat Transfer Components
* **Scope:** Rules for piping systems carrying refrigerants and secondary coolants.
* **Core Fluids:** Ammonia, fluorocarbons, glycol loops, and brine solutions used in industrial refrigeration plants and commercial cooling.

### ASME B31.8 - Gas Transmission and Distribution Piping Systems
* **Scope:** Governs gas transmission pipelines, compressor stations, gas metering and regulation stations, gas mains, and service lines leading right up to the customer's meter.
* **Core Fluids:** Natural gas, synthetic gas, and liquefied petroleum gas (LPG) distributions.

### ASME B31.9 - Building Services Piping
* **Scope:** A simplified code for piping systems typically found in industrial, institutional, commercial, and public buildings, as well as multi-unit residential structures. It operates under low pressure and temperature limits.
* **Core Fluids:** Hot/chilled water, low-pressure steam, steam condensate, fuel gas, compressed air, and domestic water systems.

### ASME B31.12 - Hydrogen Piping and Pipelines
* **Scope:** Developed specifically to meet the unique structural requirements of handling hydrogen. It is divided into two distinct parts:
    - *Part IP:* Industrial piping networks (similar to process plant layouts).
    - *Part PL:* Pipelines transporting hydrogen over long geographical distances.
* **Core Fluids:** Gaseous and liquid hydrogen.

### Pipeline Standards
- B31.8S Managing System Integrity of Gas Pipelines
- B31Q Pipeline Personnel Qualification
- B31G Manual for Determining the Remaining Strength of Corroded Pipelines

---

## 2. Companion Enhancement Standards (Universal Engineering Support)
These standards do not provide rules for a specific plant sector. Instead, they act as design, thermal, or material math extensions that can be universally called upon by B31.1, B31.3, or any other primary code.

### ASME B31E - Standard for the Seismic Design and Retrofit of Above-Ground Piping Systems
* **Scope:** Provides localized math formulations and criteria for evaluating above-ground piping systems to withstand seismic events and earthquakes.

### ASME B31J - Standard Test Method for Determining Stress Intensification Factors (i-Factors) for Metallic Piping Components
* **Scope:** Establishes experimental and mathematical test methods to determine stress intensification factors (SIFs), flexibility factors, and sustained stress factors for metallic piping fittings and branch connections (e.g., tees, elbows, weldolets).

### ASME B31P - Standard Heat Treatments for Fabrication Processes
* **Scope:** Consolidates common heat treatment rules across multiple piping codes. It outlines procedures for preheating, interpass temperature control, and Post-Weld Heat Treatment (PWHT) to relieve residual crystalline stress in steels.

### ASME B31T - Standard Toughness Requirements for Piping
* **Scope:** Provides a uniform set of evaluation metrics regarding material toughness, Charpy V-notch impact testing, and low-temperature service limits to protect systems against brittle fracture.

---

## 3. Historic, Withdrawn, or Absorbed Codes
When auditing legacy piping systems or studying historical plant records, you may encounter references to these old designations:

* **ASME B31.2 - Fuel Gas Piping:** Withdrawn. Its scope was entirely absorbed by the National Fuel Gas Code (**NFPA 54 / ANSI Z223.1**).
* **ASME B31.6 - Chemical Plant Piping:** Never formally published as a standalone book. Its proposed content was fully integrated during development into **ASME B31.3**.
* **ASME B31.7 - Nuclear Power Piping:** Withdrawn. Its construction, quality assurance, and layout rules were moved directly into **ASME BPVC Section III**.
* **ASME B31.10 - Cryogenic Piping:** Never published as a separate volume. Cryogenic rules were integrated directly into the low-temperature design sections of **ASME B31.3**.
* **ASME B31.11 - Slurry Transportation Piping Systems:** Withdrawn. Its cross-country transport specifications were consolidated completely into **ASME B31.4**.

---

## Key Matrix: Pressure & Temperature Restrictions
When determining which code governs a simple utility system (like compressed air in a back room), designers often compare boundaries using this quick reference framework:

| Piping Code | Focus Sector | Pressure/Temp Bounds |
| :--- | :--- | :--- |
| **B31.1** | Power Plant Loops | High Energy / No Limit |
| **B31.3** | Process Plants & Refineries | Comprehensive / Severe Duty |
| **B31.9** | Light Building Utilities | Steam $\le$ 15 psi, Water $\le$ 350 psi, Temp $\le$ 250°F |
| **B31.4 / B31.8** | Cross-Country Pipelines | Transport Networks / Long Distance |