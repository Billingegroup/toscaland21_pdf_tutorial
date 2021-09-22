Methylammonium lead triiodide refinement information:

Cubic MAPbI3:
====================================

Space group:		Pm-3m
lattice a:		6.31728 Angstroms

structure file:         Cubic_MAPbI3.cif
Radiation:		x-ray
Qmax:			25.0 Inv. Angstroms
Qdamp for PDF:	0.0434
Qbroad for PDF: 0.0165

Tetragonl MAPbI3:
====================================

Space group:		I4/mcm
lattice a/b:		8.80625 Angstroms
lattice c:		12.7127 Angstroms

structure file:         I4mcm_MAPbI3.cif
Radiation:		x-ray
Qmax:			25.0 Inv. Angstroms
Qdamp for PDF:	0.0434
Qbroad for PDF: 0.0165


DATA: MAPbI3 measured at 300K using x-rays at the XPD beamline at NSLS-II.

GOAL: demonstration of r-dependent fitting 

TASKS:
1) Set up and refine cubic model to the MAPbI3 dataset over a short range.
2) Then use the r-Series macro to set up a box-car fit in which the structure is refined over incremental ranges.
3) Think about how the fit range contributes to the sensitivity to local and average structure.
4) What happens to the speed of the fit as the r-range increases. Think about a way to make this run faster.
5) Set up and refine the tetragonal model to the MAPbI3 dataset.
6) Again, use the r-Series macro to set up and run a boxcar fit.
7) Compare the trends in Rw values for the two models. What do you notice?
