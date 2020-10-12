# QuantumTeleportation
A simple execution of Quantum Teleportation using the Qiskit Library created by IBM for Quantum Computing. Here i attempt to teleport the Information from one Qubit to another.

*First we add a NOT gate to the first Qubit, then add a Hadamard gate to the second Qubit. Finally Add a ControlledNot gate between the 2nd and 3rd Qubits

![1](/images/1.png)

*Then the reverse is done between the 1st and 2nd Qubits

![2](/images/2.png)

*Then using '.measure' we connect the Qubits to the Classical Bits. Create another ControlledNot gate between 2nd and 3rd Qubits and connect the 1st and 3rd Qubits

![3](/images/3.png)

Now the Quantum Circuit is ready for Quantum Teleportation

When the Circuit is executed using the QASM simulator we can see that the 3rd Qubit has inherited the information of the first Qubit

![4](/images/4.png)

Quantum Teleporation has been achieved.

## A Mathematical representaion of Quantum teleportation
![5](/images/5.jpeg)

Have Funn

Yours Truely

Anuraag Rath
