# 4-bit ALU Physical Design using OpenLane

## Overview
This project implements the complete RTL-to-GDSII ASIC physical design flow of a 4-bit ALU using OpenLane and Sky130 PDK.

The project demonstrates:
- RTL design using Verilog
- Logic synthesis
- Floorplanning
- Placement
- Clock Tree Synthesis (CTS)
- Routing
- Static Timing Analysis (STA)
- Power analysis
- GDSII generation

---

## Tools Used
- OpenLane
- OpenROAD
- Magic VLSI
- Sky130A PDK
- Docker
- Ubuntu WSL2

---

## ALU Operations

| Select | Operation |
|---|---|
| 00 | Addition |
| 01 | Subtraction |
| 10 | AND |
| 11 | OR |

---

## Results

### Timing
- TNS: 0.00
- WNS: 0.00
- Setup Slack: 6.15 ns
- Hold Slack: 1.90 ns

### Area
- Total Cells: 38
- Chip Area: 420.403200

### Power
- Total Power: 3.88e-05 W

---

## Project Structure

```text
src/        -> Verilog RTL
reports/    -> Timing, power, area reports
config.json -> OpenLane configuration
