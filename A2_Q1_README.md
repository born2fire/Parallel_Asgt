This program estimates the value of π (Pi) using the Monte Carlo method with CUDA and MPI.

1.Each MPI process runs a CUDA kernel to generate random points inside a unit square.
2.The program checks how many points fall inside a unit circle to approximate π.
3.The results from all MPI processes are aggregated using MPI_Reduce().
4.The final π estimate is computed on rank 0.
5.Requires both MPI and CUDA to execute.
