# 🖱️ Cenere Mouse (Open Source Tri-Mode Connectivity)

<p align="center">
  <img src="/Electronics Docs/Cenere Mouse 3D.png" alt="3D Render of PCB" width="600"/>
</p>

---

## 🔎 Project Overview

This project is an **open-source tri-mode connectivity gaming mouse**, designed around the **Nordic nRF52840** SoC.  
It supports three connectivity modes:

- **USB HID**  
- **Bluetooth Low Energy (BLE)**  
- **Nordic 2.4 GHz Wireless protocol**  

### ✨ Key Features
- Custom **monopole 2.4 GHz PCB antenna** optimized for the nRF52840  
- **PixArt PAW3395 optical sensor** for high-precision tracking  
- **Battery charging circuit** to support Bluetooth and Wireless power  
- **DC/DC Supply** to achieve maximum efficiency, low energy consumption
- **Addressable RGB LEDs** to optionally enable some aestethic glowing effect
- Fully open-source hardware and firmware*

---

## 📐 PCB Layer Previews

The design is a **4-layer PCB**, manufactured by **JLCPCB**, chosen for their reliable stackup and cost-effective prototyping services.  

<p align="center">
  <img src="/Electronics Docs/CenereMouse Gerbers TOP.png" alt="PCB Layer 1 - TOP" width="400"/>
  <img src="/Electronics Docs/CenereMouse Gerbers IN1.png" alt="PCB Layer 2 - IN1" width="400"/>
</p>

<p align="center">
  <img src="/Electronics Docs/CenereMouse Gerbers IN2.png" alt="PCB Layer 3 - IN2" width="400"/>
  <img src="/Electronics Docs/CenereMouse Gerbers BOTT.png" alt="PCB Layer 4 - BOTTOM" width="400"/>
</p>

<p align="center">
  <img src="/Electronics Docs/CenereMouse Gerbers.png" alt="All PCB Layers Together" width="600"/>
</p>

---

## 🏗️ PCB Stackup (JLCPCB)

The board will be fabricated at **JLCPCB** with the following stackup:

- **Top Layer (Copper, 35 µm)** – signal + components  
- **Prepreg (0.2104 mm, Dk ≈ 4.4)** – dielectric (7628*1) 
- **Mid Layer 1 (Copper, 152 µm)** – ground/pwr
- **Core (1.065 mm, Dk ≈ 4.6)** – dielectric (FR4)
- **Mid Layer 2 (Copper, 152 µm)** – ground/pwr
- **Prepreg (0.2104 mm, Dk ≈ 4.4)** – dielectric (7628*1) 
- **Bottom Layer (Copper, 35 µm)** – signal + components

This configuration provides an easy to work with controlled impedance environment for the **high speed signals** as well as the **RF Section**.

---

## 🚀 Goals

- Provide a **fully open-source reference design** for hobbyists, makers, and researchers  
- Explore advanced **antenna design** on low-cost PCB fabrication  
- Enable experimentation with **custom gaming peripherals**  

---

## 📂 Repository Structure

/Kicad Files        → KiCad design files
/Electronics Docs   → Documentation, layer renders, diagrams


Work in progress..



---

## 📜 License

This project uses a **dual-license** model:

- **Software (Code)** → [GNU GPL v3.0](LICENSES/GPL-3.0.txt) with a **Non-Commercial Use Exception**  
  - You may use, modify, and redistribute the source code for **personal, educational, or research** purposes.  
  - **Commercial use is prohibited** without prior written permission.  
  - Attribution is required.

- **Hardware (Schematics, PCB Layouts, Documentation)** → [CC BY-NC 4.0](LICENSES/CC-BY-NC-4.0.txt)  
  - You may copy, redistribute, remix, and adapt the hardware files.  
  - **Commercial use is prohibited.**  
  - Attribution is required.

### Attribution Requirement

If you use this project (code or hardware) in your own work, you must credit:

**© [Your Name or Handle] – [Year]**  
Repo: [GitHub Repository URL]

Example attribution:  
> “Based on the open-source design/code by [Your Name], available at [GitHub Repo URL].”

### Commercial Use

For commercial licensing, please contact the author.