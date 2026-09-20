# Fig. 3: training curve for N = 18 electrons at nu = 1/3

Per-particle energy `E/N` and local-energy standard deviation `sigma(E)/N` as functions of `kappa`, recorded during the staged optimization of CF-Flow starting from the Laughlin wavefunction.

## Files
`training_curve_N18_nu1_3.csv`

## Columns
1. `stage`: training stage. `only_cusp` (i, Kato cusp term), `real_jastrow` (ii, amplitude Jastrow), `imag_jastrow` (iii, phase Jastrow), `backflow` (iv, backflow), `all_on` (v, fine-tuning with reduced learning rate), `eval_qgt` (final evaluation of the best model; the red curve in the figure)
2. `epoch`: training epoch (sets the color in the figure)
3. `kappa`: Landau-level mixing strength at which the model was evaluated
4. `energy_over_N`: `E/N`
5. `energy_std_dev_over_N`: local-energy standard deviation `sigma(E)/N`
6. `energy_std_error_over_N`: Monte Carlo standard error of `E/N`
