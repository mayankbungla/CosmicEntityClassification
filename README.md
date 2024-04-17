# Stellar Classification Dataset  
## Context  
Stellar classification is fundamental in astronomy, providing insights into the spectral characteristics of stars, galaxies, and quasars. This dataset comprises observations from the Sloan Digital Sky Survey (SDSS), offering a comprehensive view of celestial objects.  

## Content  
The dataset contains 100,000 observations, each characterized by 17 features and 1 class label, indicating whether the object is a star, galaxy, or quasar. The features include:  
  
obj_ID: Object Identifier, unique to the catalog used by the CAS.  
alpha: Right Ascension angle (J2000 epoch).  
delta: Declination angle (J2000 epoch).  
u, g, r, i, z: Photometric filter measurements in the ultraviolet, green, red, near-infrared, and infrared ranges, respectively.  
run_ID: Run Number identifying the specific scan.  
rereun_ID: Rerun Number specifying image processing details.  
cam_col: Camera column identifying the scanline within the run.  
field_ID: Field number identifying each field.  
spec_obj_ID: Unique ID for optical spectroscopic objects.  
class: Object class (galaxy, star, or quasar).  
redshift: Redshift value indicating the increase in wavelength.   
plate: Plate ID identifying each plate in SDSS.  
MJD: Modified Julian Date, indicating when the SDSS data was taken.  
fiber_ID: Fiber ID pointing the light at the focal plane in each observation.  
This dataset facilitates the classification of celestial objects based on their spectral properties, aiding in astronomical research and understanding of the universe.  
