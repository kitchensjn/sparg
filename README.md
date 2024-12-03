# sparg Manuscript

This repository contains all of the code needed to recreate the figures in the sparg manuscript, found [here](https://doi.org/10.1101/2024.04.10.588900).

## Instructions

### Download simulation outputs from Dryad

Place these in the simulations folder. The README within this folder explains the differences between the simulations.

### Create the conda environment from environment.yml and launch Jupyter Lab

The following commands will load all necessary dependencies including sparg from its GitHub repository as well as Jupyter Lab for viewing the figures. The conda environment is named `sparg`. The final command launches the Jupyter Lab notebook.

```
conda env create -f environment.yml
conda activate sparg
jupyter lab
```

### Recreate Figures

Within the figures folder, there is a folder for each figure in the manuscript. The