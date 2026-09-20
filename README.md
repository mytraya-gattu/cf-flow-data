# Data and figure scripts for "Dressing composite fermions with artificial intelligence"

Mytraya Gattu, *PRX Intelligence* (2026). DOI: 10.1103/zq76-147c. Preprint: arXiv:2512.00527.

This repository contains the post-processed data behind every data-based figure in the paper and the scripts that regenerate those figures.

## Layout

- `data/` — post-processed results (CSV). One file per system size, filling factor, and state (uniform ground state or largest-L CF exciton), plus the fixed-phase DMC and DeepHall reference values used for comparison.
- `scripts/` — plotting scripts; each script names the `data/` files it reads and the figure it writes.
- `figures/` — the figures as they appear in the paper, regenerated from `data/` by `scripts/`.
- `mcmc_data/`, `post_processed_data/` — raw training and Monte Carlo outputs (not tracked in git; available from the author on request).

## Figure → data map

(filled in below)

## Columns in `data/per_particle_energies_*.csv`

`row_iter` (evaluation index), `kappa` (Landau-level mixing strength), `energy_per_particle` (E/N in units of e²/εℓ_B, includes background and density-shift correction), `mcmc_error_in_energy_per_particle` (Monte Carlo standard error), `local_energy_deviation_per_particle` (σ(E)/N).

## Citing

Please cite the paper and this repository.
