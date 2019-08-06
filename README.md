# GlobalFishNutrients
 Data and code for Hicks et al. 2019

*Note: the shapefiles used to define the maps are too large for GitHub, they can be accessed here: https://www.dropbox.com/sh/xk4d5wnocwz50nf/AADIDHkDTREovQG2RsqS64Bca?dl=0*


This repository holds the majority of code used for the Bayesian statistical analysis and plots presented in Hicks *et al*'s manuscript *Harnessing global fisheries to tackle micronutrient deficiencies*. 

All modelling and plots were produced in [Python 3](https://www.python.org/), via [Anaconda](https://www.anaconda.com/what-is-anaconda/), and the [PyMC3](http://docs.pymc.io/index.html) Bayesian modelling package. These must be installed to replicate our analysis.

If you would like to replicate our analysis, clone this repository and install [Jupyter](https://jupyter.org/), then proceed running the code in the associated Jupyter notebooks in this order:

	- Nutrients_analysis.ipynb
	- Nutrients_analysis_STD.ipynb
	- SAU_nutrients_EEZ.ipynb
	- SAU_nutrients_EEZ_reported.ipynb
	- Nutrients_plots.ipynb
	- Nutrients_plots_reported.ipynb

This will reproduce the entire analysis from start to finish, re-estimating the various parameters etc from the original data. Note that new results will differ slightly from those in the paper due to new initial random starting values and the nature of Bayesian analysis. However, new results should be nearly identical.

Please contact Aaron MacNeil ([a.macneil@dal.ca](mailto:a.macneil@dal.ca)) for questions regarding the code or modelling.