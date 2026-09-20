# cf-flow-data

Numerical data generated for the article *Dressing composite fermions with artificial intelligence* (Mytraya Gattu, PRX Intelligence, 2026, DOI: 10.1103/zq76-147c; preprint arXiv:2512.00527), presented in Figs. 3–7.

The remaining figures of the article (Figs. 1, 2, and 8) are schematic illustrations.

This repository contains the (post-processed) data needed to reproduce the figures from the paper. The data are organized by figure: each folder name starts with the figure number.

## Data Format and Conventions
- **CSV files with a header row** naming the columns; detailed column definitions are given in the README of each figure folder.
- **Units**: energies are in units of `e^2 / (eps lB)`, where `lB` is the magnetic length; lengths are in units of `lB`; the Landau-level mixing strength `kappa` is dimensionless.
- **Energies** per particle include the contribution of the uniform neutralizing background and the density-shift correction of the spherical geometry, as described in the paper.
- **Errors**: for Monte Carlo results both the Monte Carlo standard error of the mean and the local-energy standard deviation are reported in separate columns.
- **Smoothing**: the CF-Flow curves shown in the paper are Gaussian-process smoothings of the evaluations tabulated here (see the paper); the tables contain the unsmoothed evaluations.

## License
CC BY 4.0, see `LICENSE`. Please cite the paper when using these data.
