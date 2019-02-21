# Quantum Mechanics for Engineers

## Setup

View `py-primer.ipynb` for an introduction to python, numpy, and matplotlib.
Installation instructions are below, and also in `py-primer.ipynb`.

These instructions work best on Ubuntu machines (and it's highly encouaged to use Linux). However, only very slight modifications are necessary for Mac and Windows.

Once Anaconda and the necessary packages are installed, and you can get jupyter up and running, all the coding should be completely agnostic to the operating system.

1. Download the most recent Anaconda distribution (with python 3.x) from: `https://www.anaconda.com/download/`. Alternatively, on Ubuntu command line execute: `wget https://repo.continuum.io/archive/Anaconda3-2018.12-Linux-x86_64.sh`

2. Install Anaconda distribution. On Ubuntu, run `sh Anaconda3-2018.12-Linux-x86_64.sh`

3. In the directory of your choice, clone this git repo: `git clone https://github.com/fleeb24/qc_intro`

4. In the cloned git repo, create a virtual conda environment with python 3.6 and some of the required packages (`numpy`, `matplotlib`, `jupyter`, and `sympy`) by executing `conda create -n qc python=3.6 numpy matplotlib jupyter sympy` and complete the installation.

5. Activate your conda environment with the command `source activate qc` (or `activate qc` for Windows).

6. From inside your `qc` environment, execute `pip install qiskit` to install `qiskit`.

7. Start a local jupyter server with the command: `jupyter notebook`. This should open the jupyter dashboard in your web browser. Alternatively, a link will be printed out in the terminal, which you can paste into your web browser to open the dashboard manually.

8. From the jupyter dashboard open `py-primer.ipynb` and start executing cells (using Shift+Enter).

## Contents

Aside from the `py-primer` notebook, this repo contains a series of jupyter notebooks designed to introduce students to the core principles of quantum mechanics, with a focus on simulation and quantum computing. These notebooks are meant to supplement lecture notes and addtional materials found elsewhere, and to give a hands-on intro to a couple of the jems of the quantum world!

1. **Schrödinger Equation**: Dive straight into the formalism and heart of quantum mechanics with the infinite square well and the harmonic oscillator
2. **Quantum Phenomena**: Investigate several of the mysterious and unintuitive behavior of quantum systems including the uncertainty principle, time evolution of superposition states, and wavefunction collapse
3. **Cats and Qubits**: Build quantum circuits using IBM's excellent `qiskit` and see how quantum computing arises from superposition and entanglement 
4. **Quantum Interpretations**: Test Bell's inequality and reflect on the philosophical implications thereof
