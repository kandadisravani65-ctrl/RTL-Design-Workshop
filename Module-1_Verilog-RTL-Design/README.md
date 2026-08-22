# Module 1 — Verilog RTL Design

## Overview

This module focuses on the fundamentals of Verilog HDL and the RTL design flow. The work includes writing RTL designs, creating testbenches, simulating the designs, analyzing waveforms and performing synthesis using open-source EDA tools.

## Topics Covered

### 1. Verilog HDL Fundamentals

- Verilog syntax
- Modules and ports
- Inputs and outputs
- Data types
- Operators
- Continuous assignments
- Procedural blocks

### 2. RTL Design

- RTL coding
- Combinational logic
- Sequential logic
- Module-based design
- Synthesizable Verilog

### 3. Testbench Development

- Testbench structure
- DUT instantiation
- Input stimulus
- Clock generation
- Reset generation
- Output verification

### 4. RTL Simulation

Simulation was performed using Icarus Verilog to verify the functional behavior of the RTL designs.

### 5. GTKWave

GTKWave was used to analyze simulation waveforms and verify the relationship between inputs, outputs and control signals.

### 6. Yosys Synthesis

Yosys was used to synthesize the Verilog RTL and understand the conversion of RTL into a gate-level representation.

## Design Flow

```text
Verilog RTL
     ↓
Testbench
     ↓
Icarus Verilog
     ↓
VCD Waveform
     ↓
GTKWave Analysis
     ↓
Yosys Synthesis
     ↓
Gate-Level Representation


## Learning Outcomes

Understanding Verilog RTL coding
Writing basic RTL modules
Developing testbenches
Performing RTL simulation
Analyzing waveforms
Understanding the synthesis process
Using open-source EDA tools
