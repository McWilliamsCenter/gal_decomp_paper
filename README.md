# Dynamical Galaxy decomposition
 


This repository contains a dynamically decomposed (bulge-disc) catalog for  [IllustrisTNG-100-1](https://www.tng-project.org/) (which at the time the work was carried out was the highest resolution publicly available dataset) and an example code describing the methodology in *Galaxy_decomposition_methodology.ipynb*.  
For full details please refer to the paper at https://arxiv.org/abs/2105.02237


![alt text](https://github.com/McWilliamsCenter/gal_decomp_paper/blob/main/figs/mc_image.png?raw=true)

*Figure: Example of a decomposed galaxy from TNG100-1. The procedure, dynamical/kinematic parameters and variables used here are explained in the paper.*

## Performance on large ensemble of galaxies: Distribution of half-mass radii and Sersic indices
 

![alt text](https://github.com/McWilliamsCenter/gal_decomp_paper/blob/main/figs/sersic.png?raw=true)
*Figure: Parameters from fits to Sersic profiles on the projected mass profiles of decomposed components of galaxies of TNG100-1. More details are in the paper.*
 
*Examples_with_catalog.ipynb* notebook demonstrates how to use the data catalog `data/TNG100-1_99_galaxy_scale_len_height_no-idx-bound_Cis1_5r.dat`
 

 
## Dependencies

To run the example notebook, the following Python packages are required other than standard ones like pandas, numpy, scipy, matplotlib:

* [astropy](http://www.astropy.org)
* [inertia_tensors](https://github.com/duncandc/inertia_tensors/edit/master/README.md)
* [illustris_python](https://bitbucket.org/illustris/illustris_python)
* [pomegranate](https://pomegranate.readthedocs.io/en/latest/)


## Contact and reporting issues
For questions/issues regarding this repo please use the Issues feature by clicking on "New Issues"
