Parallel Odd-Even Sort Using MPI

This project implements the Odd-Even Sort algorithm using (MPI) for parallel execution. The algorithm distributes an array among multiple processes and sorts it in parallel using the **odd-even transposition sort** method.

1.The array is divided among multiple MPI processes.
2.Each process sorts its local subarray using odd-even transposition.
3.Neighboring processes exchange boundary elements to maintain correct order.
4.The process continues iteratively until the entire array is sorted.


