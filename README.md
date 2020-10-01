# GEM Tutorial

This repository contains the scripts and documentation associated with the tutorial on working with genome-scale metabolic models (GEMs) and using them to interpret -omics data in the context of metabolism.

## Exercise 1: COBRApy

1. Create the `cobra-env` conda environment from the `cobra_environment.yml` file in the `envs/` directory.
```
$ conda env create -f cobra_environment.yml
```

2. Activate the `cobra-env` conda environment
```
$ conda activate cobra-env
```

3. Start up Jupyter notebook
```
$ jupyter notebook
```

4. From the Jupyter browser, navigate to the `scripts/` directory and open the `COBRApy_tutorial.ipynb` notebook. Follow the instructions within.


## Exercise 2: GEM-based gene set enrichment and analysis

### OPTIONAL setup: regenerates the `HumanGEM_metabolite_GSC.gmt` and `HumanGEM_subsystem_GSC.gmt` files

1. Start up Jupyter notebook
```
$ jupyter notebook
```

2. From the Jupyter browser, navigate to the `scripts/` directory and open the `GEM_GSC_extraction.ipynb` notebook. Follow the instructions within.


### R Exercise

1. Create the `gsa-env` conda environment from the `gsa_environment.yml` file in the `envs/` directory.
```
$ conda env create -f gsa_environment.yml
```

2. Activate the `gsa-env` conda environment
```
$ conda activate gsa-env
```

3. Launch RStudio from the command line
```
$ conda activate gsa-env
```

4. Follow the instructions found in the `GEM_GSA.html` document, located in the `scripts/` directory. Optionally, the source RMarkdown file `GEM_GSA.Rmd` can be opened within RStudio, though it is not as easy to read as the HTML.





