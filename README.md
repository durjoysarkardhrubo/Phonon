## Phonon

This repository contains all the tools and scripts needed to measure phonon properties using [LAMMPS](https://www.lammps.org/) and other analysis utilities. It includes:

- **LAMMPS Input Files**: Configuration files, force-field parameters, and scripts for running simulations that capture phonon modes.
- **Analysis Scripts**: Python or other scripts to post-process simulation data for phonon dispersion, density of states, and related properties.
- **Documentation**: Step-by-step instructions for setting up simulations, analyzing outputs, and validating results.

### Suggested Folder Structure

- `docs/`  
  Documentation, project notes, and references.
  
- `lammps/`  
  Core LAMMPS input scripts, force-field parameters, and example data files.
  
- `analysis/`  
  Python/R/Matlab scripts for processing LAMMPS outputs and extracting phonon information.
  
- `results/`  
  Simulation outputs, processed data, and plots (organized by project or material system).

- `tests/`  
  Automated tests or validation scripts to ensure correctness of analysis pipelines.
