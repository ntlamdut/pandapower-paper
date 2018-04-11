# pandapower case study

This repository includes an exemplary case study that demonstrates the capabilities of pandapower.
The case study showcases some pandapower functionality and is also used in a reference paper for pandapower (to be published)

The case study consists of three parts, which are available in interactive jupyter notebooks:
1. Definition of a 10kV ring main grid in radial operation ([grid.ipynb](grid.ipynb))
2. Analysis of all possible switching states in the grid to analyse feasible switch positions considering radiality and short-circuit constraints ([switch_evaluation.ipynb](switch_evaluation.ipynb))
3. Time series simulation for one day optimising switching states and transformer taps considering active power losses, line loading, transformer loading and voltage constraints ([time_series_simulation.ipynb](time_series_simulation.ipynb))

The case study works with pandapower 1.4.3.