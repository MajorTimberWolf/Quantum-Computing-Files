# Superdense Coding

Superdense coding is a quantum communication protocol that allows two parties to transmit two classical bits of information using only one qubit. It takes advantage of the phenomenon of quantum entanglement to achieve this efficient communication.

## Protocol

The superdense coding protocol involves the following steps:

1. Initialization: Alice and Bob share a pair of entangled qubits, typically in the Bell state |Φ⁺⟩ = (|00⟩ + |11⟩)/√2.

2. Encoding: Alice applies a specific quantum gate on her qubit based on the two classical bits she wants to send. There are four possible gates: I (identity), X (Pauli-X), Z (Pauli-Z), and Y (Pauli-Y).

3. Transmission: Alice sends her qubit to Bob through a quantum channel.

4. Decoding: Bob applies a series of quantum gates on his qubit to retrieve the two classical bits encoded by Alice.

## Analysis

Superdense coding has several advantages over classical communication:

- Efficient use of quantum resources: It allows the transmission of two classical bits using only one qubit, which can be beneficial in scenarios where qubits are a limited resource.

- Increased communication capacity: Superdense coding can transmit two bits per qubit, while classical communication can only transmit one bit per classical channel.

- Quantum advantage: Superdense coding takes advantage of quantum entanglement, a uniquely quantum phenomenon, to achieve its efficiency.

## Implementation using Qiskit

Qiskit is an open-source framework for quantum computing that provides tools for implementing superdense coding. A coded jupyter notebook explaining the superdense coding is present.
