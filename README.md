# 🪙 Quantum Coin Flip Simulation using PennyLane

This project demonstrates a basic **quantum coin flip** using [PennyLane](https://pennylane.ai/), a Python library for quantum machine learning and differentiable programming.

By applying a **Hadamard gate** to a single qubit, we place it into a quantum superposition of |0⟩ and |1⟩ — representing heads and tails. The measurement of the qubit simulates the outcome of a fair coin toss.


## 🔬 Objective

- Simulate a quantum coin flip using a 1-qubit circuit.
- Measure the output over 1000 shots.
- Visualize the distribution of outcomes.


## 📦 Tools & Libraries

- `PennyLane` — for building and simulating the quantum circuit.
- `Matplotlib` — for visualizing the outcomes.
- `NumPy` — for numerical processing.
- `collections.Counter` — to count measurement results.


## 📈 Results

- The outcomes are measured in the Z-basis, resulting in values of +1 and -1.
- These are mapped to `0 = heads` and `1 = tails`.
- A histogram plot shows the frequency of each result across 1000 trials.

<p align="center">
  <img src="quantum_coin_plot.png" width="400">
</p>

### 🖼️ Simulation Result

![Quantum Coin Flip Plot](quantum_coin_plot.png)

This plot shows the outcome distribution from the quantum coin flip simulation using the Hadamard gate on a single qubit.
## 🧠 What I Learned

- How to define and run a quantum circuit using `qml.qnode`.
- The role of **Hadamard gates** in generating superpositions.
- Basics of quantum measurement and probabilistic outcomes.
- Visualization of quantum measurement data.


## 🚀 How to Run

```bash
# Install PennyLane
pip install pennylane
