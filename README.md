# PINNs for 2D Steady Cavity Flow Simulation

This project utilizes Physics-Informed Neural Networks (PINNs) to simulate steady-state fluid flow within a rectangular cavity. It tackles two scenarios:

Empty Cavity: This simulates the standard cavity flow problem without any obstacles.
Cavity with Cylinder: This scenario introduces a cylinder placed in the center of the cavity, allowing you to study the flow behavior around the object.
# Features

Solves the Navier-Stokes equations for incompressible flow using PINNs.
Visualizes the resulting flow field and pressure distribution.
Offers customization of:
Boundary conditions
Simulation parameters (e.g., Reynolds number)
The presence and size of a cylinder (for the second scenario)
# Installation

1. Clone the repository:
Bash
git clone https://github.com/YanivAB/PINN-Incompressible-N-S-equations-for-low-speed/tree/main
content_copy
2. Install dependencies:
Bash
pip install -r requirements.txt
content_copy
# Usage

1. Train the PINNs model for empty cavity and visualize results:
Run PINN_Incompressible_NS_equations_Cavity_150k.ipynb.ipynb

Or train the PINNs model for cavity with cylinder and visualize results:
Run PINN_Incompressible_NS_equations_Cavity_Cylinder_150k.ipynb.ipynb
content_copy
2. Modify simulation parameters and boundary conditions in config.py.

3. Refer to example.ipynb for a step-by-step demonstration, including selecting the desired cavity configuration (empty or with cylinder).

# Documentation

Developed for Technion's Applied Machine Learning for Scientists and Engineers course (036049) by Prof. Steven H. Frankel.
Course materials: [https://students.technion.ac.il/local/technionsearch/course/36049/202302)]
# Credits

Developed by Yaniv Abramov, Tal Solomonovich, and Matar Hedi.
Inspired by the work of Maziar Raissi on PINNs for fluid flow simulations.
# License

This project is licensed under the MIT License (see LICENSE file).

# Contact

For inquiries, please contact yaniv.abramov12@gmail.com.

# Additional Notes

Allocate sufficient computational resources for training, as PINNs can be computationally intensive.
Experiment with different neural network architectures and optimization algorithms for improved performance.

