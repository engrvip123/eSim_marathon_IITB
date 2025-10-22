# 📡 Single-Stage Common-Source Cascode LNA Design at 1.5 GHz

[![Built with eSim](https://img.shields.io/badge/Built%20With-eSim-blue)](#)
[![SPICE Simulator](https://img.shields.io/badge/Simulated%20In-Ngspice-orange)](#)
[![Open-Source](https://img.shields.io/badge/EDA-Open%20Source-success)](#)
[![Technology](https://img.shields.io/badge/PDK-IHP%20SG13G2-lightgrey)](#)

---

### **Author:** Vipul Sharma  
📧 [engr.vipul@gmail.com](mailto:engr.vipul@gmail.com)

---

## 🧩 Overview

This project presents the **design and simulation of a single-stage common-source cascode Low Noise Amplifier (LNA)** operating at **1.5 GHz**, implemented using the **IHP SG13G2 130 nm SiGe BiCMOS process** in an **open-source EDA environment (eSim + Ngspice)**.

Developed as part of the **eSim Marathon – Circuit Design and Simulation with IHP SG13G2**.

---

## 🎯 Objective

Design and simulate a **low-noise, high-gain LNA** with:

- Proper **input/output matching**  
- **Low power consumption**  
- **Improved gain and isolation** using cascode configuration  

---

## ⚙️ Circuit Design

### **Architecture**

The circuit employs:
- Common-source transistor (**M1**)  
- Cascode transistor (**M2**)  
- Gate inductor (**Lg**)  
- Source degeneration inductor (**Ls**)  
- Load inductor (**Ld**)  
- AC coupling capacitor (**Cp**)  

**Design features:**
- Inductive source degeneration → 50 Ω input match  
- Cascode topology → minimizes Miller capacitance, improves isolation  
- Resonant load network tuned for **1.5 GHz**

---

### **Circuit Schematic**

Add your schematic image here:

```markdown
![LNA Schematic](./images/lna_schematic.png)
