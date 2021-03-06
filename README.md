# Benchmarking binding energy calculations for organic structure-directing agents in pure-silica zeolites

This repository contains the data from the following paper:

D. Schwalbe-Koda and R. Gómez-Bombarelli. "Benchmarking binding energy calculations for organic structure-directing agents in pure-silica zeolites". [ChemRxiv.13270184](https://doi.org/10.26434/chemrxiv.13270184) (2020).

BibTeX format:
```
@article{,
    title={Benchmarking binding energy calculations for organic structure-directing agents in pure-silica zeolites},
    author={Schwalbe-Koda, Daniel and Gómez-Bombarelli, Rafael},
    journal={ChemRxiv.13270184},
    year={2020},
    doi={10.26434/chemrxiv.13270184}
}
```

## Contents

This repository contains:

* [Data](data/) summarizing the calculations performed for the article and storing all the crystal structures from each one of them.
* [Plots](plots.ipynb) that reproduce the figures in the article.

The dataset of initial poses at `data/docked_poses.json` contains all 272 poses initially used for all optimizations performed in the paper. Structures were generated using the [VOID package](https://github.com/learningmatter-mit/VOID) using DFT-optimized substrates and molecular conformers, as described in the paper.

## Requirements

The Jupyter Notebook was written in Python and requires the following packages:

```
numpy
pandas
seaborn
matplotlib
```
