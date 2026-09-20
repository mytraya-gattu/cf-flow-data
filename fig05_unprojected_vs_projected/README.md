# Fig. 5: projected versus unprojected initialization, N = 16 electrons at nu = 2/5

Per-particle energy `E/N` (top) and local-energy standard deviation `sigma(E)/N` (bottom) as functions of `kappa` for CF-Flow initialized from the projected and from the unprojected Jain wavefunction, after training with identical hyperparameters.

## Files
- `projected_N16_nu2_5.csv`: initialized from the LLL-projected Jain wavefunction
- `unprojected_N16_nu2_5.csv`: initialized from the unprojected Jain wavefunction

## Columns
1. `kappa`: Landau-level mixing strength
2. `energy_over_N`: `E/N`
3. `energy_std_error_over_N`: Monte Carlo standard error of `E/N`
4. `energy_std_dev_over_N`: local-energy standard deviation `sigma(E)/N`
