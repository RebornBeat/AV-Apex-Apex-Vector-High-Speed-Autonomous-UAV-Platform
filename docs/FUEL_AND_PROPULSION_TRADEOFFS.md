# Fuel & Propulsion Tradeoff Analysis

**Author:** RebornBeat
**Date:** June 2026

## 1. Engine Type Analysis
To achieve the 180° inversion and thrust stacking, engine selection is critical.
* **Turbojets:** Pure thrust, lighter, but extremely loud and fuel-inefficient at lower altitudes. Suitable for dash speeds but ruins the 6,000 km range.
* **Small Turbofans (High Bypass) - *Baseline Choice*:** Best fuel economy. By using 6 small turbofans (e.g., class of 1,500 lbf each), thrust stacking is maximized. If one engine fails, the drone retains 5/6th of its thrust and can still complete the inversion via differential vectoring.
* **Ramjets:** Cannot be used. The drone needs static thrust to execute the 90° vector flip from subsonic speeds.

## 2. Fuel Type Tradeoff Matrix

| Fuel Type | Energy Density (MJ/kg) | Cost per kg | Estimated Range | Pros / Cons |
| :--- | :--- | :--- | :--- | :--- |
| **Jet A (Kerosene)** | 43.1 | $1.20 | 6,300 km | **Baseline.** Cheap, stable, universally available. Easy to store in F1-F7 spine. |
| **Avgas (Aviation Gas)** | 44.0 | $1.80 | 6,400 km | Slightly higher density, but highly volatile. Turbofans cannot burn it efficiently. |
| **Liquid Hydrogen (LH2)** | 142.0 | $5.50 | 12,000+ km | Incredible range, but requires heavily insulated, pressurized spherical tanks. Physically impossible to fit into the F1-F7 cascading Apex spine without destroying the aerodynamics. |
| **RP-1 (Rocket Kerosene)**| 42.8 | $2.50 | 6,250 km | Highly refined, but offers zero aerodynamic benefit over Jet A while costing twice as much. |
| **Battery (Li-Ion)** | 1.0 | $100+ /kg equiv| < 200 km | Useless for high-speed jet flight. Mass destroys the 100% fuel fraction metric. |

## 3. Conclusion: Why Jet A is the Optimal Choice
Jet A (Kerosene) provides the ultimate balance of energy density, cost-effectiveness, and storage flexibility. It allows the F1–F7 nodes to be simply hollow structural tubes acting as fuel manifolds without requiring complex pressurization. It guarantees the $18,840 mission cost outlined in the manufacturing doc, making the AV-Apex the most efficient high-speed survey platform theoretically possible.
