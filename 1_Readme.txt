Predicting the metabolic capabilities of Synechococcus elongatus PCC 7942 adapted to different light regimes

Broddrick et.al. 

Instructions for running sample code.

1) Install python and the constraint-based modeling package Cobrapy (Ebrahim et. al 2013).

2) Install Jupyter Notebook.

3) From the command prompt, navigate to the 'Dataset S1' folder included in the SI.

4) Run Jupyter Notebook.

5) Launch the 'Simulation of growth rate' notebook.

5a) Launch the 'Simulation of 23BD production' notebook.

6) From the tool bar select 'Cell' -> 'Run All'

The code will run and return the simulation results.

The code was the same for all simulations in the manuscript with the intial conditions updated.


To Plot Fluxes:

Navigate to escher.github.io

Load a blank Builder map

Load the map "map_Escher.json"
Map -> Load Map JSON

Load the model file "iJB792.json"
Model -> Load COBRA model JSON

Load fluxes "HL_Ci_norm.csv" or "LL_RBPC_norm.csv"
Data -> Load reaction data

The LL_RBPC_norm contains the fluxes used to build Figure 4A and 5 A,B in the main text.
The HL_Ci_norm.csv contains the fluxes used to build Figure 5 C,D and 6A in the main text.
