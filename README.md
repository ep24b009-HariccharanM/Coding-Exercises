# Coding-Exercises

I have attached most of my coding exercises here. The coding exercises include 
- Variational Quantum Eigensolver 2x2
- Variational Quantum Eigensolver 4x4
- Hartree Fock method for 1D infinite well.

**Variational Quantum Eigensolver 2x2:** \
 _Problem Statement_ : In this exercise I have used VQE to find the eigenvector of 2x2 Hermitian matrix.\
 _Modules_:The program has been made from scratch with numpy and simple functions from Qiskit module.\
_Result_:Through the exercise I was able to understand and execute VQE for 2x2 Hermitian.

**Variational Quantum Eigensolver 4x4:** \
 _Problem Statement_ : In this exercise I have used VQE to find the eigenvector of 4x4 Hermitian matrix.\
 _Failed Attempt_ : In the first attempt, I used a Quantum circuit without any means of Entanglement. This lead to the shrinkage of Hilbert space where the exact solution lies. Hence the code did not work.\
 _Modules_:The second program has been made from scratch with numpy and simple functions from Qiskit module. This program uses 8 parameters though there are only 6 independent variables in the problem. Taking 8 parameters ensures a smooth rotation of state vectors. I have used both Gradient method and COBYLA for optimising the Quantum state.\
_Result_:Through the exercise I was able to understand and execute VQE for 4x4 Hermitian and why is Entanglement required to find the exact solution. The end results of both Gradient and COBYLA match and only vary by global phase.
