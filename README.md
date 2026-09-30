# Optimal Linear Inviscid Damping and Vorticity Depletion for Non-monotonic shear flows

This repository contains the code for the explicit formula justification parts of in the proofs for the paper ``Optimal Linear Inviscid Damping and Vorticity Depletion for Non-monotonic shear flows''

The justifications are presented in two different Jupyter.ipynb notebooks, found in the notebooks directory. These notebooks are responsible for justifying the explicit formula of singularities and remainder terms in the Sections 5 and 7 in the paper. It is possible to view the results of notebooks without running any code by opening the corresponding html-files found in the notebooks directory; they can be opened in any browser such as Firefox. The two notebooks are:

- Justifynd.ipynb - Contains the explicit formulas of Lemmas 5.7, 5.9, 5.10, 5.12, 5.14 and 5.15, corresponding to the regularity of the remainder in the non-degenerate case.

- Justifyd.ipynb - Contains the explicit formulas of Lemmas 7.3, 7.5, 7.6, 7.8, 7.9 and 7.10, corresponding to the regularity of the remainder in the degenerate case. 

## Reproducing the justifications
The proofs were generated with Python 3.12, 

## Notes about implementation
The code in this repository is spread out over two directories:

1. tex/ - This directory contains the mathematical formulas
2. notebooks/ - This directory contains the notebooks justifying the formulas using Sympy.