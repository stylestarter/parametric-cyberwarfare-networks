# Parametric Strategy in Military Cyberwarfare

### A Game-Theoretic & Algorithmic Analysis for Dynamic Decision-Making and Adversarial Forecasting

This repository accompanies the undergraduate thesis:

**Parametric Strategy in Military Cyberwarfare: A Game-Theoretic & Algorithmic Analysis for Dynamic Decision-Making and Adversarial Forecasting**

submitted at **LUISS Guido Carli University**.

The project investigates how strategic behavior emerges in military cyberwarfare environments through a combination of game theory, adaptive learning algorithms, and network analysis. The research examines whether theoretically derived equilibrium predictions remain valid when strategic actors learn and adapt over time, and how network structure can alter the strategic importance of cyber targets.

---

## Research Objectives

The thesis focuses on two central questions:

1. **Parametric Equilibrium Formation**

   * Under what conditions do attacker-defender games admit a full-support mixed Nash equilibrium?
   * How do parameter choices influence strategic outcomes and equilibrium feasibility?

2. **Networked Cyber Conflict**

   * How does strategic behavior change when cyber targets are embedded within an interconnected network?
   * Can network position and connectivity become more strategically valuable than intrinsic target value?

---

## Topics Covered

* Zero-Sum Attacker-Defender Games
* Nash Equilibrium Analysis
* Parametric Equilibrium Derivation
* Fictitious Play
* Replicator Dynamics
* Adaptive Learning in Games
* Network Science
* Spillover Effects
* Hub-and-Spoke Architectures
* Clique Networks
* Strategic Infrastructure Targeting
* Military Cyberwarfare Modeling

---

## Computational Methods

The analysis is implemented in Python using:

* NumPy
* NetworkX
* Matplotlib
* Game-Theoretic Modeling
* Evolutionary Dynamics
* Agent-Based Simulation Techniques

---

## Main Experiments

### Experiment 1 — Three-Node Clique

Analysis of strategic interaction within a fully connected cyber network without spillover effects.

### Experiment 2 — Five-Node Hub-and-Spoke Network

Evaluation of how centralized network structures influence attacker and defender behavior.

### Experiment 3 — Spillover Activation

Investigation of how actions at one node propagate across connected infrastructure and alter equilibrium behavior.

### Experiment 4 — Strategic Value versus Network Position

Assessment of whether network connectivity can outweigh intrinsic target value in determining strategic importance.

---

## Repository Structure

```text
.
├── README.md
├── learning_algorithms.ipynb
└── network_analysis.ipynb
```

### Files

- `learning_algorithms.ipynb`
  - Implements the attacker-defender game presented in the thesis.
  - Includes fictitious play, replicator dynamics, equilibrium verification, and calibrated parameter analysis.

- `network_analysis.ipynb`
  - Implements the network extension of the model.
  - Includes clique and hub-and-spoke architectures, spillover mechanisms, and network-based strategic value experiments.

- `README.md`
  - Repository documentation and thesis overview.
```

---

## Author

**Chloe Monique Quevedo**
BSc Management and Computer Science
LUISS Guido Carli University

Supervisor: **Prof. Xavier Venel**
