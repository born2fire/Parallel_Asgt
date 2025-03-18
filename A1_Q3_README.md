This program demonstrates ping-pong message passing using MPI between two processes.

1.The two processes take turns sending and receiving a counter value.
2.The process with the matching turn sends the updated count to the other process.
3.The exchange continues until the count reaches a defined limit (PING_PONG_LIMIT).
4.The program requires exactly two processes to execute.
