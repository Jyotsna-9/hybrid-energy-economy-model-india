# hybrid-energy-economy-model-india
Masters Thesis
# Hybrid Energy–Economy Modelling of Decarbonisation Pathways in India

## Overview
This repository presents a **hybrid integrated assessment modelling framework** developed to analyse long-term decarbonisation pathways in India under climate constraints.

The model combines:
- **Top-down Computable General Equilibrium (CGE)** modelling (IMACLIM-IND)
- **Bottom-up energy system modelling** (AIM/Enduse)

The framework is designed to simulate **economy-wide transitions (2030–2050)** under alternative climate policy scenarios, capturing interactions between:
- macroeconomic structure  
- sectoral energy demand  
- technology transitions  
- emissions constraints  

---

## Model Architecture

The modelling framework integrates two complementary approaches:

### 1. CGE Model (Top-Down)
- Represents the **macroeconomic structure of the Indian economy**
- Based on **Input–Output (IO) tables and national accounts**
- Captures:
  - sectoral production (KLEM structure: capital, labour, energy, materials)
  - price dynamics  
  - consumption and trade  

### 2. Energy System Model (Bottom-Up)
- Technology-explicit representation of:
  - power generation  
  - industry  
  - transport sectors  
- Captures:
  - energy demand by sector  
  - technology costs and efficiencies  
  - fuel substitution and electrification  

### 3. Model Coupling (Hybrid Framework)
The two models are linked through an **iterative coupling mechanism**:

- CGE → provides:
  - sectoral output  
  - energy demand  
  - price signals  

- Energy model → provides:
  - technology pathways  
  - energy mix  
  - emissions outcomes  

The system iterates until **convergence between economic structure and energy system configuration** is achieved.

---

## Model Formulation (Conceptual)

### Objective
The framework evaluates **feasible and policy-constrained transition pathways**, balancing:
- economic activity  
- energy system transformation  
- emissions reduction  

### Key Components

**Decision Variables**
- Energy demand by sector  
- Technology adoption levels  
- Sectoral outputs  

**Constraints**
- Carbon emissions constraints (1.5°C / 2°C scenarios)  
- Energy balance constraints  
- Technology capacity and efficiency limits  

**Outputs**
- Emissions trajectories  
- Energy mix evolution  
- Sectoral economic impacts  
- System-level trade-offs  

---

## Data & Calibration

A key contribution of this work is the construction of a **hybrid Input–Output dataset**, integrating:

- National IO tables  
- Energy balance data  
- Sectoral energy consumption  

Adjustments include:
- Treatment of **captive coal consumption**  
- Inclusion of **traditional biomass use**  
- Correction for **energy sector accounting inconsistencies**  

This enables **consistent linkage between economic and energy system representations**.

---

## Scenarios

The model evaluates multiple long-term transition pathways:

- **Business-as-Usual (BAU)**  
- **2°C Scenario**  
- **1.5°C Scenario**
- KLEM .jpg

Scenarios differ in:
- carbon constraints  
- technology deployment rates  
- structural economic adjustments  

---

## Key Insights

- Deep decarbonisation is **technically feasible**, but requires:
  - large-scale structural transformation  
  - rapid deployment of low-carbon technologies  

- Significant **trade-offs emerge between economic growth and emissions reduction**, particularly in industry and energy sectors  

- Energy system transformation requires:
  - expansion of low-carbon electricity  
  - increased system flexibility  
  - cross-sectoral coordination  

---

## Repository Structure

---

## Reproducibility

To run the model:

1. Install required dependencies:
  
2. Run model scripts: 
3. Outputs will be generated in `/results`

---

## Limitations

- Static or quasi-static modelling structure  
- Limited representation of uncertainty  
- Aggregated sectoral resolution  
- Data constraints in IO–energy integration  

---

## Future Work

Planned extensions include:

- Dynamic modelling of transition pathways  
- Integration of **hydrogen systems and sector coupling**  
- Enhanced representation of **storage and system flexibility**  
- Incorporation of **uncertainty and stochastic modelling approaches**  

---

## Author

**Jyotsna Rani**  
M.Sc. (Gold Medalist), Jamia Millia Islamia  

Research focus:  
Energy systems modelling | Integrated assessment | Decarbonisation pathways  

GitHub: https://github.com/Jyotsna-9  

---
