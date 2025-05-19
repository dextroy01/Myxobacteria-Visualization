# Myxobacteria Visualization
This project simulates the behaviors of myxobacteria in a spatially inhemogenous environment using the advection-diffusion equation and the finite element method

## Installation
1) Download Docker
2) Download devcontainers in vscode to automaticaly run the dolfinx container
3) Otherwise download the contianer from https://hub.docker.com/r/dolfinx/dolfinx

## Project Directory and usage
- The **Example Code** folder contains example code from the dolfinx tutorials
- The advection diffusion code can be found in the **Project Code** folder. Simulations have been saved as .gif's.
- AdvectionDiffusion.ipynb contains the simulation for the normal advection diffusion equation.
- AdvectionDIffusion_spatial_variance.ipynb contains the code for the spatially varrying advection diffusion equation.
- Two simulation gifs are included, one with a large velocity coefficient and one with a low velocity coefficient
