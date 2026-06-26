# cmos-digital-circuit-design

```markdown
# CMOS Digital Circuit Design using Cadence Virtuoso

Implementation and analysis of CMOS digital circuits using **Cadence Virtuoso** in **90 nm CMOS technology**. This project covers MOSFET characterization, CMOS inverter design, delay and power analysis, transistor sizing, CMOS NAND gate design, layout implementation, and physical verification using DRC and LVS.

---

## Project Overview

This repository demonstrates the complete design flow of fundamental CMOS digital circuits from transistor-level simulation to physical layout. The experiments investigate the influence of transistor sizing, body effect, capacitive loading, propagation delay, switching threshold, power consumption, and layout verification.

The work was carried out using Cadence Virtuoso and Spectre Simulator.

---

## Technology

| Parameter | Value |
|-----------|-------|
| Technology Node | 90 nm CMOS |
| Supply Voltage | 1 V |
| Design Tool | Cadence Virtuoso |
| Simulator | Spectre |
| Design Style | Complementary CMOS |

---

## Experiments

### Experiment 1 – MOSFET Characterization

- NMOS ID–VDS Characteristics
- PMOS ID–VDS Characteristics
- Threshold Voltage Extraction
- Body Effect Analysis
- Channel Length Modulation

---

### Experiment 2 – CMOS Inverter Design

- CMOS Inverter Schematic
- DC Analysis
- Voltage Transfer Characteristics (VTC)
- Noise Margin Calculation
- Switching Threshold (VM)
- Transient Analysis
- Propagation Delay Measurement
- Loaded and Unloaded Delay Analysis
- PMOS/NMOS Transistor Sizing
- Dynamic Power Estimation
- Leakage Power Analysis

---

### Experiment 3 – Two-Input CMOS NAND Gate

- CMOS NAND Design
- DC Characteristics
- Transient Response
- Delay Analysis
- NAND Sizing
- Capacitive Load Analysis
- Truth Table Verification

---

### Experiment 4 – Three-Input CMOS NAND Layout

- CMOS Schematic Design
- Layout Implementation
- Design Rule Check (DRC)
- Layout Versus Schematic (LVS)
- Area Optimization

---

## Key Results

| Parameter | Measured Value |
|-----------|---------------:|
| Technology | 90 nm |
| Supply Voltage | 1 V |
| Inverter Switching Threshold | 409.91 mV |
| Minimum tPLH | 11.11 ps |
| Minimum tPHL | 5.17 ps |
| Leakage Power | 404 pW |
| Dynamic Power (Minimum Size) | 0.777 μW |
| Loaded Delay (10 fF) | tPLH = 173 ps, tPHL = 73.92 ps |

---

## Repository Structure

```

cmos-digital-circuit-design
│
├── README.md
├── report/
│   └── CMOS_Digital_Circuit_Design_Report.pdf
│
├── images/
│   ├── exp1/
│   ├── exp2/
│   ├── exp3/
│   └── exp4/
│
└── docs/
└── results_summary.md

```

---

## Design Topics Covered

- MOSFET Device Characteristics
- Body Effect
- Threshold Voltage
- Channel Length Modulation
- CMOS Inverter Design
- Voltage Transfer Characteristics
- Noise Margin
- Propagation Delay
- Dynamic and Leakage Power
- Transistor Sizing
- Capacitive Loading
- CMOS NAND Logic Design
- Physical Layout Design
- LVS Verification

---

## Tools Used

- Cadence Virtuoso
- Spectre Simulator
- 90 nm CMOS PDK

---

## Learning Outcomes

- Understanding MOSFET device behavior
- Designing CMOS logic gates from transistor level
- Analyzing delay and power trade-offs
- Optimizing transistor sizing for balanced performance
- Implementing CMOS layouts
- Performing physical verification using DRC and LVS

---



## License

This repository is intended for educational and learning purposes.
```
