This project implements parallel computation of π using MPI_Bcast and MPI_Reduce.  
Each process computes a portion of the sum, and the results are aggregated efficiently.

1.Uses MPI_Bcast to distribute the number of steps  
2.Uses MPI_Reduce to sum partial results  
3. Efficient parallel computation of π  
4. Measures execution time using MPI_Wtime()  
