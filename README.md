# 🔋 2kWh Li-ion Battery Pack with Custom BMS

## 🚀 Overview

This project presents the design and implementation of a **2kWh Li-ion battery system** built for real-world energy applications.  
The system consists of **280 Li-ion cells**, organized into **40 groups (7 cells per group)**, with a focus on **safety, reliability, and performance optimization**.

---

## ⚙️ System Architecture

- 🔋 Total Cells: 280 Li-ion cells  
- 🔗 Configuration: 40 groups × 7 cells  
- ⚡ Output: Designed for high-capacity energy systems  
- 🔌 Charging System: Modified and calibrated for safe operation  

---

## 🧠 Key Engineering Challenges

### 1️⃣ Cell Matching & Grouping (Critical Challenge)

Each Li-ion cell has:
- Different internal resistance  
- Different behavior under load and charging  

👉 To solve this:

- Developed a **battery testing system (Arduino + Embedded C)**  
- Used **Python-based data analysis** to evaluate cells  
- Grouped cells into matched sets for balanced performance  

💣 This ensured:
- Stable operation  
- Increased lifespan  
- Improved system reliability  

---

### 2️⃣ Charging System Optimization

- Studied and modified the charger for safe Li-ion operation  
- Calibrated output to ensure proper charging per group  
- Ensured safe charging behavior across all battery groups  

---

### 3️⃣ Custom BMS Design (PIC16F688)

Designed a **custom protection system** using a microcontroller:

- 📊 Per-group voltage monitoring  
- 🔌 Charging cutoff at safe voltage levels  
- 🔋 Load cutoff to prevent deep discharge  
- ⚡ MOSFET-based control for charge/load switching  

---

### 4️⃣ Safety & Protection

Implemented multiple protection layers:

- Overcharge protection  
- Over-discharge protection  
- Overcurrent protection using shunt resistor  
- Load control to prevent excessive current draw  

---

## 🔥 Key Features

✔ Data-driven battery grouping (Arduino + Python)  
✔ Custom BMS using PIC microcontroller  
✔ Multi-layer safety system  
✔ Scalable architecture for larger energy systems  
✔ Real-world deployment ready  
