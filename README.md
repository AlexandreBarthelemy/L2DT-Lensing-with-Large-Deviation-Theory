# L2DT (Lensing with Large Deviation Theory)
This mathematica notebook presents a practical and pedagogical implementation of the weak-lensing convergence/aperture mass PDFs as computed with the large-deviations formalism.
You are free to use this notebook for your own science. If you do so please cite arXiv:2307.09468.

Currently it computes:
- The convergence cumulant generating function (CGF) and 1-point PDF for single source planes as well as source distributions.
- New lensing kernels when using the BNT transform, a nulling technique to compartmentalise small-scales physics to the closest sources in a tomographic experiment.
- The joint CGFs and joint PDFs between projected quantities for any projection kernel. This allows to compute joint statistics between different lensing sources and/or lensing and clustering quantities.

The notebook restricts itself to the case of top-hat filters although the theory allows for more general filters. It also ignores simulation-specific corrections (like discrete lensing shells or resolution effects) that are usually necessary for fair comparison of the formalism to simulated data. It assumes one specific cosmology since the goal of this notebook is mostly pedagogical but which is straightforwardly changed in the notebook itself.

Later revisions of this notebook will include :
- Correction induced by the Kaiser-Squires reconstruction of the convergence field from a masked shear field.
- The aperture-mass CGF and 1-point PDF for single source planes as well as source distributions.
- Inclusion of observational systematics (baryonic feedback, intrinsic alignments, photometric redshift errors) and high-order lensing corrections (lens-lens couplings, geodesic deviation, reduced shear and magnification bias).
- More general filtering scheme.

This notebook was written by Alexandre Barthelemy -- Universitäts-Sternwarte München, Fakultät für Physik der Ludwig-Maximilians-Universität.
Any questions/remarks should be addressed to A.Barthelemy@lmu.de

This notebook is based on numerous papers but mostly arXiv:1909.02615 for the convergence PDF (with and without BNT transform), arXiv:2106.11632 for the computation of joint-PDFs between sources, arXiv:2012.03831 for the aperture mass PDF and finally arXiv:2307.09468 for the reconstructed convergence PDF from actual cosmic observations.

You are free to use this notebook for your own science. If you do so please cite arXiv:2307.09468.

# Instructions

You can either download the notebook on its own or download the zip file that also contains pre-ran quantities used in the notebook to avoid some lengthy evaluations.
