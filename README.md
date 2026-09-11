# Basic exoplanet detection via light curves 

Inputs: Input a file containing a photometric time-series in the format of time (in days), flux, and flux error as 3 separate columns. 
The flux and flux error can be in arbitrary units. 

Results: The code first estimates the exoplanet period using a BLS algorithm. It then phase folds the light curve to determine the transit time and depth. A more detailed analysis is then performed to obtain the orbital period, orbital separation, and radius ratio (comparison of exoplanet radius compared to the star). 

Example outputs: 
<img width="1232" height="722" alt="Screenshot 2026-09-11 at 2 16 07 AM" src="https://github.com/user-attachments/assets/9f2d2563-0610-48b5-a173-ac8956be12fb" />

<img width="1214" height="700" alt="Screenshot 2026-09-11 at 2 16 28 AM" src="https://github.com/user-attachments/assets/796a9daf-15b3-4e17-8277-fbaac093f0fe" />

<img width="1220" height="710" alt="Screenshot 2026-09-11 at 2 16 46 AM" src="https://github.com/user-attachments/assets/92dc716b-f8b5-410d-925c-7341b1f43b41" />

