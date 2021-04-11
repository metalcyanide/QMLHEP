## Task 5: About Quantum Computing, QML and Quantum Software

### Quantum computing:

My perspective on quantum computing mainly stems from Moore's law. I was always fascinated about the fact that there should be a physical limit on doubling the number of transistors every two years. After not so many blog posts, I came across quantum computing. The potential to make the moore's law persist in terms of capacity of computation power. Being a CS student, I started to ponder about the breadth of the field mainly in the direction of algorithmic perspective. Neven from google had stated quantum equivalent for Moore's law. I started seeing quantum equivalent for most of the classical solutions and paradigms.

One of the most amazing one among these is Quantum machine learning. Though things are not so trivial, the book by Peter Wittek gave a brief outlook on this field from CS perspective. The applications are so versatile that I started finding papers on Quantum Reinforcement learning, which is quantum equivalent for the best known paradigm for control problems, Reinforcement learning.

Coming on to the algorithms part, the two best known quantum algorithms are Shor's algorithm for factorizing and Grover's Search algorithm (famously known as needle in a haystack). Though these are not realized for any practically useful scale, it still motivates us to build robust quantum computers to make them implementable. 

### QML:
There are multiple ways to look out for the applications of ML using Quantum Computers. Few of them are, quantum-enhanced machine learning, quantum-inspired machine learning, hybrid-classical-quantum machine learning and completely-quantum machine learning. The names speaks for themselves. Though the NISQ devices causes significant issues in scaling the solutions, many robust methods are coming in place to counter these issues. 

## Quantum Algorithms

Grover's Search is a very interesting algorithm that searches the database effectively provided the condition we are searching for is obeyed by extremely tiny fraction of the whole. The speed up provided by this algorithm is square-root-N (O(sqrt(N))). Two important things here, the extremely tiny fraction obeying the condition is not generally observed. But for those cases, even classical algorithms work better, the usage of quantum algorithm when and only when classical algorithms doesn't work should be noted. The other important thing is probabilistic result from quantum algorithms. We can answer questions only probabilistically. These two factors makes creating new quantum algorithms a bit difficult.

## Quantum Control

Fascinated by Quantum Computing, I started working on implementing robust quantum gates using classical machine learning techniques to optimize fidelity for any n-qubit unitary provided n-qubit underlying hamiltonian system. In doing so, I had came across quite a handful of quantum softwares, like qutip, Cirq, Q#, Qiskit, Rigetti and Pennylane.ai. The implementation details and flexibility to create customized functions made be more curious to work in this field.

