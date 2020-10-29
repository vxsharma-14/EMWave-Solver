# EMWave-Solver

This application solves the interaction of waves with a linear, isotropic, dispersive/non-dispersive, dielectric material.

At the start of simulation, a text file will be created in the OUTPUT folder of the directory with the details of experiment number and simulation conditions. The experiment number serve as the unique identifier for each experiments to keep a track of the experiments conducted on a given data. The results will be saved in the OUTPUT folder.

NOTE:
Non-dispersive properties are modeling using 2-pole Debye equation with static conductivity term.
Grid generation module will be added later. I have a different program that geneartes grid data. Grid input file for square, circle to be added.
User defined inputs must be provided in the text files contained in INPUT folder.
At this stage of development, conduction boundary condition is implemented. Work is under progress to include PML boundary conditions.
Subroutines to write output data to files is incomplete and I will add write output functionalities as time allows.
I have to prepare a code documentation that will serve as the USER MANUAL.
USE CFL = 0.5 for optimum results. I am working on investigations for accuracy improvement at higher CFL numbers.


No LICENSE is being offered for this application at this time.
2020 Copyright by Vishal Sharma.
