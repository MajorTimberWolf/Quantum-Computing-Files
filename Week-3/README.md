Here is a markdown for quantum teleportation protocol using the current page:

# Quantum Teleportation Protocol

Quantum teleportation is a process that allows a sender (Alice) to transmit a qubit to a receiver (Bob) by using a shared entangled state and two bits of classical communication¹[1]. The protocol can be summarized as follows:

- Alice and Bob share an entangled pair of qubits (A, B) in the state $\vert \phi^+ \rangle = \frac{1}{\sqrt{2}} (\vert 00 \rangle + \vert 11 \rangle)$.
- Alice has another qubit (Q) that she wants to send to Bob². The state of Q is unknown and arbitrary, and can be written as $\alpha \vert 0 \rangle + \beta \vert 1 \rangle$.
- Alice performs a controlled-NOT operation on the pair (Q, A), with Q as the control and A as the target, followed by a Hadamard operation on Q³.
- Alice measures both Q and A in the standard basis and sends the outcomes to Bob as two classical bits.
- Depending on the values of the two bits, Bob performs one of the following operations on his qubit B: nothing, Z, X, or ZX.
- After Bob's operation, his qubit B is in the same state as Alice's original qubit Q, up to a global phase.


The protocol works because Alice's operations transform the initial state of the three qubits into one of the four Bell states, depending on the state of Q. By measuring Q and A, Alice effectively projects the pair (B, R) onto one of these Bell states, where R is another system that Q may be entangled with. Bob's operation then reverses this projection and recovers the state of Q.

The protocol does not violate the no-cloning theorem, because Alice's measurement destroys the state of Q. It also does not allow for faster-than-light communication, because Bob needs to receive Alice's classical bits before he can recover Q. The protocol does demonstrate the power of entanglement as a resource for quantum information processing.

