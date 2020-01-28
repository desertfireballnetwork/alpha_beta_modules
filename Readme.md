# Alpha-Beta calculation for fireball data
### This is a Jupyter notebook for calculating dimensionless coefficients Alpha and Beta from fireball velocity and height information. 

This notebook allows you to calculate the basic dimensionless alpha - beta parameters for a set of fireball data after [Gritsevich et al., 2012]( https://doi.org/10.1134/S0010952512010017). 
You may then proceed to check if this corresponds to a likely meteorite dropping event following [Sansom et al., 2019](https://iopscience.iop.org/article/10.3847/1538-4357/ab4516).
This uses the exponential atmosphere simplification. To use a complete atmosphere model for your fireball, please see [Lyytinen et al. 2016](https://doi.org/10.1016/j.pss.2015.10.012).

## Requirements:
- Jupyter (running python 3 kernel)
- Astropy 2.0+
- MPI4py

Example csv file provided.
