This program simulates heat distribution over a 2D grid using the finite difference method.  
It utilizes MPI to parallelize the computation across multiple processes.

1.Initialization: The grid is initialized with a heat source at the center.
2.Parallel Processing: The grid is divided among processes.
3.Communication: Processes exchange boundary rows to update values.
4.Computation: Each process updates its part of the grid using the finite difference method.
5.Gathering Results: The final grid is collected and displayed by the root process.
