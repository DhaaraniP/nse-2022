# NSE Notebooks
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/martincornejo/nse-2022/main)

This repository contains a collection of Jupyter notebooks as a supporting material to the lecture *Grid integration of stationary energy storage* (Netzintegration stationärer Energiespeicher) at TUM.


## Setup

### Set up the conda environment
Install conda: https://docs.conda.io/en/latest/miniconda.html

Create the environment from the dependency file.
```
conda env create --file environment.yml
```

### Start Jupyter notebook
Activate the conda environment.
```
conda activate nse-nb
```

Start the Jupyter-lab session.
```
jupyter lab
```

### Update conda environment

During the course, some new packages might be added or removed from the environment. To update to the latest environment version use the following command:
```
conda env update --name nse-nb --file environment.yml --prune
```