# Linsteretal2025
Simulation code 
The folder contains .c files that contain the code, .mak are make files to compile and link, .dat files are parameter files user can change and .init files
contain parameters and definitions needed to run the code. 
SIM.C defines how to create neurons and synapses 
UPDATE.C has functions that allow network to be updated each time step and to run a simulation plus some miscallenous. 
CURVES.C, DRAW.C, GRA.C, SHOW.C, COLOR.C are all about display
FFT.C computer FFTs
FUNCTIONS.C defines functions that govern neurons 
IO.C defines functions to create odor stimulations 
SET.C reads parameters from .dat files and creates a network. 
UTIL.C has a list of useful functions 
.dat files are parameter files that user can change when setting up a network. These define neurons, connectivity, channels and so on
.init files define functions and global variables 
NEURON.C runs the simulation 
SAVE.C gives a means to run through various parameter ranges and save results 
