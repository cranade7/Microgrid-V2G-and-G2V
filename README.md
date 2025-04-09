# Microgrid Integration with Electric Vehicle Charging

This project demonstrates the design and simulation of a microgrid system integrated with electric vehicle (EV) charging infrastructure. It focuses on both **Vehicle-to-Grid (V2G)** and **Grid-to-Vehicle (G2V)** operation modes, optimizing energy flow using renewable sources like solar PV.

## 📌 Project Objectives

- Design a microgrid integrating solar PV and EV charging stations.
- Enable V2G and G2V functionalities for bidirectional energy flow.
- Optimize converters, inverters, and energy storage for system reliability.
- Simulate switching topology and control strategies using MATLAB Simulink.

## ⚙️ Simulation Overview

- A complete Simulink model demonstrates the interaction between the grid, PV source, bidirectional inverter, buck-boost converter, and EV battery.
- The model switches between **charging** (G2V) and **discharging** (V2G) modes.
- Incorporates voltage and current control loops, PV charging circuits, and system synchronization mechanisms.

## 🛠 Tools & Technologies

- MATLAB Simulink (`.slx` model)
- Control theory (Grid-forming and Grid-following strategies)
- Renewable energy integration (PV-based sources)

## 📂 Files Included

- `EE684_Project.slx` – Complete Simulink model of the microgrid with EV charging
- `Microgrid Integration with Electric Vehicle_EE684_Chinmay_Surbhi.pdf` – Detailed project report

## 📈 Results Highlights

- Simulated dynamic waveforms for grid voltage/current, battery states, and DC bus behavior in both V2G and G2V modes.
- PV-to-battery charging voltage characteristics analyzed for optimization.
- Identified key challenges like grid stability, synchronization, and bidirectional flow control.

## 🚀 Future Work

- Expand on control strategy comparisons (droop control, predictive control, etc.).
- Integrate battery health monitoring and efficiency benchmarking.
- Scale the system for larger microgrid and EV fleet applications.

