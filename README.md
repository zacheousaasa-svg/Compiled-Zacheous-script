# Deep Reinforcement Learning-Based Optimization of RIS for 6G Multi-User Connectivity

This repository serves as the official reproducibility artifact for the paper: **"Deep Reinforcement Learning-Based Optimization of Reconfigurable Intelligent Surfaces (RIS) for 6G Multi-User Connectivity in NLOS Environments."**

The codebase provides a standalone implementation of a Twin Delayed Deep Deterministic Policy Gradient (TD3) framework, specifically designed to optimize RIS passive phase shifts under high-frequency sub-THz NLOS conditions.

---

## 🗺️ Mapping Code to Manuscript Sections
To assist reviewers in verifying the theoretical claims, the codebase is modularized as follows:

| Module | Purpose | Paper Reference |
| :--- | :--- | :--- |
| **Module 2** | Channel generation (Sub-THz path loss & Rician fading) | Section 2.1 – 2.3 |
| **Module 2** | SINR formulation & Sum-Rate objective calculation | Section 2.4 (Eq. 4-5) |
| **Module 3** | Actor-Critic networks & TD3 training logic | Section 3.3 – 3.4 |
| **Module 4** | Manuscript figure generation (Figs 1–4) | Section 4 |
| **Module 6** | Latency benchmarks & Table export | Section 4 (Tables 1-2) |

---

## 🚀 Quick Start
1. **Clone the repository:**
```bash

   
