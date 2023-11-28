---
title: synth_clifford_bm
description: API reference for qiskit.synthesis.synth_clifford_bm
in_page_toc_min_heading_level: 1
python_api_type: function
python_api_name: qiskit.synthesis.synth_clifford_bm
---

<span id="qiskit-synthesis-synth-clifford-bm" />

# qiskit.synthesis.synth\_clifford\_bm

<span id="qiskit.synthesis.synth_clifford_bm" />

`synth_clifford_bm(clifford)`

Optimal CX-cost decomposition of a Clifford operator on 2-qubits or 3-qubits into a QuantumCircuit based on Bravyi-Maslov method.

**Parameters**

**clifford** ([*Clifford*](qiskit.quantum_info.Clifford "qiskit.quantum_info.Clifford")) – a clifford operator.

**Returns**

a circuit implementation of the Clifford.

**Return type**

[QuantumCircuit](qiskit.circuit.QuantumCircuit "qiskit.circuit.QuantumCircuit")

**Raises**

**QiskitError** – if clifford is on more than 3 qubits.

## Reference:

1.  S. Bravyi, D. Maslov, *Hadamard-free circuits expose the structure of the Clifford group*, [arXiv:2003.09412 \[quant-ph\]](https://arxiv.org/abs/2003.09412)
