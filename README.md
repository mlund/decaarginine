# Self-association of a highly charged arginine-rich cell-penetrating peptide

_Giulio Tesei and Mikael Lund, 2017_

[DOI:10.1073/pnas.1712078114](www.pnas.org/cgi/doi/10.1073/pnas.1712078114).

This repository contains a [Jupyter](http://jupyter.org) Notebook reproducing the work of the scientific
paper _Self-association of a highly charged arginine-rich cell-penetrating peptide_ published in the Proceedings of the National Academy of Sciences.

The layout is as follows:

- `environment.yml` - Environment file for setting up dependencies for Anaconda
- `SI-notebook.ipynb` - Jupyter Notebook for reproducing the analyses of SAXS data, MD simulations, and PDB, as well as all presented plots  
- `distances/` - Directory containing distances between pair of atoms of two peptides simulated using umbrella sampling MD
- `mx1908/` - Directory containing SAXS data collected at ESRF (Grenoble, France) in 2016
- `nmr/` - Directory containing NMR data collected at the Grenoble Instruct Center (Grenoble, France) in 2017
- `pdb-analysis/` - Directory containing Jupyter Notebook and data files to reproduce the analysis of the PDB
- `pmfs/` - Directory containing PMFs calculated from umbrella sampling MD simulations using gmx wham
- `fig/` - Directory containing graphical representations generated using VMD
- `r10lstckd/` - Directory containing trajectory files of the R10 dimer at ionic strength 0.01 M   
- `r10mstckd/` - Directory containing trajectory files of the R10 dimer at ionic strength 0.07 M
- `r10hstckd/` - Directory containing trajectory files of the R10 dimer at ionic strength 0.32 M
- `k10lstckd/` - Directory containing trajectory files of the K10 dimer at ionic strength 0.01 M   
- `k10mstckd/` - Directory containing trajectory files of the K10 dimer at ionic strength 0.07 M
- `k10hstckd/` - Directory containing trajectory files of the K10 dimer at ionic strength 0.32 M

To open this Notebook, install python via [(Mini)conda](https://www.continuum.io/downloads) and make sure all required packages are installed and active by issuing the following terminal commands,

    conda env create -f environment.yml
    source activate decaarginine
    jupyter-notebook SI-notebook.ipynb
