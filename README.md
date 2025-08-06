# ♻️ Lithium-Ion Battery Recycling Plant Design

A comprehensive, modular plant design for recycling lithium-ion batteries using hydrometallurgy, pyrometallurgy, and advanced separation techniques. Includes kinetic modeling, green chemistry, and process simulation tools for recovering Li, Co, Ni, Mn, and Cu.

---

## 📘 Project Overview

This project presents a full-scale engineering design for a lithium-ion battery (LIB) recycling facility. As battery use surges in electric vehicles and energy storage, recycling becomes essential to reduce environmental impact, prevent unethical mining, and close the loop on critical materials.

The plant integrates **hydrometallurgical**, **pyrometallurgical**, and **hybrid processes** to treat a wide variety of LIB chemistries — including LFP, NMC, LCO, and NCA — even in mixed, damaged, or unsorted conditions.

---

## 🎯 Objectives

- Recover >90% of high-value materials (Li, Co, Ni, Mn, Cu)
- Minimize emissions and effluent through green process design
- Avoid reliance on virgin or unethical cobalt mining
- Enable circular economy for LIBs
- Validate process feasibility via kinetic models and simulations

---

## ⚙️ Technology Stack

### 🧩 Shared Front-End Processing
- **Sorting** by chemistry
- **Automated Discharging**
- **Shredding** under cooling
- **Separation** of black mass, casings, and foils

---

### 🧪 Line A: Cobalt-Rich Batteries (LCO, NMC, NCA)
- Method: Hydrometallurgy  
- Key Features:
  - CSTR leaching (H₂SO₄ + H₂O₂)
  - Solvent extraction (Co, Ni, Mn)
  - Lithium crystallization  
- Simulated in **PRO/II**

---

### 🔋 Line B: LFP Batteries (Fe-Based)
- Method: Green Hydrometallurgy  
- Key Features:
  - Delithiation using **CO₂ + H₂O₂**
  - Low-temperature, low-energy process
  - Avrami kinetics (Ea ≈ 13.9–15.7 kJ/mol):contentReference[oaicite:0]{index=0}
  - FePO₄ product suitable for cathode reuse

---

### 🔥 Line C: Mixed/Unknown Chemistries
- Method: Pyrometallurgy + optional hydromet  
- Key Features:
  - Plasma/electric arc smelting
  - Slag leaching for Li
  - Electrorefining for Ni/Co

---

### 🧯 Line D: Damaged/Swollen Batteries
- Method: Inert Pyro + Hydro Hybrid  
- Features:
  - Sealed nitrogen handling
  - Real-time off-gas monitoring
  - Safety-first sealed chamber design

---

## 📈 Technical Highlights

- **Kinetics**:
  - LCO: Shrinking core model (gas crust resistance):contentReference[oaicite:1]{index=1}
  - NMC: Dual control (diffusion + surface reaction):contentReference[oaicite:2]{index=2}
  - LFP: Avrami growth model (n=1), fast solid-state transformation:contentReference[oaicite:3]{index=3}

- **Simulation**: PRO/II used for Line A; MATLAB modeling for kinetics

- **Green Chemistry**:  
  - CO₂ buffering to reduce acid waste  
  - Solvent reuse (e.g., DMG, P204, C272)  
  - Lithium carbonate crystallization

---

## 📂 Repository Structure

| File | Description |
|------|-------------|
| `Executive_Summary.pdf` | Complete design summary |
| `Kinetics_LCO.pdf` | Leaching kinetics for LiCoO₂ (acid-reductive) |
| `Kinetics_LFP.pdf` | Green delithiation of LFP using CO₂ + H₂O₂ |
| `Kinetics_NCA.pdf` | Kinetic modeling of NCA leaching |
| `Ternary_Separation.pdf` | Solvent extraction & selective recovery from NMC |
| `README.md` | Project overview (this file) |
| `LICENSE` | MIT License for reuse |

---

## 🤝 Collaboration & Use

You're welcome to:
- Use this design for research or educational purposes
- Reference kinetic models or flowsheets
- Build upon this to create your own lab-scale or pilot-scale systems
- Contribute insights, modeling upgrades, or data

📬 **We welcome collaboration from**:
- Battery recyclers
- Chemical & process engineers
- Sustainability researchers
- Circular economy advocates

---

## 📜 License

This project is released under the **MIT License**.  
Documents (PDFs) and models are free to use, modify, and redistribute with attribution.

> See [LICENSE](./LICENSE) for full details.

---

## 🔗 Citation

If you use this project in academic or technical work, please cite it as:

