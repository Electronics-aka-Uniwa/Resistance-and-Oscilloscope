<p align="center">
  <img src="https://www.especial.gr/wp-content/uploads/2019/03/panepisthmio-dut-attikhs.png" alt="UNIWA" width="150"/>
</p>

<p align="center">
  <strong>UNIVERSITY OF WEST ATTICA</strong><br>
  SCHOOL OF ENGINEERING<br>
  DEPARTMENT OF COMPUTER ENGINEERING AND INFORMATICS
</p>

<hr/>

<p align="center">
  <strong>Electronics</strong>
</p>

<h1 align="center" style="letter-spacing: 1px;">
  Resistance and Oscilloscope
</h1>

<p align="center">
  <strong>Vasileios Evangelos Athanasiou</strong><br>
  Student ID: 19390005
</p>

<p align="center">
  <a href="https://github.com/Ath21" target="_blank">GitHub</a> ·
  <a href="https://www.linkedin.com/in/vasilis-athanasiou-7036b53a4/" target="_blank">LinkedIn</a>
</p>

<p align="center">
  Supervisor: Ioannis Amorginos, Applications Lecturer
</p>
<p align="center">
  <a href="https://ice.uniwa.gr/en/emd_person/ioannis-amorginos/" target="_blank">UNIWA Profile</a> ·
  <a href="https://www.linkedin.com/in/%CE%B1%CE%BC%CE%BF%CF%81%CE%B3%CE%AF%CE%BD%CE%BF%CF%82-%CE%B3%CE%B9%CE%AC%CE%BD%CE%BD%CE%B7%CF%82-7185b088/" target="_blank">LinkedIn</a>
</p>

<p align="center">
  Co-supervisor: Eleni Tsalera, Laboratory Teaching Staff
</p>
<p align="center">
  <a href="https://www.researchgate.net/profile/Eleni-Tsalera-2" target="_blank">UNIWA Profile</a>
</p>

<p align="center">
  Co-supervisor: Michalis Diamantopoulos, Lecturer in Applications
</p>
<p align="center">
  <a href="https://ice.uniwa.gr/emd_person/22674/" target="_blank">UNIWA Profile</a>
</p>

<p align="center">
  Athens, November 2022
</p>

---

# Project Overview

This README provides an overview of **Lab 1**, submitted for the **Electronics** course at the University of West Attica. The lab focuses on **resistor measurements**, **D.C. voltage**, and **A.C. signal analysis**.

---

## Table of Contents

| Section | Folder / File | Description |
|--------:|---------------|-------------|
| 1 | `assign/` | Assignment documents |
| 1.1 | `assign/Exercise-1st-Resistance-and-Oscilloscope.pdf` | Assignment instructions (English) |
| 1.2 | `assign/Άσκηση-1η-Αντιστάσεις-και-Παλμογράφος.pdf` | Assignment instructions (Greek) |
| 2 | `components/` | Lab components and equipment photos |
| 3 | `docs/` | Theory and reference documents |
| 3.1 | `docs/Resistance-and-Oscilloscope.pdf` | Theory (English) |
| 3.2 | `docs/Αντιστάσεις-και-Παλμογράφος.pdf` | Theory (Greek) |
| 4 | `multisim/` | Multisim projects and screenshots |
| 4.1 | `multisim/Screenshots/` | Screenshots of Multisim simulations |
| 4.2 | `multisim/*.ms14` | Multisim project files |
| 5 | `photos-in-lab/` | Photos of lab setup and measurements |
| 6 | `visio/` | Visio diagrams for circuits and measurements |
| 7 | `README.md` | Repository overview and instructions |

---

## Equipment & Components

- **Analog & Digital Training System:** MCP M21-7000A  
- **Breadboard:** M21-7000A  
- **Oscilloscope:** HAMEG HM203-5  
- **Digital Multimeter:** MT8045  
- **Resistors:** 1 kΩ, 27 kΩ, 39 kΩ  

---

## Project Objectives

1. **Resistor Resistance Measurement**  
   Calculate and measure resistor values using:
   - Color codes
   - Theoretical formulas
   - Simulation software

2. **D.C. Voltage Measurement**  
   Analyze and measure direct current both theoretically and experimentally.

3. **A.C. Measurement**  
   Measure signal period and calculate frequency.

---

## Key Findings – Resistance Measurement

### Theoretical & Simulative Analysis

The equivalent resistance for **resistors in parallel** was calculated.  

For a **1 kΩ** and a **27 kΩ** resistor in parallel:

$$
R_{\text{eq}} = \frac{1 \times 10^3 \cdot 27 \times 10^3}{1 \times 10^3 + 27 \times 10^3} \approx 0.97 \text{ kΩ}
$$

- **Simulation Result (Multisim):** 964.286 Ω  

---

### Experimental Observations

Actual measurements differed slightly due to resistor **tolerance ±5%** (gold stripe):

- **1 kΩ Resistor:** 0.9893 kΩ  
- **27 kΩ Resistor:** 27.12 kΩ  
- **39 kΩ Resistor:** 38.43 kΩ  

These results confirm that both theoretical calculations and simulations closely match practical measurements.

---

# Installation & Setup Guide  

This guide explains how to set up the **Resistance and Oscilloscope Lab** project, including prerequisites, software setup, and running the simulations.  
The repository contains Multisim simulations, documentation, and experimental instructions for **resistor measurements**, **D.C. voltage**, and **A.C. signal analysis**.

---

## Prerequisites

Before running the project, ensure the following software and hardware requirements are met:

### 1. Software

#### Multisim
- **NI Multisim 14 or higher**  
- Required for running the simulation files (`*.ms14`) included in the repository.

#### PDF Reader
- Any PDF viewer to open assignment instructions and theory documents:
  - `assign/Exercise-1st-Resistance-and-Oscilloscope.pdf`  
  - `docs/Resistance-and-Oscilloscope.pdf`  

#### Optional Tools
- **Microsoft Visio** or compatible software to view circuit diagrams in `visio/`.
- Spreadsheet software (Excel, LibreOffice Calc) for calculations if needed.

---

### 2. Hardware (Optional for Lab Experiments)

- **Analog & Digital Training System:** MCP M21-7000A  
- **Oscilloscope:** HAMEG HM203-5  
- **Digital Multimeter:** MT8045  
- **Resistors:** 1 kΩ, 27 kΩ, 39 kΩ  
- **Breadboard:** Included with the training system

> Hardware is optional if performing only simulation-based exercises.

---

## Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Electronics-aka-Uniwa/Resistance-and-Oscilloscope.git
cd Resistance-and-Oscilloscope
```

### 2. Open Multisim Simulations
1. Launch NI Multisim.
2. Navigate to the `multisim/` folder in the repository.
3. Open any `.ms14` project file, for example:
```bash
multisim/Lab1_Resistor_Oscilloscope.ms14
```
4. Run the simulation using the Simulate button.
5. Verify measurements and compare with theoretical calculations provided in `docs/`.

### 3. Access Documentation
1. Open the `docs/` folder:
    - English: `Resistance-and-Oscilloscope.pdf`
    - Greek: `Αντιστάσεις-και-Παλμογράφος.pdf`

2. Open the `assign/` folder for lab instructions:
    - English: `Exercise-1st-Resistance-and-Oscilloscope.pdf`
    - Greek: `Άσκηση-1η-Αντιστάσεις-και-Παλμογράφος.pdf`

4. Optional: Open Visio Diagrams
    - Navigate to `visio/`
    - Open `.vsd` or `.vsdx` files in Microsoft Visio to view the circuit diagrams.

---

## Running Experiments
### 1. Resistor Measurements
- Use color codes and theoretical formulas to calculate resistance.
- Compare results with Multisim simulations.
- Optionally, measure resistors with a multimeter.

### 2. D.C. Voltage Analysis
- Set up the circuit in Multisim or on the breadboard.
- Measure voltage values and verify against theoretical calculations.

### 3. A.C. Signal Analysis
- Apply sinusoidal or square signals.
- Use the oscilloscope (real or simulated) to measure:
  - Period
  - Frequency
  - Amplitude

