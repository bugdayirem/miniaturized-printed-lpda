# Miniaturized Printed Log-Periodic Dipole Antenna (LPDA)

Undergraduate thesis project in Electronics and Communications Engineering at Kocaeli University.

## Overview

This project investigates the design and simulation of a miniaturized printed log-periodic dipole antenna (LPDA) for wireless communication applications, including RFID, GSM, GPS, 3G, Bluetooth, and 2.4 GHz Wi-Fi.

A conventional printed LPDA is used as a reference design. **Triangular** and **square** dipole geometries are evaluated to reduce the antenna's physical size while maintaining wideband performance. The designs use an **FR4 substrate** and are simulated in **CST Microwave Studio**.

## Design and simulation

The reference LPDA design includes **11 dipole elements** and an initial target frequency range of **0.9–2.0 GHz**. The FR4 substrate parameters used in the thesis are:

- Relative permittivity (εr): **4.3**
- Loss tangent (tan δ): **0.025**
- Thickness: **1.52 mm**

The conventional, triangular, and square configurations are compared using reflection coefficient (S11), voltage standing wave ratio (VSWR), and radiation patterns.

## Results

The thesis defense presentation reports the following physical size reductions:

| Antenna configuration | Size reduction |
| --- | ---: |
| Triangular dipole geometry | Approximately 30% |
| Square dipole geometry | Approximately 34% |

The presentation reports that the modified designs retain wideband operation and satisfy the **S11 < −10 dB** criterion in the evaluated results.

Radiation-pattern results reported at **1.05 GHz**:

| Antenna configuration | Maximum directional gain | 3 dB beamwidth |
| --- | ---: | ---: |
| Conventional LPDA | 0.225 dBi | 79.4° |
| Triangular geometry | 0.404 dBi | 82.1° |
| Square geometry | 0.7 dBi | 83.3° |

## Repository files

| File | Description |
| --- | --- |
| `Miniaturized_Printed_LPDA_Thesis.docx` | Undergraduate thesis |
| `LPDA_Thesis_Defense_Presentation.pptx` | Thesis defense presentation |
| `LPDA_Research_Poster_2026.pptx` | Research poster |
| `Miniaturized_Printed_LPDA_CST_Model.cst` | CST Microwave Studio antenna model |

## Academic information

- **Author:** İrem Buğday
- **Supervisor:** Prof. Dr. Gonca Çakır
- **University:** Kocaeli University
- **Department:** Electronics and Communications Engineering
