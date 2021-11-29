# IBM Quantum Awards: Open Science Prize 2021

IBM Quantum is excited to announce the fourth annual quantum awards (and the second annual Open Science Prize)—an award for those who can present an open source solution to some of the most pressing problems in the field of quantum computing. 

This year, the challenge will feature one problem from the field of quantum simulation, solvable through one of two approaches. The best open source solution to each approach will receive a $40,000 prize, and the winner overall will receive another $20,000. 

Simulating physical systems on quantum computers is a promising application of near-term quantum processors. This year's problem asks participants to simulate a Heisenberg model Hamiltonian for three interacting atoms on IBM Quantum's 7-qubit Jakarta system. The goal is to simulate the evolution of a known quantum state with the best fidelity as possible using Trotterization. 

**Read more at our [blog](https://www.research.ibm.com/blog/quantum-open-science-prize) and register [here](https://ibmquantumawards.bemyapp.com)**.

The competition will conclude and judging will commence on  April 16, 2022. 

Participants must choose one solution method and may submit their answer using 1) Qiskit Pulse or 2) solving the problem using Qiskit defaults, as outlined below:

- Each team or participant may only contribute to one submission
- Solution may only be executed on the designated device (ibmq_jakarta)
- Each submission must use Trotterization to evolve the specified state, under the specified Hamiltonian, for the specified duration (as outlined in the included Jupyter Notebook) with at least 4 Trotter steps.
- Only use Open Pulse and or pulsed gates functionality as outlined in the included Jupyter notebooks.
- Only use libraries that can be installed using either pip install or conda install and no purchased libraries.
- Document code with concise, clear language about the chosen methodology.
- State tomography fidelity (for 4 or more trotter steps) must meet a minimum value of 30%.

The submissions will be judged on the following criteria:
- Performance as measured by the state tomography fidelity in comparison to other submissions (Max 15 points)
- Clarity of provided documentation and solution code (Max 5 points)
- Creativity in developing a unique, innovative, and original solution (Max 5 points)
