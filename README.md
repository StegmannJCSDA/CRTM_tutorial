# Description
This is a collection of tutorial cases for the Community Radiative Transfer Model (CRTM).
There is a separate folder for each tutorial case:
- `K-Matrix_test` : How to compute instrument weighting functions with the CRTM.
- `K-Matrix_SVD` : How to use the CRTM K-Matrix in other applications.
- `NakajimaKing` : A bispectral retrieval example for cloud optical thickness and effective radius.

# Getting Started

## Requirements
This tool requires a linked version of the CRTM library and a LAPACK version.
The code has been tested with CRTM REL-2.1.3 to 2.3.0.
A Python installation with NumPy and Matplotlib modules is required for the plotting scripts.

## Compiling the Code
1. Enter the corresponding case folder.
2. Type  `make`.

## Using the Code
A detailed description on how to run each tutorial can be found in the corresponding case folder.

# LICENSE:
Please see the file `LICENSE.txt` for details.

# References
Stegmann, P., E. Liu, B. Johnson (2019): Applying the Community Radiative Transfer Model to Remote Sensing and Data Assimilation. AGU Fall Meeting 2019 (Advances in Remote Sensing Inversion), Boston MA.
