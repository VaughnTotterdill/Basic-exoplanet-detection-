# Basic exoplanet detection via light curves 

Inputs: Input a file containing a photometric time-series in the format of time (in days), flux, and flux error as 3 separate columns. 
The flux and flux error can be in arbitrary units. 

Results: The code first estimates the exoplanet period using a BLS algorithm. It then phase folds the light curve to determine the transit time and depth. A more detailed analysis is then performed to obtain the orbital period, orbital separation, and radius ratio (comparison of exoplanet radius compared to the star). 
