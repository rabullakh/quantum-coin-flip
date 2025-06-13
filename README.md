# Quantum Coin Flip Simulation 🪙

This project simulates a **quantum coin flip** using [PennyLane](https://pennylane.ai/), a quantum machine learning library. It demonstrates how a single qubit in superposition can be used to generate probabilistic outcomes—similar to flipping a fair coin.

## 🧪 How It Works

The simulation performs the following steps:

1. Creates a quantum device with 1 qubit and 1000 shots.
2. Applies a Hadamard gate to create a superposition (|0⟩ + |1⟩) / √2.
3. Measures the qubit using the Pauli-Z observable.
4. Maps +1 → 0 (heads) and -1 → 1 (tails).
5. Displays the outcome frequencies in a bar chart.

## 📦 Requirements

Make sure to install the required Python libraries:

```bash
pip install pennylane matplotlib
