# Fig. 4: per-particle energies of the uniform FQH ground states

Per-particle energy `E/N` of the uniform (`L = 0`) states at nu = 1/3 and nu = 2/5 as functions of `kappa` and `1/N`, compared with fixed-phase diffusion Monte Carlo (fp-DMC) and DeepHall. The thermodynamic-limit values in the bottom panel are linear extrapolations in `1/N` at fixed `kappa`.

## Files
- `per_particle_energies_uniform_state_N<N>_nu<nu>.csv`: CF-Flow evaluations of the optimized model. nu = 1/3 for N in {6, 7, 8, 9, 10, 11, 12, 18, 24}; nu = 2/5 for N in {8, 12, 16, 20, 26}.
- `energies_fp_dmc.csv`: fp-DMC reference values, transcribed from the literature cited in the paper.
- `energies_deephall.csv`: DeepHall reference values, transcribed from the literature cited in the paper.

## Columns
- **CF-Flow files**:
  1. `row_iter`: evaluation index
  2. `kappa`: Landau-level mixing strength
  3. `energy_per_particle`: `E/N`
  4. `mcmc_error_in_energy_per_particle`: Monte Carlo standard error of `E/N`
  5. `local_energy_deviation_per_particle`: local-energy standard deviation `sigma(E)/N`
- **Reference files** (`energies_fp_dmc.csv`, `energies_deephall.csv`):
  1. `N`: number of electrons
  2. `nu`: filling factor
  3. `E`: `E/N`
  4. `kappa`: Landau-level mixing strength
