This program performs parallel matrix transposition using MPI.

1.The root process initializes an N×N matrix.
2.The matrix is scattered row-wise to all processes.
3.Each process transposes its assigned submatrix.
4.The transposed pieces are gathered back at the root.
5.The root process prints the transposed matrix.
