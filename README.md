# Rocket Trajectory & Gravity Turn Simulation

This repository contains the codebase used to generate the results and plots for the technical report.

## Structure
* `opt_sim_forward/` - Main multi-file simulation codebase. 
  *(To execute, run: `python nazwa_pliku.py`)*
* `upc_gravity_turn.py` - Standalone script for generating the flight path angle vs. mass ratio plot.
* `prompts_history.pdf` - Supplementary document detailing the AI usage scope and reference queries.

## Requirements
To run the scripts, you need Python and the following standard packages:
```bash
pip install numpy matplotlib numba
