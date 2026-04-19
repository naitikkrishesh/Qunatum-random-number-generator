![Python](https://img.shields.io/badge/Python-3.x-blue)
![Qiskit](https://img.shields.io/badge/Qiskit-Quantum-purple)
# Quantum Random Number Generator

## 🧠 Motivation
This project uses the intrinsic probabilistic nature of quantum mechanics to generate random numbers. A qubit in superposition collapses to either |0⟩ or |1⟩ upon measurement with equal probability.

---

## ⚙️ Methodology

### Step 1: Initialise qubit
|0⟩ = [1, 0]^T

### Step 2: Apply Hadamard gate
H = (1/√2) * [[1, 1], [1, -1]]

### Step 3: State after applying H
|ψ⟩ = (1/√2)(|0⟩ + |1⟩)

### Step 4: Measurement
P(0) = P(1) = 1/2

### Step 5:
Repeat 4 times to generate a 4-bit binary number and convert to decimal (0–15)

---

## 🔄 Workflow
- Prepare qubit  
- Apply Hadamard gate  
- Measure  
- Repeat 4 times  
- Convert to decimal  

---

## 🛠 Hardware
Any quantum simulator or device (e.g., IBM Qiskit backend)

---

## 💻 Software Stack
- Qiskit  
- NumPy  
- Matplotlib  

---

## 📌 Key Insight
Quantum superposition and measurement provide true randomness, unlike classical pseudo-random generators.
