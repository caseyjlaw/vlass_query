# VLASS Transient Search and Analysis of FIRST J141918.9+394036

This repo includes code, data, and analysis related to the Very Large Array Sky Survey and radio transient FIRST J141918.9+394036.

## Contents

1) The basic search tool is a Python module that scrapes the NRAO VLASS archive for quicklook images. 
Import `get_vlass.py` to use functions for querying NRAO VLASS 1.1 quick look image release.
This module is now obsolete, since the CADC has a nice query tool at http://www.cadc-ccda.hia-iha.nrc-cnrc.gc.ca/en/search.

2) The jupyter notebook includes analysis of radio transient FIRST J141918.9+394036.
Clone the repo, load `J141918.855+394036.03.ipynb` in Jupyter or nteract, and execute
all cells to reproduce original analysis and plots.
This repo also includes GRB simulation and radio source fitting results used as input to the notebook.

See [Law et al 2018](https://arxiv.org/abs/1808.08964) for the first compiled version of the
FIRST J141918.9+394036 paper.
