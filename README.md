# Parallel_Linear_Solver
Software which uses OpenMP to parallelise the three classic Algebraic Iterative Methods: Jacobi, Gauss-Seidel &amp; Successive Over Relaxationolving, for solving Systems of the form Ax = b 

## Requirements
* __Compiler__:`g++ 13.1.0`. Where possible, __C++20__ features have been used.
* __OS__: `Ubuntu 20.04`.
* `OpenMP`. For __parallelising__ the iterative methods: __Jacobi__, __Gauss-Seidel__ and __SOR__.
* `CMake`. For building the software.
* `matplotlib-cpp`. For plotting __Convergence Rates__.
