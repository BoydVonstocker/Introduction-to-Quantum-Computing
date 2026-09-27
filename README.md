# Introduction to Quantum Computing

A beginner-friendly introduction to Quantum Computing with Qiskit.

This repository covers:

* Qubits and quantum states
* Quantum gates and circuit models
* Superposition and entanglement
* Measurement and Bloch sphere visualization
* Quantum circuits using Qiskit
* Foundational quantum algorithms: Deutsch, Deutsch-Jozsa, Bernstein-Vazirani, Grover, and teleportation

The repository contains explanatory notes, examples, and interactive Jupyter/Colab notebooks to help learners build intuition and practical skills in quantum computing.

## Notebooks

Open any notebook in Colab from the link at the top of the file, or run them locally after `pip install -r requirements.txt`.

| # | Topic | Notebook |
|---|---|---|
| 01 | Qubits and quantum states | [Notebks/01 - Introduction_to_quantum_Computing_and_Qiskit.ipynb](Notebks/01%20-%20Introduction_to_quantum_Computing_and_Qiskit.ipynb) |
| 02 | Quantum gates and the circuit model | [Notebks/Notebook_02_Gates_and_how_they_work.ipynb](Notebks/Notebook_02_Gates_and_how_they_work.ipynb) |
| 03 | Superposition and entanglement | [Notebks/03 - Superposition_and_Entanglement.ipynb](Notebks/03%20-%20Superposition_and_Entanglement.ipynb) |
| 04 | Measurement and Bloch sphere | [Notebks/04 - Measurement_and_Bloch_Sphere.ipynb](Notebks/04%20-%20Measurement_and_Bloch_Sphere.ipynb) |
| 05 | Quantum circuits with Qiskit | [Notebks/05 - Quantum_Circuits_with_Qiskit.ipynb](Notebks/05%20-%20Quantum_Circuits_with_Qiskit.ipynb) |
| 06 | Foundational algorithms | [Notebks/06 - Foundational_Algorithms.ipynb](Notebks/06%20-%20Foundational_Algorithms.ipynb) |

Notebook 06 now includes:

1. Deutsch
2. Deutsch-Jozsa
3. Bernstein-Vazirani
4. Grover search ($N=4$)
5. Quantum teleportation

## Suggested path

1. Start with Notebook 01 if Dirac notation or `|0>` / `|1>` still feels new.
2. Notebook 02 is the gate reference: X, Y, Z, H, S, T, CNOT.
3. Notebooks 03 and 04 build the two pictures you will reuse everywhere: interference / Bell pairs, and the Bloch sphere plus measurement.
4. Notebook 05 is the Qiskit workshop (registers, `compose`, transpile, Aer).
5. Notebook 06 puts the pieces together in five standard algorithms.

Each notebook ends with short exercises.

## Local setup

```bash
python -m pip install -r requirements.txt
jupyter notebook Notebks
```
