# Prospectivity Mapping of Lateritic Ni-Co Mineralisation in the Lachlan Orogen

[![DOI](https://zenodo.org/badge/590281373.svg)](https://doi.org/10.5281/zenodo.10681931)

This repository contains the notebooks and supplementary files required to reproduce the results presented in the paper: Wake, N., Farahbakhsh, E., Müller, R. D. (2024) Lateritic Ni-Co prospectivity modeling in eastern Australia using an enhanced generative adversarial network and positive-unlabeled bagging, Natural Resources Research. The notebook enables users to create a prospectivity map for Lateritic Nickel-Cobalt Mineralisation in the Lachlan Orogen, New South Wales (NSW), Australia.

## Input Files

The input files include geological and geophysical data, which can be downloaded via this [link](https://doi.org/10.5281/zenodo.10681931). Geological data are provided as polyline and polygon files, while geophysical data are available as raster layers. The polyline files contain information on intrusion boundaries, metamorphic boundaries and isograds, rock unit boundaries, and faults. The polygon files represent intrusions, metamorphic facies, and rock units. The raster layers include magnetic, gravity, radiometric, remote sensing, and elevation grids.

## Environment Setup

To set up the necessary environment to run the notebooks, use the `env.yml` file available in this repository. This file configures a Conda environment with all the dependencies required to run the notebooks.

Before training the models, the user needs to run the SMOTE-GAN notebook to generate synthetic positive samples.

## Output Files

The final output is a GeoTIFF file that shows the probability of the targeted mineralisation in NSW or a specific area within it.

### Cite

```bib
@article{Wake2024,
  title = {Lateritic Ni-Co prospectivity modeling in eastern Australia using an enhanced generative adversarial network and positive-unlabeled bagging},
  author = {Wake, N. and Farahbakhsh, Ehsan and M{\"u}ller, R. Dietmar},
  year = {2024},
  journal = {Natural Resources Research},
  volume = {?},
  number = {?},
  pages = {?},
  doi = {10.1007/s11053-024-10423-4},
}
```
