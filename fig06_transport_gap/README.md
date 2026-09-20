# Fig. 6: transport gap at nu = 1/3 and nu = 2/5

The transport gap is `Delta = N [E_exciton/N - E_uniform/N]`, where `E_exciton` is the energy of the largest-`L` CF-exciton state (`L = N` at nu = 1/3, `L = N/2 + 1` at nu = 2/5) and `E_uniform` that of the uniform `L = 0` state. The uniform-state energies are those of the folder for Fig. 4; both energies are smoothed onto a common `kappa` grid before the difference is taken (see the paper). The thermodynamic-limit values in the bottom panel are linear extrapolations in `1/N` at fixed `kappa`, with the exponential fits given in the paper. The dashed lowest-Landau-level reference lines in the bottom panel are at `Delta = 0.106` (nu = 1/3) and `0.058` (nu = 2/5).

## Files
- `per_particle_energies_transport_gap_N<N>_nu<nu>.csv`: CF-Flow evaluations of the optimized largest-`L` CF-exciton state. nu = 1/3 for N in {6, 7, 8, 12, 18, 24}; nu = 2/5 for N in {8, 12, 16, 20, 26}.
- `transport_gaps_fp_dmc.csv`: fp-DMC reference gaps, transcribed from the literature cited in the paper.
- `transport_gaps_deephall.csv`: DeepHall reference gaps, transcribed from the literature cited in the paper.

## Columns
- **CF-Flow files**:
  1. `row_iter`: evaluation index
  2. `kappa`: Landau-level mixing strength
  3. `energy_per_particle`: `E_exciton/N`
  4. `mcmc_error_in_energy_per_particle`: Monte Carlo standard error of `E_exciton/N`
  5. `local_energy_deviation_per_particle`: local-energy standard deviation `sigma(E)/N`
- **Reference files**:
  1. `N`: number of electrons
  2. `nu`: filling factor
  3. `E`: transport gap `Delta`
  4. `kappa`: Landau-level mixing strength
