# Chassis Structural Simulation and Analysis using Ansys

## 📘 Project Overview

This repository documents the structural analysis and simulation of a chassis frame using Ansys. The aim was to validate the chassis design for performance, safety, and manufacturability through rigorous simulation techniques and engineering best practices.

## 🔧 Tools and Technologies

- **CAD Software**: (Specify your CAD tool here)
- **Simulation Software**: Ansys
- **Programming/Scripting**: (If any used for post-processing or automation)
- **Report Format**: PDF

## 🧪 Structural Analysis and Simulation

All simulations were carried out using a mesh-converged model to ensure accurate and computationally efficient results.

### ✅ Torsional Rigidity
- **Objective**: Validate resistance to twisting.
- **Load**: 1175.9 N·m applied at front axle points.
- **Result**: `1678.57 N·m/deg` (Target: >1650 N·m/deg)

### ✅ Bending Stiffness
- **Objective**: Minimize vertical deflection under deceleration.
- **Load**: 1101.02 N applied at front suspension.
- **Result**: `6928.09 N/mm` (Target: >6100 N/mm)

### ✅ Impact Tests
- **Front Impact**: 38,940 N — FOS: `3.13`
- **Side Impact**: 38,940 N — FOS: `3.24`
- **Rear Impact**: 38,940 N — FOS: `1.66`

### 🔩 Chassis Properties
- **Weight**: `25.78 kg`
- **CG Height**: `194.87 mm`
- **Weight Distribution**: 41.3% Front / 58.7% Rear

## 🏗 Manufacturing Considerations

A dedicated jigging system was designed for accurate and repeatable assembly, including fixtures for:
- Main Hoop
- Front Hoop
- Suspension Mounts (Front & Rear)

## 📊 Performance Summary

| Metric              | Unit      | Target   | Theoretical |
|---------------------|-----------|----------|-------------|
| Torsional Rigidity  | N·m/deg   | >1650    | 1678.57     |
| Bending Stiffness   | N/mm      | >6100    | 6928.09     |
| Weight              | kg        | <28.3    | 25.78       |
| CG Height           | mm        | <183     | 194.87      |
| Front Impact FOS    | -         | >3.0     | 3.13        |
| Side Impact FOS     | -         | >2.5     | 3.24        |
| Rear Impact FOS     | -         | >3.0     | 1.66        |

> ⚠️ Note: Rear impact safety factor is slightly below target, suggesting scope for reinforcement in future iterations.

## 📂 Repository Structure

