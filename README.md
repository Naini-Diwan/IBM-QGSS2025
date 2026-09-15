# Qiskit Global Summer School 2025

These are my lab notebooks for the IBM [Qiskit Global Summer School](https://www.ibm.com/quantum/blog/qiskit-summer-school-2025) (QGSS) 2025. Each notebook combines theory with hands-on Qiskit exercises, graded inline.

## Contents

| Notebook | Topic |
|---|---|
| `Lab-0.ipynb` | Environment setup: installing Qiskit 2.x and the grader, configuring an IBM Cloud account, running a sanity-check circuit, and building/optimizing/executing a three-qubit GHZ state on simulator and real hardware. |
| `Lab-1.ipynb` | Superposition, interference, measurement, and entanglement. Covers the double-slit experiment, Schrödinger's cat, the CHSH game, and quantum teleportation, with a bonus run on real hardware. |
| `Lab-2.ipynb` | Solving Max-Cut with QAOA. Covers selecting qubits by hardware metrics, mapping the problem to an Ising Hamiltonian, running on noisy simulators, transpilation and layout selection, and error mitigation (folding, extrapolation, NEAT). |
| `Lab-3.ipynb` | Quantum chemistry basics and Sample-based Quantum Diagonalization (SQD). Covers the Schrödinger equation, basis sets, Hamiltonian size scaling, the LUCJ ansatz, and the configuration-recovery loop, finishing with a real-hardware run. |
| `Lab-4.ipynb` | Quantum error correction. Covers classical linear codes, the stabilizer formalism, the 3-qubit bit-flip code, the [[7,1,3]] Steane code, and an introduction to toric and gross codes. |

## Requirements

- Python with Qiskit SDK `>=2.0.0` (`pip install 'qiskit[visualization]'`)
- Qiskit IBM Runtime `>=0.22` (later labs require `>=0.40`)
- The QGSS grader (`>=0.22.x`, version requirement increases per lab)
- An IBM Cloud / IBM Quantum account and API token (set up in Lab 0)
- Lab 3 additionally needs Qiskit Addons SQD and `ffsim`; some of its dependencies are not available on Windows
- Lab 2 needs the `Graphviz` library for one optional plotting cell


## Note

- Exercises were graded inline via the QGSS grader.
- I'm [Naini Diwan](https://naini-diwan.github.io/Hello-Naini/), and here's is my [Excellence Badge](https://drive.google.com/file/d/1JflSxnJd-IZ9Ltv8tjF4pwT8HpY-JHMc/view?usp=sharing) for this summer school :)
