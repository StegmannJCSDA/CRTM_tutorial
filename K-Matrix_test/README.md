# Short Description
This tutorial demonstrates how to use the CRTM to compute the Jacobian matrix (or K-matrix) for an example test case involving AMSU-A.
The so-called K-Matrix, or Jacobian is used in linear(-ized) retrieval problems to relate the measurement vector `y` to the state vector `x`:
```
y = K*x
```

# Running the test case
Below is a walkthrough for all the steps of this tutorial case.

## Compilation
In order to compile the test, simply type 
```
make 
```
in this folder.

### If something goes wrong...
The `makefile` expects the CRTM installation to reside in `/usr/local/crtm_v2.3.0/`.
If this is not the case for installation, you need to modify the CRTM path in the makefile accordingly.

## Running the computations
If the compilation was successful, an executable called `K.x` is created.
In order to run the executable, first type 
```
rm output_*
```
to remove the existing output files, and then 
```
./K.x
```
to run the actual executable for this example.
