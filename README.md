# RTL Design Using Verilog, Yosys and SKY130

## About This Repository

This repository documents my hands-on learning and practical work in RTL design and VLSI design using Verilog HDL, Icarus Verilog, GTKWave, Yosys and SKY130.

The repository covers the complete learning flow from Verilog RTL design and simulation to synthesis, Gate-Level Simulation and RTL optimization.

---

## Course Modules

### Module 0 — Getting Started

- Cloud Lab Setup
- Local Lab Setup
- Linux/Ubuntu Environment
- VLSI Development Environment
- EDA Tool Setup

### Module 1 — Verilog RTL Design

- Verilog HDL Fundamentals
- RTL Design
- Icarus Verilog
- Testbench Development
- RTL Simulation
- GTKWave Waveform Analysis
- Introduction to Yosys
- RTL Synthesis

### Module 2 — Timing Libraries & Hierarchical Design

- Timing Libraries
- Standard Cell Libraries
- `.lib` Files
- Timing Information
- Hierarchical Verilog Design
- Module Instantiation
- Flip-Flops
- Sequential Elements

### Module 3 — Combinational & Sequential Logic

- Combinational Logic
- Sequential Logic
- Clock and Reset
- Flip-Flops and Registers
- Lab 06
- Lab 07
- Sequential Logic Optimization
- Simulation and Synthesis

### Module 4 — Gate-Level Simulation & Synthesis

- RTL Synthesis
- Gate-Level Netlists
- Gate-Level Simulation
- RTL vs Gate-Level Simulation
- Blocking Assignments
- Non-Blocking Assignments
- Synthesis Labs

### Module 5 — RTL Optimization

- IF Constructs
- CASE Constructs
- Incomplete IF/CASE Constructs
- Latch Inference
- IF/CASE Optimization
- FOR Loop Constructs
- RTL Optimization
- Synthesis-Friendly RTL Coding

---

## RTL Design Flow

```text
Verilog RTL
     ↓
Testbench
     ↓
RTL Simulation
     ↓
GTKWave
     ↓
Yosys Synthesis
     ↓
Gate-Level Netlist
     ↓
Gate-Level Simulation
     ↓
RTL Optimization
'''
