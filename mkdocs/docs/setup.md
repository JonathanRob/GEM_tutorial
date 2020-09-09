# Setup and Installation

## Clone or download the GEM_tutorial GitHub repository

Clone the GEM_tutorial repository to your local machine using git
```
git clone https://github.com/JonathanRob/GEM_tutorial.git
```

Or [download the .zip file](https://github.com/JonathanRob/GEM_tutorial/archive/master.zip) directly.

## Install COBRApy

!!! tip
    See the [COBRApy installation guide](https://github.com/opencobra/cobrapy/blob/devel/INSTALL.rst) if you encounter installation problems.

### Option 1. Using the pre-defined conda environment
The `GEM_tutorial` repository contains a conda `environment.yml` file that can be used to create a conda environment with COBRApy. From your terminal, navigate to the tutorial repository directory where the `environment.yml` file is located, and build the environment.
```
conda env create -f 'environment.yml'
```

Activate the conda environment.
```
conda activate cobra-env
```

### Option 2. Using pip
COBRApy can also be installed using pip.
```
pip install cobra
```












