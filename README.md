# Lithium-Ion Battery Recycling Plant Design (Ongoing Project)

**A modular lithium-ion battery recycling plant combining hydrometallurgy, pyrometallurgy, and advanced separation. Line A and Line B have been fully modeled and simulated. Lines C and D are currently under development.**

---

## Project Overview

This project is an ongoing engineering effort to design a comprehensive, scalable, and sustainable lithium-ion battery (LIB) recycling facility. It includes completed modeling for:

- **Line A:** Cobalt-rich batteries (LCO, NMC, NCA) — hydrometallurgy
- **Line B:** Iron-based batteries (LFP) — green hydrometallurgy with CO₂ and H₂O₂

Future development is planned for:
- **Line C:** Mixed/unknown chemistries — pyrometallurgy + hybrid
- **Line D:** Damaged/swollen batteries — inert atmosphere pyro-hydro hybrid
- **Improvements to Line A and Line B code

---

## Current Status

| Line | Chemistry Type         | Methodology         | Status       | Code/Model Available |
|------|------------------------|---------------------|--------------|----------------------|
| A    | LCO, NMC, NCA          | Hydrometallurgy     | Completed    | `Line A MATLAB Code` |
| B    | LFP                    | Green Hydromet      | Completed    | `Line B MATLAB Code` |
| C    | Mixed chemistries      | Pyrometallurgy +    | In progress  | Not yet implemented  |
| D    | Damaged/swollen LIBs   | Inert Pyro + Hydro  | In progress  | Not yet implemented  |

---

## Key Deliverables

- MATLAB simulations for Line A and Line B, with kinetic modeling
- Integrated kinetic models for:
  - **LiCoO₂** leaching (shrinking-core model) [`LiCoO2_kinetics.pdf`]
  - **NCA** kinetics [`NCA_kinetics_3.pdf`]
  - **LFP** green delithiation with Avrami modeling [`larouche-et-al-2023-kinetics-mech...`]
  - **Ternary LIB separation and recovery** [`Separation and recovery of nickel...`]
- MIT License for open use

---

## Methods & Approaches

### Line A (Hydromet for Co-Rich Batteries)
- **Chemistries**: LCO, NMC, NCA
- **Reagents**: H₂SO₄, H₂O₂
- **Simulation**: MATLAB CSTR model
- **Kinetics**: Shrinking core, crust-limited diffusion

### Line B (Green Hydromet for LFP)
- **Chemistry**: LiFePO₄
- **Reagents**: CO₂ + H₂O₂
- **Model**: Avrami-based nucleation/growth
- **Simulation**: MATLAB batch reactor code

---

## Next Steps

- [ ] Develop and simulate **Line C** (mixed battery stream)
- [ ] Implement **Line D** process for damaged LIBs under inert conditions
- [ ] Perform lifecycle assessment and environmental modeling
- [ ] Visualize flowsheets and generate block flow diagrams
- [ ] Invite collaboration and peer review

---

## Repository Contents

| File | Description |
|------|-------------|
| `LICENSE` | MIT License file |
| `README.md` | This project overview |
| `LiCoO2_kinetics.pdf` | Leaching kinetics and modeling of LiCoO₂ |
| `NCA_kinetics_3.pdf` | Kinetics of NCA leaching |
| `larouche-et-al-2023-kinetics-mech...` | Green delithiation modeling of LFP |
| `Separation and recovery of nickel...` | Solvent extraction & precipitation for NMC |
| `Line A MATLAB Code` | Reactor model for Co-rich batteries |
| `Line B MATLAB Code` | Green hydromet model for LFP |

---

## License

This project is released under the **MIT License**.  
You are free to use, adapt, and build on this work for research, education, or commercial applications with attribution.

---

## Contributions Welcome

This is an evolving project. If you're interested in:
- Battery recycling process modeling
- Hydromet or pyrometallurgical systems
- Emissions control and sustainability
- Academic-industry collaboration

Feel free to open an issue or submit a pull request. Let’s accelerate ethical, circular, and sustainable battery recycling together.





