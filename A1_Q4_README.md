This program demonstrates token passing in a ring topology using MPI.

1.Process 0 initializes a token and starts the passing sequence.
2.Each process receives the token from its previous process and forwards it to the next.
3.The last process sends the token back to Process 0, completing the loop.
4.The communication follows a circular pattern among all available processes.







