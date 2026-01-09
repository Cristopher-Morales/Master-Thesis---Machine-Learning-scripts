# Machine Learning Scripts – Master Thesis Project

This repository contains Python notebooks and data files developed during my **Master’s thesis at TU Delft**, focused on **Machine Learning applications in Numerical Combustion**.

The main objective of this work is the development and analysis of **Artificial Neural Network (ANN) models** as a computationally efficient alternative to conventional **lookup tables** used in numerical simulations of **turbulent combustion**, with particular focus on hydrogen combustion.

## Repository Contents

### Data
- `Information_ANN_Architectures_4D_hydrogen.csv`  
  Dataset containing information on ANN architectures used for 4D hydrogen combustion cases. This file is updated as new architectures and results are generated.

### Jupyter Notebooks
- `function_ANNs.ipynb`  
  Functions developed for training and evaluating Artificial Neural Networks, including data preprocessing and model handling.

- `Steady_unsteady_flamelets.ipynb`  
  Generation and analysis of steady and unsteady flamelet-based lookup tables, including updated 4D datasets.

- `Plots_6D.ipynb`  
  Functions and scripts for post-processing and visualisation of results obtained from 6D ANN models.

- `tables to csv file.ipynb`  
  Jupyter Notebook used for converting lookup tables from `.txt` format to `.csv` format for easier processing and analysis.

### Documentation
- `README.md`  
  Overview and description of the repository contents.

- `LICENSE`  
  GNU General Public License v3.0 (GPL-3.0).

## Background and Reference

The theoretical background of the lookup tables and combustion modelling approaches used in this repository are detailed in my Master’s thesis:

**Cristopher Morales**,  
*Using Artificial Intelligence for turbulent combustion modelling: Simplifying the conventional lookup tables*,  
TU Delft, 2021.  
Available at:  
https://repository.tudelft.nl/islandora/object/uuid:0e4db0e6-1852-4346-ad25-11f3eed9d0bd?collection=education

## Citation

If you find this repository or the associated thesis useful for your research, I would greatly appreciate if you cite the thesis in your work.

## Notes

- The notebooks are intended for **research and educational purposes**.
- Some scripts may require adaptation depending on the dataset size, ANN architecture, or combustion configuration.
- Contributions, issues, and suggestions are welcome.
