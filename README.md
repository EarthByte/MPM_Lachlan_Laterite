# Prospectivity Mapping of Ni-Co Laterites in the Lachlan Orogen

[![DOI](https://zenodo.org/badge/590281373.svg)](https://zenodo.org/doi/10.5281/zenodo.10681931)

This repository contains the notebooks and supplementary files required to reproduce the results presented in a paper currently under review by Wake et al. The notebook enables users to create a prospectivity map for nickel-cobalt laterites in the Lachlan Orogen, New South Wales (NSW), Australia.

## Input Files

The input files include geological and geophysical data. Geological data are provided as polyline and polygon files, while geophysical data are available as raster layers. The polyline files contain information on intrusion boundaries, metamorphic boundaries and isograds, rock unit boundaries, and faults. The polygon files represent intrusions, metamorphic facies, and rock units. The raster layers include magnetic, gravity, radiometric, remote sensing, and elevation grids.

## Environment Setup

To set up the necessary environment to run the MPM notebooks, use the `env.yml` file available in this repository. This file configures a Conda environment with all the dependencies required to run the notebooks.

Before training the models, the user needs to run the SMOTE-GAN notebook to generate synthetic positive samples.

## Output Files

The final output is a GeoTIFF file that shows the probability of the targeted mineralization in NSW or a specific area within it.

### Cite

```bib
@article{Wake2024,
  title = {Lateritic Ni-Co prospectivity modelling in eastern Australia using an enhanced generative adversarial network and positive-unlabelled bagging},
  author = {Wake, N. and Farahbakhsh, Ehsan and M{\"u}ller, R. Dietmar},
  year = {2024},
  journal = {?},
  volume = {?},
  number = {?},
  pages = {?},
  doi = {?},
}
```
