Experimental data and theoretical model code from the Preprint https://arxiv.org/abs/2509.12830: Sources of nonlinearity in the response of a driven nano-electromechanical resonator

The folder titled 'Measurements' contains the measured data set used in Fig. 4 and Appendix D.

The codes to produce the current and displacement simulations are the following: 

'TheorySimulations_displacement.ipynb' --> Fig. 2 and 3

'ExperimentalSimulations_displacement.ipynb' --> Fig. 4

To run the codes, it is necessary to supply them with initial conditions. This is for differential equations problem to converge. We have provided the ones used in this manuscript in the folder labeled 'InitialConditions'. To produce new initial conditions with other parameters, we recommend to take a look at: https://github.com/oxquantum-repo/spin-mechanical-coupling-2025-data-model/blob/publication/model/resonant/oscillator.jl

These codes are written in Julia v1.12.4. The following packages are used:
DifferentialEquations (v"7.17.0"), LinearAlgebra (v"1.12.0"), NPZ (v"0.4.3"), ProgressBars (v"1.5.1"), ProgressMeter (v"1.11.0"), Integrals (v"5.1.0"), and Plots (v"1.41.4").

The saved final simulations can be found in the folder titled 'Simulations'. We additionally have provided the python code 'Visualization.ipynb' for plotting. 

