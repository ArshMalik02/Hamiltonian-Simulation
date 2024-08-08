# Hamiltonian Simulation

This project involves simulating the evolution of quantum systems under given Hamiltonians using Trotter-Suzuki decomposition. The implementation is carried out using Qiskit, and the results are visualized to provide insights into the system's behavior over time.

## Methodology

To simulate the Hamiltonian, the following steps were taken:

1. **Initialization**: Define the Hamiltonian of the system.
2. **Decomposition**: Apply the Trotter-Suzuki decomposition to approximate the time evolution operator.
3. **Simulation**: Use Qiskit to simulate the time evolution of the quantum system.

## Getting Started

### Prerequisites

- Python 3.6 or higher
- Jupyter Notebook
- Qiskit
- Matplotlib
- NumPy

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/ArshMalik02/hamiltonian-simulation.git
    cd hamiltonian-simulation
    ```

2. Install the required packages:
    ```bash
    pip install qiskit matplotlib numpy
    ```

3. Start Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

4. Open the desired notebook from the Jupyter interface.

## Usage
Simply run the cells in the notebook to see the Hamiltonian simulation in action and verify the results.

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## License
This project is licensed under the MIT License.

## Acknowledgements
- [IBM Quantum](https://quantum-computing.ibm.com/) for providing access to quantum processors and simulators.
- The Qiskit community for their excellent documentation and support.
