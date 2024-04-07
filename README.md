# Quantum MIS Solver

## Overview

This repository contains Python code for solving the Maximum Independent Set (MIS) problem using quantum computing techniques. The code implements two quantum approaches: the Quantum Approximate Optimization Algorithm (QAOA) and Quantum Adiabatic Simulation (QS). These approaches are applied to different instances of the MIS problem represented as graphs.

## Features

- Implementation of QAOA and QS algorithms for solving MIS problems.
- Graph generation and visualization tools for creating and visualizing graphs.
- Optimization functions for finding the optimal parameters for quantum circuits.
- Evaluation functions for assessing the quality of solutions obtained from quantum algorithms.
- Experimentation scripts for running simulations and analyzing results.

## Installation

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/Matrixmang0/MIS-QAOA.git
    ```

2. Navigate to the project directory:

    ```bash
    cd quantum-mis-solver
    ```

3. Create a virtual environment (optional but recommended):

    ```bash
    python -m venv venv
    ```

4. Activate the virtual environment:

    - On Windows:

    ```bash
    venv\Scripts\activate
    ```

    - On macOS and Linux:

    ```bash
    source venv/bin/activate
    ```

5. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Generate graphs:

    ```bash
    # Example: Generating a graph with 5 nodes
    python generate_graph.py --nodes 5 --output graph.gml
    ```

2. Run experiments:

    ```bash
    # Example: Running QAOA experiment on a graph
    python run_experiment.py --algorithm qaoa --graph graph.gml
    ```

3. Analyze results:

    ```bash
    # Example: Analyzing results from experiment
    python analyze_results.py --experiment results.csv
    ```

## Contributing

Contributions are welcome! If you have any suggestions, improvements, or bug fixes, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
