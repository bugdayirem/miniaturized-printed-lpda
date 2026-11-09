# Miniaturized Printed Log-Periodic Dipole Antenna (LPDA)

**Undergraduate thesis project | Electronics and Communications Engineering, Kocaeli University**

This repository presents the design and simulation of a miniaturized printed log-periodic dipole antenna (LPDA) for wireless communication applications. The study compares a conventional printed LPDA with modified dipole geometries intended to reduce physical dimensions while retaining useful wideband performance.

## Project overview

The antenna study considers wireless applications including **RFID, GSM, GPS, 3G, Bluetooth, and 2.4 GHz Wi-Fi**. A conventional printed LPDA serves as the reference design. Two alternative element shapes—**triangular** and **square**—are investigated for size reduction.

The designs use an **FR4 dielectric substrate** and are modeled and evaluated in **CST Microwave Studio**. The thesis discusses reflection coefficient (S11), voltage standing wave ratio (VSWR), and radiation patterns.

## Design and methodology

1. Model a conventional printed LPDA as a baseline.
2. Modify the dipole elements using triangular and square geometries.
3. Simulate the designs in CST Microwave Studio.
4. Compare impedance matching, operating characteristics, radiation behavior, and physical dimensions.

The thesis describes a baseline design with **11 dipole elements**, an initial target frequency interval of **0.9–2.0 GHz**, and FR4 substrate parameters of **relative permittivity 4.3**, **loss tangent 0.025**, and **thickness 1.52 mm**. These are documented design parameters, not a claim that every listed wireless standard was experimentally validated.

## Reported results

The thesis defense presentation reports:

| Configuration | Reported physical size reduction |
| --- | ---: |
| Triangular dipole geometry | Approximately 30% |
| Square dipole geometry | Approximately 34% |

The presentation also reports that the modified configurations retain wideband behavior and meet an **S11 < -10 dB** matching criterion in the evaluated results. At **1.05 GHz**, its radiation-pattern slides report:

| Configuration | Reported maximum directional gain | Reported 3 dB beamwidth |
| --- | ---: | ---: |
| Conventional LPDA | 0.225 dBi | 79.4° |
| Triangular geometry | 0.404 dBi | 82.1° |
| Square geometry | 0.7 dBi | 83.3° |

These numbers are taken from the project presentation and should be interpreted in the context of the thesis and its simulation setup; they are not independently reproduced measurements.

## Repository contents

| File | Description |
| --- | --- |
| `Miniaturized_Printed_LPDA_Thesis.docx` | Full undergraduate thesis |
| `LPDA_Thesis_Defense_Presentation.pptx` | Thesis defense slides and results |
| `LPDA_Research_Poster_2026.pptx` | Research poster |
| `Miniaturized_Printed_LPDA_CST_Model.cst` | CST Microwave Studio project/model |

**Software:** CST Microwave Studio is required to work with the native `.cst` project. The documents and presentations can be opened using compatible office software.

## Academic information

- **Author:** İrem Buğday
- **Supervisor:** Prof. Dr. Gonca Çakır
- **Institution:** Kocaeli University, Faculty of Engineering
- **Department:** Electronics and Communications Engineering

## Note

This repository documents an academic design and simulation study. Refer to the full thesis and native CST model for the design details, assumptions, and interpretation of results. The repository does not include a Turnitin similarity report.
