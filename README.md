# Rosemary-Derived Compounds for Diabetes: Molecular Dynamics Project

This project investigates the inhibitory potential of phytochemicals from *Rosmarinus officinalis* (rosemary) against key enzymes in type 2 diabetes using molecular docking and dynamics simulations.

## Targets Studied

- **α-Amylase** – compared with **Acarbose**
- **DPP-4** – compared with **Linagliptin**
- **α-Glucosidase** – compared with **Miglitol**

For each target, docking was followed by GROMACS-based 20 ns molecular dynamics simulations.

## Project Structure


Each folder includes:
- `.mdp` input files
- `.pdb` structures
- GROMACS-ready system files
- Sample result files like RMSD plots or `.xvg` outputs
- Simulation setup scripts or logs

> ⚠️ Large output files (e.g., `.xtc`, `.trr`, `.edr`) were excluded to keep this repo lightweight. Full data is available upon request.

## Tools Used

- **PyRx** / AutoDock Vina – for initial docking
- **GROMACS** – for energy minimization, equilibration, and production MDS
- **Python / Bash** – for trajectory analysis (RMSD, RMSF, Rg)

## Author

James Jacob Wabwile  
jamesbwile@gmail.com  
MSc Bioinformatics, University of Nairobi  
Erasmus+ Research Intern – CEU Spain

---

This GitHub repository is a simplified version of my MSc thesis project:  
**“Computational Drug Discovery of Rosemary-Derived Compounds as Potential Therapeutics for Diabetes”**

Feel free to contact me for raw data, simulation trajectories, or full methodology details.
