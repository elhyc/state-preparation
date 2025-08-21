# state-preparation
A Qiskit implementation of a quantum state preparation algorithm 


This repository contains some code which implements a quantum state preparation algorithm, outlined in papers such as [https://arxiv.org/abs/quant-ph/0208112](https://arxiv.org/abs/quant-ph/0208112) and [https://quantum-journal.org/papers/q-2024-06-17-1375/pdf/](https://quantum-journal.org/papers/q-2024-06-17-1375/pdf/). 

In particular, the notebook [StatePrep.ipynb](StatePrep.ipynb) defines a Qiskit function which takes in an $N = 2^{n}$ dimensional complex state vector $\psi = \sum_{x} \psi_{x} \ket{x}_{n}$, and outputs a circuit $U$ such that 

$\begin{equation}
U \ket{0}_{n} =  \sum_{x} \psi_{x} \ket{x}_{n}  
\end{equation}$
