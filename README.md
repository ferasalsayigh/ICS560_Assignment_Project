# Quantum Gates, Superposition, and Entanglement  
### A Qiskit Implementation of the Bell State  
#### Author: Feras Alsayigh

This repository contains an assignment project for **ICS560 – Foundations of Quantum Computing** in the **MSc in Quantum Computing** program at **KFUPM**, taught by **Dr. Alawi Alsaggaf**.  
The project was completed by **Feras Alsayigh** as part of the course requirements.

The project investigates three fundamental quantum behaviors—superposition, bit flipping, and entanglement—through the construction and simulation of simple quantum circuits using **Python** and **Qiskit**. A key component is the theoretical and experimental study of the Bell state and its non-separability.

---

## Repository Contents

- `ExprimentalSimulation.ipynb`  
  Main Jupyter notebook containing the implementation of all experiments:
  - Single-qubit superposition using the Hadamard gate  
  - Single-qubit bit flip using the Pauli-X gate  
  - Two-qubit Bell-state generation using Hadamard + CNOT  
  The notebook includes circuit construction, simulation, Bloch-sphere visualization, and measurement histograms.

- `Quantum_Gates_Superposition_and_Entanglement_A_Qiskit_Implementation_of_Bell_State.pdf`  
  Full project report describing the background theory, methodology, experimental setup, results, analysis, and a detailed theoretical proof that the Bell state is not separable.

---

## Project Overview

The goal of this project is to:

1. Design simple quantum circuits using basic quantum gates (Hadamard, Pauli-X, and CNOT).
2. Observe and visualize the resulting quantum states, with emphasis on:
   - Superposition  
   - Deterministic bit flipping  
   - Entanglement via the Bell state
3. Validate theoretical predictions through simulation.
4. Demonstrate, via a separability test, that the Bell state cannot be expressed as a product of two single-qubit states.

The work connects the theoretical principles taught in ICS560 with practical simulation tools, providing a clearer understanding of quantum gates and multi-qubit behavior.

---

## Author

**Feras Alsayigh**  
MSc Candidate in Quantum Computing  
King Fahd University of Petroleum & Minerals (KFUPM)

---

## Requirements

To run the notebook, you will need:

- Python 3.9+ (3.10/3.11 also fine)
- Recommended packages:
  - `qiskit`
  - `matplotlib`
  - `numpy`
  - `jupyter` or `jupyterlab`

You can install them with:

```bash
pip install qiskit matplotlib numpy jupyter
