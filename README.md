# Quantum Teleportation — Week 6

This repository contains the **Quantum Teleportation** notebook used for **Week 6** exercises in the *Introduction to Quantum Computing* course.

---

## Files

- **Quantum_teleportation_week6.ipynb**  
  Jupyter notebook containing:
  - Quantum teleportation circuit construction  
  - Circuit visualization  
  - Execution on an IBM Quantum backend using **Qiskit Runtime (Sampler)**  
  - Measurement results and histogram visualization  

> Local working file path used during development:  
> `/mnt/data/Quantum_teleportation_week6.ipynb`

---

## Description

The notebook demonstrates the complete **quantum teleportation protocol**, including:

- Preparation of an arbitrary quantum state  
- Creation of an entangled Bell pair  
- Bell-state measurement on Alice’s qubits  
- Classical communication of measurement outcomes  
- Conditional correction operations on Bob’s qubit  

The circuit is executed on an **IBM Quantum backend** via **Qiskit Runtime (Sampler)**, and the resulting **bitstring counts** are displayed along with a **histogram** for analysis.

---

## How to Run Locally

### 1. Create and activate a Python environment (conda recommended)

```bash
conda create -n qiskit_runtime python=3.10
conda activate qiskit_runtime
