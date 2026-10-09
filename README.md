# FLAC3D-Examples

**Reproducible Numerical Simulation Examples for Mining Engineering**

A structured collection of FLAC3D and FISH examples for mining engineering, focusing on roadway excavation, rock mechanics, ground support, stress analysis, and mining-induced deformation.

本项目用于整理采矿工程中的 FLAC3D 数值模拟案例，逐步建立可复现、可扩展的工程计算案例库。

## Objectives

- Build reusable FLAC3D numerical simulation examples.
- Document model geometry, material parameters, boundary conditions, and solution procedures.
- Explore roadway excavation and ground support simulation.
- Develop FISH scripts for model automation and result processing.
- Provide reproducible examples for engineering research and learning.

## Topics

| Module | Description |
|---|---|
| Basic Models | Model geometry, zoning, and boundary conditions |
| Roadway Excavation | Roadway geometry and excavation sequences |
| Rock Mechanics | Constitutive models and material parameters |
| Ground Support | Rock bolts, cables, and support systems |
| Stress Analysis | Stress redistribution and displacement analysis |
| Mining Engineering | Mining-induced deformation and surrounding-rock response |
| FISH Scripting | Model automation and custom calculations |

## Repository Structure

```text
FLAC3D-Examples/
├── README.md
├── LICENSE
├── .gitignore
├── 01-basic-model/
├── 02-roadway-excavation/
├── 03-rock-mechanics/
├── 04-ground-support/
├── 05-stress-analysis/
├── 06-mining-simulation/
├── 07-fish-scripting/
└── docs/
```

Each example will include, where applicable:

- `README.md` — problem description and execution instructions
- `model.dat` — FLAC3D model commands
- `fish.dat` — FISH functions and automation scripts
- `results/` — selected simulation outputs or figures

## Example Documentation Standard

Each documented case should specify:

1. Engineering problem and modeling assumptions
2. Model dimensions and geometry
3. Rock mass parameters and constitutive model
4. Boundary conditions and initial stress
5. Excavation and support procedures
6. Calculation commands and convergence checks
7. Displacement, stress, and plasticity results
8. Software version and reproducibility notes

## Requirements

- FLAC3D: use a compatible version specified by each example.
- FISH: use syntax supported by the corresponding FLAC3D version.
- Python: optional, for data processing, visualization, and automation.

## Validation and Limitations

Examples are intended for learning, research, and numerical simulation development. Model assumptions, units, boundary conditions, constitutive models, and convergence must be checked before interpreting results.

These examples do not replace site-specific geological investigation, engineering verification, or professional design review.

## License

This project is released under the MIT License. Refer to `LICENSE` for details.

## Language

Documentation may be provided in English and Chinese to support international collaboration and practical engineering use.

---

**Project focus:** Mining Engineering · FLAC3D · FISH · Numerical Simulation · Ground Support
