# python-assignment-
Interactive Round Robin CPU scheduling visualizer modeling SDG municipal and emergency workloads. Features second-by-second execution timelines, customizable time quanta, and automatic performance metrics for Activities 1 and 2.
Overview
Static diagrams often make scheduling behavior hard to follow. This visualizer animates how requests are served step-by-step, plots head movements and process timelines, and compares algorithm efficiency on shared inputs
Key Capabilities
Part A — Disk Scheduling (Compulsory): Animates FCFS, SSTF, SCAN, C-SCAN, and LOOK using disk size (cylinders), initial head position, request queue, and scan direction (for SCAN/LOOK). Displays a seek graph (cylinder number vs. request order), service sequence, total head movement, and a comparison bar chart of total head movement across all five algorithms on the same input.
Part B — CPU Scheduling (Any Two Selected): Supports choosing any two algorithms from FCFS, SJF (non-preemptive), SRTF, Priority, and Round Robin (with a configurable time quantum). Takes process ID, arrival time, burst time, and priority as inputs, and renders an animated Gantt chart alongside per-process and average waiting and turnaround times.
Interactive Playback & Validation: Includes input validation (such as rejecting out-of-range head positions), step-by-step playback (Next / Previous), and Auto-Play controls.
