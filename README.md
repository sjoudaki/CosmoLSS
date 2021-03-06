# CosmoLSS

We release modified CosmoMC modules and associated data files to perform a combined analysis of cosmic shear tomography, galaxy-galaxy lensing tomography, and redshift-space multipole power spectra (monopole and quadrupole) using 450 sq deg of imaging data by the Kilo Degree Survey (KiDS-450) overlapping with two spectroscopic surveys: the 2-degree Field Lensing Survey (2dFLenS) and the Baryon Oscillation Spectroscopic Survey (BOSS). We include the full covariance between the observables, scales, and samples using a large suite of N-body simulations.

The fitting pipeline includes key astrophysical systematics arising from intrinsic galaxy alignments, baryonic effects in the nonlinear matter power spectrum, photometric redshift uncertainties, galaxy bias, pairwise velocity dispersion, and shot noise (the latter three for each galaxy sample). The modified modules and associated data are contained in a clean version of CosmoMC (July 2015 version) in "cosmolss.tar.gz". The extension "...onlyupdatedfiles.tar.gz" includes only the new/updated files relative to a clean CosmoMC.

There is more specific information in the readme included in the tarballs. 

The measurements and fitting pipeline are presented in https://arxiv.org/abs/1707.06627. The central chains of the paper are available to [download from here](https://www.dropbox.com/s/54djmqph4s4as62/kids2dflenschains.tar.gz?dl=0).

The version of CosmoLSS used for benchmarking the 3x2pt calculation of the LSST-DESC Core Cosmology Library (CCL) can be found here: https://github.com/sjoudaki/cosmolss_cclbenchmarking

UPDATE: 2019/05/31 Releasing an updated version of the code with improved user-friendly capabilities and modifiable precision vs speed settings (see data/CosmoLSS.dataset). The fiducial precision is chosen to be higher following the benchmarking of the LSST-DESC CCL with negligible impact on the parameter constraints.

Please feel free to contact us at shahab.joudaki@physics.ox.ac.uk if you have any questions.
