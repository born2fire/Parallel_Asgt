This program demonstrates dynamic memory allocation for message reception using MPI.

1.Process 0 generates a random number of integers and sends them to Process 1.
2.Process 1 first probes the message to determine its size before dynamically allocating memory.
3.This approach ensures efficient handling of variable-sized data transmissions.
4.The program requires at least two processes to execute properly.
