# CFD-Codes
This repsository has comparision beween 2 cfd codes. First one is based on finite difference method and other one is based on adams bashforth method.

1. N-S Equstion Solver (Unsteady, Incompressible 2D) using FDM

Author:- Kshitij Gupta (developed as a part of internship at IITD)

Note* Linearised Navier-Stokes doesn't work with this MAC formulation. Time step should considered carefully for explicit solver (generally smaller than implicit or semi-implicit solvers)

Method used: 

Marker and Cell method:- Staggered grid is used to solve the various parameters. u and v velocity is solved on edges and pressure p is solved at grid centre.
FDM:- Finite difference method is used

Equations used are provided in .mlx file 

2. N-S equation solver ( unsteady incompressible 2D) using Second-order Adams-Bashforth method

Author:- Kshitij Gupta (developed as a part of internship at IITD)

Solving the incompressible Navier-Stokes equations using staggered-grid, i.e u and v velocity is solved on edge and pressure p is solved at grid centre.
Base Tank excitation: boundary condition number == 4


Equations and theoretical formulation are provided in .mlx file