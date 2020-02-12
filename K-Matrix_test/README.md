# Short Description
This tutorial demonstrates how to use the CRTM to compute the Jacobian matrix (or K-matrix) for an example test case involving AMSU-A.

# Running the test case
Below is a walkthrough for all the steps of this tutorial case.

## Compilation
In order to compile the test, simply type 
`make` 
in this folder.The `makefile` expects the CRTM installation to reside in `/usr/local/crtm_v2.3.0/`.
If this is not the case for installation, you need to modify the CRTM path in the makefile accordingly.

## Running the computations
If the compilation was successful, an executable called `K.x` is created.
In order to run the executable, type 
`./K.x`
