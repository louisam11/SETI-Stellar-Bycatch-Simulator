# SETI-Stellar-Bycatch-Simulator
We provide a simple calculator to simulate the stellar bycatch using the Besançon Galactic Model, to better understand the population and spectral types captured as well as improve estimations of the prevalence of extraterrestrial transmitters. Based on work by Mason, Garrett and Siemion (2025) [in prep].

Essential:

1. Input parameters from user - coordinates, field of view, SEFD, etc.
2. Run BGM simulation for calculated solid angle
3. Open results from simulation, filter for stars within FoV, and save table as output file. We plot the stellar bycatch within the FoV, colour coded by spectral type.

Optional:

4. Plot stellar bycatch's distance against absolute magnitude
5. For increasing shells of EIRP, we calculate the number of stars per shell and corresponding transmitter rate.
6. We seperate the bycatch population by spectral & luminosity type, and calculate the prevelance per spectral class for increasing shells of distance. We plot a HR diagram for the bycatch sample.
7. We estimate the prevelance due to the total stellar bycatch up up to 25kpc.
