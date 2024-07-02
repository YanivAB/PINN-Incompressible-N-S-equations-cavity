# PINNs for 2D Steady Cavity Flow Simulation

## Description
This project implements Physics-Informed Neural Networks (PINNs) to simulate 2D steady cavity flow. The goal is to solve the Navier-Stokes equations within a rectangular cavity, considering both the fluid flow behavior and the cavity and cylinder boundary conditions.

## Features
- Solves the Navier-Stokes equations using PINNs.
- Visualizes the flow field and pressure distribution.
- Allows customization of boundary conditions and simulation parameters.

## Installation
1. Clone the repository:
git clone https://github.com/YanivAB/PINN-Incompressible-N-S-equations-cavity.git

2. Install dependencies:
pip install -r requirements.txt

## Usage
Run  `PINN_Incompressible_NS_equations_Cavity.ipynb` to train the PINNs model or run read section to read the workspace from .npz file.

## Documentation
The project was made for Technion Applied Machine Learning
for Scientists and Engineers course (036049) by Prof. Steven H. Frankel.
- Course materials: [https://students.technion.ac.il/local/technionsearch/course/36049/202302)]
- TA: Hemanth Kakumani

## Credits
- Developed by Yaniv Abramov, Tal Solomonovich and Matar Hedi.

## Contact
For inquiries, please contact yaniv.abramov12@gmail.com.

## Additional Notes
- Make sure to allocate sufficient computational resources for training the PINNs model, as it can be computationally intensive.
- Experiment with different neural network architectures and optimization algorithms to improve performance and convergence.