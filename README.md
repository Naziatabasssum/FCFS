# FCFS
Implementation:  

1-  Input the processes along with their burst time (bt).
2-  Find waiting time (wt) for all processes.
3-  As first process that comes need not to wait so 
    waiting time for process 1 will be 0 i.e. wt[0] = 0.
4-  Find waiting time for all other processes i.e. for
     process i -> 
       wt[i] = bt[i-1] + wt[i-1] .
5-  Find turnaround time = waiting_time + burst_time 
    for all processes.
6-  Find average waiting time = 
                 total_waiting_time / no_of_processes.
7-  Similarly, find average turnaround time = 
                 total_turn_around_time / no_of_processes.
 

 Output: 

Processes  Burst time  Waiting time  Turn around time    //The Output is Wrong please correct it
 1        10     0         10
 2        5     10         15
 3        8     15         23
Average waiting time = 8.33333
Average turn around time = 1
