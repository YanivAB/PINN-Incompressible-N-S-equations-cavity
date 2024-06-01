# PINNs for 2D Steady Cavity Flow Simulation

## Description
This project implements Physics-Informed Neural Networks (PINNs) to simulate 2D steady cavity flow. The goal is to solve the Navier-Stokes equations within a rectangular cavity, considering both the fluid flow behavior and the cavity boundary conditions.

## Features
- Solves the Navier-Stokes equations using PINNs.
- Visualizes the flow field and pressure distribution.
- Allows customization of boundary conditions and simulation parameters.

## Installation
1. Clone the repository:
git clone https://github.com/YanivAB/PINN-Incompressible-N-S-equations-for-low-speed/tree/main

2. Install dependencies:
pip install -r requirements.txt

## Usage
1. Run `T_final.py` to train the PINNs model and visualize the results:
python T_final.py

markdown
Copy code
2. Modify `config.py` to adjust simulation parameters and boundary conditions.
3. Refer to the Jupyter Notebook `example.ipynb` for a step-by-step demonstration.

## Documentation
The project was maded for Technion Applied Machine Learning
for Scientists and Engineers course (036049) by Prof. Steven H. Frankel.
- Course materials: [https://students.technion.ac.il/local/technionsearch/course/36049/202302)]
- Research papers: [Link to relevant papers]

## Credits
- Developed by Yaniv Abramov, Tal Solomonovich and Matar Hedi.
- Inspired by the work of [Researcher Name] on PINNs for fluid flow simulations.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For inquiries, please contact [Your Email Address].

## Additional Notes
- Make sure to allocate sufficient computational resources for training the PINNs model, as it can be computationally intensive.
- Experiment with different neural network architectures and optimization algorithms to improve performance and convergence.

Feel free to customize this template to fit your project's specific details and requirements!