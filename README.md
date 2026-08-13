# Custom Arduino Nano PCB Design

This repository contains the complete Altium Designer project files, manufacturing data, and documentation for a custom-designed Arduino Nano-compatible development board.

##  Project Overview
This project was undertaken to practice dense component routing and manage strict footprint constraints while designing a reliable, fully functional microcontroller board. The design was created from scratch using **Altium Designer** and successfully passed all Design Rule Checks (DRC) with zero errors or warnings.

*(Optional: You can insert your 3D render image here later)*

##  Key Specifications & Components
*   **EDA Tool:** Altium Designer
*   **Microcontroller:** ATmega328P (AVR 8-bit)
*   **USB-to-Serial Converter:** CH340C
*   **Power Management:** Onboard voltage regulation for 5V.
*   **Form Factor:** Standard Arduino Nano footprint.
*   **PCB Details:** 2-Layer board.

## Repository Contents
*   **`Nano.PrjPcb`, `schematic.SchDoc`, `NANO PCB.PcbDoc`:** The original Altium Designer project and source files.
*   **`Nano.pdf`:** The complete schematic in PDF format for quick viewing without needing EDA software.
*   **`BOM.xlsx`:** The Bill of Materials, listing all necessary components for assembly.
*   **`Gerber files.rar`:** The complete Gerber and NC Drill files ready for fabrication.

##  Manufacturing & Fabrication
The board is ready for fabrication. You can download the Gerber archive and upload it directly to any standard PCB manufacturer (e.g., JLCPCB, PCBWay). 
*   **Dimensions:** Standard Nano size
*   **Layers:** 2

##  Feedback & Contributions
I am constantly looking to improve my hardware design and PCB routing skills. If you are a hardware engineer, I would love to hear your feedback on the layout, routing, or component selection! Feel free to open an issue or reach out to me directly on [LinkedIn](https://www.linkedin.com/in/omar-el-sawah-631328283 ).

---
*Designed by Omar El-Sawah.*
