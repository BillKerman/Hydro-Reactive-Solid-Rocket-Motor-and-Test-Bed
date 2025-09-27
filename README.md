
# Hydro‑Reactive Rocket Motor Test Stand

**Modular 4‑DoF hydro‑reactive rocket motor test stand**

> High‑pressure (30 bar), high‑temperature (2000 K) dual‑chamber vessel with multi‑angle water injection and interchangeable exhaust nozzles. All components optimized for manufacturability and validated using coupled thermal‑structural FEA.

---

## Overview

This repository contains the CAD, analysis, experimental data, and simulation inputs for a modular rocket motor test stand designed and validated for hydro‑reactive testing. The system supports: multi‑angle water injection, interchangeable nozzles, and a dual‑chamber architecture capable of sustained operation at design pressures and temperatures.

## Highlights

* **CAD / Mechanical Design:** SOLIDWORKS assemblies and part models for a modular 4‑DoF test stand and dual‑chamber motor vessel.
* **Design Specs:** Design pressure 30 bar (nominal), design temperature up to 2000 K, modular nozzle interfaces, and multi‑angle water injection ports.
* **Structural & Thermal Analysis:** Analytical stress calculations (Lamé, von Mises), fatigue (S–N method), transient heat transfer (lumped‑mass approximation), and coupled thermal–structural FEA in ANSYS for verification.
* **Propellant & Experimental Work:** Fabrication workflow for APCP (vacuum casting), strand‑burner test data and empirically derived burn‑rate coefficients.
* **Ballistics & Performance:** Internal ballistic simulations driven by NASA CEA outputs and empirical burn‑rate data; OpenMotor inputs for chamber‑pressure estimation and motor‑casing sizing.

## Design & CAD

* SOLIDWORKS used for full system CAD and parametric part design.
* Modular interfaces for nozzle and injector swapping to support rapid instrumentation and nozzle geometry studies.
* Design choices were driven by manufacturability: standardized fasteners, fillets for stress reduction, simplified weld/prep geometry, and accessible inspection ports.

## Analysis & Validation

### Analytical checks

* **Static/pressure stress:** Lamé’s solution for thick‑walled vessels used to estimate hoop and radial stress bounds.
* **Yield & failure index:** von Mises stress criterion applied to compare with material yield strength.
* **Fatigue:** S–N curve approach for expected cyclic loading; Miner’s rule used for cumulative damage estimation.
* **Transient thermal response:** Lumped‑mass approximation used for initial transient estimates and to size thermal time constants for FEA boundary conditions.

### FEA verification

* Coupled thermal–structural simulations were run in ANSYS to validate analytical results and to capture local stress concentrations, thermal gradients, and transient behavior under expected worst‑case loadings.
* Results correlated against analytical solutions (Lamé, lumped

  <img width="1561" height="788" alt="Screenshot 2025-07-11 0504465" src="https://github.com/user-attachments/assets/ba252187-a7cf-4226-a3eb-29458c987589" />
    
  <img width="1338" height="775" alt="image" src="https://github.com/user-attachments/assets/7af757d6-c24c-48ab-a3c0-a6073fa3cd31" />

  <img width="1338" height="775" alt="image" src="https://github.com/user-attachments/assets/ff68f6fd-b265-4583-85e6-f8c316b50e82" />
