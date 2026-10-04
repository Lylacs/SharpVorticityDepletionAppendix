# Optimal Linear Inviscid Damping and Vorticity Depletion for Non-monotonic Shear Flows

This repository provides explicit formulas and their symbolic verification for the remainders $\mathcal{R}_{a,b,\epsilon}^\iota$ presented in the paper *Optimal Linear Inviscid Damping and Vorticity Depletion for Non-monotonic Shear Flows*. These formulas are used in the proofs in Sections 5 and 7 to show that, after the explicit singular terms $\mathcal{S}_{a,b,\epsilon}^\iota$ are extracted from the higher-order spectral derivatives of the spectral density functions, the resulting remainders have sufficient regularity to be controlled by the limiting absorption principle.

The formulas and their symbolic verifications are organized into two cases: non-degenerate and degenerate. For each case, the table below lists the appendix subsection containing the explicit formulas, the corresponding verification notebook, and the lemmas in which these formulas are used.

|Explicit formulas | Verification notebook | Case | Related lemmas |
| --- | --- | --- | ---|
|[Appendix](tex/Appendix.pdf) A.1| [Justifynd.ipynb](notebooks/Justifynd.ipynb) | Non-degenerate | 5.7, 5.9, 5.10, 5.12, 5.14, and 5.15 |
|[Appendix](tex/Appendix.pdf) A.2| [Justifyd.ipynb](notebooks/Justifyd.ipynb) | Degenerate | 7.3, 7.5, 7.6, 7.8, 7.9, and 7.10 |


## Repository structure

The files in this repository are organized into two directories:

- [tex/](tex/): The appendix in PDF format and its LaTeX source files.
- [notebooks/](notebooks/): Jupyter notebooks that verify the formulas.


## Notes about the verification notebooks

- The symbolic verifications were performed in two Jupyter notebooks using Python 3.12 and SymPy 1.14.0 in Google Colab. 
- To view the results without running any code, download the corresponding HTML files from the [notebooks](notebooks) directory and open them in any browser such as Firefox. 
- To reproduce the verifications, open either notebook in Google Colab or a local Jupyter environment and run its cells in order.

