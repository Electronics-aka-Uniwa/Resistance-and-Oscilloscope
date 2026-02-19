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

# README

## Resistance and Oscilloscope

This README provides an overview of **Lab 1**, submitted for the **Electronics** course at the University of West Attica. The lab focuses on **resistor measurements**, **D.C. voltage**, and **A.C. signal analysis**.

---

## Table of Contents

| Section | Folder / File                                         | Description                                  |
| ------: | ----------------------------------------------------- | -------------------------------------------- |
|       1 | `assign/`                                             | Assignment documents                         |
|     1.1 | `assign/Exercise-1st-Resistance-and-Oscilloscope.pdf` | Assignment instructions (English)            |
|     1.2 | `assign/Άσκηση-1η-Αντιστάσεις-και-Παλμογράφος.pdf`    | Assignment instructions (Greek)              |
|       2 | `components/`                                         | Lab components and equipment photos          |
|       3 | `docs/`                                               | Theory and reference documents               |
|     3.1 | `docs/Resistance-and-Oscilloscope.pdf`                | Theory (English)                             |
|     3.2 | `docs/Αντιστάσεις-και-Παλμογράφος.pdf`                | Theory (Greek)                               |
|       4 | `multisim/`                                           | Multisim projects and screenshots            |
|     4.1 | `multisim/Screenshots/`                               | Screenshots of Multisim simulations          |
|     4.2 | `multisim/*.ms14`                                     | Multisim project files                       |
|       5 | `photos-in-lab/`                                      | Photos of lab setup and measurements         |
|       6 | `visio/`                                              | Visio diagrams for circuits and measurements |
|       7 | `README.md`                                           | Project documentation                        |
|       8 | `INSTALL.md`                                          | Usage instructions                           |

---

## 1. Equipment & Components

- **Analog & Digital Training System:** MCP M21-7000A
- **Breadboard:** M21-7000A
- **Oscilloscope:** HAMEG HM203-5
- **Digital Multimeter:** MT8045
- **Resistors:** 1 kΩ, 27 kΩ, 39 kΩ

---

## 2. Project Objectives

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

## 3. Key Findings – Resistance Measurement

### 3.1 Theoretical & Simulative Analysis

The equivalent resistance for **resistors in parallel** was calculated.

For a **1 kΩ** and a **27 kΩ** resistor in parallel:

$$
R_{\text{eq}} = \frac{1 \times 10^3 \cdot 27 \times 10^3}{1 \times 10^3 + 27 \times 10^3} \approx 0.97 \text{ kΩ}
$$

- **Simulation Result (Multisim):** 964.286 Ω

---

## 4. Experimental Observations

Actual measurements differed slightly due to resistor **tolerance ±5%** (gold stripe):

- **1 kΩ Resistor:** 0.9893 kΩ
- **27 kΩ Resistor:** 27.12 kΩ
- **39 kΩ Resistor:** 38.43 kΩ

These results confirm that both theoretical calculations and simulations closely match practical measurements.
