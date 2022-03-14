# Benchmarking binding energy calculations for organic structure-directing agents in pure-silica zeolites

This repository contains the data from the following paper:

D. Schwalbe-Koda and R. Gómez-Bombarelli. "Benchmarking binding energy calculations for organic structure-directing agents in pure-silica zeolites". J. Chem. Phys. **154**, 174109 (2021). [DOI](https://doi.org/10.1063/5.0044927).

BibTeX format:
```
@article{schwalbe2021benchmarking,
  title={Benchmarking binding energy calculations for organic structure-directing agents in pure-silica zeolites},
  author={Schwalbe-Koda, Daniel and G{\'o}mez-Bombarelli, Rafael},
  journal={The Journal of Chemical Physics},
  volume={154},
  number={17},
  pages={174109},
  year={2021},
  publisher={AIP Publishing LLC}
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
