Computes the dot product of two vectors using MPI with MPI_Scatter and MPI_Reduce.

1.Root initializes two vectors A and B.
2.Data is distributed using MPI_Scatter.
3.Each process computes a local dot product.
4.MPI_Reduce aggregates results at root.
5.Root prints the computed and expected dot product.
