# Quantum-Blockchain-Simulator

A simulator for exploring the interactions between quantum computing and blockchain.

**Features:**
•   Simulate quantum attacks on blockchain cryptography.
•   Model post-quantum cryptographic algorithms.
•   Analyze the security of blockchain protocols in the quantum era.

**Requirements:**
•   Python 3.7+
•   Qiskit
•   Cryptography library

**Usage:**
python
from src.simulator import QuantumAttackSimulator

# Initialize the simulator
simulator = QuantumAttackSimulator()

# Simulate Shor's algorithm attack on RSA
simulator.simulate_shor_rsa_attack()

# Analyze the results
simulator.analyze_results()
