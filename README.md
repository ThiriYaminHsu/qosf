
# QOSF Screening Task 2 — Complex Amplitudes

This repository implements Task 2 of the QOSF Mentorship Program Cohort 11 screening tasks.

## Task Description
Prepare a two-qubit quantum state from arbitrary complex amplitudes using only basic linear algebra (no `initialize` or similar quantum functions).

## How It Works
1. Normalize input amplitudes.
2. Compute the correct RY rotation on the first qubit.
3. Construct controlled single-qubit unitaries to prepare the conditional second-qubit states.
4. Verify that the resulting state equals the target state.

## Files
- `complex_amplitudes.ipynb`: Jupyter notebook with full explanation and code.

## Requirement
- numpy>=1.21

## Stretch Goal
Generalize this method to three-qubit states by extending the block decomposition and recursive structure.
