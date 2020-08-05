Radiative kernels for the GFDL AM2.1 in its aquaplanet configuration as described in the following paper: Feldl, N., S. Bordoni, and T. M. Merlis (2017), Coupled high-latitude climate feedbacks and their impact on atmospheric heat transport, Journal of Climate, 30, 189–201, [doi: 10.1175/JCLI-D-16-0324.1](https://doi.org/10.1175/JCLI-D-16-0324.1).

Use notes:

The extra vertical level in the temperature kernel is the surface temperature kernel. To construct the temperature kernel, each of the 24 atmospheric levels (matching pfull) was perturbed individually and the TOA radiative response for each was calculated, then all levels were concatenated back together along with the surface temperature kernel.

The units of the surface kernels are W/m^2/% and W/m^2/K for surface albedo and surface temperature, respectively, as in Fig. A1 of Feldl et al. (2017). The /100mb is a metadata entry mistake that should only apply to the 4-D kernels.

For the water vapor kernel, the standard anomaly is the change in specific humidity for a 1-K warming assuming no change in relative humidity. However, when calculating the water vapor feedback, it is recommended to multiply the kernel by the change in ln(q), which is a better approximation than dq (Eqn. 2 Feldl and Bordoni 2016).
