# RK4 Rocket Trajectory Simulation

This project models the trajectory of a rocket under the effects of gravity and atmospheric drag using the classical fourth-order Runge-Kutta (RK4) method. It also performs a convergence study to verify the accuracy of the numerical method.

## Project Features

- Models rocket thrust phase with mass loss over time.
- Includes atmospheric drag with altitude-dependent air density.
- Simulates full flight: thrust, coasting, and descent back to the ground.
- Performs convergence study showing fourth-order accuracy of RK4.
- Compares rocket trajectories with and without atmospheric drag.

## Repository Contents

- `rocket_simulation.py` — Main simulation code for the rocket trajectory.
- `convergence_study.py` — Code for verifying the RK4 method through a convergence study.
- `figures/` — (Optional) Folder containing generated plots from the simulations.

## How to Run

Clone the repository or download the files directly. Then, run the Python scripts:
