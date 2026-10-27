# Island 1 of TSET-As-1: Coulomb diamonds

21/10/26 - Island1_functions.ipynb defines the model of island 1 of the arsenic three-way SET (TSET-As-1): units, parameters, the Island class (Beenakker's constant-interaction model with a ladder of energy levels) and the function blockade_map, which finds where the island is Coulomb blockaded. 
Island1_outputs.ipynb loads those functions and uses them to plot the energy levels, the addition energies and the Coulomb diamonds at T = 0.

27/10/26 - Now the code can output Coulomb diamonds for T>0 and calculate the main current passing through the device (with no stray dopants or oxide defects modelled yet).

Keep both notebooks in the same folder and run Island1_outputs.ipynb (needs numpy and matplotlib). 
