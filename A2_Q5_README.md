Computes the sum of the first N natural numbers using MPI_Scatter and MPI_Reduce.

Steps
1.Root initializes an array (1 to N).
2.Data is distributed using MPI_Scatter.
3.Each process computes a local sum.
4.MPI_Reduce aggregates results at root.
5.Root prints the computed and expected sum.
