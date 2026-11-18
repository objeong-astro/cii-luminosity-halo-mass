Data for "An Empirically Calibrated [CII] Luminosity-Halo Mass Relation for Line Intensity Mapping"

We provide the posterior of a double power-law relation between halo mass and [CII] 158 micron
luminosity, L(M_h, z), calibrated on [CII] data alone: the mean [CII] intensity at 0 < z < 4.2
and luminosity-function measurements and limits at z ~ 0 and 4.3 < z < 8. Two fits are released.
The single-redshift fits at z = 4.5 and z = 5.5 constrain the four parameters of the relation
with no assumption about their evolution. The joint fit covers 0 < z < 7 with one power law in
(1+z) per parameter. The model, the data, and the definitions of all quantities are given in
Jeong, Chiang, and White (2026).

Two sets of files are provided:

1. Summary tables
   "CII_LofM--single_z.ecsv" gives the four parameters of the relation and the derived mean
   brightness temperature T_b, luminosity-weighted bias b_eff, shot-noise power P_shot, k_c,
   and A_pf at z = 4.5 and 5.5.
   "CII_LofM--joint_fit.ecsv" gives the same quantities for the joint fit at z = 0 to 7 in
   steps of 0.1.
   Values are posterior medians, with _low and _up the bounds of the 68% interval. The last
   two columns are the growth rate and the velocity dispersion used for the redshift-space
   monopole.

2. Posterior samples (3000 per fit)
   "CII_LofM_posterior--single_z4.5.ecsv" and "CII_LofM_posterior--single_z5.5.ecsv" give the
   four parameters and the derived quantities for each sample.
   "CII_LofM_posterior--joint_fit.ecsv" gives the eight coefficients of the joint fit (_p1 is
   the value at z = 2 and _p2 the exponent of 1+z).
   "CII_LofM_posterior--joint_fit_dense_z.ecsv" gives the derived quantities of the same
   samples at z = 0 to 7 in steps of 0.1.

Units: M_1 in M_sun, N in L_sun/M_sun, T_b in microkelvin, P_shot in h^-3 Mpc^3 uK^2, k_c in
h/Mpc, and sigma_v in Mpc/h. L(M_h) is the median luminosity at fixed halo mass, with a
log-normal scatter of 0.4 dex, so the mean intensity and the shot noise carry the scatter
factors of Equations (2) and (7) of the paper.

This data release is meant as a reference for forecasts of [CII] line intensity mapping
experiments.
