This program demonstrates sending and receiving a variable number of integers using MPI.

1.Process 0 generates a random number of integers and sends them to Process 1.
2.Process 1 receives the data and determines how many numbers were actually received.
3.The communication is dynamic, meaning the number of transmitted elements varies in each run.
4.The program requires at least two processes to execute properly.
