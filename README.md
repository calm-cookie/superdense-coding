# Superdense Coding

_Implementation of Superdense Coding using Qiskit._

Superdense Coding is a way to communicate **two classical bits** of information using a **quantum channel** of communication. Only **one qubit** is transferred and the communicaiton is **not** faster than light.

Let's say ```Alice``` wants to send two classical bits of information to ```Bob```.
- They must share an **entangled pair of qubits** for it to work. 
- Alice performs some operations on her qubit of the shared entangled pair depending upon the message to be shared. 
- After the operations, she sends her **qubit** to Bob through a quantum channel.
- Bob performs some operations on both the entangled qubits, independent of the message.
- **Finally Bob measures the qubits to get the two bits of classical information**.
