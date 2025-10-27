# FSEV Steering & Braking System Documentation

This repository contains the detailed design, calculation, and simulation reports for the **Steering** and **Braking** subsystems of our Formula Student Electric Vehicle (FSEV). The aim is to document the complete design workflow — from conceptual decisions and analytical calculations to CAD modeling and simulation validation.

---

## Contents

### Steering System
- **Design Philosophy:** Focused on achieving precise handling and reduced steering effort using **Anti-Ackermann geometry** optimized for high-speed cornering stability.  
- **Design Calculations:**  
  - Ackermann and Anti-Ackermann angle derivation  
  - Turning radius and steering ratio computation  
  - Rack and pinion design parameters (module, pitch, teeth count)  
  - Steering effort estimation using force and torque balance    

---

### Braking System
- **System Layout:** Dual-circuit hydraulic braking system designed as per FSAE rules, with a **balance bar and twin master cylinder** setup.  
- **Calculations:**  
  - Brake force distribution (front/rear)  
  - Line pressure and pedal ratio determination  
  - Caliper torque, deceleration, and stopping distance analysis  
  - Thermal load estimation on brake discs during endurance cycles  
- **Component Design:**  
  - Pedal box assembly with adjustable bias  
  - Caliper and disc selection based on performance and packaging constraints  
- **Simulation Reports:**  
  - Thermal and structural FEA of the brake disc
---

## Tools Used
- **SolidWorks** — 3D CAD modeling  
- **Ansys Mechanical** — Thermal and structural analysis of braking components  

---
