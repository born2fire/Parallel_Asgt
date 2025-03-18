This program computes the prefix sum of an array using MPI.

1.Root process initializes the array and scatters it using MPI_Scatter.
2.Each process computes its local prefix sum.
3.MPI_Exscan is used to get the sum of previous processes' prefix values.
4.Local prefix sums are adjusted using this value.
5.The final prefix sum is gathered and printed by the root process.
