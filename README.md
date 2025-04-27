# QBMvsRBM
Quantum vs Classical Boltzmann Machine: Small-Scale Comparison

Summary:
In this project, we build and train:

A small Quantum Boltzmann Machine (QBM) using PennyLane (4–6 qubits simulated on Colab),

And a classical Restricted Boltzmann Machine (RBM) using Scikit-learn.

We use a simple binary dataset (like 4-bit patterns) and compare how well each model learns and generates new samples.
The QBM is implemented via a Parameterized Quantum Circuit (PQC) approach, optimizing circuit parameters to match the data distribution.
We evaluate and compare both models based on sample quality, reconstruction error, and cost convergence.
