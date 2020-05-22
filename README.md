# ranjanschwietermanharman2020
292K NUV H2O Cross-Sections published in Ranjan, Schwieterman, Harman et al. 2020
This repository gives the H2O cross-sections measured and reported in Ranjan et al. (2020), as well as the prescriptions for inclusion into photochemical models reported therein. If using these data, please cite:

Ranjan, S., Schwieterman, E.W., Harman, C., Fateev, A., Sousa-Silva, C., Seager, S. and Hu, R., 2020. Photochemistry of Anoxic Abiotic Habitable Planet Atmospheres: Impact of New H$ _2 $O Cross-Sections. The Astrophysical Journal, accepted. arXiv:2004.04185.

The files given here correspond to Figure 2 of that paper. Specifically,

cs_h2o_19-4C_updated.txt: corresponds to the total cross-sections measured in our work (measurements done by A. Fateev, TDU). Column 1 is wavelength in nm; column 2 is cross-section in cm^2; column 3 is uncertainty on cross-section, in cm^2. To convert these to the absorption cross-sections reported as the magenta points in Figure 2 of Ranjan et al. 2020, one must subtract off the Rayleigh scattering contribution. To calculate the Rayleigh scattering of H2O, we used the formalism and parameters given in Ranjan & Sasselov (2017, Astrobiology). 

H2O_prescriptions.txt: provides the prescriptions for the extrapolation prescription (black points in Figure 2) and cutoff prescriptions (purple points in Figure 2). Units are given in the file. 

These data correspond to 292 K (room temperature)


