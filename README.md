# Dining Philosophers Problem

We provide an outline of a solution to the dining-philosophers problem. This project involves implementing a solution to this problem using POSIX mutex locks and condition variables.

Implementation will require creating five philosophers, each identified by a number 0 . . 4. Each philosopher will run as a separate thread. Philosophers alternate between thinking and eating. To simulate both activities, have each thread sleep for a random period between one and three seconds.


