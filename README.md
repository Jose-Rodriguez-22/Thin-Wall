# Directed Energy Deposition Thin-Wall

### Transient Thermal Analysis of Moving Heat Source in Metal Additive Manufacturing

---

## 📌 Project Overview

This project investigates the thermal behavior of a thin-wall structure fabricated using Directed Energy Deposition (DED) metal additive manufacturing.

A transient thermal finite element analysis was performed in ANSYS to simulate the effect of a moving heat source along a stainless steel substrate. The study focuses on heat accumulation, temperature gradients, and thermal diffusion during the deposition process.

The objective was to understand how a moving beam influences temperature distribution and localized heat buildup in thin-wall metal structures.

---

## 🎯 Objective

- Model a parametric thin-wall geometry in SolidWorks
- Simulate a moving heat flux representing DED energy input
- Capture transient temperature evolution during deposition
- Evaluate heat accumulation and convection cooling
- Analyze thermal gradients within substrate and wall

---

## 🛠 Software & Tools

- CAD: SolidWorks
- Simulation: ANSYS Mechanical 2024
- Analysis Type: Transient Thermal

---

## 📐 Geometry Description

- Base height: 0.50 in
- Thin wall thickness: 0.12 in
- Total height: 3.00 in (±0.01 tolerance)
- Parametric geometry designed to reflect real-world AM substrate configuration

Mesh Details:

- Minimum element size: 0.5–1.0 mm (heat-affected zone)
- Number of elements: 616
- Number of nodes: 3724
- Hexahedral/Tetrahedral elements

---

## 🔬 Material Properties

**Stainless Steel 316**

- Density: 7.93 g/cm³
- Young’s Modulus: 193 GPa
- Yield Strength: 502 MPa
- Melting Temperature: 1350–1400 °C

Material temperature set near melting point (1350 °C) to simulate deposition conditions.

---

## 🌡 Thermal Simulation Setup

- Initial Temperature: 22 °C
- Moving Heat Flux Velocity: 0.005 m/s
- Source Power Intensity: 10,000 W/m²
- Simulation Duration: 5 seconds
- Minimum Step Time: 0.005 s
- Convection applied to exposed surfaces
- Fully constrained base to simulate rigid fixture

The moving heat flux traveled along the thin-wall path, simulating directed energy input during deposition.

---

## 📊 Key Results

- Maximum Heat Flux Achieved: **98,691 W/m²**
- Peak temperature concentrated along deposition path
- Gradual heat diffusion into substrate
- Convection effectively reduced peripheral temperature

Thermal contour results show localized heat accumulation near the beam path and smooth dissipation outward from the heat-affected zone :contentReference[oaicite:1]{index=1}.

Temperature graph illustrates steady thermal increase along the deposition line before cooling stabilization.

---

## 🧠 Engineering Insights

- Moving heat flux generates steep localized gradients
- Thin-wall geometry retains heat more intensely than substrate
- Substrate acts as heat sink, reducing excessive thermal buildup
- Convection significantly impacts cooling rate
- Thermal management critical in DED process stability

This simulation provides foundational understanding of process–thermal interactions in metal additive manufacturing.

---

## 🏗 Industrial Relevance

- Applicable to WAAM and DED systems
- Supports aerospace thin-wall structural fabrication
- Useful for predicting distortion risk
- Enables process parameter refinement
- Relevant to in-space and remote manufacturing

---

## 🚀 Key Competencies Demonstrated

- Moving heat source modeling
- Transient thermal FEA
- Mesh refinement in heat-affected zone
- Convection boundary modeling
- Additive manufacturing process simulation
- Thermal gradient interpretation

---

## 📎 Author

Jose Rodriguez  
Mechanical Engineering – University of Texas at Dallas  
Specialization: Additive Manufacturing & Process Simulation  

📧 jmr180004@utdallas.edu  
🔗 LinkedIn: https://www.linkedin.com/in/jose-m-rodriguez-/
