# CPU-Scheduling-Simulator
A menu-driven C++ program that simulates major CPU scheduling algorithms — FCFS, SJF, Round Robin, Priority Scheduling, and MLFQ — with performance analysis.

🔹 Features

Implements 5 classical scheduling algorithms from Operating Systems.

Uses priority queues (heaps) for efficient selection in SJF and Priority Scheduling.

Uses FIFO queues for Round Robin and MLFQ time-sharing.

Reports completion time, turnaround time, waiting time, and their averages.

Menu-driven interface for testing multiple algorithms in one run.

🔹 Data Structures & Algorithms Used

Sorting → for FCFS ordering

Min-Heap (priority_queue) → for SJF & Priority scheduling

FIFO Queue → for RR & MLFQ

Greedy selection logic → for minimizing turnaround/waiting times
