# Files for the study *'Simulations of the Advection-Diffusion Equation for Traffic Flow: A Finite Element Approach'*

This repository contains the FreeFEM++ and Jupyter Notebook files used to simulate traffic flow and generate additional visualization for the study's use.

### Prerequisites
Before downloading and running the files, please ensure that:
- FreeFEM++ has been installed to detect and run `.edp` files.
- `.ipynb` Notebook files can be ran on your device.

Each folder contains a `.edp` file for the simulation on the specific road shape, and a `.ipynb` file for generating the *density evolution plot* based on the output files from the `.edp` file. Please download each folder as is.

### Simulation Files
When successfully running the `.edp` simulation file for a road shape, `.dat` output files are created. They save the density profile of the simulation based on the established midsection/s of the road, per `moduloTimeStepIndex` out of `nSteps`, and are stored in a new output folder within the road shape folder. Other output files are also created, but have not been used in the study. Regardless, they can be viewed for reference.

### Visualization Files
The `.ipynb` Notebook file refers to the output folder with the stored `.dat` files to generate the density evolution plot. `.png` files of the generated graphs will be saved within the output folder.
