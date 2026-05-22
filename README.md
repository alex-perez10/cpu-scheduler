# CPU Scheduling Simulator
A web-based CPU scheduling simulator that visualizes how operating system scheduling algorithms manage processes. The simulator allows users to enter process details and compare scheduling behavior through a Gantt chart and performance metrics.

## How to Run
1. Clone or download the repository
2. Open `index.html` in any modern browser
3. No installation or server setup required

## Features
- Supports First-Come, First-Served (FCFS)
- Supports Shortest Job First (SJF)
- Supports Priority Scheduling
- Supports Round Robin with a configurable time quantum
- Displays a Gantt chart showing process execution order
- Shows idle CPU time when no process is ready
- Calculates waiting time and turnaround time for each process

## Tech Stack
- HTML
- CSS
- JavaScript

## What I Built
I built the simulator using vanilla JavaScript to handle process input, scheduling logic, Gantt chart generation, and results table output. The project focuses on making operating system scheduling concepts easier to understand through visualization.

## How It Works
Users enter a process name, arrival time, burst time, and priority. After selecting a scheduling algorithm, the simulator calculates the execution order and displays the result as a Gantt chart. It also computes waiting time and turnaround time so users can compare the efficiency of each algorithm.

## Algorithms Implemented
### First-Come, First-Served
Processes are executed in the order they arrive.

### Shortest Job First
The ready process with the shortest burst time is selected next.

### Priority Scheduling
The ready process with the highest priority is selected next. A lower number represents a higher priority.

### Round Robin
Each process receives CPU time for a fixed time quantum before being moved to the back of the queue if it is not finished.

## What I Learned
- How CPU scheduling algorithms work internally
- How to calculate waiting time and turnaround time
- How to represent scheduling behavior visually with a Gantt chart
- How to structure JavaScript code for algorithm-based simulations
- How to handle edge cases such as idle CPU time and invalid user input

## Future Improvements
- Add comparison charts between algorithms
- Add export options for results
- Improve mobile responsiveness
- Add automated test cases for scheduling calculations
