# HARDGRID-Q

## Hardness-Aware Hybrid Quantum Optimization for Distribution Grid Expansion Planning

HARDGRID-Q is a Phase 1 concept developed by **QuantumForge** for the **2026 Global Quantum + AI Challenge**, addressing E.ON's problem statement:

**Quantum-Enabled Grid Expansion Planning for Distribution System Energy Networks**

## Core Idea

HARDGRID-Q investigates where distribution-grid expansion problems become genuinely difficult for strong classical optimization and whether quantum-enhanced optimization can provide measurable value in those regimes.

The proposed workflow combines:

- physics-based distribution-grid modeling,
- classical optimization and solver-based hardness analysis,
- AI-assisted hardness prediction,
- QUBO formulation,
- QAOA-based quantum refinement,
- HPC-supported scaling and simulation,
- post-optimization power-flow validation.

The central principle is:

> **Use classical optimization where it remains effective, and deploy quantum resources only where measured difficulty justifies them.**

## Research Question

**Where does classical grid-expansion optimization become hard, why does it become hard, and can quantum optimization provide measurable improvement at that boundary?**

## Phase 1 Status

This repository currently contains concept documentation and supporting prior work.

No Phase 2 implementation is presented as completed at this stage.

## Prior Work

Previous research by J K Pawan Kumar and Tarun Solanki includes:

- **GRID-Q** — Hybrid AI–Quantum Framework for Resilient Distribution Grid Expansion Planning
- **Q-RESGRID** — Hybrid AI–Quantum Optimization Framework for Cost-Efficient and Resilient Microgrid Energy Systems

Supporting reports are available in:

`docs/prior-work/`

## Team

**QuantumForge**

- J K Pawan Kumar — Team Lead, Quantum AI & Optimization
- Tarun Solanki — HPC Systems & Computational Workflow Lead

## Challenge

2026 Global Quantum + AI Challenge  
Enterprise Partner: **E.ON**

## Repository Structure

```text
HARDGRID-Q/
├── README.md
├── docs/
│   └── prior-work/
│       ├── GRID-Q_Fujitsu_2026_Report.pdf
│       └── Q-RESGRID_Fujitsu_2026_Report.pdf
└── LICENSE
