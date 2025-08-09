# Design and Analysis of Basic Digital Blocks Using Cadence Virtuoso

This repository contains the **design, layout, simulation, and analysis** of fundamental digital circuit blocks implemented in **Cadence Virtuoso** as part of the **VLSI II Laboratory (EECE–458)** coursework at the **Military Institute of Science & Technology**.

---

## 📜 Overview
The project explores the complete VLSI workflow, from schematic capture to layout generation and performance evaluation, focusing on **Configurable Logic Blocks (CLBs)** and other essential digital components.  
Simulations were performed for both **combinational** and **sequential** logic to determine key performance metrics such as **setup time**, **critical frequency**, **average energy consumption**, **layout area**, and **Figure of Merit (FOM)**.

---

## ⚙️ Implemented Components
- **2-input NAND gate (2IPNAND)**
- **2-input OR gate (2IPOR)**
- **2×1 Multiplexer (2×1MUX)**
- **3-input NAND gate (3IPNAND)**
- **6T SRAM Cell**
- **8-bit SRAM**
- **8×1 Multiplexer (8×1MUX)**
- **D Flip-Flop (D-FF)**
- **Configurable Logic Block (CLB)**

---

## 📊 Key Analyses Performed
- **D-FF Setup Fixing** – Adjusting delay to achieve correct timing  
- **Worst-Case Delay Analysis** – Using state transition delay calculations  
- **Clock-to-Q Delay Measurement** – Determining optimal clock period (~93 ps)  
- **Critical Frequency Determination** – Found to be 86 ps for CLB sequential mode  
- **Average Energy Consumption** – CLB consumes 171.6 fJ over 500 cycles  
- **Layout Area Measurement** – CLB area is 5.28976 × 10⁻⁸ m² using SKILL scripting  
- **Figure of Merit (FOM)** – Calculated as 8.44182 × 10⁻³¹ J·s·m²  

---

## 🛠 Tools & Technologies
- **Cadence Virtuoso** – Schematic capture, layout, simulation  
- **ADE XL** – Energy and performance measurements  
- **SKILL IDE** – Automated layout area calculation  

---

## 📌 Conclusion
This project provided **hands-on experience** in digital IC design, from conceptual schematics to fully verified layouts, reinforcing both theoretical and practical VLSI design skills.  
The techniques and analysis workflows presented here are applicable to **research** and **industry-grade semiconductor design**.
