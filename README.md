# Flow-Analysis-on-an-Atmospheric-Re-Entry-Capsule

This project presents a comprehensive CFD analysis of an atmospheric re-entry capsule, modeled after NASA’s Apollo AS-202 Command Module. The simulation investigates external aerodynamic behavior, pressure variations, Mach number distributions, and aerodynamic heating experienced during high-speed atmospheric re-entry.

---

## 🚀 Objective

To analyze the hypersonic flow over a blunt-body re-entry capsule and evaluate:

- Pressure distribution
- Mach number variation
- Temperature rise due to aerodynamic heating

across multiple atmospheric altitudes and velocities.

---

## 🧪 Methodology

- 📐 Geometry: Designed in **ANSYS DesignModeler**
- 🕸️ Meshing: Unstructured mesh with **inflation layers** for improved boundary resolution
- 🔬 Simulation Tool: **ANSYS CFX**
- 🌀 Turbulence Model: RNG k-ε model
- 🧪 Fluid Model: Compressible ideal gas
- 🌡️ Static Temperature: 245.5 K (approximate upper atmosphere)
- 🚀 Inlet Velocities: 5.09 – 7.92 km/s
- 📈 Pressure and velocity values adjusted for each altitude

---

## 📊 Results Summary

| **Altitude (km)** | **Pressure (Pa)** | **Temperature (K)** | **Mach Number** |
|-------------------|-------------------|----------------------|------------------|
| 54.6              | 3.24 × 10⁷        | 1.28 × 10⁴           | 16.11            |
| 70.0              | 7.78 × 10⁷        | 3.14 × 10⁴           | 25.61            |
| 77.2              | 5.18 × 10⁷        | 2.12 × 10⁴           | 20.92            |

- The **maximum temperature** and **pressure** were recorded at lower altitudes due to higher atmospheric density.
- High **Mach numbers** confirmed hypersonic conditions and strong shock formation in front of the capsule.

---

## 🧰 Tools & Technologies Used

- [ANSYS Workbench](https://www.ansys.com/products/platform/ansys-workbench) – Simulation platform
- ANSYS DesignModeler – 3D geometry modeling
- ANSYS Meshing – Mesh generation and control
- ANSYS CFX – Flow solver for compressible, turbulent flows

---

## 📚 Key Concepts

- Hypersonic aerodynamics
- Atmospheric re-entry dynamics
- Thermal protection systems (TPS)
- CFD-based simulation of external compressible flows

---
