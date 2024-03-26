# BA_Lumerical
This repository contains important files and information used for the simulations of the BA-project.

# Sim_latestVersion.fsp
This file includes the simulation file of the newest simulation setup I used. This file includes:

Material stack Structure Group:
This is latest version of the simulation model created in Lumerical.
The Material stack contains structure group contains the base/substrate, Box, Cladding and the SiN layer for positive x.
To create gratings, this SiN is overwritten with SiO2 material. The size of the stack can be adapted in the properties section.

circularG&GaussSource Analysis Group:
this group contains all the other structures like the gratings, the source and the two waveguides.
They are implemented in the Script file in a way so that all usefull parameters of the two tapers, the source and the grating can be changed in the Variales section.
Here are two screenshots of the variable section:

![grafik](https://github.com/TobsTha/BA_Lumerical/assets/116896852/f75ae407-0419-4cdb-bade-ac3940d09ce0)
![grafik](https://github.com/TobsTha/BA_Lumerical/assets/116896852/74258296-5d44-4a2a-9dd0-71a9f718db8c)

This analysis group is intended to be used for further optimization of the the tapers, the exact source alignment and other improvments. This is done doing sweeps over the corresponding values in the variables section.

Appart from the FDTD simulation region and the mesh override regions all other activated elements of the simulations are monitors, intended to collect useful data during simulations.

The design of the Grating Coupler including the first taper looks like that (the image monitor was used to create the picture before adding some labels in Powerpoint):

![FinalDesign](https://github.com/TobsTha/BA_Lumerical/assets/116896852/52963efd-1b9a-4966-a4d7-13864070ffe2)

The polarization angle dependence was simulated to be sine-like as expected:

