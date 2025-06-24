# Benchmark_Instances_ST2P_Cmax
Herein, five groups of instances are organized according to the number of tasks n: 10, 20, 100, 500, and 1000.

Each subfolder (for example, "N=10") contains 15 CSV files, and each CSV file includes 10 instances, resulting in a total of 150 instances per group. 
The instances within each CSV file are separated by a blank line.

The first column in each file corresponds to rr (the release date), the second column to dd (the task duration), and a third column represents the due date. 
However, this third column is not used in solving the Cmax scheduling problem.

In addition, the instances follow specific task assignment rules based on five task types. For each instance group:

    Type 1: n1=n, n2=n/2, n12=n/2

    Type 2: n1=n, n2=n, n12=n/2

    Type 3: n1=n, n2=n/2, n12=n

    Type 4: n1=n, n2=n, n12=n

    Type 5: n1=n/2, n2=n/2, n12=n

These parameters define the number of tasks processed exclusively on machine 1 (n1​), exclusively on machine 2 (n2​), and jointly on both machines (n12​).
