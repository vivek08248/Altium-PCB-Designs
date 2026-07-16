\# PCB Designing Using Altium Designer



A collection of PCB design projects developed using \*\*Altium Designer\*\*, covering both \*\*Single Layer\*\* and \*\*Multi-Layer PCB Design Techniques\*\*.



This repository contains two PCB projects created as part of the Mini Project on PCB Design using Altium Designer.



\---



\## Projects Included



\### 1. Single Layer LED Chaser PCB



A single-layer PCB implementing an LED chaser circuit using:



\- NE555 Timer IC

\- Decade Counter IC

\- LEDs

\- Resistors

\- Capacitors



The circuit generates clock pulses using a 555 timer and sequentially lights LEDs through a decade counter.



\#### Features



\- Single-layer PCB

\- Auto-routed design

\- ERC/DRC verified

\- Gerber files generated

\- 3D PCB visualization



\#### Preview



!\[Top Layer](Single-Layer-LED-Chaser/assets/images/pcb\_top.png)



!\[3D View](Single-Layer-LED-Chaser/assets/images/pcb\_3d\_iso.png)



\---



\### 2. Smart Home Automation PCB



A multi-layer PCB developed around the ESP32 microcontroller for home automation applications.



\#### Features



\- ESP32 based controller

\- Relay control interface

\- Manual switch inputs

\- Power supply circuitry

\- Multi-layer PCB stackup

\- Noise reduction through dedicated power planes

\- Manufacturing-ready outputs



\#### PCB Stackup



| Layer | Purpose |

|---------|---------|

| Top Layer | Components + Signals |

| Inner Layer 1 | Signal + Ground |

| Inner Layer 2 | 5V Power Plane |

| Inner Layer 3 | 3.3V Power Plane |

| Inner Layer 4 | Signal Routing |

| Bottom Layer | Components + Signals |



\#### Preview



!\[Top Layer](Smart-Home-Control-PCB/assets/images/pcb\_top.png)



!\[3D View](Smart-Home-Control-PCB/assets/images/pcb\_3d\_iso\_top.png)



\---



\## Software Used



\- Altium Designer Professional

\- Proteus (Simulation)

\- Altium CAMtastic

\- Altium Layer Stack Manager



\---



\## Design Verification



The designs were verified using:



\- ERC (Electrical Rule Check)

\- DRC (Design Rule Check)

\- Netlist Verification

\- 3D Clearance Check

\- BOM Verification



\---



\## Manufacturing Outputs



The repository includes:



\- Gerber Files

\- NC Drill Files

\- Bill of Materials (BOM)

\- PCB Layout Files

\- Schematics

\- 3D PCB Views



\---



\## Repository Structure



```text

Altium-PCB-Designs

│

├── Single-Layer-LED-Chaser

│   ├── Schematics

│   ├── PCB

│   ├── Outputs

│   ├── Libraries

│   └── assets

│

├── Smart-Home-Control-PCB

│   ├── Schematics

│   ├── PCB

│   ├── Outputs

│   ├── Libraries

│   ├── Bill\_of\_Materials

│   └── assets

│

└── docs

