# Quantifying Two-Qubit Entanglement from Pauli Expectation Values  
**02456 Deep Learning — Group 45, Fall 2025**

This repository contains the report for our 02456 Deep Learning final project:  
**Quantifying Two-Qubit Entanglement from Pauli Expectation Values Using a Two-Stage Autoencoder–Regressor Architecture**.

The project explores whether a compact latent representation learned by an autoencoder can be used to predict Wootters' concurrence from only nine Pauli–Pauli expectation values.  
All results, tables, figures, and conclusions are documented in the report.

## Project Overview (as described in the report)

- 100,000 two-qubit states were generated (mixed, separable, pure).
- Each state was mapped to the 9 Pauli–Pauli expectation values: <σ_X⊗σ_X>, <σ_X⊗σ_Y>, ..., <σ_Z⊗σ_Z>.
- A two-stage method was evaluated:
  - **Stage 1:** Autoencoder (9 → 3 → 9) learns a latent representation.
  - **Stage 2:** Frozen encoder + regression head predicts concurrence.
- Baseline comparison performed against the architecture from Pan et al. (2024).
- Noise robustness tested with Gaussian noise (0.0, 0.05, 0.15).

All detailed methodology and results are in the PDF report.

## Authors
**Group 45 — DTU 02456 Deep Learning**

| Name | Student ID |
|------|------------|
| Diego A. Mijares | s251777 |
| Carlos Cuilty | s252974 |
| Kai Wen Tay | s252046 |
| Kelvin Rasmussen | s224345 |

**Supervisor:** Ekaterina Protsenko

## License
This project is released under the **MIT License**.  
You may reuse, modify, and distribute the material while including the license.
