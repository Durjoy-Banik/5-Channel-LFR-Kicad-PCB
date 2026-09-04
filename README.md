# 5-Channel Line Follower Robot (LFR) - Custom PCB Design

An end-to-end Robotics and Hardware Engineering project featuring a custom chassis-shaped PCB, optimized signal routing, and manufacturing-ready deliverables.

---

## 📌 Project Overview
The goal of this project was to design a professional, error-free, custom chassis-shaped 5-channel Line Follower Robot (LFR) PCB using KiCad (v9.0). It integrates power management, sensor interfacing, and motor driving capabilities directly onto a single board layout.

---

## 🛠️ Core Technical Highlights

### 1. Hardware & Component Integration
* **Microcontroller:** Arduino Uno (Shield-compatible design)
* **Sensors:** HW-871 5-Channel IR Sensor Array with dedicated pin headers
* **Actuation & Power:** L298N Motor Driver integration for dual-DC motor control

### 2. PCB Design & Signal Integrity (KiCad v9.0)
* **Custom Form Factor:** Custom chassis-shaped PCB outline engineered for mechanical stability and sleek aesthetics.
* **Routing Geometry:** Clean, professional 45-degree trace routing on Front Copper layer (F.Cu).
* **Trace Width:** Strict **0.4mm trace width** maintained for optimal current capacity and signal reliability.
* **Industrial Validation:** Achieved **0 Design Rule Check (DRC) errors and 0 warnings**.

### 3. Fabrication & Manufacturing Deliverables
* Fully generated production-ready fabrication files including:
  * **Gerber Files** (F.Cu, B.Cu, Mask, Silk, Edge.Cuts)
  * **NC Drill Files** (.drl)
  * **ZIP Archive** ready for direct submission to PCB manufacturers (e.g., JLCPCB, PCBWay).

---

## 📂 Repository Structure

```text
├── Schematic/          # KiCad schematic files (.kicad_sch)
├── PCB_Layout/         # KiCad PCB layout files (.kicad_pcb)
├── Gerber_Files/       # Fabrication-ready Gerber and Drill files (.zip)
└── Assets/             # Circuit diagrams and project documentation media

