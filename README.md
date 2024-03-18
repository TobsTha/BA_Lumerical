# BA_Lumerical
This repository contains important files and information used for the simulations of the BA-project.

# Sim_latestVersion.fsp

Material stack Structure Group:
This is latest version of the simulation model created in Lumerical.
The Material stack contains structure group contains the base/substrate, Box, Cladding and the SiN layer for positive x.
To create gratings, this SiN is overwritten with SiO2 material. The size of the stack can be adapted in the properties section.

circularG&GaussSource Analysis Group:
this group contains all the other structures like the gratings, the source and the two waveguides.
They are implemented in the Script file in a way so that all usefull parameters of the two tapers, the source and the grating can be changed in the Variales section.
The parameters which can be accessed in the variable section can be seen at the following tow screenshots:
![grafik](https://github.com/TobsTha/BA_Lumerical/assets/116896852/f75ae407-0419-4cdb-bade-ac3940d09ce0)
![grafik](https://github.com/TobsTha/BA_Lumerical/assets/116896852/74258296-5d44-4a2a-9dd0-71a9f718db8c)
This analysis group is intended to be used for further optimization of the the tapers, the exact source alignment among others.

Appart from the FDTD simulation region and the mesh override regions all other elements of the simulations are monitors intended to collect useful data during simulations.
