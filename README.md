# resolved_SED

Idea is to measure resolved physical properties of galaxies starting from HST imaging. One can use other lower spatial resolution imaging, if science is not restricted to be at kpc-scale. For details please refer to Hemmati et al. 2014.


The HST images in five CANDELS fields as well as the multi-wavelength catalogs (needed to do initial selection of sources) can be found and downloaded from here:
https://archive.stsci.edu/prepds/candels/

I upload the PSFs I build using stars in the GOODS-S field for all HST filters in this repository. There might be more optimized versions for different parts of each field or in different fields.

Codes are written in jupyter notebooks and you can find short description below. 

- An ipython notebook to select galaxies, from an integrated multi-wavelength catalog.
- An ipython notebook to generate per pixel multi-wavelength photometry catalog for a galaxy given RA, DEC and Redshift. 
- Fitting using SOMfit in python instead of LePhare. (Not there yet!)
- Plotting LePhare results into 2D maps. 




