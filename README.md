# QubitVise: Double-Sided Crosstalk Attack in Superconducting Quantum Computers

This notebook provides a demonstration of the *QubitVise* attack. The notebook shows how to create two attacker circuits with many $CNOT$ gates each and assign the circuits to specific physical qubits in the target quantum computer. It then demonstrates how to add a victim circuit and to assign it to qubits physically located between the two attacker circuits. The circuits are executed on the Rigetti Ankaa-3 quantum computer by using qBraid service. The example attacker circuits use many $CNOT$ gates to generates noise or crosstalk that affects the victim circuit. As of June 2025 this is first demonstration of double-sided crosstalk attack on a victim quantum circuit that is larger than 1 qubit, and also first type of this attack on Rigetti.

# Research Paper Citation

Adriana Aranguren Arellano, He Xie, and Jakub Szefer. "QubitVise: Double-Sided Crosstalk Attack in
Superconducting Quantum Computers". Under review, 2025.

Students Adriana and He, listed in alphabetical order, contributed to early evaluation of the ideas presented in this paper as part of the Secure Quantum Computing course at Northwestern University.

This work was supported in part by NSF grant 2332406.

# Code License

The code in this repository is licensed under the GNU General Public License v3.0 (GPLv3). You may redistribute and/or modify it under the terms of the GPLv3. See the [LICENSE](./LICENSE.txt) file for details.

# Text and Image Copyright

The text and images in the [main](./main.ipynb) Python notebook are copyrighted by Jakub Szefer, June 2025.

#  Contact

All questions, improvementns, and suggestions can be sent to Jakub Szefer <jakub.szefer@northwestern.edu>
