# qiskit-learning-journey
This repository documents my hands-on practice with **quantum computing fundamentals** using **IBM Qiskit**, completed as part of the Coursera + Packt course *“Practical Quantum Computing with IBM Qiskit for Beginners.”*  
It includes my **code implementations, experiments, and visualizations** of essential quantum gates, circuits, and algorithms.  

---

## Motivation  

- Build an applied understanding of **qubits, gates, and circuits**  
- Learn how to represent states with **statevectors and Bloch spheres**  
- Explore key **quantum operations** through code  
- Create a personal reference that I (and others) can reuse and build upon  
- Part of my learning journey to deepen my knowledge of quantum technologies and prepare to contribute to **research and innovation**  

---

## Repository Contents  

1. **CNOT & Controlled Gates**  
   - Implements CNOT, Controlled-Y, and Controlled-Z gates  
   - Demonstrates entanglement and Bell states  
   - Includes Bloch sphere visualizations  

2. **Hadamard Gate & Measurement**  
   - Introduces the Hadamard transformation  
   - Demonstrates measurement results with simulators and histograms  

3. **Pauli Gates, Bloch Sphere & Histogram**  
   - Visualizes Pauli-X, Pauli-Y, and Pauli-Z gates  
   - Simulates initial states, transitions, and measurement results  

4. **U, R(Φ), S & T Gates**  
   - U-gate with Euler rotations  
   - R(Φ) rotation gates (Rx, Ry, Rz)  
   - S and S† phase gates  
   - T and T† phase gates  
   - Custom initial states and normalization  
   - Bloch sphere visualizations  
   - Statevector representation (including LaTeX formatting)  

5. **Swap Gate**  
   - Demonstrates the SWAP gate  
   - Includes decomposition into a CNOT-based implementation  

6. **Toffoli Gate (CCX and CCZ)**  
   - X- and Z-controlled Toffoli gates  
   - Implementation with standard gates  
   - Simulation results and histogram plots  

---

## Requirements  

**Mandatory:**  
```bash
pip install qiskit qiskit-aer matplotlib numpy
