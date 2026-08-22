# Module 4 — Gate-Level Simulation, Synthesis and Verilog Coding

## Overview

This module focuses on the transition from RTL design to synthesized gate-level implementation. It also covers Gate-Level Simulation and important Verilog coding practices related to blocking and non-blocking assignments.

## Topics Covered

### 1. RTL Synthesis

* Introduction to synthesis
* RTL-to-gate-level conversion
* Logic optimization
* Standard-cell mapping
* Synthesized netlists
* Synthesis analysis

### 2. Gate-Level Simulation

* Introduction to Gate-Level Simulation
* Gate-level netlists
* RTL simulation versus Gate-Level Simulation
* Simulation of synthesized designs
* Waveform comparison
* Verification of synthesized behavior

### 3. Blocking Assignments

Blocking assignments use:

```verilog
=
```

Topics include:

* Procedural execution
* Statement ordering
* Combinational RTL coding
* Simulation behavior

### 4. Non-Blocking Assignments

Non-blocking assignments use:

```verilog
<=
```

Topics include:

* Clocked sequential logic
* Sequential RTL coding
* Simulation behavior
* Proper coding practices

### 5. Synthesis Labs

The laboratory work includes:

* Writing RTL designs
* Creating testbenches
* Performing RTL simulation
* Synthesizing RTL using Yosys
* Generating gate-level netlists
* Performing Gate-Level Simulation
* Analyzing waveforms

## RTL-to-Gate-Level Flow

```text
RTL Design
     ↓
RTL Simulation
     ↓
Yosys Synthesis
     ↓
Gate-Level Netlist
     ↓
Gate-Level Simulation
     ↓
Waveform Analysis
```

## RTL Simulation vs Gate-Level Simulation

### RTL Simulation

RTL simulation verifies the functional behavior of the original RTL design before synthesis.

### Gate-Level Simulation

Gate-Level Simulation verifies the behavior of the synthesized gate-level representation.

## Learning Outcomes

* Understanding the RTL synthesis process
* Understanding gate-level netlists
* Performing Gate-Level Simulation
* Comparing RTL and gate-level behavior
* Understanding blocking assignments
* Understanding non-blocking assignments
* Applying appropriate Verilog coding styles
* Understanding the relationship between RTL and synthesized hardware
