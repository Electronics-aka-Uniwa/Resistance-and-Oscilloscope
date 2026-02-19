<p align="center">
  <img src="https://www.especial.gr/wp-content/uploads/2019/03/panepisthmio-dut-attikhs.png" alt="UNIWA" width="150"/>
</p>

<p align="center">
  <strong>UNIVERSITY OF WEST ATTICA</strong><br>
  SCHOOL OF ENGINEERING<br>
  DEPARTMENT OF COMPUTER ENGINEERING AND INFORMATICS
</p>

<p align="center">
  <a href="https://www.uniwa.gr" target="_blank">University of West Attica</a> ·
  <a href="https://ice.uniwa.gr" target="_blank">Department of Computer Engineering and Informatics</a>
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

<hr>

<p align="center">
  <strong>Supervision</strong>
</p>

<p align="center">
  Supervisor: Panagiotis Giannakopoulos, Professor
</p>
<p align="center">
  <a href="https://ice.uniwa.gr/en/emd_person/panagiotis-yannakopoulos/" target="_blank">UNIWA Profile</a> ·
  <a href="https://www.linkedin.com/in/panos-yannakopoulos-b9b6987/" target="_blank">LinkedIn</a>
</p>

<p align="center">
  Supervisor: Ioannis Amorginos, Applications Lecturer
</p>
<p align="center">
  <a href="https://ice.uniwa.gr/en/emd_person/ioannis-amorginos/" target="_blank">UNIWA Profile</a> ·
  <a href="https://www.linkedin.com/in/%CE%B1%CE%BC%CE%BF%CF%81%CE%B3%CE%AF%CE%BD%CE%BF%CF%82-%CE%B3%CE%B9%CE%AC%CE%BD%CE%BD%CE%B7%CF%82-7185b088/" target="_blank">LinkedIn</a>
</p>

<p align="center">
  Co-supervisor: Eleni Tsalera, Academic Scholar
</p>
<p align="center">
  <a href="https://ice.uniwa.gr/academic_sc_ho/" target="_blank">UNIWA Profile</a> ·
  <a href="https://scholar.google.com/citations?user=-LnaZGgAAAAJ&hl=en" target="_blank">Scholar</a>
</p>
<p align="center">
  Co-supervisor: Michalis Diamantopoulos, Applications Lecturer
</p>
<p align="center">
  <a href="https://ice.uniwa.gr/emd_person/22674/" target="_blank">UNIWA Profile</a>
</p>

</hr>

---

<p align="center">
  Athens, November 2022
</p>

---

<p align="center">
  <img src="https://devxplained.eu/images/o/s/c/i/l/oscilloscope-rc-filter-7075e27f.jpg?g-982d5237" width="250"/>
</p>

---

# INSTALL

## Resistance and Oscilloscope

This guide explains how to set up the **Resistance and Oscilloscope Lab** project, including prerequisites, software setup, and running the simulations.  
The repository contains Multisim simulations, documentation, and experimental instructions for **resistor measurements**, **D.C. voltage**, and **A.C. signal analysis**.

---

## 1. Prerequisites

Before running the project, ensure the following software and hardware requirements are met:

### 1.1 Software

#### 1.1.1 Multisim

- **NI Multisim 14 or higher**
- Required for running the simulation files (`*.ms14`) included in the repository.

#### 1.1.2 PDF Reader

- Any PDF viewer to open assignment instructions and theory documents:
  - `assign/Exercise-1st-Resistance-and-Oscilloscope.pdf`
  - `docs/Resistance-and-Oscilloscope.pdf`

#### 1.1.3 Optional Tools

- **Microsoft Visio** or compatible software to view circuit diagrams in `visio/`.
- Spreadsheet software (Excel, LibreOffice Calc) for calculations if needed.

---

## 2. Hardware

- **Analog & Digital Training System:** MCP M21-7000A
- **Oscilloscope:** HAMEG HM203-5
- **Digital Multimeter:** MT8045
- **Resistors:** 1 kΩ, 27 kΩ, 39 kΩ
- **Breadboard:** Included with the training system

> Hardware is optional if performing only simulation-based exercises.

---

## 3. Installation & Setup

### 3.1 Clone the Repository

```bash
git clone https://github.com/Electronics-aka-Uniwa/Resistance-and-Oscilloscope.git
cd Resistance-and-Oscilloscope
```

### 3.2 Open Multisim Simulations

1. Launch NI Multisim.
2. Navigate to the `multisim/` folder in the repository.
3. Open any `.ms14` project file, for example:

```bash
multisim/Lab1_Resistor_Oscilloscope.ms14
```

4. Run the simulation using the Simulate button.
5. Verify measurements and compare with theoretical calculations provided in `docs/`.

### 3.3 Access Documentation

1. Open the `docs/` folder:
   - English: `Resistance-and-Oscilloscope.pdf`
   - Greek: `Αντιστάσεις-και-Παλμογράφος.pdf`

2. Open the `assign/` folder for lab instructions:
   - English: `Exercise-1st-Resistance-and-Oscilloscope.pdf`
   - Greek: `Άσκηση-1η-Αντιστάσεις-και-Παλμογράφος.pdf`

3. Optional: Open Visio Diagrams
   - Navigate to `visio/`
   - Open `.vsd` or `.vsdx` files in Microsoft Visio to view the circuit diagrams.

---

## 4. Running Experiments

### 4.1 Resistor Measurements

- Use color codes and theoretical formulas to calculate resistance.
- Compare results with Multisim simulations.
- Optionally, measure resistors with a multimeter.

### 4.2 D.C. Voltage Analysis

- Set up the circuit in Multisim or on the breadboard.
- Measure voltage values and verify against theoretical calculations.

### 4.3 A.C. Signal Analysis

- Apply sinusoidal or square signals.
- Use the oscilloscope (real or simulated) to measure:
  - Period
  - Frequency
  - Amplitude
