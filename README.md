# Topological Features in Haldane Model

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

## Overview
This repository contains a Python simulation of the Haldane model on a 2D honeycomb lattice. The project focuses on:
- Constructing the Hamiltonian matrix across the Brillouin zone.
- Computing eigenvalues and eigenvectors.
- Extracting topological invariants such as the Berry curvature and Chern number.
- Visualizing phase transitions and band structures to reveal the underlying topological features.

## Features
- **Hamiltonian Construction:** Set up the Haldane model Hamiltonian on a 2D lattice.
- **Eigen-Analysis:** Numerical computation of eigenvalues and eigenvectors.
- **Topological Invariants:** Calculation of Berry curvature and integration to obtain the Chern number.
- **Visualization:** Plotting band structures, Berry curvature distributions, and edge state properties.
- **Parameter Exploration:** Easily adjust model parameters to study various topological regimes.

## Installation

### Prerequisites
- Python 3.x
- [NumPy](https://numpy.org/)
- [SciPy](https://scipy.org/)
- [Matplotlib](https://matplotlib.org/)

### Setup Instructions
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/Haldane-Model-Topological-Features.git
    ```
2. Change into the project directory:
    ```bash
    cd Haldane-Model-Topological-Features
    ```
3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
Run the main script to start the simulation:
```bash
python main.py
