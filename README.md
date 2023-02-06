# C-PhLARE Scientific Analysis Code Repo

This repository contains the analysis code and data (or pointers to the data) used for the Colorado Physics Laboratory Academic Research Effort (C-PhLARE) resulting in a paper submitted to The Astrophysical Journal (citation forthcoming). 

## Code
The main files to look at are the two Jupyter notebooks containing Python code: [AlphaCalculation.ipynb](AlphaCalculation.ipynb) and [minxss_make_flare_frequency_distribution.ipynb](minxss_make_flare_frequency_distribution.ipynb). 

## Data
The data for the former is contained in this repo. The data for the latter is too large for the repo (128 MB) but can be found on the [mission's data page](https://lasp.colorado.edu/home/minxss/data) (find MinXSS-1, Level 1; we used v4.0.0 for this analysis), or directly from [this link](https://www.dropbox.com/s/vhfph5w3yyk6hh0/minxss1_l1_mission_length_v4.0.0.sav?dl=0). 

## Environment
[AlphaCalculation.ipynb](AlphaCalculation.ipynb) only requires a basic scientific python environment (e.g., `numpy`, `pandas`) and the notebook uses `!pip install` for anything more special. For the MinXSS analysis, an [environment.yml](environment.yml) file is provided that can be installed with `conda`, or inspected to see what packages are needed to install with `pip` or otherwise. 
