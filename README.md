# Physics-Informed Neural Network (PINN) for Solving Ordinary Differential Equations (ODEs)

## Overview

This repository contains a Python implementation of a Physics-Informed Neural Network (PINN) for solving Ordinary Differential Equations (ODEs). The PINN approach involves incorporating the ODEs into the loss function of the neural network, allowing the network to learn the underlying physics of the problem.

## Features

* Solves systems of ODEs using a PINN approach
* Incorporates the ODEs into the loss function of the neural network
* Uses a neural network to approximate the solution to the ODEs
* Supports multiple ODEs and initial conditions
* Compares the performance of the PINN approach with traditional numerical methods (Euler's method, Improved Euler's method, and Runge-Kutta method)

## Requirements

* Python 3.x
* TensorFlow 2.x
* NumPy
* SciPy
* Matplotlib

## Usage

1. Clone the repository: `git clone https://github.com/your-username/pinn-ode-solver.git`
2. Install the required dependencies: `pip install -r requirements.txt`
3. Open the Jupyter Notebook file `pinn_ode_solver.ipynb` and run the cells to execute the code.

## Results

The results of the code are plotted in several figures, including:

* Local deviations for Euler's method, Improved Euler's method, and PINN with respect to Runge-Kutta method
* Global deviations for Euler's method, Improved Euler's method, and PINN with respect to Runge-Kutta method
* Comparison of the performance of the PINN approach with traditional numerical methods

## Contributing

Contributions are welcome! If you'd like to contribute to this repository, please fork the repository and submit a pull request.

## License

This repository is licensed under the MIT License.

## Acknowledgments

This repository was inspired by the work of Raissi et al. on Physics-Informed Neural Networks.
