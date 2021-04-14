# Dynamical Galaxy decomposition
This repo contains the dynamically decomposed (bulge-disc) catalog for IllustrisTNG-100-1 and an example code describbing the methodology in *Galaxy_decomposition_methodology.ipynb*.  


![alt text](https://github.com/McWilliamsCenter/gal_decomp_paper/blob/main/figs/mc_image.png?raw=true)

*Figure: Example of a decomposed galaxy from TNG100-1. The procedure, dynamical/kinematic parameters and variables used here are explained in the paper.*

## Performance on large ensemble of galaxies: Distribution of half-mass radii and Sersic indeces
*Examples_with_catalog.ipynb* notebook demonstrates how to use the data catalog `data/TNG100-1_99_galaxy_scale_len_height_no-idx-bound_Cis1_5r.dat`
![alt text](https://github.com/McWilliamsCenter/gal_decomp_paper/blob/main/figs/sersic.png?raw=true)
*Figure: Fit paramters from a Sersic profile on galaxies of TNG100-1. More details are in the paper.*


## Dependencies

To run, the following Python packages are required other than standard ones like pandas, numpy, scipy, matplotlib:

* [astropy](http://www.astropy.org)
* [inertia_tensors](https://github.com/duncandc/inertia_tensors/edit/master/README.md)
* [illustris_python](https://bitbucket.org/illustris/illustris_python)
