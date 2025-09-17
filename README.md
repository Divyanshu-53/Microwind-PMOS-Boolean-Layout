# Microwind-PMOS-Boolean-Layout
This project demonstrates the design and implementation of a Boolean expression using PMOS-only transistors in Microwind. It includes Boolean simplification, gate-level design, transistor-level schematic, stick diagram, Microwind layout, and simulation analysis with results and comparisons to CMOS

# PMOS-Only Boolean Function Layout Design (Microwind)

This repository contains the **VLSI Special Assignment Project** where a Boolean function is implemented **using only PMOS transistors**. The project includes the Boolean function derivation, gate-level diagram, transistor-level schematic, stick diagram, Microwind layout, and simulation results.

---

## 📌 Project Overview
- **Boolean Function Implemented**:  
  \[
  F = AB' + C(D' + A)
  \]  
  Rewritten and optimized for PMOS-only design:  
  \[
  F = \bigl((A' + B)(C' + D A')\bigr)'
  \]

- **Tools Used**:  
  - Microwind (layout and simulation)  
  - LaTeX (report preparation)  
  - Circuitikz (schematics in LaTeX)  

- **Key Learning Points**:  
  - Designing logic using PMOS-only implementation.  
  - Understanding duality and De Morgan transformations for transistor mapping.  
  - Creating stick diagrams and layouts in Microwind.  
  - Measuring rise time, fall time, propagation delay, and power.  

---

## 📂 Repository Structure
.
├── report/ # LaTeX source files and final PDF report
├── images/ # Layout screenshots, simulation results, diagrams
└── README.md # Project documentation (this file)

---

## 🖼️ Highlights
- **Gate-Level Diagram** (AOI/Universal mapping)  
- **Transistor-Level Schematic** (PMOS-only)  
- **Stick Diagram** with standard VLSI color coding  
- **Microwind Layout** of the function  
- **Simulation Results** with timing parameters  

---

## ⚖️ License
This project is released under the **MIT License** for code/resources and **CC-BY-NC** for the report/documentation.  
- You are free to use and adapt this project for learning purposes.  
- Please provide proper attribution if you reuse diagrams, code, or report content.  

---

## ✍️ Author
- **Divyanshu Kalal**  
  Roll No: 23BEC053  
  B.Tech Semester V, Nirma University

  - Reference Texts:  
  - Sung-Mo Kang & Yusuf Leblebici, *CMOS Digital Integrated Circuits – Analysis and Design*  
  - Neil Weste & David Harris, *CMOS VLSI Design*  
  - Pucknell & Eshraghian, *Basic VLSI Design* 
