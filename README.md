# Using a non-linear least squares approach to find cosmological parameters Omega and Lambda using redshift and magnitude data from 42 high-redshift Type Ia Supernovae 
## Description
In this project, my goal was to estimate the Cosmological Parameters Ω<sub>M</sub> and Ω<sub>Λ</sub> from data taken from "Measurements of the Cosmological Parameters Ω and Λ from the First 7 Supernovae at z ≥ 0.35" by Perlmutter et al 1996. This data contained Redshift and Magnitude measurements from seven Type Ia Supernovae gathered during the Supernova Cosmology Project. To find the Ω<sub>M</sub> and Ω<sub>Λ</sub> parameters, I attempted to fit the Redshift and Magnitude data to a luminosity distance function, which tells us how far an object is from Earth relative to its apparent and peak brightness. The luminosity distance function that was used is given below, with c and H excluded in my own calculation

This function was used in two parts, one where Ω<sub>M</sub> + Ω<sub>Λ</sub> ≠ 1, and another where I set Ω<sub>M</sub> + Ω<sub>Λ</sub> = 1

## Background 

## Method 
To find Ω<sub>M</sub> and Ω<sub>Λ</sub>, I used curve fit from SciPy to find the optimal parameters needed to fit the Redshift and Magnitude measurements to the luminosity distance function. To test the accuracy of this model, I applied Chi-Square Minimization to measure the goodness of fit and Mean Squared Estimation to measure the difference between the approximate and real Redshift and Magnitude values.

## Results 
