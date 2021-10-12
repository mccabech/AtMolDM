# AtMolDM

The purpose of this website is to host data files and Mathematica notebooks used to calculate the dark matter—electron scattering results in ‘Fuelling the search for light dark matter—electron scattering’ by Louis Hamaide and Christopher McCabe, arXiv:2110.02985. If you use any of the data or code from this website, please cite the paper.

There are results for the three atoms (helium, neon and xenon) and the two molecular species (methane and isobutane) that we considered in the paper. Below is a brief description of the contents of each folder:

--- Formfactor_Coulomb - This is the rotationally-averaged single-electron dimensionless ionisation form factor (eq. (3) in the paper) calculated with a Coulomb outgoing wave function. For molecules, this is the best form factor to use. For atoms, Formfactor_HX is better.

--- Formfactor_HX - This is the rotationally-averaged single-electron dimensionless ionisation form factor (eq. (3) in the paper) calculated with an outgoing wave function calculated using Cowan’s HX method. For atoms, this is the best form factor to use. There is no HX form factor for molecules.

--- Formfactor_planewave - This is the rotationally-averaged single-electron dimensionless ionisation form factor (eq. (3) in the paper) calculated with a plane wave outgoing wave function. This is the least accurate result and is included for completeness.

--- Orbitals - Here you will find Mathematica notebooks containing the analytic expressions for the wave functions in position and momentum space that have been calculated using PySCF.

--- cubegen - This folder contains a Mathematica notebook that can generate pretty pictures of the orbitals for all of the atomic and molecular species using the cubegen format output from PySCF. Support for cube files was added to Mathematica from version 12.1. Earlier versions of Mathematica will not support cube (or cub) datafiles. See https://reference.wolfram.com/language/ref/format/Cube.html for additional information.

--- dRdE - This provides a notebook to generate recoil spectra for DM-electron scattering (eq. (1) of the paper). The gvmin_round.dat file is a tabulated version of the g(vmin) function.

In addition, each folder contains the text file “XXX_pyscf_out.txt”, where XXX=He, Ne, Xe, CH4, C4H10, that provides the detailed output from our PySCF calculation. This gives the version of PySCF, a summary of the input settings, the basis set coefficients, and the most relevant results from the calculation.

Please email me [christopher.mccabe@kcl.ac.uk] if you have any questions/comments/complaints or if you need guidance on how to use the data.
