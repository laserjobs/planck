# Planck Lattice Calculation

Numerical routines for deriving fundamental constants from discrete lattice geometries.

## Workflow
1.  **`alpha_scaling.py`**: Computes the fine-structure constant ($\alpha$) using spectral zeta functions on a D4 lattice.
2.  **`planck_calc.py`**: Uses the derived $\alpha$ to calculate the lattice resolution ($N$) required to reproduce Planck's constant ($\hbar$).

## Usage

```bash
pip install -r requirements.txt
python planck_calc.py
