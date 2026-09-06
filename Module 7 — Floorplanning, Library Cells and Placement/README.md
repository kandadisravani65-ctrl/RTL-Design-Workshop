# Module 2 — Floorplanning, Library Cells and Placement

## 📌 Introduction

This module focuses on the physical design stage of ASIC implementation.

It introduces the concepts of floorplanning, utilization factor, aspect ratio, pre-placed cells, decoupling capacitors, power planning, pin placement, placement blockages, standard-cell libraries, library binding, placement optimization, library characterization and congestion-aware placement.

---

# 🎯 Objectives

The main objectives of this module are:

- Understand good and bad floorplans.
- Understand utilization factor.
- Understand aspect ratio.
- Understand pre-placed cells.
- Understand decoupling capacitors.
- Understand power planning.
- Understand pin placement.
- Understand placement blockages.
- Generate a floorplan using OpenLANE.
- View the floorplan using Magic.
- Understand library binding.
- Understand initial and optimized placement.
- Understand standard-cell characterization.
- Understand timing parameters.
- Understand congestion-aware placement.

---

# 📚 Topics Covered

### 1. Floorplanning Considerations

Understanding good and bad floorplans and the factors affecting floorplan quality.

### 2. Utilization Factor and Aspect Ratio

Understanding core utilization and physical dimensions.

### 3. Pre-Placed Cells

Understanding the placement of macros and other fixed blocks.

### 4. Decoupling Capacitors

Understanding the role of capacitors in maintaining power stability.

### 5. Power Planning

Understanding power rings, straps and standard-cell power rails.

### 6. Pin Placement

Understanding I/O pin placement and placement blockages.

### 7. Floorplan Using OpenLANE

Generating the physical floorplan using OpenLANE.

### 8. Floorplan in Magic

Viewing and inspecting the physical layout using Magic.

### 9. Library Binding

Understanding how logical cells are mapped to technology-specific cells.

### 10. Placement Optimization

Understanding global and detailed placement.

### 11. Library Characterization

Understanding timing and electrical characterization.

### 12. Timing Parameters

Understanding propagation delay and transition time.

---

# 🔄 Physical Design Flow

```text
Floorplanning
      ↓
Power Planning
      ↓
Placement
      ↓
Clock Tree Synthesis
      ↓
Routing
      ↓
Parasitic Extraction
      ↓
Static Timing Analysis
      ↓
Physical Verification
