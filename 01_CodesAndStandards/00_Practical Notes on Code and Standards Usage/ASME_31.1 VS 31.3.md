# Difference between ASME B31.1 and ASME B31.3

*⚠️ **Disclaimer:** This repository contains personal study notes compiled as I learn the ASME B31 piping codes. These summaries are prone to errors and omissions and should **not** be used as a substitute for official engineering standards or professional calculations in real-world industrial plant design. Independent verification is highly encouraged, and constructive corrections are always welcome.*

## ASME B31.1 - Power Piping
* **Plants:** Electric power generating stations, cogeneration plants, district heating/cooling systems, and boiler plants.
* **Fluids:** Mostly Water and Steam at high temperatures and pressures.

## ASME B31.3 - Process Piping
* **Plants:** Petroleum refineries, chemical plants, pharmaceutical facilities, semiconductor plants, and cryogenic facilities.
* **Fluids:** A massive variety of Fluids, many of which could be highly dangerous. Specifically, the code defines six main fluid services:
    - **Normal Fluid Service** – The standard catch-all category for non-severe fluids that do not fit into any other specialized category.
    - **Category D Fluid Service** – Low-hazard, non-flammable, non-toxic fluids operating under 150 psi (1035 kPa) and between -29°C and 186°C.
    - **Category M Fluid Service** – Highly toxic fluids where even a single, small exposure can cause serious, irreversible health damage.
    - **High-Pressure Fluid Service** – Systems where the pressure exceeds the limits allowed by standard ASME B16.5 Class 2500 ratings.
    - **Elevated Temperature Fluid Service** – Piping operating at temperatures high enough to cause material creep or a loss of strength.
    - **High Purity Fluid Service** – Services requiring extreme cleanliness and specialized fabrication to prevent product contamination.

## Summary Comparison Table

| Feature | ASME B31.1 (Power Piping) | ASME B31.3 (Process Piping) |
| :--- | :--- | :--- |
| **Typical Facility** | Power Plants, Boiler Rooms | Refineries, Chemical/Pharma Plants |
| **Typical Fluids** | Steam, Water | Chemicals, Hydrocarbons, Acids, Gases |
| **Fluid Classification** | Uniform (based on pressure/temp) | Categorized (Category D, M, High Purity, etc.) |
| **Base Design Margin** | More conservative (thicker walls) | Less conservative (unless fluid is hazardous) |
| **Inspection (NDE)** | Prescriptive based on temperature/pressure | Dictated entirely by Fluid Service Category |
| **Associated Equipment** | ASME Section I (Boilers) | ASME Section VIII (Pressure Vessels) |